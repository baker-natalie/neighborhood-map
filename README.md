# Houston Museum Finder
### This app is being built for project 5 of Udacity's Front-End Developer Nanodegree

## Project Requirements
- **Interface Design**
  - All components should render on-screen in a responsive manner
  - All components should be useable across modern desktop, tablet, and phone browsers.
- **App Functionality**
  - Should include text input or dropdown menu that filters map markers and list items to locations matching the text input of selection. Should run error-free.
  - A list-view of location names should display all locations by default, and filtered locations when filter is applied. Clicking a location on the list should display information about the location, and animate its map marker. Should run error-free.
  - Map should display all location markers by default, and the filtered subset of location markers when a filter is applied.
  - Clicking a marker should display location information in an infowindow or DOM element.
  - Markers should animate when clicked.
  - Custom functionality should run error-free.
- **App Architecture**
  - Code should be properly organized based upon Knockout best practices
    - MVVM pattern
    - Avoid updating DOM maually with jQuery or JS
    - Use observables rather than forcing refreshes manually
    - Knockout should not be used to handle the Google Map API.
  -There are at least 5 locations hard-coded in the model.
- **Asynchronous Data Usage**
  - App should utilize Google Maps API and at least one non-Google third-party API.
  - All data requests should be retrieved in an asynchronous manner.
  - Failed data requests should be handled gracefully using common fallback techniques. There should be some visible indication that it didn't load.
- **Location Details Functionality
  - Addition data about locations should be provided and sourced from a 3rd party API. Information can be provided in the marker's infoWindow, or an HTML element in the DOM.
  - Provide attribution for additional data. Indicate your use of the API somewhere in the UI and in the README.
  - App runs without errors.
  - App functionality is usable and responsive.
- **Documentation**
  - README file should detail all steps required to run application.
  - Comments should effectively explain longer code procedures.
  - Code should be formatted with consistent, logical, and easy-to-read formatting: see [Udacity Javascript Style Guide](http://udacity.github.io/frontend-nanodegree-styleguide/javascript.html)
  - Source and production code should be submitted in the same repository in separate directories.
- **Make Your Project Stand Out!**
  - Add unique functionality.
  - Incorporate a build process allowing for production quality, minified code to be delivered to the client.
  - Data persists when the app is closed and reopened.
  - Include additional third-party data sources.
  - Style different markers in different (and functionally-useful) ways.
  - Implement additional optimizations that improve performance and UX of the filter functionality.
  - Integrate all app components into a cohesive and enjoyable user experience.
