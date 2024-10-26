# Case Management API

## Overview
The Case Management API is a Django REST framework-based application that provides a backend for managing legal case information. The API allows users to access and filter case data, ensuring that users can only view the data without the ability to modify it.

## Features
- **Read-Only Access**: Users can access case files without the ability to delete, update, or patch them.
- **Filtering**: Users can filter cases based on various attributes, including case number, date delivered, court name, and county name.
- **Searching**: Users can search for cases using keywords in the case number and full text.

## Technologies Used
- **Django**: A high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **Django REST Framework**: A powerful toolkit for building Web APIs in Django.
- **Django Filter**: A Django application that provides filtering capabilities for Django REST Framework.
- **MySQL**: A relational database management system used to store case information.

## Installation

### Prerequisites
- Python 3.x
- pip (Python package installer)
- MySQL server

### Steps to Set Up
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/case-management-api.git
   cd case-management-api

