---
name: User Story
about: This template is for creating user stories
title: 
labels: 
assignees: ''
---

## User Story

As a product manager  
I need the ability to create a new product in the catalog  
So that customers can view and purchase products online  

## Details and Assumptions

* Products will have a name, description, price, and category
* Only authorized users can create products

## Acceptance Criteria

```gherkin
Given the product catalog system is running
When the user enters valid product details and submits the form
Then the new product should be added to the catalog

Given a product already exists
When the user tries to create a product with the same ID
Then the system should display an error message
