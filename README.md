
# Roxiler System Assessment - MERN Stack

This project implements backend APIs and a frontend UI for managing product transactions data, using the MERN stack.

## Backend
The backend fetches product transaction data from a third-party API and provides the following functionalities:
1. Initialize the database with product transaction data.
2. List product transactions with search and pagination.
3. Show statistics (total sales, sold items, unsold items) for a selected month.
4. Display data for a bar chart (price ranges).
5. Display data for a pie chart (item categories).
6. Combine data from the statistics, bar chart, and pie chart APIs.

### Available APIs:
- **/initialize**: Initializes the database.
- **/transactions**: Lists product transactions with search and pagination.
- **/statistics**: Shows total sales, sold and unsold items.
- **/price-range**: Displays price ranges and counts.
- **/categories**: Shows item categories and counts.
- **/combined**: Combines data from all statistics APIs.

## Frontend
The frontend uses the above APIs to:
- List transactions in a table with pagination.
- Show statistics for sales, sold and unsold items.
- Display a bar chart for price ranges.
- Display a pie chart for item categories.


