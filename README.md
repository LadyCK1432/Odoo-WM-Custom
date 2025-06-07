Demo - Company, Warehouse, and Defective Products Management
## Overview
This module implements the following features:

Control over subsidiaries purchasing from external suppliers

Management of defective products with three categories: discard, repair, return

Automatically select the nearest warehouse based on GPS

## Features
Purchase Control: Prevent subsidiaries from purchasing from suppliers outside the system.

Defective Product Management: Classify defective items into three types: discard, repair, return.

Nearest Warehouse Selection: Automatically determine and select the nearest warehouse based on GPS location.

## Installation
Download the module to the custom_vendor_odoo17 directory.

Ensure all required dependencies are installed: base, purchase, stock, sale_management, contacts.

Install the module via the Apps menu in Odoo.

## Configuration
Access the relevant menus in the Inventory module to configure and use the features.

Manage access rights via pre-defined security rules.

## Data
The module includes the following configuration files:

security/ir.model.access.csv

security/security_rules.xml

views/res_partner_views.xml

views/stock_scrap_views.xml

views/sale_order_views.xml

views/stock_menu.xml

views/warehouse_finder_views.xml

## Information
Version: 1.0

Author: Team 1

Category: Inventory/Inventory

## License
This module is licensed under the AGPL-3.0 or later (http://www.gnu.org/licenses/agpl).
