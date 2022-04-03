# MyQ Shopping Design Documents

## Overview

These are matterials of a solution software design that's applicable to following business requirements:

* The MyQ shopping is an online service for goods retailers listing their products in organization of the main catalogue for sale.
* Retailers have to register themself and have a space for add their products and its' price.
* Customers do browsing/searching products in catalogue, or using tags browsing, comparing the price between retailers of single interested product and select. They can add the product with desired quantity to a shopping cart then checking out.
* Customers are checking out the cart then it places an order to specific retailers of selected products.
* The new order information will be notified to the retailers or called to the retailer’s online shopping API (if he/she has) for order processing & delivery.

Following assumption of technologies and platforms:

* Using AWS Cloud service.
* Using Java platforms for most applications.
* Containerize of running instance (mostly).

The documents here is for development teams know how to build a new online shopping service in generally with microservices architecture. There are more detail documents need to be added in the working task of the project. The design is intent to get robust, highly responsive, and highly scalable goal.

## Document listing

1. The main slide (read first): "MyQ Online Shopping.odp"
2. design/illustration: the directory of illustration to describe: System components diagram, Entities Relationship Diagrams (ERD), Table Design, Sequence diagrams, Illustration of a feature.

## Design working status on modules:

Following items are done/partial done by the slide and illustrations:

* Overview of features, business follow and microservices scoping: completed.
* Overall system diagram on AWS: completed.
* Product Catalogue: all completed (overview, ERD, Feature description by examples, operation description, implementation logic guidance, solution options for scalable).
* Shopping Carts: overview, ERD and table design, scalable options.
* Order and Delivery: only overview, ERD and table design.
* Customer and Session: only overview and ERD.
* Retailer and Integration: only overview and ERD.
