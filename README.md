React Product Catalog

- Live Preview: [Demo Link](https://melarkkkk.github.io/react_phone-catalog/)

- Design Reference: [Original](https://www.figma.com/design/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog--V2--Original?node-id=0-1&p=f&t=gBjLFr5ueQIheSqp-0) / [Original Dark](https://www.figma.com/file/BUusqCIMAWALqfBahnyIiH/Phone-catalog-(V2)-Original-Dark)

Technologies Used

- React + TypeScript

- Vite for bundling and fast development

- CSS Modules with SCSS

- React Context for state management (Cart, Favorites, App settings)

- React Router DOM for routing

- LocalStorage for persisting cart and favorites

- ESLint, Prettier for code quality

Project Structure
```
src/
├── components/      # Shared components like Header, Footer, Logo
├── context/         # React Contexts for App, Cart, Favorites, Products
├── modules/         # Pages: HomePage, CartPage, FavoritesPage, ProductDetailsPage, ProductsPage, NotFoundPage
└── utils/           # Helpers, types, variables
```
Getting Started

1. Clone the repo
```
git clone <repo_url>
cd phone-catalog
```

2. Install dependencies
```
npm install
```

3. Run development server
```
npm run dev
```

4. Build for production
```
npm run build
```

5. Lint and format
```
npm run lint
npm run format
```

- Features

  - Responsive Design: Optimized for different screen sizes and devices

  - Navigation: react-router-dom library is used in the application to enable navigation between multiple pages, and URL-based search parameters saved when navigating

  - Favorites & Cart: adding products to favorites or shopping cart, with total price calculation,

  - Product Filtering: Filter products by capacity and color inside product card.

  - Sorting: Sort products based on criterias: year, price, alphabeticaly.

  - Pagination: Navigate through large lists of products, with the opportunity to choose number of items per page, and number of pages depends on this.

  - Sticky Header: Keeps the header visible as you scroll.

  - Scroll to Top Button: Easily return to the top of the page.


