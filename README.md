# E-Commerce Sales Visualization

A dynamic and interactive visualization tool designed to celebrate every sale made on an e-commerce platform. Each sale triggers a bubble animation containing the product image, rising from the bottom to the top of the screen.

 <img width="1466" alt="Captura de Tela 2023-10-06 às 12 56 57" src="https://github.com/lirad/bubbles/assets/4331050/e023ad85-e175-464c-94fb-8ddd2badb2d3">

## Features

- **Real-time Animation**: Bubbles appear in real-time as sales occur.
- **Responsive**: Narrow visualization container ensures that the bubbles are visible and impactful on all screen sizes.
- **Randomized Movement**: Each bubble not only rises but also has a subtle randomized X-axis movement, ensuring a natural and organic feel.

## How it Works

- The project utilizes vanilla JavaScript to simulate sales and trigger the bubble animations.
- CSS3 animations power the bubbles' rise and lateral movement.
- The project can be integrated with real-time sales data using WebSockets or AJAX polling to fetch sales data and trigger animations accordingly.

## Getting Started

1. Clone this repository:
2. Open `index.html` in a browser to view the simulation.
3. Integrate with your e-commerce platform to trigger the `onSale(productImageUrl)` JavaScript function with a product image URL each time a sale occurs.

## Contribution

Feel free to fork, improve, and submit pull requests. For major changes or feature additions, please open an issue first to discuss.

## License

MIT License. See `LICENSE` for more information.
