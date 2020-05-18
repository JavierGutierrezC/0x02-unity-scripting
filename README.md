<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/19/Unity_Technologies_logo.svg/275px-Unity_Technologies_logo.svg.png" alt="drawing" width="300"/>
</p>

# 0x02. Unity - Scripting

## 0. Ready player one
Clone this repository containing a ```maze``` Unity project. You will build on this project by adding new GameObjects and scripts to create a playable game. This project should be pushed to its own repo called ```0x02-unity-scripting```, not within a subdirectory.

## 1. Bust a move 
Create a directory ```Scripts```. In this directory, create a new C# script called ```PlayerController.cs```. Attach this script to the ```Player``` object. Within this script, update the ```Start()``` and ```FixedUpdate()``` functions to allow the ```Player``` to move when either the WASD or arrow keys are pressed

## 2. Camera ready 
Move the ```Main Camera``` to position ```(22, 26, 7)```. Create a new C# script in the Scripts directory called ```CameraController.cs```.

## 3. Insert coin 
Create a new Cylinder GameObject named ```Coin```.

## 4. Coin collecting 
Create a new C# script called ```Rotator.cs``` and attach it to ```Coin```.

## 5. Danger zone 
Create a new Plane GameObject named ```Trap```.

## 6. You've activated my trap card 
Add a new ```public int health``` variable to your ```PlayerController.cs``` script. Set the initial value of ```health``` to ```5```.

## 7. The finish line 
Create a new Plane GameObject named ```Goal```.

## 8. Goaaaaaaaaaaal 
In ```PlayerController.cs```, add to the existing ```void OnTriggerEnter(Collider other)``` function.

## 9. Game over 
Create an ```Update()``` function within ```PlayerController.cs```.

## Author

Javier Gutierrez  | [https://github.com/JavierGutierrezC](https://github.com/JavierGutierrezC)
