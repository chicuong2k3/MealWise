# Requirements

## Links
- [Requirements](#requirements)
  - [Links](#links)
  - [Core Features](#core-features)
  - [Functional Requirements](#functional-requirements)
  - [Technical Requirements](#technical-requirements)

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

Functional requirements describe the specific behaviors, features, and functions the system must perform to meet user needs and project objectives. These requirements define what the system should do, detailing the interactions between users and the system, including inputs, processes, and expected outputs. Functional requirements are solutions to user-centered needs and ensure the application delivers on its primary purpose.

- Meal Suggestions: Allow users to discover meal ideas quickly based on budget, number of people, and preferences.
- Meal Filters: Allow users to filter meals based on preferences (e.g., vegetarian, spicy, allergen-free) and cooking time.
- Budget-based Planning: Users input a budget, and the app suggests meals within the given limit. Provide a cost breakdown for ingredients.
- Smart Fridge: Suggest meals based on ingredients the user already has at home. Prioritize soon-to-expire ingredients to minimize food waste.
- Cost Estimation for Ingredients: Estimate the total cost of meals based on current or average market prices. Include alternative ingredient suggestions to stay within budget.
- Favorites and History: Enable users to save favorite meal ideas and access recently suggested meals.
- Shopping List Generator: Automatically create a shopping list for the suggested meal and allow users to mark purchased items.
- Offline Mode: Save user data and meal lists locally for offline access.
- Push Notifications: Notify users about expiring ingredients or meal ideas to use them effectively.

## Technical Requirements

Technical requirements describe the technical aspects and issues that need to be addressed for the project or software to work and execute successfully. These aspects include performance concerns, reliability, and accessibility. Essentially, technical requirements serve as solutions to technical issues.

- The application will be built with .NET 8 to leverage its performance improvements and modern features.
- If LLM usage is included, prioritize a lightweight language model capable of running on end-user hardware for efficient operation.
- Use SignalR for real-time updates if live data is required (e.g., ingredient pricing updates).

