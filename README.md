## Demo Transaction API Testing Using JMeter
## Project Sumary:
This project based on the demo transaction API. I have generated load testing on  positive test case each request of this transaction API using JMeter software.

## Technology Used:
1. Apache Jmeter
2. Visual Studio Code

## API Reference:
User documentation: https://documenter.getpostman.com/view/1844288/2s9YeABaGo
Transaction documentation: https://documenter.getpostman.com/view/1844288/2s9YeABaGp

## Test Cases:
1. Admin creates an agent and a customer
2. Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
3. Deposit 1000 tk to customer from agent account
4. Check balance from customer account
5. Withdraw 500 tk from customer account
6. Payment 200 tk from customer account (Merchant account: 01686606905)

## JMeter HTML Report
![html-1](https://github.com/ishratgithub/demo-transaction-api-jmeter/assets/158293575/909fb029-53b1-425b-8368-ae2b3aa2f7ba)
![html-2](https://github.com/ishratgithub/demo-transaction-api-jmeter/assets/158293575/fbe9ba02-518e-4581-85ef-e4db83f97130)
## How to Run
1. Install & Run JMeter software
2. Download this "demo-transaction-api-jmeter.jmx" file
3. Save this .jmx file into apache "bin" folder
4. Run "ApacheJMeter.jar"
5. And finally open "demo-transaction-api-jmeter.jmx", then click on the "start" button
