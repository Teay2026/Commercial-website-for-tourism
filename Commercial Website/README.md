# Website-TLW

# Travel Agency Website Project

This website was created by Tahiri El Youness and Hadj-Hamdri Mohammed Amine during their 3rd year at CPE Lyon engineering school.

## Project Specifications:

### 1. Minimum Required Pages:
   - Main page showcasing various destinations through photos.
   - Reservation page.
   - Recap page.
   - About & Contact page.

### 2. Navigation Flow:
   - Selection of a destination on the main page leads to the reservation page.
   - Reservation page displays the selected trip and contains a reservation form.
   - Upon correct form submission, a validation button leads to the recap page, displaying trip details and a randomly generated reservation number.

### 3. Reservation Form:
   - Mandatory fields: Name, last name, email, departure date, return date, number of adults, number of children (under 12).
   - Additional elements: Phone, breakfast preference, request for information.
   - Automatic price calculation based on stay duration, number of adults, children, and breakfast preference.
   - Form reset button.
   - Real-time price display.

### 4. Data Model:
   - Simple model: Each stay characterized by a title and a price per adult per day.
   - Possibility to enhance the model with additional elements (e.g., flight cost, optional guided tours).

### 5. Price Calculation:
   - Automatically calculated based on stay duration, number of adults, children, and breakfast preference.
   - Children pay 40% of the adult price.
   - Additional charge for breakfast.

### 6. Contact Page:
   - Agency address.
   - Clickable phone number opening the phone app for calls.
   - Email button with pre-filled subject and message.

### 7. Common Elements:
   - Navigation menu.
   - Footer.
   - Scroll-to-top button.

### 8. Weather Integration:
   - Display current temperature on each destination photo using the OpenWeatherMap API.

### 9. Filters:
   - User-friendly filters on the page offering different trips.
   - Automatically hide destinations not matching the filters.

### 10. Shopping Cart:
   - Site includes a shopping cart for managing customer orders.
   - Users can modify their cart, e.g., remove a trip.

### 11. Responsiveness:
   - While not mandatory, attention will be given to accessibility standards.

### 12. Design Freedom:
   - Design elements are open-ended, allowing for creativity.
   - Attention to code quality and clarity is prioritized over visual aesthetics.

## Development Guidelines:

- Create a "Destination" class with properties and methods for representing different destinations.
- Use a JavaScript array of "Destination" objects to dynamically fill HTML files.
- Implement a mechanism to obtain the selected trip from the homepage to the reservation page using URL parameters.
- Dynamically update the reservation form using the "onchange" event.
- Create a new page with an SVG world map highlighting countries corresponding to the offered destinations during mouse hover.
- Incorporate multimedia elements, such as YouTube videos, to present destinations.
