# pwmled2
- Summarize the project and what problem it was solving?
  This project focuses on controlling LED intensity using Pulse Width Modulation (PWM) on a Texas Instruments microcontroller. The program alternates the duty cycle of two PWM signals to change the brightness of two LEDs, effectively creating a visual display or indicator. The application is useful in scenarios requiring visual alerts or signals, such as indicating device statuses or alerts in industrial or consumer electronics settings.

- What did you do well?
  The project effectively utilizes PWM to control LED brightness, demonstrating an understanding of both hardware capabilities and software implementation for real-time signal management. The project is straightforward, focusing solely on PWM control without unnecessary complications, which makes the behavior easy to understand and verify.

- Where could you improve? 
  While the project works well for its intended purpose, it could be expanded to include user interaction, such as adjusting the brightness or the pattern of the LEDs through external inputs like buttons or sensors. Also the program enters an infinite loop if the PWM channels fail to open, which might not be the most effective way to handle errors. Implementing a more sophisticated error handling mechanism could improve the robustness of the application.

- What tools and/or resources are you adding to your support network?
  The main tools employed in this project are the Code Composer Studio IDE and the relevant Texas Instruments hardware for PWM control. Future projects could benefit from integrating additional debugging and simulation tools to test and refine PWM control strategies before deployment on actual hardware.

- What skills from this project will be particularly transferable to other projects and/or course work?
  Learning to control PWM can be applied to various applications, including motor control, lighting systems, and signal generation. Managing timing and hardware interfaces in real-time is a crucial skill in many embedded systems and IoT applications.

- How did you make this project maintainable, readable, and adaptable?
  The code is structured clearly, separating PWM setup from the main operational loop, which simplifies modifications and troubleshooting. Defining critical values such as PWM period at the beginning of the file makes the program adaptable to different hardware setups or requirements by editing a few lines. Although minimal, the existing comments and structured code blocks provide a basic understanding of the program flow and operations, which can be built upon for more detailed documentation.
