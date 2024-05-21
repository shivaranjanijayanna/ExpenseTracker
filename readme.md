## Idea Overview
This project is an expense tracker designed for individuals living together in the same household. The goal is to monitor both individual and group expenditures and present the spending patterns through visual charts.

## User Requirements

### Signup Page:
- New users can sign up using their email address and create a password for their shared apartment.
- Email and password inputs undergo validation, with users receiving an OTP for email verification.
- Users click the signup button to create a new profile.

### Sign-in Page:
- Existing users can log in by entering their email and password.
- Login credentials are validated and authenticated.
- Password reset option is available for users who forgot their password.
- Successful login redirects users to the home page.

### Home Page:
It offers two options:
* New Flat Mate
* Existing Flat Mate

#### New Flat Mate:
1. Users create a username and password.
2. A form collects details about the new flat mate.

#### Existing Flat Mate:
3. Existing flat mates can log in using their credentials to access the home page.

#### Flat Mate Dashboard:
1. The dashboard displays an expense chart.
2. Users can input their expenses and categorize them as common or personal.
3. Common expenses are further categorized.

### Notification Feature:
1. Recurring expenses allow users to set due dates with notifications sent via email.
2. Monthly budget and savings information is entered during signup, with notifications triggered at 80% expenditure.
3. Notifications for common expenses like Gas, Electricity, WIFI, and rent are sent on due dates.

### Common Expense Page:
1. Displays information on all common expenses within the flat.
2. Tracks which flat mate has paid and who hasn't.
3. Presents analysis charts of common expenses.

### Sign Out:
A sign-out option in the menu bar allows users to log out, redirecting them to the main login page.