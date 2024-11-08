
# PTO Manager

PTO Manager is a simple web application that allows users to manage their Paid Time Off (PTO). It includes features for selecting an employer, viewing and interacting with two calendars to select start and end dates for PTO, and adding PTO requests.

## Features
- **Employer Selection**: Users can select an employer from a dropdown list.
- **Calendars**: Two calendars are provided for selecting the start and end dates of the PTO.
- **Add PTO**: Users can add a PTO request once the dates are selected.
- **Log Out**: A button for logging out of the application.

---

## Project Structure

The project is organized into the following structure:

```
PtoManager/
│
├── index.html               # Main HTML file for the PTO Manager page
├── styles/
│   ├── normalize.css        # CSS for normalizing default browser styles
│   └── style_pto.css        # Custom styles for the PTO Manager page
├── scripts/
│   ├── sign_out.js          # JavaScript for log out functionality
│   ├── calendar.js          # JavaScript for handling calendar interactions
│   └── pto.js               # JavaScript for handling PTO addition logic
└── README.md                # This README file
```

## Usage

### Select Employer
1. In the "Select employer" dropdown, choose the employer for whom you want to request PTO.

### Select Dates
1. Use the **first calendar** to select the **start date** of your PTO.
2. Use the **second calendar** to select the **end date** of your PTO.

### Add PTO
1. After selecting the start and end dates, click the **"Add PTO"** button to submit your PTO request.

### Log Out
- Click the **"Log out"** button to log out of the application.

---

## Files Explanation

### HTML (`index.html`)
The main structure of the web page is defined here. It includes two calendars for start and end date selection and a button for logging out.

### CSS (`style_pto.css` & `normalize.css`)
- `normalize.css`: This is used to normalize the default styling across browsers.
- `style_pto.css`: Contains custom styles for the PTO Manager page, including layout and calendar design.

### JavaScript (`sign_out.js`, `calendar.js`, `pto.js`)
- **`sign_out.js`**: Handles the functionality for logging out.
- **`calendar.js`**: Controls the calendar interactions, such as displaying dates and navigating between months.
- **`pto.js`**: Handles the logic for adding and managing PTO requests.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

