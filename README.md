# CanvasPlayground

CanvasPlayground is an tool that you can easily draw images. Using the game.js file you can add simple logic to draw images and change their positions. Events and other stuff are coming soon.

# Main Functions (where to type code)

## init

Init is the function that is run on body load.

## Update

Update updates at the rate declared in start.html.

## Draw

Draw updates at the rate the browser allows. This is the place to draw images.

# Non-required functions that can be used

## mouseup

Calls function when user releases mouse button.

## mousedown

Calls function when user holds mouse button.

## mousemove

Calls function when user moves mouse.

# Functions usable in game.js

## drawImage(img,x,y,width,length)

Draws image. There are 500 hundred images ready for you to use. Check their name in the image folder and type it in img.

## LoadImg(nameOfImage)

Put your own custom image in the image folder and use it! (WARNING! BE SURE FOR IT TO NOT BE WITH THE SAME NAME AS AN EXISTING ONE!)

## areColliding(Ax, Ay, Awidth, Aheight, Bx, By, Bwidth, Bheight)

Function to check if two rectangles are colliding.

## randomInteger(upTo)

Makes generating random integers easier and more simpler.

## isFunction(f)

Checks if the given parameter is a function. Returns boolean.

# Global Variables

<ol>
<li>MouseX - Mouse on X position
<li>MouseY - Mouse on Y position
</ol>
