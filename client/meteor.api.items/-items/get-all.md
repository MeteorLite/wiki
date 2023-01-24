//[client](../../../index.md)/[meteor.api.items](../index.md)/[Items](index.md)/[getAll](get-all.md)

# getAll

[Meteor Automation API]\
fun [getAll](get-all.md)(vararg ids: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), container: InventoryID? = InventoryID.INVENTORY): [ArrayList](https://docs.oracle.com/javase/8/docs/api/java/util/ArrayList.html)&lt;Item&gt;?

checks the specified item [container](get-all.md) and returns all matching items with the [ids](get-all.md) provided

#### Parameters

Meteor Automation API

| | |
|---|---|
| ids | the item ids to look for |
| container | the item container to check |

[Meteor Automation API]\
fun [getAll](get-all.md)(vararg names: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), container: InventoryID? = InventoryID.INVENTORY): [ArrayList](https://docs.oracle.com/javase/8/docs/api/java/util/ArrayList.html)&lt;Item&gt;?

checks the specified item [container](get-all.md) and returns all matching items with the [names](get-all.md) provided

#### Parameters

Meteor Automation API

| | |
|---|---|
| names | the item names to look for |
| container | the item container to check |

[Meteor Automation API]\
fun [getAll](get-all.md)(container: InventoryID = InventoryID.INVENTORY): [ArrayList](https://docs.oracle.com/javase/8/docs/api/java/util/ArrayList.html)&lt;Item&gt;?

returns all items from a specified [container](get-all.md)

#### Parameters

Meteor Automation API

| | |
|---|---|
| container | the item container to check |
