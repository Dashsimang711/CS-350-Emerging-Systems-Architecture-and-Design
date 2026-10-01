### CS 350 Module Eight Journal

**Summarize the project and what problem it was solving.**

The project I selected was the smart thermostat project. The goal was to create a working thermostat prototype using a Raspberry Pi and several hardware components. The thermostat used an AHT20 temperature sensor to read the room temperature, LEDs to show whether the system was heating or cooling, buttons to control the thermostat, an LCD to display information, and UART to simulate sending data to a server. The project solved the problem of creating a basic embedded thermostat system that could collect information from sensors, respond to user input, display information, and communicate with another system.

**What did you do particularly well?**

I think I did well with connecting the different parts of the project together and troubleshooting problems when something did not work correctly. Throughout the course, I gained experience working with GPIO, PWM, I2C, UART, buttons, LEDs, and the LCD. I also learned how a state machine can be used to organize the different operating states of a device. When I ran into problems with the Raspberry Pi, wiring, or locating files, I learned how to work through the problem instead of starting over. Getting the hardware and software working together was one of the most useful parts of the project.

**Where could you improve?**

One area I could improve is becoming more comfortable writing and troubleshooting the code without relying as much on step-by-step instructions. I sometimes spent extra time locating files or figuring out why a program was not running. I would also like to improve my understanding of how the individual hardware components communicate with the Raspberry Pi. With more practice, I would be able to identify problems faster and make changes to the code more independently.

**What tools and/or resources are you adding to your support network?**

The main tools and resources I am adding to my support network are Raspberry Pi documentation, Python documentation, GPIOZero documentation, and resources for working with I2C and UART. I also found that using the Linux command line and commands such as `ls`, `cd`, and `python` is important when working with the Raspberry Pi. Draw.io was also useful for creating the state machine diagram and documenting how the system operates. These resources will be useful when I work on future embedded systems and programming projects.

**What skills from this project will be particularly transferable to other projects and/or course work?**

The most transferable skills I gained are troubleshooting, Python programming, working with hardware peripherals, and breaking a larger problem into smaller parts. I learned that embedded systems require both software and hardware to work together correctly. I also gained experience using state machines, interrupts, sensors, displays, and communication interfaces. These skills can be used in future programming, software development, IoT, and embedded systems projects.

**How did you make this project maintainable, readable, and adaptable?**

I made the project more maintainable by organizing the code into logical sections for the different hardware components and functions. Comments and descriptive names help explain what different parts of the program are doing. Using a state machine also makes the thermostat easier to understand because each operating state has a specific purpose. The design can also be adapted because additional features could be added without completely changing the existing structure. For example, the prototype could eventually be connected to Wi-Fi and a cloud server so that thermostat information could be sent remotely.
