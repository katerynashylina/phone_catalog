# Phone Catalog

The necessary links:
    [DEMO LINK](https://katerynashylina.github.io/phone_catalog/), 
    [Figma Design](https://www.figma.com/file/uEetgWenSRxk9jgiym6Yzp/Phone-catalog-redesign?type=design&node-id=1-2&mode=design)

React Phone Catalog is a web application consisting of six main pages: Home, Phones, Tablets, Accessories, Favorites, and Cart.

Home Page:
The Home page features top slides that users can navigate using arrows or dots underneath. It also includes a slider showcasing the best discount offers, the ability to shop by categories, and the latest phone models.

Phones Page:
On the Phones page, users can view a list of all available phones. They have the option to sort the phones alphabetically, by newest, or by price (cheapest first). The page includes pagination, allowing users to change the number of phones displayed per page. By clicking on a phone card, users can view all the details of the selected phone. The phone details page presents various phone photos, available colors, and capacities. Clicking on any color or capacity redirects the user to the page with the details of the chosen phone variant. Users can add the phone to the cart or mark it as a favorite. Additionally, the phone details page displays necessary information and a slider with recommended phone models.

Tablets and Accessories Pages:
The Tablets and Accessories pages are not yet implemented but will showcase available tablets and accessories for purchase once added.

Favorites Page:
The Favorites page displays all the phones that users have liked. It serves as a convenient place to view and manage their preferred products.

Cart Page:
On the Cart page, users can view all the phones they have added to their cart. They can adjust the quantity of phones and easily remove any device using the provided cross button. The page also displays the total cost of all products in the cart. Although checkout is not yet implemented, users will see a modal when clicking on the checkout button.

Navigation:
Every page includes top and bottom navigation menus. The top navigation menu allows users to easily navigate to any page of the website. The Phones, Tablets, Accessories, and Favorites pages feature a search component for users to find specific products. The bottom navigation menu allows users to access links and quickly return to the top of the window.

Technologies Used:
The React Phone Catalog is built using HTML, SCSS (CSS preprocessor). It employs React for creating dynamic components and managing the state of the application, React Router library for handling navigation and routing within the React application and Redux Toolkit for the search component. BEM methodology is utilized for structured and maintainable CSS code.

Please note that some features like tablet and accessory pages, checkout functionality are still under development and will be added in future updates to enhance the user experience.

# To run the app on your local machine, follow these simple steps:

1. Fork the Repository:
Click the "Fork" button on the top right corner of this page to create your own copy of the repository.

2. Clone the Repository:
Clone the repository to your local machine. Open your terminal, navigate to the desired location, and use `git clone 'your link'`.

3. Install Dependencies:
Navigate into the cloned folder using the terminal and run `npm install / npm i` to install the required dependencies.

4. Start the App:
After installing the dependencies, start the game using `npm start`.

5. Use the App:
Once the app is successfully started, open your web browser and visit http://localhost:3000 to use the app.

Prerequisites:
It is better to fork this repository with Node.js version 14, as the application relies on certain features that are available in Node.js 14.
