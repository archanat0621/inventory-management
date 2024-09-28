# Inventory Management API
This project is a simple **Inventory Management System** built using **Django Rest Framework (DRF)**. It supports **CRUD operations** (Create, Read, Update, Delete) on inventory items and is secured with **JWT-based authentication**. The API uses **PostgreSQL** as the database and **Redis** for caching frequently accessed items, improving the performance of the system.

## Features

- **User Registration and Authentication**: Users can register, log in, and retrieve tokens using JWT for secured API access.
- **CRUD Operations on Inventory Items**:
  - **Create**: Add new items to the inventory.
  - **Read**: Retrieve item details.
  - **Update**: Modify existing item details.
  - **Delete**: Remove items from the inventory.
- **Redis Caching**: Items are cached in Redis when accessed and served from cache for subsequent requests to improve performance.
- **Unit Tests**: Comprehensive unit tests to ensure the API functions correctly.
- **Logging**: Integrated logging to track API usage, errors, and events for monitoring and debugging.

## Installation

### Prerequisites

Ensure you have the following installed on your system:

- **Python 3.x**
- **PostgreSQL**
- **Redis**
- **pip** (Python package installer)
- **Virtualenv** (optional but recommended)

### Setup

#### 1. Clone the Repository

```bash
git clone https://github.com/archanat0621/inventory-management
cd inventory-management
2. Create a Virtual Environment
bash
Copy code
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
