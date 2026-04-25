The Welcome page is the first screen users see when accessing the website.
The layout is centered and minimal, focusing on the logo and the application name FATFOOD.
The main color used is orange (#ff6600), which creates a vibrant and food-related visual identity.
Two primary buttons are provided:
Get Started → navigates to the Sign Up page
Sign In → navigates to the Sign In page
The layout uses Bootstrap container and text-center to align content in the middle.
The vertical structure makes it suitable for mobile devices.
<img width="1912" height="962" alt="Screenshot 2026-04-25 181831" src="https://github.com/user-attachments/assets/e0eab53e-efb2-449f-9ac2-7858a68d773b" />

2. Sign In Page
This page simulates a login interface.
It includes:
A title (WELCOME)
Email input field
Password input field
Sign In button
Built using Bootstrap form components for consistency and responsiveness.
The orange button color matches the overall design → ensures UI consistency.
No real authentication is required (UI only, as per assignment).
<img width="1915" height="962" alt="Screenshot 2026-04-25 181839" src="https://github.com/user-attachments/assets/6e1a7cc9-607c-43e4-a7ea-4ebbd133b043" />

3. Home Page (index.html)
This is the main page displaying all food items.
Main Components:
a. Header
Displays greeting
Includes an icon for a modern app-like feel
b. Search Bar
Provides a search input (UI only, no logic implemented)
Enhances realism of the application
c. Category Menu
Includes 4 buttons:
Pizza
Burger
Spaghetti
Drink
Uses JavaScript to:
Hide all sections
Show the selected category
<img width="1916" height="969" alt="Screenshot 2026-04-25 181846" src="https://github.com/user-attachments/assets/126deaf0-1084-479e-aec1-a31b618e1044" />
d. Food Cards (Bootstrap Grid)
Built using:
row and col-md-4
Bootstrap card
Each card includes:
Image
Food name
Price
“Add to Cart” button
Responsive layout:
Desktop: 3 items per row
Mobile: 2 items per row
<img width="1916" height="952" alt="Screenshot 2026-04-25 184926" src="https://github.com/user-attachments/assets/fe03339d-f09f-42c4-8670-6eb129fe2415" />
<img width="1919" height="915" alt="Screenshot 2026-04-25 184936" src="https://github.com/user-attachments/assets/77850bcc-b899-4567-976d-025c65ac626a" />


4. Detail Page
This page displays detailed information about a selected food item.
Functionality:
Data is passed via URL parameters
The page dynamically displays:
Food image
Name
Price (formatted in VND)
Description (auto-generated)
<img width="1911" height="965" alt="Screenshot 2026-04-25 181853" src="https://github.com/user-attachments/assets/ade6f1e7-6d94-4c4d-b9ba-6d4259100200" />


5. Responsive Design
The website is fully responsive using Bootstrap:
Desktop: multi-column layout
Tablet: adjusted grid
Mobile: stacked layout
The layout remains stable across screen sizes.

6. Bootstrap Components Used
The project uses multiple Bootstrap features:
Container
Grid system (row, col)
Cards
Buttons
Forms
Spacing utilities (margin, padding)
Ensures structured and efficient UI development.

Conclusion
The project successfully meets all assignment requirements:
Includes multiple pages (Welcome, Sign In, Home, Detail)
Follows a consistent visual design
Fully responsive
Uses Bootstrap components effectively
Implements interactive features
