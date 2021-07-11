# Interflowing Physics Minigames Design and Display Platform
## Basically no further changes after July 2017

Runtime Environment: 
1. Use Processing3
2. JRE 1.7.0_40 
3. Under the relatively root path of "Interflowing" 
4. Install in-app library by: Sketch->Import Library->Add Library->Libraries->Box2D for Processing | Daniel Shiffman.
5. Run the main access: "Interflowing.pde"

This project is programmed in 'Processing', which is an open-source graphical library and integrated development environment built for visual design. It was only for fun, but also has won several national and provincial prizes. Besides I tried to commercialise it(also for fun) but not succeeded xD. 

It can be defined as an agile development platform, but it actually is the combination of three different parts: programming-free physics minigames development platform and automatic programming code generator, which has been shown in this repository, as well as the projects presentation and management platform.

For more straightforward comprehension, you can [download and watch the display video of this project.](display_video.mp4)
### Design purpose
In the field of computer games, light creative physics games are the most distinctive, like the Flappy Bird and Fruit Ninja. Such kind of games have very low development costs, but usually with significant creativity and playability. If this characteristic can be rationally used, then it can create an extremely reasonable profit. However, the flashpoints of people's favour are very hard to catch. Hence, is there a possibility to implement people's ideas more efficiently and smoothly, then dominated by the quantity of it?

It is also crucial to diminish the gap between people and technology -- not everyone has the abilities to make their idea come true, not only about programming but also art design as well as audio production. For solving this common demand, a set of solutions were proposed which can meet the needs of human-computer interaction. Using this technology demo, users can use no matter what device at no matter which places, and quickly express their ideas for physics minigames and directly export the reproducible prototype products without entering any single line of code. People can record their inspiration and ideas only like producing pictures on the 'MSPaint', which is feasible for all ages.

The project as a complete software ecosystem is divided into three following modules:

### First module: 'Cavans'(Done)
By using it, you can draw everything you want very conveniently, even the logical relationship.

### Second module: 'Code Generator'(Done) 
By using it, you can directly get the industrial-level code which has been implemented while you are drawing things on 'Cavans', and can be used by professionals for agile development

### Third module: 'Ideas Centre'(Undone)
By having it users can create and release their creative designs and projects at this website(also platform), and others can play, social, clone, modify and pull requests just like people are doing here in GitHub. It also allows users to share and exchange ideas, organise teamwork, or even make money by the clicks of advertisement which is attached to their project.

### The units have been implemented:

1. set_ball
2. set_bomb
3. set_rectangle
4. set_particle
5. set_line
6. set_fixed_dot
7. set_rocker_controller
8. set_paddle
9. set_slingshot
10. set_curve
11. set_bridge

### The functions have been implemented:

1. eraser_mode_on/off 
2. select_object
3. selected_object_follow_mouse_icon_on/off
4. selected_object_horizontal_movement_only_on/off
5. boundary_on/off
6. attravction_of_fixed_dot_on/off
7. gravity_on/off
8. elastic_property_on/off
9. start/finish_record_operation
10. add_logic(add_trigger)
11. pause/resume
12. clear_cavans

## Function_Demo_1: Run this platform fluently on every device of every operating system.
![alt text](https://github.com/SylvanLiu/PhysicsMinigamesDesignPlatform/blob/master/Display/Cross_platform.gif)

## Function_Demo_2: Record operations, export the generated source code, reproduce it by running on compiler. 
![alt text](https://github.com/SylvanLiu/PhysicsMinigamesDesignPlatform/blob/master/Display/Code_generator.gif)

## Game_Demo_1: Simple reproduction of Bricks Ball Crusher.
![alt text](https://github.com/SylvanLiu/PhysicsMinigamesDesignPlatform/blob/master/Display/game_demo_1.gif)

## Game_Demo_2: Simple reproduction of Angry Birds.
![alt text](https://github.com/SylvanLiu/PhysicsMinigamesDesignPlatform/blob/master/Display/game_demo_4.gif)

## Game_Demo_3: Simple space mod. (In old interface style)
![alt text](https://github.com/SylvanLiu/PhysicsMinigamesDesignPlatform/blob/master/Display/game_demo_5.gif)

## Game_Demo_4: Simple maze game. (In old interface style)
![alt text](https://github.com/SylvanLiu/PhysicsMinigamesDesignPlatform/blob/master/Display/game_demo_3.gif)

## Modules Setting(Simplified Chinese)
![alt text](https://github.com/SylvanLiu/PhysicsMinigamesDesignPlatform/blob/master/Display/P3.png)

## Editions Planning(Simplified Chinese)
![alt text](https://github.com/SylvanLiu/PhysicsMinigamesDesignPlatform/blob/master/Display/P4.png)
