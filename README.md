# Dosa Restaurant Order Processor
This Python application processes customer orders for a Dosa restaurant. It reads from a JSON file to generate two key outputs: a customer directory (customers.json) and an itemized summary (items.json). The customer directory links phone numbers with names, while the itemized summary provides details about menu items, their prices, and order frequency.

## Setup
1. Ensure you have Python 3 installed on your machine.

2. Clone this repository to your local environment to get started:

git clone https://github.com/yourusername/midterm_project.git

cd midterm_project

## Requirements
1. Python 3.x
2. A code editor (e.g., VSCode)

## Running the Application
To process the orders, navigate to the project directory in your terminal and execute:

==> python3 process_orders.py example_orders.json


## Project Structure
1. project.py: The script that reads and processes order data.
2. example_orders.json: A sample file containing order data.
3. customers.json: Output file linking customer phone numbers to names.
4. items.json: Output file detailing menu items, prices, and order counts.