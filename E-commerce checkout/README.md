# E-COMMERCE CHECKOUT
## SCENARIO:
An online store needs a checkout system. When a customer places an order, the system must process payment, update inventory, and send a confirmation email. If payment fails, inventory should not change.

## GOAL:
Design an architecture that handles checkout reliably, even when one step fails.

### DIAGRAM INCLUDES:
-	The checkout API endpoint
-	How payment processing is separated from inventory updates
-	What happens when the payment fails
-	How the confirmation email is sent
-	Where order data is stored
