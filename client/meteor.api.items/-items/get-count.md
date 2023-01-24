//[client](../../../index.md)/[meteor.api.items](../index.md)/[Items](index.md)/[getCount](get-count.md)

# getCount

[Meteor Automation API]\
fun [getCount](get-count.md)(vararg ids: [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html), container: InventoryID? = InventoryID.INVENTORY): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

checks the specified item [container](get-count.md) and returns the amount of items matching any of the [ids](get-count.md) provided

#### Parameters

Meteor Automation API

| | |
|---|---|
| ids | the item action to look for |
| container | the item container to check |

[Meteor Automation API]\
fun [getCount](get-count.md)(vararg names: [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html), container: InventoryID? = InventoryID.INVENTORY): [Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

checks the specified item [container](get-count.md) and returns the amount of items matching any of the [names](get-count.md) provided

#### Parameters

Meteor Automation API

| | |
|---|---|
| names | the item action to look for |
| container | the item container to check |
