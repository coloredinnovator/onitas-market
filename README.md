<div align="center">
  <h2>Onitas Market — Multivendor Delivery Platform</h2>
  <i>A modern, customizable platform for managing online ordering and delivery operations across industries.</i>
 <br/>
<br />
</div>

<div align="center">

[![Static Badge](https://img.shields.io/badge/License-MIT-red)](./LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/coloredinnovator/Onitas-market-)](https://github.com/coloredinnovator/Onitas-market-/graphs/contributors)

</div>

<br>

Onitas Market is a complete multivendor delivery management system designed for businesses looking to deploy a ready-to-use platform for online ordering and logistics. Whether it's food delivery, grocery delivery, parcel logistics, home services, pharmacy orders, or other delivery-based businesses, Onitas Market adapts to your needs.

Built with scalability and ease of use in mind, the system supports multiple vendors and service regions. With dedicated applications for customers, vendors, delivery riders, and a comprehensive admin dashboard, Onitas Market enables you to launch and operate your own end-to-end ordering and delivery ecosystem.

<!-- Add a horizontal rule for separation -->
<hr/>

## :fast_forward: Quick Links

- [:book: What is included](#heading-1)
- [:rocket: Features](#heading-2)
- [:wrench: Setup](#heading-3)
- [:gear: Prerequisites](#heading-4)
- [:computer: Technologies](#heading-5)
- [:triangular_ruler: High Level Architecture](#heading-7)
- [:page_with_curl: Documentation](#heading-8)
- [:computer: Project Setup Guide](#heading-15)

<!-- Add a horizontal rule for separation -->
<hr/>

## :question: What is included: <a id="heading-1"></a>

Onitas Market provides a complete set of software components, including:

- Customer Mobile App (React Native / Expo)
- Rider / Driver Mobile App (React Native / Expo)
- Vendor / Store Mobile App (React Native / Expo)
- Customer Ordering Website (Next.js)
- Admin Web Dashboard (Next.js)
- Analytics Dashboard using Amplitude
- Error monitoring and reporting with Sentry

## :fire: Features: <a id="heading-2"></a>

- Authentication using Google, Apple, and Facebook
- Dynamic home sections for highlighting top vendors and services
- Push notifications and email alerts for account creation, order updates, and delivery progress
- Real-time tracking of delivery agents and in-app chat
- Email and phone number verification
- Location-based vendor discovery on Maps and Home Screen
- Multi-language support and customizable themes
- Ratings and reviews for orders and service experiences
- Vendor/service details including ratings, schedules, delivery timelines, offerings, location, minimum order amount, and more
- Payment integrations including PayPal and Stripe
- Order and booking history with the ability to favorite vendors
- Address management with Google Places suggestions and Maps integration
- Analytics and error reporting with Amplitude and Sentry
- Support for item/service variations, notes, pickup and delivery modes, and customizable timing options


## :repeat_one: Setup: <a id="heading-3"></a>

The solution includes five separate modules. To set up these modules, follow the steps below:

You need to have Node.js installed on your machine (version 18–20). Once Node.js is installed, navigate to the directory and enter the following commands.

## :information_source: Prerequisites: <a id="heading-4"></a>

App Ids for Mobile App in app.json

- Facebook Scheme
- Facebook App Id
- Facebook Display Name
- iOS Client Id Google
- Android Id Google
- Amplitude Api Key
- Server URL

Set credentials in environment files:

- Firebase configuration
- Google Maps API Key
- Sentry DSN
- Server URLs (GraphQL, WebSocket, REST)

## :hammer_and_wrench: Technologies: <a id="heading-5"></a>

|                                               Expo                                                |                                                   React-Navigation                                                   |                                                Apollo GraphQL                                                |                                               ReactJS                                                |                                                NodeJS                                                 |                                                 MongoDB                                                 |                                                   Firebase                                                   |
| :-----------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------: |
| <a href="https://expo.dev/"><img src="./assets/expoicon.png" alt="Expo" width="100"></a> | <a href="https://reactnavigation.org/"><img src="./assets/react-navigation.png" alt="React Navigation" width="100"></a> | <a href="https://www.apollographql.com/"><img src="./assets/apollo.png" alt="Apollo" width="100"></a> | <a href="https://reactjs.org/"><img src="./assets/react-js.png" alt="React" width="100"></a> | <a href="https://nodejs.org/en/"><img src="./assets/node-js.png" alt="Node" width="100"></a> | <a href="https://www.mongodb.com/"><img src="./assets/mongoDB.png" alt="MongoDB" width="100"></a> | <a href="https://firebase.google.com/"><img src="./assets/firebase.png" alt="Firebase" width="100"></a> |

|                                                 React Native                                                 |                                                       React Router                                                       |                                                GraphQL                                                |                                                ExpressJS                                                 |                                                Amplitude                                                |
| :----------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------: |
| <a href="https://reactnative.dev/"><img src="./assets/react-native.png" alt="React Native" width="100"></a> | <a href="https://reactrouter.com/"><img src="./assets/react-router-svgrepo-com.png" alt="React Router" width="100"></a> | <a href="https://graphql.org/"><img src="./assets/graphQl-1.png" alt="GraphQL" width="100"></a> | <a href="https://expressjs.com/"><img src="./assets/express-js.png" alt="Express" width="100"></a> | <a href="https://amplitude.com/"><img src="./assets/amplitude.png" alt="Amplitude" width="100"></a> |

## :wrench: High Level Architecture: <a id="heading-7"></a>

![](./assets/high-level.webp)

## :book: Documentation <a id="heading-8"></a>

See the [Project Setup Guide](#heading-15) below for detailed instructions on running each component.

## :warning: Disclaimer: <a id="heading-12"></a>

The frontend source code for this solution is open source under the MIT license. The backend API is proprietary and requires a separate license agreement.

## :computer: Project Setup Guide <a id="heading-15"></a>

This section provides detailed instructions for setting up and running each component of the Onitas Market platform.

### Admin Dashboard (Next.js)

The admin dashboard allows you to manage restaurants, orders, riders, and more.

```bash
# Navigate to the admin dashboard directory
cd enatega-multivendor-admin

# Install dependencies
npm install

# Start the development server
npm run dev
```

After running these commands, open your browser and navigate to [http://localhost:3000](http://localhost:3000) to access the admin dashboard.

### Customer Web (Next.js)

The customer web application allows users to browse vendors and place orders through a web browser.

```bash
# Navigate to the customer web directory
cd enatega-multivendor-web

# Install dependencies
npm install

# Start the development server
npm run dev
```

### Customer App (React Native / Expo)

```bash
# Navigate to the customer app directory
cd enatega-multivendor-app

# Install dependencies
npm install

# Start the Expo development server
npx expo start -c
```

### Rider App (React Native / Expo)

```bash
# Navigate to the rider app directory
cd enatega-multivendor-rider

# Install dependencies
npm install

# Start the Expo development server
npx expo start -c
```

### Store / Vendor App (React Native / Expo)

```bash
# Navigate to the store app directory
cd enatega-multivendor-store

# Install dependencies
npm install

# Start the Expo development server
npx expo start -c
```

### Testing on a Physical Device (Expo Go)

1. Press `s` in the terminal to switch to Expo Go mode
2. Scan the QR code displayed in the terminal:
   - Android: Open the Expo Go app and scan the QR code
   - iOS: Use the device's camera app to scan the QR code

---

## License

This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for details.
