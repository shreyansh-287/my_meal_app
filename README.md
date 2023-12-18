# Meals App

# Recording

https://github.com/shreyansh-287/my_meal_app/assets/108536541/989fa4db-a9b4-4ef3-a0c3-5f8daec4895e

## Overview

The **Meals App** is an engaging mobile application designed for exploring and discovering a diverse array of dishes across various categories. The app features an intuitive user interface, including an expandable menu in the top left corner, giving users the option to set filters for meals or navigate to the main page. On the main page, users encounter food categories presented as tiles, leading to visually appealing and animated pages with detailed information about each dish. The app further enhances the user experience by providing a star button to add or remove dishes from favorites. Users can view their favorite dishes through a bottom navigation bar, which offers options to switch between food categories and their favorite dishes.

## Features

### Expandable Menu and Filters

The app incorporates an expandable menu in the top left corner, allowing users to set filters for meals or return to the main page with ease.

**Flutter Properties Used:**
- **AppBar Widget:** Used to create the app bar, featuring an expandable menu.
- **Drawer Widget:** Implemented for the expandable menu, providing a clean and organized user interface.

### Main Page with Food Categories

The main page displays a variety of food categories, such as Italian and Indian, in tile format, enabling users to explore different cuisines effortlessly.

**Flutter Properties Used:**
- **GridView Widget:** Employed to present food categories in an aesthetically pleasing grid layout.
- **GestureDetector Widget:** Used to capture user clicks on each category tile, guiding them to the next page.

### Animated Details Page

Upon selecting a category, users are directed to an animated details page with captivating UI and seamless animations, providing in-depth information about each dish.

**Flutter Properties Used:**
- **Hero Widget:** Utilized for smooth transitions and animations between the main page tiles and the details page.
- **ListView and Card Widgets:** Implemented to present detailed information about each dish in a structured and visually appealing manner.

### Favorites Functionality

The app introduces a star button for users to add or remove dishes from their favorites, enhancing personalization.

**Flutter Properties Used:**
- **State Management:** Employed to handle the state of favorite dishes, allowing for dynamic updates.
- **BottomNavigationBar Widget:** Implemented for easy navigation between food categories and the user's favorite dishes.

## Usage

To use the Meals App, follow these steps:

1. Clone the repository to your local machine.
2. Open the project in a Flutter-compatible IDE.
3. Run the app on an emulator or physical device.

Explore a world of delicious dishes and tailor your culinary experience with the Meals App!

## Dependencies

- Flutter: 3.10.6
- Dart: 3.0.6

## Contributors

**Shreyansh Pathak**
