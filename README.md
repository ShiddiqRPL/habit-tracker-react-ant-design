# Habit Tracker App

## Description

The **Habit Tracker App** is a simple yet effective way to track and record your daily habits. It allows users to:
- Record habits with history.
- View pinned habits on the main screen.
- Add new records for habits and confirm them through a dialog.
- Manage habits (edit, delete) from a list of all habits.
- Generate habit reports based on weekly or monthly data, or a custom date range.
  
This app provides a user-friendly interface with easy navigation and several useful features to monitor and improve your daily habits.

## User Story

### Main Features
- **Main View:**
  - Displays a list of up to 5 pinned habits. Each pinned habit shows the last recorded date and time in a readable format.
  - If there are fewer than 5 pinned habits, non-pinned habits will be listed below the pinned ones.
  
- **Add Habit History:**
  - You can add a new habit history by tapping on a habit in the list. 
  - A confirmation dialog will appear to confirm the action, and there’s also a cancel button to abort the process.
  - Once the add process is confirmed, the main view will update with the new information.

- **Add New Habit Record:**
  - A button located after the pinned list allows users to add a new habit.
  - Clicking this button changes the view to show a sorted list of all habit data (sorted alphabetically A-Z, 0-9).
  
- **All Habit Data View:**
  - The all habit data list can be searched by habit names through a search box at the top.
  - You can add a new habit history to any habit in this list, similar to how it's done from the main view.
  - A floating button is also available for adding new habit data.

- **Edit/Delete Habit:**
  - Each habit in the data list has action buttons for editing and deleting.
  - If delete is clicked, a confirmation dialog appears to confirm the deletion process.
  
- **Side Menu Drawer:**
  - A side menu provides navigation options with the following menus:
    - **All Habit Data**: View and manage your entire list of habits.
    - **Habit Report**: Generate and view reports of your habits.
    - **About**: Information about the app.
  
- **Habit Reports:**
  - The app allows you to generate habit reports based on:
    - **Weekly**
    - **Monthly**
    - **Custom Date Range**
  - The report will consist of a list of habit names with the average habit counter across the selected date range.

## Installation

To install and run the app locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/ShiddiqRPL/habit-tracker-react-ant-design.git
    ```
2. Navigate into the project folder:
    ```bash
    cd habit-tracker-react-ant-design
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Run the app:
    ```bash
    npm start
    ```
   Open your browser and visit `http://localhost:3000` to view the app.

## Technologies Used

- **React** for building the user interface.
- **React Router** for routing and navigation.
- **Ant Design** for pre-built UI components.
- **React Context** or **Redux** for state management (depending on the implementation).
  
## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
