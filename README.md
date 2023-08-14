# Robotic Process Automation

Demonstrating the process that goes into automating the process through which job-cards are generated for customers complaints in a customer care center with UiPath. 

 This project focused on automating tasks involving Excel and a web application (Zoho Desk). The automation was modularized into logical components, including Excel processing, Zoho interaction, and the main workflow. This modular approach ensures a clean and organized project structure.

## Key Learning Points

During this project, we learned and implemented several important concepts:

- Utilized arguments to efficiently pass data between different parts of the workflow.
- Employed variables to store and manage data within the automation process.
- Gained familiarity with Try-Catch blocks to handle exceptions gracefully.
- Used If control structures to manage conditional logic based on true-false conditions.

The effort invested in this project has provided a strong foundational understanding of RPA concepts, setting the stage for tackling more complex projects.

## Project Enhancement

1. **Rename Request Files:** After processing, the automation should rename the Request file to "Request + Date Timestamp" before moving it to the Requests folder. This enhancement aims to organize queries chronologically, making it easier to manage similar queries.

2. **Capture All Fields:** Enhance the Zoho ticket creation process to capture all fields, not just the mandatory three. This improvement ensures comprehensive information is included in each ticket, enhancing query tracking and resolution.

3. **Enhanced Attended Automation:** Build upon the existing attended automation by adding a feature to stop the automation using a hotkey. This provides users with greater control over the execution process.

## Repository Structure

- https://github.com/sarahgumbe/RPA/blob/master/Main.xaml: The main workflow orchestrating the automation process.
- https://github.com/sarahgumbe/RPA/blob/master/ReadRequest.xaml: Workflow for reading and processing request data.
- https://github.com/sarahgumbe/RPA/blob/master/SaaSAutomation.xaml: Workflow for automating interactions with Zoho Desk.

## Contributions

Contributions are welcome! If you have ideas for further enhancements or improvements, feel free to create pull requests. Please ensure you adhere to coding standards and guidelines.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or feedback, feel free to contact us at [your-email@example.com](mailto:your-email@example.com).

Thank you for being part of this automation journey!

