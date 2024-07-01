# CS-350-Emerging-Systems-Architectures-and-Technologies-
CS 350: Emerging Systems Architectures and Technologies - cc3220s launchPad



Here's how you can organize and reflect on your projects for your GitHub portfolio:

---

## Portfolio Submission

### Project Artifacts

For this assignment, I've selected two projects from this course that best reflect my talents and skills in emerging systems architectures and technologies. These projects demonstrate my ability to write interface software to control hardware components, analyze fundamental considerations regarding hardware architecture design and their impact on application performance, and recommend and justify emerging systems architectures and technologies based on business requirements. 

You can view the projects in my [GitHub repository](https://github.com/WwiseAudioMaker/CS-350-Emerging-Systems-Architectures-and-Technologies-/edit/main/README.md)).

### Project Reflections

#### Project 1: Simple State Machine (Module 5)
**Summary:** 
This project involved designing and coding a simple state machine that controls an LED based on user input. When a user types "ON" into the console, the LED turns on, and when the user types "OFF," the LED turns off. The challenge was to achieve this using only 1 byte of RAM.

**What I Did Well:** 
I managed to create an efficient state machine with minimal memory usage, which is critical in embedded systems with limited resources. The simplicity and efficiency of the code were my main strengths.

**Where I Could Improve:** 
While the project was functional, I could improve by adding error handling to manage unexpected inputs and ensure the system remains stable under various conditions.

**Tools and Resources Added to Support Network:** 
For this project, I relied on resources such as the course materials, online forums, and documentation for the specific microcontroller I used. These resources helped me understand the constraints and capabilities of the hardware.

**Transferable Skills:** 
The skills I gained in designing state machines and optimizing memory usage are highly transferable to other embedded systems projects. Understanding how to efficiently manage hardware resources will be beneficial in future coursework and professional projects.

**Maintainability, Readability, and Adaptability:** 
I ensured that the code was well-documented, with clear comments explaining each part of the state machine. This makes the project easy to maintain and adapt for future enhancements.

#### Project 2: Synchronous State Machine with Morse Code (Module 5)
**Summary:** 
In this project, I designed a synchronous state machine that blinks an LED in Morse code. The message that the LED relays changes when a button is pushed.

**What I Did Well:** 
I effectively implemented the Morse code logic and ensured that the state machine operated synchronously, providing accurate timing for the LED blinks.

**Where I Could Improve:** 
The project could be improved by adding more flexibility in changing messages and incorporating debounce logic for the button press to avoid false triggers.

**Tools and Resources Added to Support Network:** 
I used online Morse code references and microcontroller datasheets to understand timing requirements and ensure accurate implementation.

**Transferable Skills:** 
The experience in handling synchronous operations and timing constraints is valuable for any real-time embedded systems work. It also improved my understanding of state machines and user interactions.

**Maintainability, Readability, and Adaptability:** 
I wrote modular code with separate functions for each part of the state machine, making it easy to read and adapt. Comments and documentation were added to describe the functionality and timing logic.

### Additional Project: GPIO Interrupt Modification (Module 7)
**Summary:** 
This project aimed to modify the `gpiointerrupt.c` file to monitor buttons every 200ms, check temperature every 500ms, and update an LED and report to a server via UART every second. The specific requirements included adjusting the temperature set-point based on button presses and controlling the LED based on temperature conditions.

**What I Did Well:** 
I successfully integrated multiple timing functions and ensured that all tasks ran concurrently without interfering with each other. The project also demonstrated effective use of UART communication for reporting to a server.

**Where I Could Improve:** 
I could enhance the robustness of the system by adding more comprehensive error handling and improving the efficiency of the temperature monitoring algorithm.

**Tools and Resources Added to Support Network:** 
For this project, I used microcontroller documentation, UART communication protocols, and various online tutorials on embedded systems design.

**Transferable Skills:** 
The skills in integrating multiple hardware components and managing concurrent tasks are highly applicable to complex embedded systems. The experience with UART communication is also beneficial for future projects involving data transmission.

**Maintainability, Readability, and Adaptability:** 
I structured the code to separate different functionalities into distinct functions and modules, making it easier to understand and modify. Clear comments and documentation were provided to explain the logic and flow of the program.

---

By reflecting on these projects, I've gained a deeper understanding of my strengths and areas for improvement. This exercise also helps me prepare for future projects by building on the skills and knowledge I've acquired in this course.
