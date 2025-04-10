# Data Flow Diagram (DFD) - Market Romi Store Management System

## Overview
This Data Flow Diagram (DFD) illustrates how information flows through the Market Romi Store Management System. It visualizes the interaction between external entities, processes, and data stores, showing how data is input, processed, stored, and output within the system.

## Diagram Components

### External Entities (Rectangles)
Represent people, organizations, or systems outside the system boundary that interact with the system:
1. **Customer** - End users who place orders and make inquiries
2. **Supplier** - External vendors who provide products to the store
3. **Management** - Decision makers who receive reports and set requirements
4. **Staff** - Store employees who provide support and manage inventory

### Processes (Circles)
Represent activities or functions that transform data within the system:
1. **Order Processing (1.0)** - Handles customer orders and checks product availability
2. **Inventory Management (2.0)** - Manages stock levels and supplier orders
3. **Reporting & Analytics (3.0)** - Generates insights and reports from system data
4. **Customer Support (4.0)** - Handles customer inquiries, issues, and order updates

### Data Stores (Parallel Lines)
Represent repositories where data is stored:
1. **D1: Product Database** - Stores product information and inventory levels
2. **D2: Order Database** - Stores customer order details and status
3. **D3: User Database** - Stores customer and employee account information

### Data Flows (Arrows)
Represent the movement of data between entities, processes, and data stores:
- Order placement and confirmation between customers and the system
- Inventory updates between suppliers and the system
- Reports sent to management
- Support inquiries and resolutions
- Database read and write operations

## Key Information Flows
1. **Order Processing Cycle**:
   - Customers place orders → system processes them → confirms to customers
   - System checks and updates product inventory
   - Order data is stored for reporting and tracking

2. **Inventory Management Cycle**:
   - Management provides inventory requirements
   - System processes purchase orders to suppliers
   - Suppliers deliver products → system updates inventory

3. **Customer Support Cycle**:
   - Customers submit inquiries → support staff address issues
   - Support process may update order or user information

4. **Reporting Cycle**:
   - System collects data from all databases
   - Analytics process generates insights and reports
   - Management receives actionable information

## Using This Diagram
This DFD serves as a blueprint for:
- Understanding system boundaries and interactions
- Identifying key data elements and their transformations
- Planning system integration points
- Documenting information flow for development and training

## Diagram

![Data Flow Diagram for Market Romi](Data-Flow-Diagram.svg)
