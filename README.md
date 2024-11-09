# Custom Alert Demo

This is a simple web page that demonstrates a custom alert system using Bootstrap and jQuery. The page provides buttons to trigger various types of alerts with different styles, such as primary, secondary, success, danger, etc. The alerts are styled dynamically with CSS and are displayed as floating modal-style alerts in the center of the screen.

## Features

- Custom alerts that can be triggered by clicking buttons.
- Alerts support different Bootstrap alert types: primary, secondary, success, danger, warning, info, light, and dark.
- Alerts have a close button (styled with a Bootstrap icon) that allows users to dismiss them.
- Alerts automatically fade out and disappear after 5 seconds.
- The alert style is dynamically applied using JavaScript/jQuery and Bootstrap classes.

## How to Use

1. Open the HTML file in a web browser.
2. Click one of the buttons to display the corresponding alert.
3. The alert will appear in the center of the screen, with a close button to dismiss it.
4. The alert will automatically disappear after 5 seconds or when the close button is clicked.

## Dependencies

- [Bootstrap 5.3.0-alpha1](https://getbootstrap.com/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [jQuery 3.6.0](https://jquery.com/)

## Code Explanation

1. **HTML Structure**: The HTML contains a series of buttons that trigger the custom alert when clicked. Each button has a Bootstrap class for styling.
2. **Custom Alert Styling**: The alert is styled using CSS dynamically inserted into the page by jQuery. It includes positioning and animation to center the alert on the screen.
3. **Custom Alert Logic**: The default `alert()` function is overridden with a custom version using jQuery. When a button is clicked, a custom alert is created and appended to the body.
4. **Alert Dismissal**: Each alert includes a close button with a Bootstrap icon (`bi-x-lg`) that removes the alert from the screen when clicked.
5. **Auto Fade-Out**: The alert will automatically fade out after 5 seconds, thanks to the `setTimeout` function.

## Demo

You can view the demo by simply opening the HTML file in your browser. Clicking any of the buttons will display an alert with the corresponding message and styling.

## License

This project is open source and available under the [MIT License](LICENSE).
