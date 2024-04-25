# gpiointerrupt
- Summarize the project and what problem it was solving?
  The gpiointerrupt project involves developing a Morse code generator, using a Texas Instruments microcontroler. The code operates by translating predefined text strings into Morse code signals, represented by LED flashes on the microcontroller board. There are two patterns programmed into the device: SOS and OK. These messages can be toggled back and forth using the button inputs on the board. The project aims to address the need for a simple, and effective way to communicate visually.
  
- What did you do particularly well?
  One of the strong points of this project is the effective use of GPIO interrupts and timer callbacks to manage Morse code timings and user inputs. This real-time processing capability allows the system to react promptly to user inputs and accurately manage the timing of signals. The code is also well-organized into functions and callbacks that manage specific tasks, such as handling button presses or processing Morse code states. This modularity makes the code easier to understand and modify.
  
- Where could you improve?
  While the code includes basic comments, more detailed documentation could be added to describe the functionality of each function and state in the Morse code state machine. Enhancing comments would make the codebase more accessible to new developers or for future maintenance. Also, the system currently supports only two Morse code patterns. A more flexible design could allow for dynamic addition of new patterns without modifying the source code, perhaps by integrating a pattern input interface.
  
- What tools and/or resources are you adding to your support network?
  The primary tools used were the Texas Instruments Code Composer Studio IDE and the corresponding hardware (microcontroller and peripherals). To support future projects, it would be beneficial to explore additional libraries and tools that can offer more advanced functionalities, such as wireless communication modules or more sophisticated sensor integration.
  
- What sills from this project will be particularly transferable to other projects and/or course work?
  Real-time System Programming: Skills in handling interrupts and managing time-sensitive tasks in embedded systems.
  State Machine Design: Ability to design and implement efficient state machines, which are applicable in various software and hardware development contexts.
  
- How did you make this project maintainable, readable, and adaptable?
  By breaking the program into distinct functions and using a clear state machine structure, the code remains organized and easier to manage. Enumerations for states and structs for timing configurations improve readability and make it easier to adjust the program's behavior. And defining timings and configurations at the top of the file and using descriptive names helps in making the system adaptable to different scenarios without deep changes in the logic code.
