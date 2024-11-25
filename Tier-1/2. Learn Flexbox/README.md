# Learn Flexbox
Flexbox is a display property of CSS which allows us to bring all the items inside a container in a line.

To get flexbox, we have to add this property and value to the container element.

```
.container {
    display: flex;
}
```

THere are many properties to customize the flex Here are the properties and values substituted with the display property of flex:

| property        | value             | explanation                                                                                              |
| --------------- | ----------------- | -------------------------------------------------------------------------------------------              |
| justify-content | flex-start        | To shift it on the left most side.                                                                       |
|                 | flex-end          | To shift the content to the right most side                                                              |
|                 | center            | To shift the whole container to center vertically.                                                       |
|                 | space-around      | Makes same space on both side of every element in a container.                                           |
|                 | space-between     | Makes same space between each two elements in a container.                                               |
|                 | space-evenly      | Makes same space between each two elements and also at the begin and the end of an element.              |
| flex            | 1                 | Gives every item the same width in a container                                                           |
|                 | 2                 | Gives an element the double width than other elements in a container                                     |
| align-items     | flex-start        | Shifts the whole container to the top most of the parent element                                         |
|                 | flex-end          | Shifts the whole container to the bottom most of the parent element                                      |
|                 | center            | Makes the container center horizontally                                                                  |
| flex-direction  | row               | default behavior of flex, organizes the items from left to right                                         |
|                 | column            | default behavior of flex, organizes the items from top to bottom                                         |
| flex-wrap       | nowrap            | makes every element in one horizontal line, though they can't be visible. This is the default behaviour. |
|                 | wrap              | makes every element flexible, make a line break when needed                                              |
| order           | any numeric value | maintains the order of elements                                                                          |
