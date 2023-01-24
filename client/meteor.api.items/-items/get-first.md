//[client](../../../index.md)/[meteor.api.items](../index.md)/[Items](index.md)/[getFirst](get-first.md)

# getFirst

[Meteor Automation API]\
fun [getFirst](get-first.md)(vararg ids: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), container: InventoryID? = InventoryID.INVENTORY): Item?

checks the specified item [container](get-first.md) and returns the first matching item with the [ids](get-first.md) provided

#### Parameters

Meteor Automation API

| | |
|---|---|
| ids | the item ids to look for |
| container | the item container to check |

[Meteor Automation API]\
fun [getFirst](get-first.md)(vararg names: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), container: InventoryID? = InventoryID.INVENTORY): Item?

checks the specified item [container](get-first.md) and returns the first matching item with the [names](get-first.md) provided

#### Parameters

Meteor Automation API

| | |
|---|---|
| names | the item names to look for |
| container | the item container to check |
