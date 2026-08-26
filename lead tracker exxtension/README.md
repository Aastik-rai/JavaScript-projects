# Lead Tracker Extension

A simple Chrome extension built with JavaScript that helps save and manage profile URLs as leads.

I built this project while learning JavaScript to practice working with the DOM, event listeners, arrays, local storage, and Chrome extension APIs.

## Features

* **Save Current Tab** — Save the URL of the currently active browser tab with one click.
* **Add Leads Manually** — Enter and save a URL manually.
* **Persistent Storage** — Saved leads are stored in the browser using `localStorage`.
* **Open Leads** — Click any saved URL to open it in a new tab.
* **Delete All Leads** — Double-click the delete button to clear all saved leads.

## Technologies Used

* HTML
* CSS
* JavaScript
* Chrome Extension APIs
* Local Storage

## How It Works

### 1. Save a URL manually

Enter a profile URL in the input field and click the save button.

### 2. Save the current tab

Open a profile in the browser and click the **Save Tab** button. The extension uses the Chrome Tabs API to get the URL of the active tab.

### 3. View saved leads

All saved URLs are displayed inside the extension. Clicking a URL opens the profile in a new browser tab.

### 4. Delete saved leads

Double-click the **Delete All** button to remove all saved leads from local storage.

## What I Learned

This project helped me practice:

* Selecting HTML elements using JavaScript
* Adding event listeners
* Working with arrays
* Creating and rendering dynamic HTML
* Using template literals
* Using `localStorage`
* Converting data with `JSON.stringify()` and `JSON.parse()`
* Using the Chrome Tabs API
* Building and working with a browser extension

## Future Improvements

* Add individual delete buttons for each lead
* Add search functionality
* Add lead names instead of storing only URLs
* Add categories or tags for leads
* Improve the UI and user experience
* Add timestamps for saved leads

## Project Status

🟢 Completed as a learning project.

More features may be added as I continue learning JavaScript.
