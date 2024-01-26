# Website-TLW

# Travel Agency Website Project

**Description:**

Welcome to the Travel Agency Website Project, a collaborative effort by Tahiri El Youness and Hadj-Hamdri Mohammed Amine, crafted during our 3rd year at CPE Lyon engineering school. This web project aims to provide users with a seamless and visually appealing platform to explore and plan their travel adventures.

**Features:**

- **Destination Exploration:** Discover a wide array of travel destinations with detailed information, captivating images, and insightful descriptions to help users choose their dream vacation spot.

- **Customized Itineraries:** Plan your trip effortlessly with the website's interactive itinerary planning feature. Tailor your journey based on preferences, budget, and travel duration.


- **Booking Integration:** Seamlessly book flights, accommodations, and activities directly through the website, offering users a convenient one-stop-shop for all their travel needs.


**Technology Stack:**

The Travel Agency Website is developed using modern web technologies, incorporating HTML, CSS, and JavaScript to create an engaging and dynamic user interface. Backend functionality is powered by robust server-side technologies, providing secure and efficient data handling.

**Contributions:**

Feel free to provide feedback or contribute to the improvement of this project. Your input is valuable in enhancing the overall user experience for fellow travelers.

Enjoy exploring the world with the Travel Agency Website!


## Website Overview

### Home Page
![Home Page](https://github.com/Teay2026/Commercial-website-for-tourism/blob/main/Commercial%20Website/README_PHOTOS/acceuil.png)
*Showcase various destinations through photos.*

### Espace Client Page
![Espace Client Page](https://github.com/Teay2026/Commercial-website-for-tourism/blob/main/Commercial%20Website/README_PHOTOS/espaceclient.png)
*Displaying the reservation and client-specific information.*

### Filtered Page
![Filtered Page](https://github.com/Teay2026/Commercial-website-for-tourism/blob/main/Commercial%20Website/README_PHOTOS/filter.png)
*User-friendly filters offering different trips.*

### Destinations Map
![Destinations Map](https://github.com/Teay2026/Commercial-website-for-tourism/blob/main/Commercial%20Website/README_PHOTOS/map.png)
*Visual representation of travel destinations.*

## Project Specifications:

### 1. Pages:
   - Main page showcasing various destinations through photos.
   - Reservation page.
   - Recap page.
   - Destionations map
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
