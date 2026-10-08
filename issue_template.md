# User Story Template

1. Account Registration

Title: Account Registration
As a user, I want to register with my name, username, age, and country so that I can create an account and access the habit tracking features.

Acceptance Criteria:

The user can enter their name, username, age, and country.
The system validates that all required registration details are provided.
The user receives confirmation when registration is completed successfully.

Priority: High
Story Points: 5

Notes:
Registration credentials are not stored in the browser cache.
User credentials are removed once the user logs out.

2. Account Login

Title: Account Login
As a user, I want to log in using my username and password so that I can access my account and track my habits.

Acceptance Criteria:

The user can enter a username and password.
The system validates the provided login credentials.
The user is granted access when valid credentials are provided.

Priority: High
Story Points: 5

Notes:
Due to security constraints, registered user credentials are not stored in the browser cache.
After logout, the user cannot log in using their previously registered credentials.
The only available login method after logout is the default username and password.

3. Error Feedback on Login

Title: Error Feedback on Login
As a user, I want to receive a message if I enter the wrong username or password so that I know my login attempt was unsuccessful.

Acceptance Criteria:

The system detects invalid username or password combinations.
An appropriate error message is displayed when login fails.
The user remains on the login page after an unsuccessful login attempt.

Priority: High
Story Points: 3

Notes:
The error message should not reveal whether the username or password specifically was incorrect.

4. View Welcome Message

Title: View Welcome Message
As a user, I want to see a personalized welcome message with my name on the homepage, so that I feel recognized and can confirm I am logged into the correct account.

Acceptance Criteria:

The homepage displays a welcome message after login.
The user's name is included in the welcome message.
The displayed name matches the user's current profile information.

Priority: Medium
Story Points: 2

Notes:
The name should update when the user changes it from the profile page.

5. Display Weekly Progress

Title: Display Weekly Progress
As a user, I want to see my daily progress for each habit on the homepage, so that I can easily monitor my progress.

Acceptance Criteria:

The homepage displays the user's habits.
Daily progress is displayed for each habit.
The progress shown corresponds to the current week.

Priority: High
Story Points: 5

Notes:
Progress should be updated when the user completes or changes a habit.

6. View Completed Habits

Title: View Completed Habits
As a user, I want to see a section for completed habits on the homepage, so that I can track what I have already achieved.

Acceptance Criteria:

The homepage contains a completed habits section.
Completed habits are displayed in this section.
Incomplete habits are not displayed as completed.

Priority: Medium
Story Points: 3

Notes:
The section should be empty or display an appropriate message when there are no completed habits.

7. Access Menu Options

Title: Access Menu Options
As a user, I want to access a menu with options for configuring my habits, viewing reports, editing my profile, and signing out, so that I can easily navigate to different parts of the app.

Acceptance Criteria:

The menu is accessible from the application interface.
The menu contains options for Profile, Habits, Reports, and Sign Out.
Each option performs its corresponding action.

Priority: High
Story Points: 3

Notes:
Menu options should be clearly labeled and easy to identify.

8. Navigate to Profile

Title: Navigate to Profile
As a user, I want to access my profile page from the menu, so that I can view and edit my personal information.

Acceptance Criteria:

The menu contains a Profile option.
Selecting Profile opens the profile page.
The profile page displays the user's current information.

Priority: Medium
Story Points: 2

Notes:
The user must be logged in to access the profile page.

9. Navigate to Habits Page

Title: Navigate to Habits Page
As a user, I want to access the habits page from the menu, so that I can configure and manage my habits.

Acceptance Criteria:

The menu contains a Habits option.
Selecting Habits opens the habits page.
The user can manage their existing habits from the page.

Priority: High
Story Points: 2

Notes:
The habits page should display the user's current habits.

10. Sign Out from Menu

Title: Sign Out from Menu
As a user, I want to sign out of my account using an option in the menu, so that I can securely log out when I'm finished using the app.

Acceptance Criteria:

The menu contains a Sign Out option.
Selecting Sign Out logs the user out.
The user is redirected to the login page after signing out.

Priority: High
Story Points: 3

Notes:
User credentials should not remain in the browser cache after logout.

11. View Personal Information

Title: View Personal Information
As a user, I want to view my saved name, username, age, and country on my profile page, so that I can see the details I provided during registration.

Acceptance Criteria:

The profile page displays the user's name.
The profile page displays the username, age, and country.
The displayed information matches the user's current profile data.

Priority: High
Story Points: 3

Notes:
Information should be displayed in an easy-to-read format.

12. Edit Personal Information

Title: Edit Personal Information
As a user, I want to update my name, username, age, and country on my profile page, so that I can keep my information up to date.

Acceptance Criteria:

The user can edit their name, username, age, and country.
The system validates the updated information.
The user can save the changes.

Priority: High
Story Points: 5

Notes:
Invalid information should not be accepted.

13. Save Updated Information

Title: Save Updated Information
As a user, I want the changes I make to my profile to be saved, so that my updated details are stored and reflected throughout the app.

Acceptance Criteria:

The user can save updated profile information.
The updated information is reflected on the profile page.
The updated information is used throughout the application.

Priority: High
Story Points: 3

Notes:
Changes should remain available during the user's current session.

14. Update Name in Header

Title: Update Name in Header
As a user, I want my updated name to be displayed in the app's header after I change it in the profile, so that my changes are immediately visible.

Acceptance Criteria:

The user can change their name from the profile page.
The updated name appears in the application header.
The header displays the new name without requiring unnecessary navigation.

Priority: Medium
Story Points: 2

Notes:
The header should reflect the latest profile information.

15. Add a New Habit

Title: Add a New Habit
As a user, I want to add new habits on the details configuration page so that I can manage and update my habits as needed.

Acceptance Criteria:

The user can enter the details of a new habit.
The user can save the new habit.
The new habit appears in the user's habit list after saving.

Priority: High
Story Points: 5

Notes:
Required habit information must be validated before saving.

16. Delete a Habit

Title: Delete a Habit
As a user, I want to delete existing habits so that I can keep my habits up to date.

Acceptance Criteria:

The user can select an existing habit.
The user can delete the selected habit.
The deleted habit no longer appears in the habit list.

Priority: High
Story Points: 3

Notes:
A confirmation message may be displayed before deletion to prevent accidental removal.

17. Personalize a Habit with Color

Title: Personalize a Habit with Color
As a user, I want to assign a specific color to each habit to make it personal to me.

Acceptance Criteria:

The user can select a color for a habit.
The selected color is associated with the habit.
The selected color is displayed consistently wherever the habit appears.

Priority: Low
Story Points: 3

Notes:
The user should be able to select from the available color options.

18. View Weekly Reports

Title: View Weekly Reports
As a user, I want to see a report of my weekly habit progress so that I can understand how well I am maintaining my habits.

Acceptance Criteria:

The reports page displays the user's weekly progress.
The report covers the current week.
Progress information is presented in an understandable format.

Priority: High
Story Points: 5

Notes:
The report should be based on the user's recorded habit activity.

19. Visualize Completed Habits

Title: Visualize Completed Habits
As a user, I want to see a chart of my completed habits for each day of the week so that I can quickly identify trends in my progress.

Acceptance Criteria:

The report includes a chart showing completed habits.
The chart displays data for each day of the week.
The chart accurately reflects the user's completed habits.

Priority: Medium
Story Points: 5

Notes:
The chart should be easy to understand and interpret.

20. View All Habits

Title: View All Habits
As a user, I want to see both completed and incomplete habits in my report so that I have a comprehensive view of my habit tracking performance.

Acceptance Criteria:

The report includes completed habits.
The report includes incomplete habits.
The user can distinguish between completed and incomplete habits.

Priority: Medium
Story Points: 3

Notes:
The report should accurately represent the user's weekly habit status.

21. Enable/Disable Notifications

Title: Enable/Disable Notifications
As a user, I want to be able to enable or disable notifications for the app, so that I can choose whether or not to receive reminders for my habits.

Acceptance Criteria:

The user can enable notifications.
The user can disable notifications.
The notification setting is reflected immediately in the application.

Priority: High
Story Points: 3

Notes:
Disabled notifications should not generate habit reminders.

22. Add Habits for Notifications

Title: Add Habits for Notifications
As a user, I want to select specific habits to receive notifications for, so that I only get reminders for the habits I am actively working on.

Acceptance Criteria:

The user can view their available habits.
The user can select specific habits for notifications.
Notifications are only generated for the selected habits.

Priority: Medium
Story Points: 5

Notes:
The user should be able to change their selected habits at any time.

23. Set Notification Times

Title: Set Notification Times
As a user, I want to have the option to receive notifications three times a day (morning, afternoon, evening) for all selected habits, so that I get timely reminders throughout the day to complete my habits.

Acceptance Criteria:

The user can enable morning notifications.
The user can enable afternoon notifications.
The user can enable evening notifications.
Notifications are sent only for the selected habits.
Notifications are sent at the configured times.

Priority: Medium
Story Points: 5

Notes:
The user should be able to configure or disable each notification period independently.
