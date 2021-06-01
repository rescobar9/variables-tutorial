# variablestutorial
## Step 1

Drag the ``||Basic:on start||`` block to the trash on the left main menu.
 
## Step 2
In the menu on the left, click the ``||Variables:Variables||`` menu, and click on ``||Variables:Make a Variable||`` and name the variable under the New variable name with "Temperature".  
 
## Step 3
In the left menu, click the ``||Variables:Variables||`` block and drag the ``||Variables:set Temperature to 0||``  inside the ``||Basic:forever||`` block. 
```blocks
let Temperature = 0
basic.forever(function () {
    Temperature = 0
})
})
```
 
## Step 4
In the menu on the left, under ``||Input:input||``, find the ``||Input:Temperature||`` block and drag the block replacing the 0 in the ``||Variables:set Temperature to 0||`` block.   
```blocks
let Temperature = 0
basic.forever(function () {
    Temperature = input.temperature()
})
```
 
## Step 5
In the left menu, click ``||Basic:Basic||`` , find ``||Basic:show number 0||`` and drag it inside the ``||Basic:forever||`` block under the ``||Variables:set Temperature to||`` ``||Input:temperature||`` block.
```blocks
let Temperature = 0
basic.forever(function () {
    Temperature = input.temperature()
    basic.showNumber(0)
})
```

## Step 6
In the left menu, click ``||Variables:Variables||``, find the ``||Variables:Temperature||`` block, drag it and replace the 0 in the ``||Basic:show number||`` block inside the ``||Basic:forever||``block.
```blocks
let Temperature = 0
basic.forever(function () {
    Temperature = input.temperature()
    basic.showNumber(Temperature)
})
```

## Step 7
Connect the Micro:bit to the USB port on your computer. Then click on ``||LED:Download||`` (Make sure that you download the file to the Micro:bit drive")
```blocks
let Temperature = 0
basic.forever(function () {
    Temperature = input.temperature()
    basic.showNumber(Temperature)
})
```
## Step 8
Congratulations, you did it!

