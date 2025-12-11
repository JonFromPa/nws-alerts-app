# 🌩️ Active NWS Alerts by U.S. State or Territory

This is a single-file, responsive web application that fetches and displays current, active weather alerts for any chosen US State or Territory, directly from the National Weather Service (NWS) API.

The application features a modern interface, a sticky header for usability, and dynamic expansion/collapse of alert details.

## ✨ Features

  * **Real-time Data:** Fetches active alerts directly from the official NWS public API.

  * **State Picker:** Easy-to-use grid for selecting any US state or territory.

  * **Responsive Design:** Optimized for mobile, tablet, and desktop viewing.

  * **Sticky Header:** The header remains fixed at the top of the viewport when scrolling, keeping key information visible.

  * **Dynamic Collapse:** Only one alert description can be expanded at a time, improving readability and navigation.

  * **Severity Indicators:** Alerts are colored and styled based on the severity reported by the NWS.

  * **External Links:** Direct links to the official NWS public notification page for each alert.

## 🚀 Live Demo

This application is hosted for free using GitHub Pages:

&nbsp;&nbsp;&nbsp;&nbsp;[**View the Live Application Here**](https://jonfrompa.github.io/nws-alerts-app/)

<!--*(Note: Replace `[YOUR-GITHUB-USERNAME]` and `[YOUR-REPOSITORY-NAME]` with your actual GitHub account and repository name after deployment.)*-->

## 🛠️ Technology Stack

This is a pure client-side application and requires no backend server.

  * **HTML5:** Structure and content.

  * **CSS3:** Styling (fully customized).

  * **JavaScript (jQuery):** Logic for API calls, state management, and DOM manipulation (especially the smooth sliding/collapsing effects).

  * **External API:** [NWS Alerts API (`api.weather.gov`)](https://www.weather.gov/documentation/services-web-api/)

## 💻 Local Setup (Running the HTML File w/o Server Hosting)

Since this is a single, self-contained HTML file, you can run it locally without a web server.

1.  **Download the File:** Save the file `active_alerts_by_state.html` to your computer.

2.  **Open in Browser:** Double-click the file. It will open directly in your default web browser (Chrome, Firefox, Safari, etc.).

3.  **Start Using:** The application will load the state picker, allowing you to select a state to view alerts.

## 📍 Setting a Default State (Optional)

You can view alerts for a specific state immediately by using a query parameter in the URL:

  * Add `?state=CA` (or any other U.S. two-letter state / territory code) to the end of the URL in your browser's address bar.

      * **Example Default State URL:** [`https://jonfrompa.github.io/nws-alerts-app/?state=TX`](https://jonfrompa.github.io/nws-alerts-app/?state=TX)

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
