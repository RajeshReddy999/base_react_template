# Base React Template

## Overview

This project is a starter template for building React applications. It follows a well-organized folder structure to separate concerns and improve maintainability. The template includes a basic setup for React components, Redux, API integration, and context management.

## Folder Structure

```
public - static files

src
    - assets
        - css
        - fonts
        - images
        - sass
        - webfonts
    - components
        - authentication
			- SignUp.jsx
			- SignIn.jsx
			- SignOut.jsx
            - admin
                - settings
                    - Settings.jsx
                - home
                    - Home.jsx
                - about
                    - About.jsx
                - utils
                    - BlogArticle.jsx
            - user
                - home
                    - Home.jsx
                - about
                    - About.jsx
                - utils
                    - Article.jsx
    - context
    - api
        - home
        - errorLogging
    - env
    - redux
    - config
    - utils
        - header
        - footer
        - chatwindow
        - whatsapp
        - back-to-top
        - copyright
        - social-media-icons
        - errorLogging.jsx
        - uploader
        - messaging-client-server
        - notification-server-client
    - mobile
        - components
            - authentication
                - SignIn.js
                - SignUp.js
                - SignOut.js
                - admin
                    - settings
                        - settings.js
                    - home-page
                        - Home.js
                    - about-page
                        - About.js
                    - utils
                        - BlogArticle.js
                - user
                    - home-page
                        - Home.js
                    - about-page
                        - About.js
                    - utils
                        - BlogArticle.js
        - assets
            - css
            - fonts
            - images
            - sass
            - webfonts
        - context
        - api
            - home
            - errorLogging
        - env
        - redux
        - config
        - utils
            - header
            - footer
            - chatwindow
            - whatsapp
            - back-to-top
            - copyright
            - social-media-icons
            - errorLogging.js
            - uploader
            - messaging-client-server
            - notification-server-client
```

## Description

### public

- static files: Contains static assets like HTML files and public images.

### src

- assets: Contains various types of assets.

  - css: Stylesheets.
  - fonts: Font files.
  - images: Images.
  - sass: SASS/SCSS files.
  - webfonts: Web font files.

- components: Contains all React components.

  - authentication: Components related to authentication.
    - admin: Admin-specific components.
      - settings: Settings related components.
        - `settings.jsx`: Settings page component.
      - home-page: Admin home page components.
        - `Home.jsx`: Admin home page component.
      - about-page: Admin about page components.
        - `About.jsx`: Admin about page component.
      - utils: Utility components for admin.
        - `BlogArticle.jsx`: Blog article component.
    - user: User-specific components.
      - home-page: User home page components.
        - `Home.jsx`: User home page component.
      - about-page: User about page components.
        - `About.jsx`: User about page component.
      - utils: Utility components for user.
        - `BlogArticle.jsx`: Blog article component.
    - signin: Sign-in component.
      - `SignIn.jsx`: Sign-in page component.
    - signup: Sign-up component.
      - `SignUp.jsx`: Sign-up page component.
    - signout: Sign-out component.
      - `SignOut.jsx`: Sign-out page component.

- context: Contains context providers and consumers for state management.

- api: Contains API-related files.

  - home: Home-related API files.
  - errorLogging: Error logging related API files.

- env: Environment configuration files.

- redux: Redux-related files for state management.

- config: Configuration files.

- utils: Utility functions and components.

  - header: Header components.
  - footer: Footer components.
  - chatwindow: Chat window components.
  - whatsapp: WhatsApp integration components.
  - back-to-top: Back-to-top button components.
  - copyright: Copyright components.
  - social-media-icons: Social media icon components.
  - `errorLogging.jsx`: Error logging utility.
  - uploader: File uploader components.
  - messaging-client-server: Messaging client-server components.
  - notification-server-client: Notification server-client components.

- mobile: Contains all mobile-specific components and assets.
  - components: Contains all mobile React Native components.
    - authentication: Components related to authentication.
      - signin: Sign-in component.
        - `SignIn.js`: Sign-in page component.
      - signup: Sign-up component.
        - `SignUp.js`: Sign-up page component.
      - signout: Sign-out component.
        - `SignOut.js`: Sign-out page component.
      - admin: Admin-specific components.
        - settings: Settings related components.
          - `settings.js`: Settings page component.
        - home-page: Admin home page components.
          - `Home.js`: Admin home page component.
        - about-page: Admin about page components.
          - `About.js`: Admin about page component.
        - utils: Utility components for admin.
          - `BlogArticle.js`: Blog article component.
      - user: User-specific components.
        - home-page: User home page components.
          - `Home.js`: User home page component.
        - about-page: User about page components.
          - `About.js`: User about page component.
        - utils: Utility components for user.
          - `BlogArticle.js`: Blog article component.
  - assets: Contains various types of assets.
    - css: Stylesheets.
    - fonts: Font files.
    - images: Images.
    - img: Additional images.
    - sass: SASS/SCSS files.
    - webfonts: Web font files.
  - context: Contains context providers and consumers for state management.
  - api: Contains API-related files.
    - home: Home-related API files.
    - errorLogging: Error logging related API files.
  - env: Environment configuration files.
  - redux: Redux-related files for state management.
  - config: Configuration files.
  - utils: Utility functions and components.
    - header: Header components.
    - footer: Footer components.
    - chatwindow: Chat window components.
    - whatsapp: WhatsApp integration components.
    - back-to-top: Back-to-top button components.
    - copyright: Copyright components.
    - social-media-icons: Social media icon components.
    - `errorLogging.js`: Error logging utility.
    - uploader: File uploader components.
    - messaging-client-server: Messaging client-server components.
    - notification-server-client: Notification server-client components.

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

Visit `http://localhost:3000` in your browser to view the application.

### Folder Details

- **`public/index.html`**: The HTML template for the application.
- **`src/assets/styles`**: Contains global and theme-specific styles.
- **`src/components`**: React components are organized into common and authentication-specific directories.
- **`src/context`**: Provides context for authentication and theme.
- **`src/api`**: Service files for API calls.
- **`src/config`**: Configuration files for API endpoints and app settings.
- **`src/redux`**: Setup for Redux state management.
- **`src/utils`**: Reusable components and utility functions.

## Contributing

Feel free to submit issues, feature requests, or pull requests. Please follow the project's coding standards and guidelines.

## License

This project is licensed under the MIT License.
