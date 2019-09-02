# Item-Catalog-Project

# About

This is the Two project for the Udacity Full Stack Nanodegree. The Item Catalog project consists of developing an application that
provides a list of items within a variety of categories, as well as provide a user registration and authentication system. This project
uses persistent data storage to create a RESTful web application that allows users to perform Create, Read, Update, and Delete operations.

# How to Run?

1- Python 3

2- Vagrant

3- VirtualBox

# Set Up

- Clone the fullstack-nanodegree-vm repository.

- Look for the catalog folder and replace it with the contents of this respository.


# JSON Endpoints

The following are open to the public:

Catalog JSON: /catalog/JSON - Displays the whole catalog. Categories and all items.

Category Items JSON: /catalog/<path:category_name>/items/JSON - Displays items for a specific category

Categories JSON: /catalog/categories/JSON - Displays all categories

Category Item JSON: /catalog/<path:category_name>/<path:item_name>/JSON - Displays a specific category item.
