# E-Commerce Transaction Data Simulation

This project simulates transaction data for an e-commerce website. The primary objective is to generate a realistic dataset that can be used for practicing data modeling and analysis. The data includes user details, transaction specifics, merchant information, and product details.

**📢Note: This project is currently in progress. Data modeling and analysis scripts are forthcoming.**

## Project Structure
The project consists of the following components:
* **Data Generation**: A Python script that generates fake data.
* **Data Modeling**: (Planned) Scripts for setting up database schemas to model the generated data.
* **Data Analysis**: (Planned) Analysis scripts to derive insights from the data.

## Data Generation
### Overview
The data generation script creates a CSV file containing 100,000 rows of transaction data. Each row represents a transaction and includes details about the user, the merchant, the transaction itself, and the product being transacted.

### Data Details
#### Transactions
* **Transaction ID**: Unique identifier for each transaction.
* **Amount**: Transaction amount in USD.
* **Transaction State**: Could be 'Success', 'Failed', or 'Pending'.
* **Transaction Type**: Includes types such as 'Purchase', 'Refund', or 'Withdrawal'.
* **Transaction Date**: The date on which the transaction occurred.
* **Shipping Date**: The date the product was shipped (if applicable).

#### Users
* **User ID**: Unique identifier for each user.
* **Name, Email, DOB, etc.**: Personal details of the user.
* **User Signup Date**: The date the user registered on the platform.
* **Onboarding Type**: How the user was onboarded, e.g., 'Online', 'In-person',
