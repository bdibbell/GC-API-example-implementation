# Toast Gift Card API example implementation

This repository represents an example of how to implement the Toast Gift Card Integration API.

It's a basic server written in Node.js that handles requests from Toast.

`db.json` represents a database. This is where the gift cards and transactions are stored. You can also edit and view the data just like any other json file. Gift card, transaction, and database related functions can be found in `cards.js`, `transactions.js`, and `db.js` respectively. These files are less important however some of the required error responses are thrown in `cards.js` and `transactions.js`.

**The majority of the logic can be found in `server.js`.** This is where incoming requests are handled and dealt with accordingly. It is also where JWT verification is handled.
