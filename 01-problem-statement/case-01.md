# Case Study: Database Design for an Instagram-Based Thrift and Handmade Store

## Problem Statement

A small creator has started an Instagram-based store where they sell thrifted fashion
items and handmade products. At first, the business is very small and receives orders
through Instagram DMs and WhatsApp. Over time, the store starts growing and now the
owner wants to manage products better, keep track of available stock, handle customer
orders properly, and maintain basic information about delivery and payments.

Some products are thrifted and only have one piece available. Some are handmade and
can have multiple units. Some items may have size, color, or condition details. The
business owner may also want to store customer details, order history, payment status,
and shipping status.

This is not just a shop problem. The design must carefully account for how thrift and
handmade products differ. A thrift item may be unique, while a handmade item may be
created in batches or in multiple pieces. A good design should reflect the business
properly.

---

## Objective

Design a database model that can support this business in a practical way.

The ER diagram should be able to answer questions like:

- What products are being sold?
- Are they thrifted items or handmade items?
- How many pieces are available?
- Which customer placed which order?
- What items were part of one order?
- Was the order paid for?
- Has the order been shipped or delivered?
- Can one customer place multiple orders?
- Can one order contain multiple products?
- How do we store product-specific details like size, category, color, condition, or price?

---

## Deliverable

Design an ER diagram for this platform.

The diagram must include:

- All important entities
- Attributes for each entity
- Primary key for every main entity
- Foreign keys wherever relationships exist
- Proper relationships between entities
- Cardinality wherever relevant
- Any junction table required for many-to-many relations

---

## Constraints and Design Considerations

- A customer can place multiple orders.
- One order can contain multiple products.
- Some products may be unique pieces.
- Some products may have reusable inventory.
- Product condition should be considered for storage.
- Payment and shipping details should be represented as separate concerns.
- Avoid putting too much unrelated information in one entity.
- Keep the design normalized and clean.
- Use meaningful names for entities and attributes.