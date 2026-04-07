# Instagram Thrift Creator Store - ER Diagram

## Overview
This project presents an Entity Relationship Diagram (ERD) for a small Instagram-based business that sells both thrifted and handmade products. The schema is designed to support product management, inventory tracking, customer orders, payments, and shipment handling in a normalized and practical structure.

## Business Scope Covered
- Product catalog management for thrifted and handmade items
- Category-based product organization
- Customer profiles and multiple addresses
- Order lifecycle with item-level details
- Payment tracking with transaction details
- Shipment tracking and fulfillment status
- Inventory support for reusable stock and reserved units

## Core Entities
- products
- thrifted_product
- handmade_product
- inventory
- customer
- address
- category
- order
- order_item
- payment
- shipment

## Key Relationship Highlights
- One customer can place many orders
- One order can contain many order items
- Products are linked to category and inventory
- Product specialization is handled through thrifted_product and handmade_product
- Orders are connected to payment and shipment records

## Diagram Link
ER Diagram: https://github.com/TheSoumenMondal/db_designs/blob/main/Instagram_Thrift_Creator_Store/er_diagram.png

## Notes
This ERD is intended for database design evaluation and focuses on clarity, normalization, and real-world thrift-store operations.

