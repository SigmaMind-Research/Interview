# Interview Task: Flutter Demo Application

## Overview
The purpose of this task is to assess your Flutter skills, focusing on both UI design and API connectivity. You are required to create a Flutter demo application that interacts with the provided API: [https://demo-xfol.onrender.com](https://demo-xfol.onrender.com). The application should have the following features:

1. **Splash Screen:**
   - Display a splash screen when the application is launched.

2. **Group Page:**
   - After the splash screen, fetch and display the list of groups using the API endpoint `/group/`.
   - Each group should be represented as a button.
   - When a user taps on a group button, navigate to the User Page.

3. **User Page:**
   - Display a list of users related to the selected group.
   - Retrieve user data from the API endpoint `/user/{groupid}/`.
   - Include a back button to return to the Group Page.

4. **Patients Page:**
   - Create a separate UI page that displays a list of patients.
   - Retrieve patient data from the API endpoint `/patients/`.
   - Include a search bar on this page.
   - Users should be able to search for a patient by ID using the API endpoint `/patient/{patientid}`.

## Task Requirements

1. **UI Design:**
   - Pay attention to the overall design and user experience.
   - Use appropriate Flutter widgets for navigation, buttons, lists, and search functionality.
   - Ensure a responsive and visually appealing layout.

2. **API Connectivity:**
   - Utilize the provided API [https://demo-xfol.onrender.com](https://demo-xfol.onrender.com) for fetching group, user, and patient data.
   - Implement error handling for API requests.
   - Use Flutter's `http` or any other relevant package for API communication.

## Submission Instructions

1. **Git Repository:**
   - Create a Git repository for your Flutter project.
   - Commit your code regularly, providing clear and concise commit messages.

2. **Readme:**
   - Include a well-documented `README.md` file in your repository.
   - Clearly explain how to run and test your Flutter application.
   - Provide any additional information or considerations that may be relevant.
   - **Add video of screen record to `README.md` file** 

3. **Code Structure:**
   - Organize your code into appropriate folders and files.
   - Ensure that your code follows Flutter best practices.

## Additional Information

- Feel free to use any state management solution (e.g., Provider, Bloc) if needed.
- While creativity is encouraged, focus on meeting the specified requirements.

## Evaluation Criteria

Your submission will be evaluated based on the following criteria:

1. **UI Design:**
   - Clarity and aesthetics of the user interface.
   - Responsiveness and visual appeal.

2. **API Connectivity:**
   - Successful integration with the provided API.
   - Proper error handling.

3. **Code Quality:**
   - Well-organized code structure.
   - Adherence to Flutter best practices.

4. **Task Completion:**
   - Successful implementation of all specified features.

## Deadline

**Please complete the task and submit your Git repository link by 25th December 2023. After completion of task please send the link of your git repo to gaurgulshan@sigmamind.xyz or you can create a pull request to this repo [submit branch].**  
If you encounter any issues or have questions, feel free to reach out to me. We look forward to reviewing your submission.

Happy coding!
