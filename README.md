# Sommelier Software

The main objective of this software is to simplify the order processing workflow by combining all the relevant automation tools in one place. It achieves this by storing data in a **MongoDB** database and utilizing the **PySimpleGui** Python library to create the graphical user interface (GUI).

The **PySimpleGui** library is built on top of the **Tkinter** standard Python library, which is included with Python when it is installed. This library offers a straightforward way of building GUIs for Python applications, making it an ideal choice for this software.

By utilizing **MongoDB** and **PySimpleGui**, the software provides a robust and user-friendly platform for managing order processing tasks. The database enables efficient data storage and retrieval, while the GUI simplifies the process of initiating and monitoring automated tasks.

#### What does the software do?

The software is designed to simplify and automate order processing tasks. The process starts with selecting an Excel or JSON file from the source website, followed by selecting the website and operations to be initiated upon clicking the "START" button.

Once the "START" button is clicked, the order data is saved on the database. Web automation techniques are then used to extract the tracking code of the order and save it in the database. The software then proceeds to authenticate the order and upload the tracking code, following which it sends email notifications to the logistics department for further processing.

The "Home" tab displays the results of the process in the "Process Info" field. The "Orders" tab displays the saved orders for the current month, from the 1st day of the month until the last day, to avoid overloading the table with unnecessary data. From this tab, users can delete or export the current table to an Excel file and search for orders based on specific dates.

The "History" tab contains all the initiated processes, and users can view, delete, or search for processes from previous dates. Selecting an order and clicking the "View" button shows the process reference for that particular order. Deleting a process removes all orders associated with it. Finally, the "Settings" tab allows users to modify their settings, which are saved on the database.

Overall, the software streamlines the order processing workflow and provides an efficient and organized way to manage orders.



![1](https://user-images.githubusercontent.com/73201340/226767978-fffc6d9e-9da4-4e5f-9692-11419503ed76.png)
![2](https://user-images.githubusercontent.com/73201340/226767981-2cbe74bd-ebac-48d8-9f46-b89ae2886c75.png)
![3](https://user-images.githubusercontent.com/73201340/226767986-c156cc6c-5645-49b4-9bc0-6c812900e9d2.PNG)
![4](https://user-images.githubusercontent.com/73201340/226767989-8ca11362-6bfb-4877-a9f9-cdbed445e227.png)
![5](https://user-images.githubusercontent.com/73201340/226767990-e1f1ef1e-0757-4e1f-8eb2-6b5ade85d1ed.png)
