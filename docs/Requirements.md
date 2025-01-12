# Requirements

## Links
- [Requirements](#requirements)
  - [Links](#links)
  - [Core Features](#core-features)
  - [Functional Requirements](#functional-requirements)
  - [Technical Requirements](#technical-requirements)
    - [Performance](#performance)
    - [Reliability](#reliability)
    - [Accessibility](#accessibility)
    - [Scalability](#scalability)
    - [Data Handling](#data-handling)
    - [Security](#security)
    - [Deployment](#deployment)
    - [Integration](#integration)

## Core Features

| **Feature**                   | **Description**                                                       | **Priority** | **Change**   |
|-------------------------------|-----------------------------------------------------------------------|--------------|--------------|
| Meal Suggestions              | Provide meal suggestions factoring in budget and preferences.         | 3            | No           |
| Budget Input                  | Accept user’s budget and calculate meals accordingly.                 | 3            | No           |
| Ingredient Cost Estimation    | Estimate meal costs based on local or average ingredient prices.      | 3            | Yes          |
| Meal Filters                  | Allow users to filter meals by dietary preferences or cooking time.   | 3            | Yes          |
| Smart Fridge                  | Suggest meals based on available ingredients and expiration dates.    | 2            | Yes          |
| Shopping List Generator       | Generate a shopping list for selected meals.                          | 2            | No           |
| Favorites and History         | Save favorite meals and provide a list of recently suggested dishes.  | 2            | No           |
| Ingredient Substitution       | Suggest cost-effective alternatives for ingredients.                  | 2            | No           |
| Offline Mode                  | Save user data and meal lists locally for offline access.             | 1            | No           |
| Push Notifications            | Notify users about expiring ingredients or meal ideas.                | 1            | No           |

| **Priority** | **Meaning**    |
|--------------|----------------|
| 3            | Essential      |
| 2            | Nice to have   |
| 1            | Low priority   |

## Functional Requirements

- Meal Suggestions
    - Allow users to discover meal ideas quickly based on budget, number of people, and preferences.
- Meal Filters
    - Allow users to filter meals based on preferences (vegetarian, spicy, etc.) and cooking time.
- Budget-based Planning
    - Users input a budget, and the app suggests meals within the given limit.
    - Provide a cost breakdown for ingredients.
- Smart Fridge
    - Suggest meals based on ingredients the user already has at home.
    - Help minimize food waste by prioritizing soon-to-expire ingredients.
- Cost Estimation for Ingredients
    - Estimate the total cost of meals based on current or average market prices.
    - Include alternative ingredient suggestions to stay within budget.
- Favorites and History
    - Enable users to save favorite meal ideas.
    - Provide access to recently suggested meals.
- Shopping List Generator
    - Automatically create a shopping list for the suggested meal.
    - Mark items already purchased or available at home.
- Offline Mode
    - Save user data and meal lists locally for offline access.
- Push Notifications
    - Notify users about expiring ingredients or suggest meal ideas to utilize those ingredients.

## Technical Requirements

Technical requirements describe the technical aspects and issues that need to be addressed for the project or software to work and execute successfully. These aspects include performance concerns, reliability, and accessibility. Essentially, technical requirements serve as solutions to technical issues.

### Performance
- Optimize for fast loading times, especially on mobile devices.
- Ensure smooth interactions, even with complex data inputs like ingredient lists or meal filters.

### Reliability
- Ensure the app remains stable during meal suggestions and data input processes.
- Handle network interruptions gracefully, particularly for offline mode.
- Include error handling for invalid user inputs or missing data.

### Accessibility
- Create a responsive and mobile-friendly UI to accommodate various devices.
- Ensure compliance with accessibility standards (e.g., WCAG) for visually impaired users.

### Scalability
- Design the architecture to support additional features in the future (e.g., user-generated recipes).
- Ensure the database can handle increased data as the user base grows.

### Data Handling
- Store user preferences, favorites, and meal data locally using IndexedDB or SQLite for offline use.
- Sync data to the backend when online to provide a seamless experience.

### Security
- Use encryption for storing sensitive user data.
- Sanitize all user inputs to prevent injection attacks.
- Secure API endpoints and ensure data integrity during communication.

### Deployment
- Host on a reliable cloud platform like Azure or AWS for scalability and uptime.
- Implement CI/CD pipelines for automated testing and deployment.
- Support PWA (Progressive Web App) features to allow installation and offline functionality.

### Integration
- Optionally integrate with third-party APIs for real-time ingredient pricing.
- Enable future support for community recipe sharing through external platforms or APIs.
