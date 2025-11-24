Simple Inventory Store Manager – Menu Driven Program
A basic Python-based inventory management system that allows users to add, view, update, and delete items from an in-memory inventory. This project demonstrates fundamental programming concepts such as functions, lists, dictionaries, loops, and user interaction.
________________________________________
📌 Features
The program provides the following functionalities:
✅ Add Item
Allows the user to add a new inventory item by entering:
•	Item ID
•	Item Name
•	Stock Count
•	Price
✅ View Items
Displays a clean, formatted list of all items currently stored in the inventory.
✅ Update Item
Modifies an item’s:
•	Name
•	Stock Count
•	Price
The user can leave any field blank to keep the existing value.
✅ Delete Item
Removes an item from the inventory using its Item ID.
✅ Exit
Gracefully closes the program.
________________________________________
🛠️ Technologies Used
•	Python 3.x
•	Data structures: Lists and Dictionaries
•	Concepts used:
o	Functions
o	Loops
o	Conditionals
o	User input handling
o	Menu-driven programming
________________________________________
📂 Project Structure
inventory_manager.py
The entire program resides within a single Python script for simplicity.
________________________________________
📘 How It Works
The inventory is stored as a list of dictionaries, where each dictionary contains:
{
    "item_id": "I001",
    "item_name": "Apple",
    "stock_count": 50,
    "price": 10.5
}
The main_menu() function handles navigation and continuously prompts the user for actions until they choose to exit.



▶️ Running the Program
1.	Ensure Python 3 is installed.
2.	Save the script as inventory_manager.py
3.	Run it using:
python inventory_manager.py
4.	Use the on-screen menu to interact with the inventory.
________________________________________
📑 Sample Menu
Inventory Store Manager
1. Add Item
2. View Items
3. Update Item
4. Delete Item
5. Exit
Enter your choice:
________________________________________
🧪 Testing
The following operations were tested:
•	Adding items
•	Viewing items
•	Updating existing and non-existing items
•	Deleting items
•	Handling invalid menu choices
•	Running the program until manual exit
All features worked as expected.
________________________________________
📄 License
This project is open-source and free to use for learning and academic purposes.

