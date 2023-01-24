//[client](../../../index.md)/[meteor.api.loot](../index.md)/[Loots](index.md)

# Loots

[Meteor Automation API]\
object [Loots](index.md)

## Functions

| Name | Summary |
|---|---|
| [exists](exists.md) | [Meteor Automation API]<br>fun [exists](exists.md)(id: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [exists](exists.md)(name: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>fun [exists](exists.md)(name: [List](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)&gt;): [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getAll](get-all.md) | [Meteor Automation API]<br>fun [getAll](get-all.md)(sortByDistance: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = false): [ArrayList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)&lt;TileItem&gt;? |
| [getAt](get-at.md) | [Meteor Automation API]<br>fun [getAt](get-at.md)(worldPoint: WorldPoint): [ArrayList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-array-list/index.html)&lt;TileItem&gt;? |
| [getFirst](get-first.md) | [Meteor Automation API]<br>fun [getFirst](get-first.md)(vararg names: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), sortByDistance: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true): TileItem?<br>fun [getFirst](get-first.md)(vararg ids: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), sortByDistance: [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) = true): TileItem? |
