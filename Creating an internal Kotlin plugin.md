```Meteor plugins may be placed in any Kotlin src dir, as they are manually added to the plugin manager```

A simple example of an internal Kotlin plugin for meteor can be found below:

```kotlin
package meteor.plugins.example

import eventbus.events.*
import meteor.plugins.Plugin
import meteor.plugins.PluginDescriptor
import net.runelite.api.GameState

@PluginDescriptor(
    name = "Example",
    description = "Show you how it's done",
    enabledByDefault = true // false by default in meteor
)
class ExamplePlugin : Plugin() {

    var npcManager = NPCManager
    var itemManager = Main.itemManager
    
    var overlay = overlay(ExampleOverlay(this))
    var config = configuration<ExampleConfiguration>()

    override fun onGameStateChanged(it: GameStateChanged) {
        if (it.gameState == GameState.LOADING) {
            client.resetHealthBarCaches()
        }
    }

    override fun onStop() {
        //This is normally handled automatically, just an example
        overlayManager.remove(overlay)
    }
}
```

First off, we should unpack the differences between a RuneLite plugin and a kotlin Meteor plugin using the example above

- Some import packages may be different!
- Managers can either be called directly, or from Main
- Some things are provided for plugins automatically, such as client, overlayManager, etc
- @Subscribe no longer exists, instead you override the functions (this allows autocomplete to function with events!)
- Overlays are managed automatically (you can still deal with overlayManager manually if it suits your needs)
- Configurations are instantiated automatically by passing it into the configuration<>() function
- onStart / onStop

```Once you have your plugin ready to go, you'll need to add it to the init block in PluginManager!```