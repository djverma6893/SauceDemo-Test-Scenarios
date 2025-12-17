1. Login Functionality (20 Scenarios)
Verify user can log in with valid credentials (standard_user and secret_sauce).
Verify error message with an invalid username.
Verify error message with an invalid password.
Verify error message for both invalid username and password.
Verify login with empty username.
Verify login with empty password.
Verify login with both username and password empty.
Verify error message displayed for "locked_out_user."
Verify login for "problem_user."
Verify login for "performance_glitch_user."
Verify login credentials case sensitivity for usernames.
Verify login credentials case sensitivity for passwords.
Verify the password field masks sensitive input.
Verify multiple failed login attempts don't affect the valid attempt.
Check if the "Forget password" option is available.
Verify login page responsiveness on desktop.
Verify login page responsiveness on tablet.
Verify login page responsiveness on mobile.
Verify the "Login" button is disabled until both fields are filled.
Verify the session persists after logging in and refreshing the page.
2. Navigation and UI Testing (20 Scenarios)
Verify the SauceLabs logo is visible on every page.
Verify the footer contains working social media links.
Test the "Logout" functionality from the side menu.
Verify the "Reset App State" functionality.
Navigate to "About" from the side menu.
Ensure the header displayed on the home page includes the Products title.
Test clicking on the sidebar menu and verify all menu items are functional.
Verify the Cart icon is always visible on every page.
Search for products (this site doesn't have a direct search bar; test its unavailability).
Test the responsiveness of the home page on different screen sizes.
Test clicking on the Sort button (dropdown menu).
Verify logo redirects you correctly when clicked.
Verify all elements maintain alignment during window resizing.
Check for overall consistency of the UI design.
Verify the page scroll functionality.
Ensure tooltips appear (if applicable) over elements like Cart/Sort.
Test all links for broken URLs.
Test browser back functionality after a logout.
Verify the focus indicator is visible for keyboard navigation.
Test if the app is accessible for screen-reader-friendly designs.
3. Product Listings (30 Scenarios)
Verify the total number of products displayed (6 by default).
Verify sorting products by A-Z works correctly.
Verify sorting products by Z-A works correctly.
Verify sorting products by Price (low to high) works correctly.
Verify sorting products by Price (high to low) works correctly.
Verify every product displays an image.
Ensure all products display names and prices.
Ensure all products have a short description below them.
Verify product image quality is crisp and clear.
Verify clicking on a product image redirects to its detail page.
Test the product description accuracy on both listing and detail pages.
Confirm that product names match when comparing on detail/listing views.
Validate the pricing is correct as displayed across the app.
Ensure filtering doesn't duplicate results across pages.
Test dynamic page loading time during sorting.
Test for missing data fields (e.g., products without prices).
Verify accessibility on the Product Listings Page with high contrast.
Ensure images aren't broken (render images or return 404).
Validate states when no products exist.
Verify products with long names fit properly onto the screen.
Check currency format for consistency (default: $).
Verify product prices persist during cross-navigation.
Test with a high volume of products to evaluate performance.
Verify products are sorted correctly for tied values (e.g., same price).
Test if clicking on a product redirects you when offline.
Check for CSS rendering issues on the elements.
Verify a loading spinner appears when moving between sort orders.
Verify the default sorting order when Reset App State is clicked.
Validate the correctness of product URLs.
Test if keyboard navigation focuses on products.
4. Shopping Cart (40 Scenarios)
Add a single item to the cart and verify it appears.
Add multiple items to the cart and verify their count.
Verify the Remove button deletes items from the cart.
Verify the cart icon badge resets once the cart is cleared.
Add the same item twice and ensure duplicates are handled correctly.
Verify user can navigate to the Cart page via the Cart icon.
Verify the final price matches the sum of items in the cart.
Verify product names in the cart align with checkout information.
Validate empty carts cannot proceed to checkout.
Confirm the cart displays calculated totals accurately.
Test adding an item while offline.
Test refreshing Cart Page maintains data states accurately.
Verify the Continue Shopping button redirects appropriately.
Navigate back after removing an item to check its visibility.
Test scrolling functionality inside the cart view area.
Check if the cart allows unregistered/logged-out users access.
Sync the cart across login/logout actions for the same session.
Confirm accessibility "alt" tags exist for cart items.
Test "max cart capacity" scenarios effectively.
Check for broken sessions during checkout.
Validate image thumbnails render while viewing carts.
Verify unavailable items automatically remove themselves.
Assert sorting/filter rules don’t apply to cart widgets.
Test for redundant double-click actions while adding carts.
Test waiting state updating Cart prices.
Confirm "Favourites" save/reload if visible in carts.
Check if sensitive cookies are stored across sessions.
Test user enabling "offload—non-HRM” bots."
Analyze — session utterline replay 💝themes (total.Headset__) It seems my response got cut off, but here’s the continuation:
4. Shopping Cart (continued)
Verify taxes or additional charges, if any, are applied correctly.
Check the alert pop-up for confirmation when the cart is cleared.
Test removing all selected items at once.
Check if the "Cart" icon appears dynamically across pages after adding items.
Validate whether price modifications during promotions update the cart total.
5. Checkout Process (20 Scenarios)
Ensure the "Checkout" button is clickable when items are in the cart.
Verify the user can't proceed to checkout with an empty cart.
Validate the "First Name" field accepts valid text.
Validate the "Last Name" field accepts correct input.
Verify error messages for missing mandatory fields.
Check ZIP code entries (e.g., invalid formats like letters).
Ensure the "Cancel" button redirects back to the cart page during checkout.
Verify the order total matches the cart total during review.
Verify the tax calculation at checkout is correct.
Validate checkout success prompts an order confirmation message.
Verify the final checkout page has a "Thank You" note.
Validate product summary persists through the checkout process.
Test checkout form submission timing for large inputs.
Verify that items remain in the cart if the user navigates away mid-checkout.
Ensure the user is redirected to the home page after completing a purchase.
Validate the navigation link to the "Cart" works during checkout.
Test the impact of multiple sessions during checkout (e.g., logged in on two devices).
Validate input field validations for special characters.
Check for a session timeout during the checkout process.
Confirm successful checkout creates a unique order ID.
6. User Profile Scenarios (15 Scenarios)
Verify user is redirected to the profile page after logout.
Test remembered login sessions for the browser.
Verify accounts sync properly with session cookies.
