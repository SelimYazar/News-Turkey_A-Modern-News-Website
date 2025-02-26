# News-Turkey_A-Modern-News-Website
This project is a news website designed to showcase the latest articles in various categories including Economy, Technology, Politics, Sports, Science, and Culture. The site features a dynamic and responsive layout with a modern look and feel. It includes functionalities like displaying cryptocurrency prices, a live news feed, and an interactive design. The website is ideal for presenting real-time articles and allowing users to navigate through different topics with ease.

## Features

- Responsive Design: Fully responsive layout that adjusts seamlessly across all devices (desktop, tablet, mobile).
- Navigation: Easy-to-use navigation with links to Home, About, Blog, and Contact sections.
- Crypto Prices: Displays real-time cryptocurrency prices (Bitcoin, Ethereum, Binance Coin, etc.) updated every 10 seconds.
- Dynamic Articles: Sections for various categories (Sports, Technology, Economy, etc.) displaying the latest articles.
- Video Backgrounds: Eye-catching video backgrounds on the homepage and footer for a modern feel.
- Category-based Layout: Each article is categorized with color-coded sections for clear identification.
- Social Media Integration: Social media icons for easy sharing and following.
- Interactive Elements: Hover and active states for buttons and links, including category buttons that highlight on hover.
- Footer with Subscription: Newsletter subscription form integrated with a styled footer for better user engagement.

## Technologies Used

### Frontend Technologies:
- HTML5: Structure of the web pages.
- CSS3: Layout and styling of the website, including media queries for responsiveness.
  - CSS Variables: For easier theming and color management (used for colors, spacing, and more).
  - Flexbox and CSS Grid: For creating responsive layouts across different screen sizes.
  - Font Awesome: Used for social media icons and various interface icons
  - Google Fonts: Fonts 'Lato' and 'Varela Round' are used for a clean, modern aesthetic
  - Video Backgrounds: For interactive sections that add visual appeal to the homepage and footer
  
### JavaScript:
- Vanilla JavaScript**: To handle dynamic features such as fetching cryptocurrency prices and updating them on the page every 10 seconds  

### Additional Libraries:
- Crypto API: Fetching real-time data for various cryptocurrencies like Bitcoin, Ethereum, Binance Coin, etc.
  
### Design:
- Custom CSS: A modern, minimalist design focusing on usability and clean typography.
- Social Media Integration: Icons for platforms like Facebook, Twitter, Instagram, and LinkedIn, styled to give a modern look

Cryptocurrency Prices:
The website showcases real-time cryptocurrency prices, including Bitcoin (BTC), Ethereum (ETH), Binance Coin (BNB), Ripple (XRP), and Cardano (ADA). The prices are updated dynamically every 10 seconds, ensuring that the information displayed is always current.

Technologies and Methods:
JavaScript: Vanilla JavaScript is used to handle the dynamic update of cryptocurrency prices.
Crypto API: The prices are fetched using the Binance API, which provides live data on various cryptocurrencies. The API is queried every 10 seconds to retrieve the latest market prices.
setInterval: The setInterval function is used to refresh the data at a regular interval of 10 seconds. Each time the data is fetched, the corresponding cryptocurrency prices are updated in the DOM (Document Object Model).
Process:
Fetch Cryptocurrency Data: The fetch() method is used to make requests to the Binance API and retrieve the data for each selected cryptocurrency.
Display Prices: Once the data is fetched, the prices are parsed and displayed dynamically in the designated HTML elements for each cryptocurrency (Bitcoin, Ethereum, etc.).
Real-time Updates: Every 10 seconds, the setInterval function re-fetches the data and updates the displayed prices, ensuring that the website always shows the latest price for each cryptocurrency.

