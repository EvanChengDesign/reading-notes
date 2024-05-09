 **Reading Notes | 9 MAY 2024**

# Class 008

### *Bookmarks:*

## **Questions & Answers**  

# Vehicle Maintenance Log

## Project Scope and Requirements

### User Roles
- **Admin**: Manages the overall platform, including adding new mechanics and overseeing all maintenance logs.
- **Mechanic**: Manages vehicle records, logs maintenance performed, and views parts inventory.
- **Car Owner**: Logs vehicle data, schedules maintenance, and views their vehicle's maintenance history.

## Features to Implement

### Authentication
- **Basic Authentication**: Implement basic authentication for initial account creation (admin, mechanic, and car owner).
- **Bearer Token Authentication**: Secure subsequent API calls with bearer tokens.

### CRUD Operations
- **Vehicles**:
  - Admins and car owners can add new vehicles and update their details.
  - Mechanics and owners can view a vehicle's maintenance history.
- **Maintenance Logs**:
  - Mechanics can add service records to a vehicle's maintenance log.
  - Admins can review all service logs for quality control.
- **Parts Inventory**:
  - Mechanics and admins can add, update, and remove parts from the inventory.
  - Admins can manage pricing and availability.

### Access Control List (ACL)
- Admins should have full control over user and data management.
- Mechanics should access only their assigned vehicles and maintenance logs.
- Car owners can only see and modify their own vehicle records.

### Database Design
- **Tables**:
  - **Users**: Store user account information, roles, and authentication tokens.
  - **Vehicles**: Hold vehicle data including VIN, model, and owner information.
  - **Maintenance Logs**: Record service history for vehicles (date, type, description, mechanic ID).
  - **Parts Inventory**: Maintain details of parts available for repairs (name, type, quantity, price).

### Endpoints
- `/vehicles` for adding/viewing vehicles.
- `/vehicles/:id/logs` for managing specific vehicle logs.
- `/logs/:id` for updating/removing logs.
- `/inventory` for managing parts.

# Recipe Sharing Platform

## Project Scope and Requirements

### User Roles
- **Admin**: Full control over platform content and user management.
- **Chef**: Create and manage personal recipe collections.
- **Reader**: Access and save recipes, rate, and leave comments.

## Features to Implement

### Authentication
- **Basic Authentication**: Create initial accounts for different roles.
- **Bearer Token Authentication**: Secure sessions after login.

### CRUD Operations
- **Recipes**:
  - Chefs can add, update, and delete their recipes.
  - Readers can view recipes and save their favorites.
  - Admins can curate featured recipes and remove inappropriate ones.
- **Comments and Ratings**:
  - Readers and chefs can comment on and rate recipes.
  - Admins can moderate comments and flag inappropriate content.

### Access Control List (ACL)
- Admins have full control over recipes, comments, and user accounts.
- Chefs can only manage their own recipes and respond to comments.
- Readers can access the public content and interact within those boundaries.

### Database Design
- **Tables**:
  - **Users**: Store account data and roles for authentication.
  - **Recipes**: Recipe metadata (title, ingredients, instructions, chef ID).
  - **Comments**: Comments associated with a specific recipe (text, user ID, recipe ID).
  - **Ratings**: Numeric rating values, with relationships to users and recipes.

### Endpoints
- `/recipes` for adding/viewing recipes.
- `/recipes/:id` for updating/removing specific recipes.
- `/recipes/:id/comments` for managing recipe comments.
- `/recipes/:id/ratings` for managing recipe ratings.
