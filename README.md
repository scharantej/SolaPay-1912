## Flask Application Design for a Payments Platform Using Solana Blockchain

**HTML Files:**

- **index.html**: Landing page of the platform, providing information on how to use the payment service and the supported cryptocurrencies.
- **payment.html**: Form for initiating payments, allowing users to specify the recipient, amount, and cryptocurrency.
- **confirmation.html**: Message displayed after a payment has been successfully completed, summarizing the transaction details.

**Routes:**

- **`/`**: Main route, rendering the **index.html** page.
- **`/payment`**: Route to handle payment initiation, rendering the **payment.html** page and accepting user input.
- **`/payment_confirmation`**: Route to process the payment, interact with the Solana blockchain, and render the **confirmation.html** page.
- **`/payment_history`**: Route to display a list of completed payments, allowing users to track their transaction history.
- **`/error`**: Error-handling route, rendering a message in case of any issues during payment processing.