Flipkart Automation using Selenium

Project Overview This project automates a simple Flipkart shopping
workflow using Python and Selenium WebDriver. The script opens Flipkart,
searches for Bluetooth speakers, applies filters, selects a product,
adds it to the cart, and captures a screenshot of the cart page.

Demo Video A demonstration video of the automation execution is included
in the repository.

Technologies Used - Python - Selenium WebDriver - Google Chrome -
ChromeDriver

Project Structure

flipkart-automation/ │ ├── Automation task.py ├──
flipkart_automation.mp4 ├── cart_result.png └── README.txt

Features

The automation script performs the following actions:

1.  Opens Flipkart website
2.  Closes login popup
3.  Searches for Bluetooth Speakers
4.  Applies filter Brand → boAt
5.  Applies filter Rating → 4★ & above
6.  Sorts products by Price Low to High
7.  Opens the first product
8.  Switches to the new tab
9.  Adds product to cart
10. Opens cart
11. Captures screenshot of cart page

Output

After execution: - The product will be added to the cart - A screenshot
will be saved as cart_result.png

Code Highlights

Key Selenium concepts used in this project:

-   WebDriver initialization
-   Finding elements using CLASS_NAME, NAME, and XPATH
-   Sending keys using Keys
-   Handling multiple browser tabs
-   Capturing screenshots
-   Basic synchronization using sleep()

Note

Flipkart UI may change over time. If elements change, XPath or class
names may need to be updated.

