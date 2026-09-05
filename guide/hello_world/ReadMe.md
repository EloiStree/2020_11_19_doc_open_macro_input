We are going to play https://hordes.io/ with a gamepad ;)

{Insert image of https://hordes.io/}

GOMI is a remapping tool and the Hordes is not playable with a gamepad.  
So let's make the game playable with controller.   

Required:
- A Window computer
- Any controller (Xbox, Nes, Playstation)

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


