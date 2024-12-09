# Tilled Integration Example
This repository provides a standalone example to assist partners in integrating with Tilled. It is not for production use or as a dependency.

# Prerequisites
Node.js
Setup
Clone the project and install dependencies:

## $ npm install  
# Retrieve configuration values:

Get API keys (link) and Merchant Account ID (link).
Optional: Create a new Merchant (instructions).
Configure values:

# reate .env file:
env

TILLED_SECRET_KEY=sk_...  
Update index.html with Merchant Account ID and Publishable API Key:


const accountId = "acct_...";  
const publishableKey = "pk_...";  
## Run and Test
Start the server:

 $ node app.js  
Process payments:

Visit http://localhost:3000.

<div align="center"> 
   
 <img src="https://github.com/venachero/simple_payment/blob/main/img/Create-Payment-Method.png" width="800">

</div>



Use 4037111111000000 (card number), valid expiration date, and 123 (CVV).
Check the Tilled Console for payments (link).
## Testing and payment methods:

Save payment methods directly using the browser toggle.
