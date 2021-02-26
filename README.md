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

In this tutorial you will create your first Turtle Logo program using Makecode Arcade. You will get a turtle showing up on your screen and have it say, "Hello, World!".

## Step 1
**Turtle Logo - "Hello, World!"**

Welcome to coding with Turtle Logo. Turtle Logo uses MakeCode Arcade to teach the fundamentals of programming. You will drag blocks of code into a sequence of steps to tell the **turtle** what to do. You can see the output in the game controller on the left hand side.

## Step 2
**Turtle Logo - "Hello, World!"**

It is tradition with programmers when they start using a new programming language to get the computer to say ["Hello, World!"](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program#:~:text=A%20%22Hello%2C%20World!%22%20program%20generally%20is%20a%20computer,by%20people%20learning%20to%20code.) back to them. This might seem strange but just getting the computer to say something back to you can sometime be complex.

## Step 3
**Turtle Logo - "Hello, World!"**

You will need 3 blocks to make this happen and the first two are already provided. All programs will have an ``on start`` block. This block runs all the commands that are inside it as soon as the program begins.
```blocks

```

## Step 4
**Turtle Logo - "Hello, World!"**

Next you will need to create your turtle. To do this you will use the ``set myTurtle to turtle of sprite ▢ of kind Player`` block and place it inside the ``on start`` block. Each new turtle object in your program will need one of these. This creates the turtle object and gives it a name - or more technically a [variable](https://tinyurl.com/95n35y8w), that you can use as a reference in your program.
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
```

## Step 5
**Turtle Logo - "Hello, World!"**

Now that we have a turtle object, you can ask it to say something. Drag out the ``myTurtle say "Hello, World!" ⊕`` block and place it inside the ``on start`` block at the bottom.

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
**Turtle Logo - "Hello, World!"**

Success!

Notice to the left, your object is now saying "Hello, World" for 1 second and then it words vanish.

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
