# BPMN Diagram - Market Romi Store Management System

## Overview
This Business Process Model and Notation (BPMN) diagram illustrates the order processing workflow within the Market Romi Store Management System. It visualizes how different stakeholders interact with the system and with each other during the order fulfillment process.

## Diagram Components

### Swimlanes
The diagram is divided into four swimlanes representing the key participants:
1. **Customer** - End users who browse products and place orders
2. **System** - The automated store management platform
3. **Sales Staff** - Employees who handle order processing
4. **Inventory Staff** - Employees who manage product inventory

### Process Flow
The diagram illustrates the following sequence:
1. Customer browses products and places an order
2. System processes the order
3. Sales staff reviews the order
4. Inventory staff checks product availability
5. Decision point: Is the product in stock?
   - If yes: Update inventory and prepare the order
   - If no: Return to order processing (potential backorder or cancellation)
6. System updates order status
7. Customer tracks their order

### Key Decision Points
- Inventory availability check is a critical gateway that determines whether an order can be fulfilled immediately

## Using This Diagram
This BPMN diagram serves as a visual guide for understanding and optimizing the order processing workflow. It can be used to:
- Train new staff on order fulfillment procedures
- Identify potential bottlenecks in the process
- Communicate process expectations to stakeholders
- Guide the technical implementation of order processing functionality

## Diagram

![BPMN Diagram for Market Romi](bpmn-diagram.svg)
