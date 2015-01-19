### RoboLib
RoboLib is a remake of the [WPILib][wpilib] libraries provided by [FIRST][first] for all frc robots. The main reason we decided to remake it was to optimize it. Currently we only have a Java version, because thats the language this library was created for. We will however convert it to C++ and maybe Python later on, if it become popular enough.

### Documentation
[RoboLibJ - RoboLib Java version][docs-robolibj]

### Why is this a thing?
* WPILibJ is not optimized for java. It is as close to a copy paste of C++ as possible.
 * Not to say its a bad library, but... Guys, you dont need to get every solenoid port each time a new one is created.
* WPILib is not the easiest to use
* I wanted to make somthing
* We needed an API that would be easy to teach to the new programmers

### Using RoboLib
We wanted to make using RoboLib as easy as possible.

When we get to making it as easy as possible, we will let you know.

Right now it involves editing the WPILib ant build script and some other stuff.. We will be realeasing an eclipse plugin later.

### Contributing
Feel free to fork and edit the library. When you finish, just send a pull request.



Anyone is free to use/remake/release inside the terms of the License.

[docs-robolibj]: http://robolib.github.io/robolibj/docs "RoboLibJ Documentation"
[wpilib]: https://usfirst.collab.net/sf/sfmain/do/viewProject/projects.wpilib "WPILib"
[first]: http://www.usfirst.org/roboticsprograms/frc "FIRST FRC"
