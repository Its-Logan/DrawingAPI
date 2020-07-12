# RobloxDrawingAPI
A multi language Drawing API! It is powerful and simple to use.

# THIS IS A WORK IN PROGRESS! NOT MANY LANGUAGES ARE SUPPORTED *YET*

# ROBLOX Documentation (Unfinished)
ROBLOX Library Link: (Wait to finished)

```* = Required```

> :CreateLine(Parent, StartPosition, EndPosition, Color, Thickness, Objects, SetMiddile) -- Creates a line
>  Parent(Instance) * -- The parent of the new line
>  
>  StartPosition(Vector2) * -- The starting position of the line
>  
>  EndPosition(Vector2) * -- The ending position of the line
>  
>  Color(Color3) -- The color of the line (Default: 0,0,0)
>  
>  Thickness(int) -- How thick the line is (Default: 1)
>  
>  Objects(table) -- The object(s) used from the positions. The first object(instance) is the StartPosition object(instance) and the second object(instance) is the EndPosition object(instance) e.x. {script.Parent.ScreenGui.Frame, script.Parent.ScreenGui.Frame2}
>  
>  SetMiddle(bool) -- Sets the line in the middle of the starting position to the ending position. REQUIRES THE OBJECTS ARGUMENT!
  
## Setting Up
First: Create a *module script* anywhere the *client* can access. And paste the ROBLOX Drawing API Source code in.

![FirstStepRoblox](https://i.gyazo.com/3408e766cac73b662fa95562d74c1f03.png)

Second: Create a *Local script* and require the API (Module script from the first step)

![SecondStepRoblox](https://i.gyazo.com/6d4088e0060127feeda842295fd1f93e.png)

![SecondStepRoblox2](https://i.gyazo.com/c8a012264ef7d3e5a43ff4ba86872a90.png)

:WaitForChild() Is not necessary 

Thats all for setting up!

