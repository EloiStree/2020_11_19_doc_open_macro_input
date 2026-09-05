We are going to play https://hordes.io/ with a gamepad ;)

{Insert image of https://hordes.io/}

GOMI is a remapping tool and the Hordes is not playable with a gamepad.  
So let's make the game playable with controller.   

Required:
- A Window computer
- Any controller (Xbox, Nes, Playstation)

Optional:
- A second monitor.

--------------------

Step: "Hello World"
- Install Firefox and create account on Hordes.io
- Install Python and download S2W that inject input in Firefox
- Download GOMI and say "Hello"
- Use a button of your controller to jump.


Step: "Move"
- Map the joysticks to the movement in game
- Map the buttons to power in game.
- Make a macro that open the map and close it.


Step: "File Overview"
- What are the basic file to use


--------------------

#  Step: "Hello World"

Our missions is to allows player to be able to play the https://hordes.io/ with a controller.

For that we need a software that can read controller and a software that can simulate input.

You can downlaod the two here:
- GOMI: https://github.com/EloiStree/GOMI/releases
- S2W: https://github.com/eloistree/s2w

GOMI is the one you read input and have fun coding around.   
S2W is a python code that allows to simulate input or inject them if the game architecture allows it.   

Firefox is a browser that understand key injection on Window.
Your can download it here:
https://www.firefox.com/en-US/

> 🤔 Why we need to inject key ?

When you learn to code by playing game or learn to remap on the same computer.
Being in the editor and in the game can be a bit tedious.

So by injecting key, you can stay in your code while playing on your seconds screen.
23



#  Step: "Move"

-

#  Step: "File Overview"


```.godot_event_to_command_at_ready
FILE>>>|.godot_event_to_command_at_ready

cmd:log Hello World !
In 2000: cmd:log Display two seconds later
```
[Doc](https://github.com/EloiStree/GOMI_DOC/blob/master/file_extension/.godot_event_to_command_at_ready.md)


```.godot_event_to_command_at_focus_exit
FILE>>>|.godot_event_to_command_at_focus_exit
cmd:log AT_FOCUS_EXIT EVENT
```
[Doc](https://github.com/EloiStree/GOMI_DOC/blob/master/file_extension/.godot_event_to_command_at_focus_exit.md)

```.godot_event_to_command_at_focus_enter
FILE>>>|.godot_event_to_command_at_focus_enter
cmd:log AT_FOCUS_ENTER EVENT
```
[Doc](https://github.com/EloiStree/GOMI_DOC/blob/master/file_extension/.godot_event_to_command_at_focus_enter.md)

```.godot_event_to_command_at_exit
FILE>>>|.godot_event_to_command_at_exit
cmd:log AT_EXIT EVENT
```
[Doc](https://github.com/EloiStree/GOMI_DOC/blob/master/file_extension/.godot_event_to_command_at_exit.md)


