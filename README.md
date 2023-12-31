# PID Model 104 Software Development

## To-Do List

1. ✅**Define Software Architecture:**
   - Outline the overall structure and design principles for the Menu Software (Version 121023) and associated modules.

2. ✅**Setup Development Environment:**
   - Establish a development environment with necessary tools, libraries, and frameworks for firmware development.

3. ✅**Implement PID Operating Software:**
   - Develop the core PID functionality for both channels (0-500 ppm and 0-5,000 ppm) with optional configurations for different ranges.

4. ✅**Keypad and Menu Navigation Implementation:**
   - Interpret signals from the 4-position keypad and implement functionality for menu navigation (MODE, Up Arrow, Down Arrow, Select).

5. ✅**Display Integration:**
   - Interface with the 2.4” OLED display to present relevant information, configurations, and menu options.

6. **Configuration Options Software:**
   - Develop software to support different configurations: PID ppm, PID ppm & ppb optional, PID and Compound Specific modes.
   - "PPB" not finished
   - *Estimated Completion Date: 01/05/2024*

7. ✅**Calibration Software Development:**
   - Create a calibration menu with options for zero calibration, calibration gas value adjustment, and calibration gas selection.

8. ✅**Alarm System Implementation:**
   - Develop software to set alarm values and control the activation or deactivation of alarms through the menu.

9. **Log Menu Software Implementation:**
   - Implement manual and automatic logging of gas concentration data with options for turning off logging.
   - *Estimated Completion Date: MM/DD/YYYY*

10. **Setup Software Development:**
    - Develop software for configuring time parameters and setting background zero (BKG Zero) for baseline correction.
    - *Estimated Completion Date: MM/DD/YYYY*

11. **Power Management Implementation:**
    - Implement efficient power management to maximize battery life and monitor battery status.
    - *Estimated Completion Date: MM/DD/YYYY*

12. **Exit Menu Software Development:**
    - Develop functionality to safely exit the menu system and transition to standby or power-off modes.
    - *Estimated Completion Date: MM/DD/YYYY*

13. **Error Handling Implementation:**
    - Implement robust error handling to manage unexpected events or user input and display clear error messages.
    - *Estimated Completion Date: MM/DD/YYYY*

14. **User Interface Software Development:**
    - Design and implement a cohesive and user-friendly interface that integrates all menu options seamlessly.
    - *Estimated Completion Date: MM/DD/YYYY*

15. **Documentation Preparation:**
    - Prepare comprehensive documentation for end-users and maintenance personnel, covering software functionalities, calibration procedures, and troubleshooting steps.
    - *Estimated Completion Date: MM/DD/YYYY*

16. **Testing and Debugging:**
    - Conduct thorough testing of each software module, addressing any bugs or issues identified during the testing phase.
    - *Estimated Completion Date: MM/DD/YYYY*

17. **Integration Testing:**
    - Ensure seamless integration of all software components and validate overall system functionality.
    - *Estimated Completion Date: MM/DD/YYYY*

18. **Firmware Update Mechanism:**
    - Implement a mechanism for firmware updates, ensuring the device can be easily updated with the latest software.
    - *Estimated Completion Date: MM/DD/YYYY*

19. **Final Testing and Quality Assurance:**
    - Conduct a final round of testing to ensure the software meets all requirements and quality standards.
    - *Estimated Completion Date: MM/DD/YYYY*

20. **Deployment:**
    - Prepare the finalized software for deployment onto the Portable Gas Analyzer Model 103.
    - *Estimated Completion Date: MM/DD/YYYY*

21. **Post-Deployment Support:**
    - Provide ongoing support for users, addressing any issues that may arise after deployment.
    - *Estimated Completion Date: MM/DD/YYYY*
   
<img width="464" alt="image" src="https://github.com/PID-Analyzers-Software/Model103/assets/26637782/2690395b-ba03-4f5b-90ce-0bf5832a8b1d">


## EEPROM Offset Table
| Parameter           | Offset (Bytes) |
|---------------------|----------------|
| TIMER               | 0              |
| GAS_SLOPE           | 8              |
| GAS_SELECT          | 24             |
| GAS_INTERCEPT       | 28             |
| GAS_SECONDP         | 36             |
| GAS_INTERCEPT2      | 44             |
| GAS_SECONDP2        | 52             |
| GAS_INTERCEPT3      | 60             |
| GAS_SECONDP3        | 68             |
| GAS_INTERCEPT4      | 76             |
| GAS_SECONDP4        | 84             |
| DEVICE_ID           | 92             |
| WIFI_SSID           | 124            |
| WIFI_PASSWORD       | 156            |
| RANGE               | 188            |
| Calvalue            | 190            |
| ALARM               | 192            |

