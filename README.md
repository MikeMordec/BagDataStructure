📚 Overview

BagDataStructure is a Python implementation of a bag (or multiset) data structure that allows for efficient management of items with a maximum size limit. This project demonstrates basic operations such as adding, removing, and checking for items, along with an accompanying test suite to validate its functionality.
🚀 Features

    Dynamic Size Management: Specify the maximum size of the bag upon initialization.
    Basic Operations: Add, remove, and check for items in the bag.
    Iteration Support: Easily iterate over the items in the bag.
    Error Handling: Robust handling of full and empty states.

🛠 Installation

To get started with this project, clone the repository and run the Python script:

git clone https://github.com/yourusername/BagDataStructure.git
cd BagDataStructure

Make sure you have Python 3.x installed on your machine. You can run the script directly:

python bag.py

📖 Usage
Initializing the Bag

from bag import Bag

# Create a bag with a maximum size of 10
my_bag = Bag(maxsize=10)

Adding Items

my_bag.add(10)
my_bag.add("item 2")

Removing Items

my_bag.remove(10)

Checking Contents

if my_bag.contains("item 2"):
    print("Item is in the bag.")

Size and Iteration

print("Current size:", my_bag.size())

for item in my_bag:
    print("Item in bag:", item)

✅ Testing

To ensure the integrity of the Bag implementation, a test suite is included. Run the following command to execute the tests:

python -m unittest test_bag.py

🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, please open an issue or submit a pull request. Follow these steps to contribute:

    Fork the repository.
    Create your feature branch: git checkout -b feature/YourFeature
    Commit your changes: git commit -m 'Add some feature'
    Push to the branch: git push origin feature/YourFeature
    Open a pull request.
