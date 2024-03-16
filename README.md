# Little Lemon Food Ordering App

- The application is a React Native Expo Food app.
- Users will be capable of signing up on the Little Lemon restaurant app.
- Users will have to go through a registration process.
- Once they successfully complete that phase, they are redirected to a home screen.
- Home screen will represent the landing screen after completing the onboarding flow, displaying a header, a banner with a search bar and a list of menu items where a user can filter each categories.
- User can also customize their name, email, photo and and other user preferences through a Profile Screen.
- Profile screen also contains four checkboxes enable specific email notifications, like order status, password changes,special offers, and newsletters.
- Use AsyncStorage module to preserve the chosen preferences even when the user quits the application
- When clicking the Logout button, user will redirect back to login page, clearing all data saved from Profile.
- Use SQLite Database to populate, query and filter menu items.

### What I learned

- Create a React Native App using Expo
- Create a wireframe and high fidelity mockup using Figma.
- Use ContextAPI for login
- Use React Navigation (Native Stack) for screen routes.
- Use ImagePicker API to set user Profile Picture
- Use useFonts Hook from expo-fonts to set custom fonts
- Use AsyncStorage to store user settings.
- Use getItem and setItem methods to read and set data to AsyncStorage
- ConnectAsyncStorage to a state
- Use SQLite to store Menu Items
- Connect SQLite to a state
- Create form validation for users
- Handling side-effects using useEffect Hook
- Use FlatList component to render menu
- Use ScrollView component to render categories title
- Use View, View, Text Components
- Extract all styles to StyleSheet API

