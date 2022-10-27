# Listscroll-gdevelop
Simple extension to create a scrollable list of items
# List scroll
## Simple extension to create a scrollable list of items
### Setup the list
* Use 1 Sprite for the `ListArea`, add to this sprite the `Draggable` behavior .
* Use 1 Sprite for the `MaskArea`.
* Use 2 Sprites  `Up button`, `Down button`.
* Use 1 Panel Sprite ("9-patch") for the `Slider button`, and add `Draggable` behavior to this Sprite.
* Use 1 Panel Sprite ("9-patch") for the `Slider background bar`.
### Setup the list items as you need.
* Use 1 Sprite for the `ItemButton` add to this Sprite the behavior `PinTo`.
* Use 1 Sprite for the `ItemIcon` add to this Sprite the behavior `PinTo`.
* Use 1 Text for the `ItemTitle` add to this Sprite the behavior `PinTo`.
* Use 1 Text for the `ItemDescription` add to this Sprite the behavior `PinTo`.

### See here how to add `PinTo` behavior to the Sprites.
![image](https://user-images.githubusercontent.com/2497411/198402557-b36600d3-3a7c-44c3-a116-d23feed38b2d.png)

### In GDevelop - Scene editor
Scene setup add add 2 Sprites the `listArea` and the `MaskArea`
Depending on the `ListArea` position the `UpButton`, `DownButton`, `SliderButton` and `SliderBackground` will be created.

1. You end with something like this, the `white sprite` is the `MaskArea`.
2. The `lightblue` is the `ListArea`

![image](https://user-images.githubusercontent.com/2497411/198400256-3014a8ff-e5af-4bee-b811-8ec3746719da.png)

### In GDevelop - Events editor
1. Add an empty event select the `ListArea` Sprite and look for `List Scroll` then select `Init List Scroll`

![image](https://user-images.githubusercontent.com/2497411/198399794-c13beb9a-061a-48fe-851f-f676c75c6098.png)

2. Then add another action just below the previous and set the `Masked items` go to `Othe actions` and set `List Scroll -> Masked Items`

![image](https://user-images.githubusercontent.com/2497411/198401274-8e5a2693-7d8d-4d70-bd16-bbea1dae8932.png)

3. You end with comething like this:
![image](https://user-images.githubusercontent.com/2497411/198400689-52cf997b-d708-4c35-bd89-2b806a0d7980.png)

## See full documentation here:
- Source & Documentation
https://github.com/UlisesFreitas/Listscroll-gdevelop
- Video Tutorial
https://www.youtube.com/watch?v=7p3FD8WvYX4


