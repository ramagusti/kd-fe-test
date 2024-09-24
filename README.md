# kd-fe-test
Test question for live coding session - Kartel Daun Front-end Developer hiring.

![image](https://github.com/ragst8/kd-fe-test/assets/115720691/9b7cba8f-9655-4c32-b630-973f3ffd219c)

Directives:
1. Clicking on each 'Add To Cart' button should add the item to the shopping cart. When an item is added to the cart:
  - The 'Add To Cart' button should be removed from view, and the 'Remove From Cart' button should be displayed.
  - An entry should be added to the table in the Cart component.
2. Clicking on each 'Remove' button should remove the item from the cart and display 'Add to Cart' for the product item.
3. The Cart component should have the following functionalities:
  - Display all the items in the cart in a table. 
  - Display the cart's subtotal, discount value, and total price.
  - The cart has a 'Select Coupon' input. On selecting a coupon from this input, an appropriate discount is applied and the total price is calculated and displayed. (Subtotal - Discount = Total Price)
4. Items should be displayed in the Cart component in the order they are added to the cart. 
5. The list of products and the cart object are passed as props to the Product Listing component and the Cart component respectively.

Each product object contains the following properties: 
  - name: Name of the product. [STRING]
  - price: Price of the product. [NUMBER]
  - id: Unique ID of the product. (Auto Generated) [NUMBER]
  - image: The image URL of the product. [STRING]
  - cartQuantity: The quantity of the item in the cart. The default value should be 0. [NUMBER]

Each item in the cart, CartItem, has the following properties:
  - id: The ID of the product added to the cart. [NUMBER]
  - item: The heading property of the product. [STRING]
  - quantity: The quantity of the item in the cart. [NUMBER]
  - price: The total price of the item in the cart. (quantity x product.price) [NUMBER]
