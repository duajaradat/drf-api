# Django REST Framework & Docker

## Author : 

Du'a Jaradat

---

## Links and Resources

- [Pull Request](https://github.com/duajaradat/drf-api/pull/1)

---

## Overview

Add full CRUD functionality to your bag of tricks by building a Django project that allows Creating, Reading, Updating and Deleting.

---
## Feature Tasks and Requirements

 - Create snacks_crud_project Django project

 - Create snacks app

 - Create Snack model
      - title field
      - purchaser field
      - description field
      - Register model with admin

 - Create SnackListView that extends appropriate generic view
      - associated url path is an empty string

 - Create SnackDetailView that extends appropriate generic view
      - associated url path is <int:pk>/

 - Create SnackCreateView that extends appropriate generic view
      - associated url path is create/     

 - Create SnackUpdateView that extends appropriate generic view
      - associated url path is <int:pk>/update/

 - Create SnackDeleteView that extends appropriate generic view 
      - associated url path is <int:pk>/delete/ 

 - Add urls to support all views, with appropriate names
 - Add templates to support all views
 - Add navigation links in appropriate locations to access all pages
 - Make all necessary changes to project level files for project to run
      - In other words, make it work          
---

## Implementation Notes

- A lot of functionality is being added here. But it should still follow the “Django way.” So when in doubt refer back to demo.

--- 

## User Acceptance Tests

 - Test all Views
 - Test Model
      - string representation
      - all fields

- When in doubt on what to test refer to demo

---

## Tools and Dependencies

- Poetry
- flake8
- black
- django

---
