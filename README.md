# Worthy Tasks

Hello Erij! :wave:

Welcome to your entry tasks in Konnect. These exercises were specifically designed for you to challenge yourself and to prove your worthiness to join our Team. You will be working on enhancing your own project by implementing some new features and further develop existing ones.

## Submission

You will have a deadline for Friday 11:59pm to deliver these tasks. To submit your work, make sure you:

- [ ] Clone this [forked repository](https://github.com/Ikdemm/gestion-de-stock-et-de-commandes)
- [ ] Create a new branch under the name of `Konnect`
- [ ] Make the changes for this challenges locally
- [ ] Commit your work whenever a task is done with a message `Task X done`
- [ ] Push your local branch
- [ ] Create a PR to the `main` branch

## Tasks


### Task 1: My server is not for storage

With many new users and employees coming in, your server is getting overwhelmed with new images. There is no space left for Storage! Don't freak out. We have the solution for this. There are many Service Providers that provide you with storage. [Cloudinary](https://cloudinary.com/) is one of them.

In this task, your mission is to:

- [ ] Create an account on Cloudinary to use their free plan
- [ ] Connect to Cloudinary API from your server
- [ ] Consume their API to store files there and save the imageURL in your database

By the end of this Task, you will be saving files on Cloudinary instead of your server.


### Task 2: Printable Invoices

For many accountants, it is mandatory to have a printable PDF version of their Invoices. In this task, you'll enable them to:

- [ ] Generate PDF version of these invoices
- [ ] Download them to their local computer

Feel free to use any package that you want.

### Task 3 (optional): Secure your Data

1. Input Validation

The first layer to protect your database is to validate the inputs' values coming from users.
In this task, you'll have to implement at least 2 input validations using [JavaScript Regex](https://regexr.com/) for:

- [ ] Phone Number format (should be a Tunisian Phone Number)
- [ ] Email Validation (should have an email format)

2. Schema Validation

A second layer of protection should be implemented in your server. Your API should reject requests that are not properly formatted. Use [Express Validator](https://express-validator.github.io/docs/) to validate the requests coming to **POST** `/api/factures/achat`.

- [ ] Create a new Directory called `validators` under your root `/` directory
- [ ] In that directory, create a new file called `facture-achat.validator.js`
- [ ] In that file, Implement your validator
- [ ] Import the validator and use it in your routers

### Task 4 (optional): Internationalize your solution

Your solution is fully implemented in the French Language. Have you ever considered that some users do not speak French? Don't worry. You won't need to re-create a new version for every language.

In this task, you'll try to use [i18next library](https://react.i18next.com/) to add an English version for at least **2 pages + the sidebar** of your Dashboard.

### Task 5 (optional): Redux for State Management

In this Task, you'll get introduced to the state management tool [Redux](https://redux.js.org/), more specifically to ReduxJS Toolkit.

Try to refactor your store from using **React Context API** to using **Redux**.

## Best of luck :crossed_fingers: