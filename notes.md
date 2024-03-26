**Customer:**
- since we have the concept of loyalty points, we might want to add loyalty points as an instance variable (add to init)

**Product:**
- it feels more intuitive to have the name, then price, then product_code.

**Order:**
- i think we can add ShoppingCart as an attribute to the Order class
	- this way, we have access to the products of this order, as well as the customer making the order. rn there is no way to get that information


**ShoppingCart:**
- it makes sense to allow users to remove product as well.

- checkout logic needs clarification: business rules says 1 point on every $10 spent, but does that mean the points should be calculated after applying the discount? right now it is calculated before applying the discount so perhaps we can discuss this
- extracting out the logic for checking discount code
- checkout:
	- can become a lot leaner