# Meal Planning App Assignment

## 1. Introduction

The Meal Planning App provides users with an organized platform to discover, plan, and curate their meals. It enables users to navigate through different meal categories, view detailed recipes, and set their dietary preferences.

## 2. User Stories

- **As** a health-conscious individual with a busy schedule, **I want** to be able to create a weekly meal plan using the Meal Planner App, so that I can maintain a balanced diet, save time on meal preparation, and reduce food waste.
- **The Meal Planner App**, allows me to view recipes, add recipes to my favorites, and search for specific categories of meals, like ‘Exotic’.

## 3. Specifications

- **Platform:** Flutter (cross-platform: iOS, Android)
- **State Management:** Using Providers for centralized state management.
- **Theming:** Custom light and dark themes using Flutter's ThemeData.
- **Data Model:** Category and Meal models with respective properties.
- **Data Source:** Dummy data for meals and categories.

## 4. File and Folder Structure

meals/
│
├── lib/
│ ├── data/
│ │ └── dummy_data.dart
│ │
│ ├── models/
│ │ ├── category.dart
│ │ └── meal.dart
│ │
│ ├── providers/
│ │ ├── favorites_provider.dart
│ │ ├── filters_provider.dart
│ │ └── meals_provider.dart
│ │
│ ├── screens/
│ │ ├── categories.dart
│ │ ├── filters.dart
│ │ ├── meal_details.dart
│ │ ├── meals.dart
│ │ └── tabs.dart
│ │
│ ├── widgets/
│ │ ├── category_grid_item.dart
│ │ ├── main_drawer.dart
│ │ ├── meal_item.dart
│ │ ├── meal_item_trait.dart
│ │ └── main.dart
│ │
│ └── main.dart
│
├── assets/ (if any)
│
├── pubspec.yaml
└── README.md


- **data:** Contains the dummy data source for the application.
- **models:** Holds the data structures and classes used.
- **providers:** Manages state and data throughout the app.
- **screens:** Individual screens/pages of the app.
- **widgets:** UI building blocks and reusable components.
- **main.dart:** Where the application is run from.

## 5. Added Function

The function I have added is the ability to search for a category on the main page. The search bar can be found at the very top of your screen, and allows you to input, for example, the letter ‘E’. This removes all categories that don’t contain the letter 'E', allowing you to find the ‘Exotic’ category easier.
