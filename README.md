# Vending-Machine-Simulator
Vending Machine Simulator is a Python project that simulates a vending machine, allowing users to purchase products by selecting and paying the required amount. It also includes an owner's menu to withdraw collected money. This project is part of my learning process to improve my Python skills.

## Features

- **Purchase Products**: Users can choose from a list of products, enter the required payment, and receive change if needed.
- **Cancel Transactions**: Users have the option to cancel their transaction at any time.
- **Owner's Menu**: A special menu for the machine owner to view and withdraw the total collected money.
- **Exit**: Users can exit the vending machine at any point.

## How to Use

1. **Run the Program**: Execute the Python script in your preferred Python environment.

2. **Choose a Product**: After the program starts, a list of available products and their prices will be displayed. Enter the corresponding number to select a product.

3. **Make Payment**: Enter the required payment in coins. If the entered amount is sufficient, the product will be dispensed, and any change will be provided. 

4. **Owner's Space**: Enter `99` to access the owner's menu, where you can view and withdraw the total collected money.

5. **Exit**: Enter `0` at any time to exit the vending machine.

## Example

```bash
Welcome to the Vending Machine!
Available products: 
1. Coke  -  $2
2. Pepsi  -  $3
3. 7up  -  $2.5
4. Coffee  -  $1.25

Enter an item number: 1
Please enter $2 in coins (Enter 0 to cancel): 2
Dispensing Coke, please collect your change of $0
```
## Requirements
Python 3.x

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
