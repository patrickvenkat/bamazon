<h1>####### bamazon customer app #######</h1>
<h2>1. Problem Definition</h2>
   <p>This node and SQL app solves a simple need to buy items available for sale</p>
   <p>a) Display items available for sale</p>
   <p>b) Select an item to purchase</p>
   <p>c) Enter the quantity you would like to purchase</p>
   <p>d) Complete the purchase and know how much you paid for it</p>
<h2>2. High-level overview of how the app is organized</h2>
   <p>This app is organized into the following sections</p>
   </p>a) Setup block. This is where the packages are loaded and the database connections are made.</p>
   <p>b) Display items block. This is where items are read from the database and displayed for the user to select.</p>
   <p>c) Select items block. This is where the user can select an item from the list of displayed items. In addition to displaying items, error checks are peformed for user input.</p>
   <p>d) Ask for quantity block. This is where the app asks for the user to enter the quantity for purchase. Error checks are also peformed for user input to ensure that the user input conforms to the needs of the App.</p>
<h2>3. Start-to-finish instructions on how to run the app</h2>
   <p>a) In the console window, type in "node bamazonCustomer.js This will return the full list of items available for sale including ID, Name and Price of each item.</p>
   <p>b) Followed by a user input field asking to enter the ID of the item they would like to purchase.</p>
   <p>c) Once the user enters an input, the system checks to make sure that the ID exists in the database. Otherwise the App will display an error and ask the user to reenter a valid ID.</p>
   <p>d) The user can exit the App by entering 'q' at any time.</p>
   <p>e) Once the ID is validated, the App ask the user to enter a quantity to purchase.</p>
   <p>f) Once the user enters an input, the system checks to make sure that the quantity is a valid and postive number. Otherwise the App will display an error and ask the user to reenter a quantity.</p>
   <p>g) Once a valid quantity is entered, the App queries the database to see if there is sufficient inventory available to complete the sale. If there is, the total cost is displayed and App exits. If there is not enough quantity, the App displays message indicating not enough quantity and exits.</p>
   <p>h) If a successful sale happens, then the inventory is updated in the database reflecting the sale.</p>
<h2>4. Screenshots, gifs or videos of the app functioning</h2>
   <p>a) See github for it. Screen shots have been provided and in the folder screen-shots.</p>
<h2>5. Link to a deployed version of the app</h2>
   <p>a) Link to run the node app: https://github.com/patrickvenkat/bamazon1</p>
<h2>6. List the technologies used in the app</h2>
   <p>a) Packages: MySQL, Inquirer.</p>
   <p>b) Files: None.</p>
<h2>7. Your role in the app development</h2>
   <p>a) Soup to nuts. Design, develop, test and deliver.</p>