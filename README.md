
# Contact List App (React + Tailwind CSS)

This is a simple contact list application built with React and Tailwind CSS. It fetches a list of 200 random users from the `randomuser.me` API and displays them in a responsive grid. The app features a real-time search bar to filter contacts by name.

This project was built to practice React functional components, hooks (`useState`, `useEffect`), data fetching, and utility-first styling with Tailwind CSS.

## Features

* **Fetches 200 Random Contacts:** Pulls user data from the `randomuser.me` API on load.
* **Responsive Contact Grid:** Displays contacts in a responsive grid that adapts from mobile to desktop screens.
* **Real-Time Filtering:** Instantly filters contacts as you type in the search bar.
    * If the query is one letter, it matches names that *start with* that letter.
    * If the query is more than one letter, it matches names that *include* that string.
* **Dynamic Messages:** Displays a "No data matches your search" message when no contacts are found.

## Technologies Used

* **React:** (Functional Components, `useState` & `useEffect` Hooks)
* **Tailwind CSS:** For all styling (utility-first approach).
* **Create React App (CRA)**
* **Craco:** To override the default CRA config and add Tailwind CSS.
* **react-fetch-hook:** A simple hook used for data fetching.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You will need [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed on your machine.

### Installation

1.  Clone the repo:
    ```sh
    git clone [https://github.com/Aditya001-max/Contact_list_app_react.git](https://github.com/Aditya001-max/Contact_list_app_react.git)
    ```
2.  Navigate to the project directory:
    ```sh
    cd Contact_list_app_react
    ```
3.  Install NPM packages:
    ```sh
    npm install
    ```
4.  Run the app:
    ```sh
    npm start
    ```
    This will run the app in development mode using Craco. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Future Improvements

Based on the original tutorial, there are several ways this project can be extended:

* **Add a Navigation Bar:** Create a simple header component.
* **Implement a Refresh Button:** Add a button to fetch a new set of 200 random users.
* **Display Search Result Count:** Show the number of contacts found for a particular query.
* **Add Loading State:** Use the `isLoading` variable from `react-fetch-hook` to display a loading spinner.
* **Add Error State:** Use the `error` variable to display an error message if the API fetch fails.
