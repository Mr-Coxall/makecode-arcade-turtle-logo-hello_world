### @explicitHints true

```template
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
```

# Turtle Logo - "Hello, World!"

## Introduction @unplugged

In this tutorial you will create your first Turtle Logo program. You will get a turtle showing up in your game console and have it say, "Hello, World!".

![Hello, World!](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-hello_world/raw/main/assets/hello_world_screenshot.png)

## Step 1
Welcome to coding with Turtle Logo.

Turtle Logo uses MakeCode Arcade to teach the fundamentals of programming. You will drag blocks of code into a sequence of steps to tell the **turtle** what to do. You can see some starter code below and the output in the game controller on the left hand side.

## Step 2
It is tradition with programmers when they start using a new programming language to get the computer to say ["Hello, World!"](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program#:~:text=A%20%22Hello%2C%20World!%22%20program%20generally%20is%20a%20computer,by%20people%20learning%20to%20code.) back to them. This might seem strange but just getting the computer to say something back to you can sometime be very complex.

## Step 3
You will need 3 blocks to make this happen and the first 2 are already provided for you below. All our programs will have an ⇢``on start``⇠ block. This block runs all the commands that are inside it as soon as the program begins.
```blocks

```

## Step 2
Into the provided code below, drag out the ⇢``myTurtle move forward 25 steps``⇠ block and then see what happens to your **Turtle**.
```blocks
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
myTurtle.say("Hello, World!")
```

## Step 3
Hopefully you noticed the **Turtle** moved forwards and it left a trail behind when it moved.
![Turtle move forward](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-moving_and_turning/raw/main/assets/move_forward_screenshot.png)

## Step 4
You can change the **25** to different numbers to make it move more or less. You can also select the **forward** tab and change the direction to **backwards** to make it move in the opposite direction.
![Turtle move forward](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-moving_and_turning/raw/main/assets/move_backwards_screenshot.png)

## Step 5
Try moving the **Turtle** backwards 50 steps.
```blocks
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
myTurtle.say("Hello, World!")
```
## Step 6
Hopefully you noticed the **Turtle** moved like the image below.
![Turtle move forward](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-moving_and_turning/raw/main/assets/move_turtle_backwards_screenshot.png)

## Step 7
Besides forwards and backwards, the **Turtle** can also turn. You use the ⇢``myTurtle turn right by 90°``⇠ block to turn the **Turtle**. Try making the **Turtle**:
- move forward 30 steps
- turn right 90°
- move forward 30 more steps
```blocks
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
myTurtle.say("Hello, World!")
```

## Step 8
Hopefully you noticed the **Turtle** moved like the image below.
![Turtle move forward](https://github.com/Mr-Coxall/makecode-arcade-turtle-logo-moving_and_turning/raw/main/assets/move_and_turn_screenshot.png)

## Step 9
Done.

You now know how to make the **Turtle** move and turn.

```ghost
let myTurtle = turtle.fromSprite(sprites.create(img`
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . e e . . . . . . . . 
    . . . . . e e e e . . 7 7 7 . . 
    . . . . e e e d e e . 7 7 f 7 . 
    . . . e e e e e d e e 7 7 7 7 . 
    . . . e e d e e e e e 7 7 7 . . 
    . . 7 e e e e e e e e . . . . . 
    . 7 . 7 7 7 7 7 7 7 7 . . . . . 
    . . . 7 7 7 7 7 7 7 7 . . . . . 
    . . 7 7 7 . . . . 7 7 7 . . . . 
    . . 7 7 7 . . . . . 7 7 . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    . . . . . . . . . . . . . . . . 
    `, SpriteKind.Player))
myTurtle.say("Hello, World!")
```
