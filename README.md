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
-API does not return updated values when updating and creating the users.
-Cannot filter all the users because the API does not give search parameters.
-The sort functionality works only on the selected page because the API does not give all the users at once.
```
