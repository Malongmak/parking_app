# Car Parking App

This project is a web-based Car Parking system that allows users to register their vehicles in a parking lot. The system stores information like the car owner’s name, plate number, car color, phone number, and the time of entry. The user can easily register their car, view the parking list, and remove any car from the system.

## Features

- **Car Registration**: Users can enter their name, plate number, car color, and phone number to register their car in the parking system.
- **Dynamic Table**: The table displays all the registered cars with details like full name, plate number, car color, phone number, check-in time, and a remove button.
- **Remove Functionality**: Each car entry has a "Remove" button that allows the user to delete it from the parking list.
- **Responsive Design**: The app uses Bootstrap to ensure that it’s fully responsive and looks great on both desktop and mobile devices.

## Technologies Used

- **HTML5**: Structure of the application.
- **CSS3**: Styling and layout of the webpage.
- **Bootstrap 5**: For responsive design and various UI components.
- **JavaScript**: Logic for dynamically adding and removing parking entries.

## Installation

Follow these steps to set up the project locally on your machine:

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/car-parking-app.git
```

### 2. Open the project in your favorite code editor.

### 3. Launch the `index.html` file in your web browser to see the app in action.

## How It Works

1. **Register a Car**: 
   - Enter your **Full Name**, **Plate Number**, **Car Color**, and **Phone Number** into the form on the page.
   - Click the **"Park"** button to register your car.
   
2. **View Registered Cars**:
   - Once you register a car, its details will appear in a table below the form, showing the following columns:
     - **Full Name**: The car owner's name.
     - **Plate Number**: The car’s plate number.
     - **Color**: The car’s color.
     - **Phone Number**: The car owner’s phone number.
     - **Check-in Time**: The time when the car was registered.
     - **Remove**: A button to remove the car from the list.

3. **Remove a Car**:
   - You can click the **Remove** button to delete a car entry from the list. 

## Screenshots

![Image](https://github.com/user-attachments/assets/eba88142-4d03-4524-8527-1ca2a83a46e4)

## Live Demo

You can view a live version of this project (https://papaya-youtiao-6adf9a.netlify.app/).

## Future Improvements

- **User Authentication**: Implement login and registration features for users to save their car details.
- **Data Persistence**: Store car details in a database to persist data across sessions.
- **Payment Integration**: Implement a payment gateway for parking fees.
- **Additional Features**: Option to edit car details or assign a parking spot.

## Contributing

We welcome contributions to this project! If you have suggestions, improvements, or fixes, feel free to fork the repository and create a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).

