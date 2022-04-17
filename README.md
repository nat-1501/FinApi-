<h1>FinApi Movimentação Financeira</h1>

> Status: Concluded ✅

### This simple api was developed in Node.Js for learning purposes. The api consists of performing functions following business rules and requirements, such as creating and deleting an account, making a deposit, withdrawing and viewing a statement.


<h2> ⚠️ Pre-requirements to run api</h2>

To get started, you will need to have these tools installed on your machine:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).
In addition to having a good editor to work with code such as [VSCode](https://code.visualstudio.com/). The REST API client tool used was [Insomnia](https://insomnia.rest/download)

<h2> 🎲 Running the API (server)</h2>

```bash
# Clone this repository
$ git clone https://github.com/nat-1501/FinApi-.git

# Access the project folder in terminal/cmd
$ cd finApi-

# Install dependency manager
$ yarn install 
# Got married npm
$ npm install

# Run the application in development mode
$ yarn dev
# Got married npm
$ npm dev

# The server will start on port:3333 - go to <http://localhost:3333>
```

<h2> 🛠 Technologies used </h2>

Were used in the construction of the project:
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com)

---

### API requirements ###
- [x] It must be possible to create an account
- [x] It must be possible to fetch the customer's bank statement
- [x] It must be possible to make a deposit
- [x] It must be possible to make a withdrawal
- [x] It must be possible to search for the customer's bank statement by date
- [x] It must be possible to update customer account data
- [x] It must be possible to get customer account data
- [x] It must be possible to delete an account
- [x] It should be possible to return the balance

---

### Business rules ###

- [x] It should not be possible to register an account with an existing CPF
- [x] It must be possible to fetch a statement from a non-existing account
- [x] It should not be possible to deposit to a non-existing account
- [x] It should not be possible to withdraw from a non-existing account
- [x] It should not be possible to withdraw when the balance is insufficient
- [x] It should not be possible to delete a non-existing account



<h3> Made with ❤️ by Natali Soares 👋🏽 Get in touch! </h3>
