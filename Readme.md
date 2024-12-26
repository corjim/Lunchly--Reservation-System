# Lunchly App

Lunchly is a simple restaurant reservation management system designed to help you manage customers and reservations efficiently.

---

## Features

1. **Customer Management**:
   - Add new customers with details like first name, last name, phone number, and notes.
   - Edit customer information.
   - Search for customers by name.

2. **Reservations**:
   - Add new reservations for customers.
   - View all reservations for a specific customer.

3. **Top Customers**:
   - View the top 10 customers who have made the most reservations.

4. **Industry Integration** (if applicable):
   - Connect companies to specific industries.
   - View associated companies by industry.

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd lunchly
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Set up the database:
   - Run the SQL scripts in the `/db` directory to create the necessary tables.
   - Update the connection settings in `db.js` as required.

5. Start the server:
   ```bash
   npm start
   ```

6. Open the app in your browser:
   ```
   http://localhost:3000
   ```

---

## Usage

### Customer Management
- To add a new customer, navigate to the “Add Customer” page and fill out the form.
- To view or edit customer details, click on their name in the customer list.

### Searching for Customers
- Use the search bar in the navigation menu to quickly find customers by name.

### Reservations
- Add reservations from a customer's detail page.
- View all reservations for a specific customer.

### Top Customers
- Visit the “Top Customers” page from the navigation menu to view customers with the most reservations.

---

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
   ```bash
   git checkout -b my-feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add a new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin my-feature-branch
   ```
5. Open a pull request.

---

## Acknowledgments

- **Express.js** for the server framework.
- **Bootstrap** for styling.
- **Moment.js** for date formatting.

---

### Notes

- Ensure your database is properly seeded before running the application.
- For any issues, please open an issue on the repository or contact the project maintainers.

