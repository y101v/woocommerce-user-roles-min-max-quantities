# WooCommerce User Role Based Quantity Rules

This plugin customizes WooCommerce to allow setting minimum, maximum, and group quantity rules based on user roles. It integrates seamlessly with the WooCommerce Min/Max Quantities plugin.

## Features

- Define custom quantity rules for WooCommerce products based on user roles.
- Support for both simple and variable products.
- Enhanced select box functionality in the admin panel using Select2.
  

## Requirements

- WordPress
- WooCommerce
- WooCommerce Min/Max Quantities Pro plugin

## Installation

1. **Plugin Installation**:
    - Install and activate the WooCommerce plugin.
    - Install and activate the WooCommerce Min/Max Quantities plugin.

## Usage

### For Simple Products

1. **Admin Settings**:
    - Go to the product edit page in the WordPress admin.
    - In the "General" tab, you will find the "User Roles" multi-select dropdown.
    - Select the user roles you want to apply quantity rules to.
    - For each selected role, set the minimum quantity, maximum quantity, and group of quantity fields.

2. **Frontend**:
    - When a user with a specific role views a product, the quantity input field will be adjusted based on the defined rules.

### For Variable Products

1. **Admin Settings**:
    - Go to the product edit page and select the "Variations" tab.
    - For each variation, you will find the "User Roles" multi-select dropdown.
    - Select the user roles you want to apply quantity rules to.
    - For each selected role, set the minimum quantity, maximum quantity, and group of quantity fields.

2. **Frontend**:
    - When a user with a specific role views a product variation, the quantity input field will be adjusted based on the defined rules.
      
