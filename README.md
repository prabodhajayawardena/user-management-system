### Dependencies Used

-   Redux for the state management tool.
-   redux-persist library for persisting the state of the app.
-   react-router library for routing purposes.
-   Material UI as a UI Library.
-   For the custom stylings, used styled components.

## Available Scripts

## Quick Setup

Install packages

```
npm install
```

## Adding environment variables

```
Refer the env.example file in the root directory and add the content of that file to a new file .env
```

## Running the App

```
npm start
```

## To run the tests

```
npm run test
```

## Build the App

```
npm run build
```

## Assumptions

```
- Used local storage to store new users and updated users.
- When adding the user, default image is fetched from the unsplash website.
```

## Limitations

```
-reqres.in do not have search endpoint in that case search only work for the currently active page. this also applicable for sort functionality as well.
-Using their update and create endpoints i have created the functionality but they are not really insert or update the data from their end so i have handled that logic in the application.
-I have used material UI table to list data but sticky header functionality only works when  apply a fixed height.
```
