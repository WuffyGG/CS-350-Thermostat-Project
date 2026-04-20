# Smart Thermostat Project (CS 350 Portfolio)

## Included Artifacts

- **Thermostat.py**: Final smart thermostat system integrating multiple hardware components, including a temperature sensor, LCD display, LEDs, buttons, and UART communication.
- **Milestone3.py**: Earlier implementation demonstrating state machine logic, LED control, and button interaction.

---

## Project Summary

This project focused on building a smart thermostat prototype using a Raspberry Pi and various hardware components. The goal was to simulate a real-world embedded system that can monitor temperature, respond to user input, and communicate data. The system uses a temperature sensor to read environmental data, buttons to control the thermostat state and setpoint, LEDs to indicate heating and cooling behavior, and an LCD display to show system information. The thermostat also sends data over UART to simulate communication with a server. This project demonstrates how hardware and software can be integrated to solve real-world problems.

---

## What I Did Well

One of my strengths in this project was successfully integrating multiple hardware components with software. I was able to correctly wire and configure the temperature sensor, LCD display, LEDs, and buttons, and connect them through GPIO, I2C, and UART interfaces. I also implemented a working state machine to control the thermostat logic, which handled transitions between off, heat, and cool states. Debugging issues with wiring, connectivity, and code helped me better understand how embedded systems function as a whole.

---

## Areas for Improvement

One area I could improve is planning and organization before starting implementation. At times, I relied on trial and error when debugging wiring or code issues. In the future, I would spend more time designing the system and mapping out connections and logic before building. I could also improve my efficiency with debugging tools and error handling to make troubleshooting faster.

---

## Tools and Resources

Throughout this project, I used several tools and resources that I will continue to use in the future. These include the Raspberry Pi platform, Python programming, Visual Studio Code for editing code, SSH and SCP for remote file transfer, and official documentation for hardware components. I also relied on course materials and guides to better understand embedded systems concepts and implementation.

---

## Transferable Skills

This project helped me develop several skills that will transfer to other courses and projects. These include working with GPIO, I2C, and UART interfaces, building and using state machines, debugging both hardware and software issues, and integrating multiple system components into a single application. These skills are valuable for embedded systems, full-stack development, and general problem-solving in software engineering.

---

## Maintainability and Readability

I made this project maintainable and readable by organizing the code into logical sections and using clear function and variable names. The use of a state machine helped separate logic and made the system easier to understand and extend. I also followed a consistent structure throughout the code, which improves readability and makes it easier for others to modify or build upon in the future.
