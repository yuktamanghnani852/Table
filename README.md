📊 Electronics Product Table

A simple HTML and CSS project that displays an electronics product list in a structured and visually styled table.

The table contains product names, quantities, per-unit prices, individual amounts, and a final total.

📸 Project Overview

The webpage displays an Electronics Product Table with 10 different products.

It demonstrates:

- HTML tables
- Table headers and data cells
- "colspan"
- CSS table styling
- Hover effects
- Background colors
- Table borders
- Centered table layout

🛠️ Technologies Used

- HTML5
- CSS3

No external libraries or frameworks are required.

📂 Project Structure

electronics-product-table/
│
├── index.html
└── README.md

📋 Product Details

SR No.| Product| Quantity| Per Unit Price| Amount
1| Television| 48| ₹30,000| ₹14,40,000
2| Laptop| 24| ₹70,000| ₹16,80,000
3| Mobile| 25| ₹50,000| ₹12,50,000
4| Tablet| 23| ₹30,000| ₹6,90,000
5| PS5 Ultimate| 25| ₹70,000| ₹17,50,000
6| AC| 10| ₹60,000| ₹6,00,000
7| Sound System| 15| ₹10,000| ₹1,50,000
8| Dyson| 23| ₹50,000| ₹15,50,000
9| Fridge| 3| ₹3,00,000| ₹9,00,000
10| Inveter| 6| ₹40,000| ₹2,40,000

«Note: The README table above formats the values for readability. The values are based on the HTML provided.»

🎨 CSS Features

Table Styling

The table uses:

table {
    border-collapse: collapse;
    margin: auto;
    height: 100%;
    width: 80%;
    background-color: bisque;
}

This makes the table:

- Centered on the page
- 80% of the page width
- Styled with a bisque background
- Displayed with collapsed borders

Header Styling

The table header uses:

th {
    background-color: darkseagreen;
}

This gives the header cells a distinct background color.

Hover Effect

When the user moves the mouse over a table row:

tr:hover {
    background-color: aquamarine;
}

The row changes to an aquamarine background color.

➕ Total Row

The final row uses the "colspan" attribute:

<tr>
    <th colspan="4">Total</th>
    <th>9850000</th>
</tr>

The "colspan="4"" combines the first four columns into a single Total cell.

▶️ How to Run

1. Create a file named "index.html".
2. Copy the provided HTML code into the file.
3. Save the file.
4. Open "index.html" in a web browser.

You can also use Visual Studio Code with the Live Server extension for development.

🎯 Learning Objectives

This project is useful for beginners learning:

- HTML table structure
- "<table>"
- "<tr>"
- "<th>"
- "<td>"
- "colspan"
- CSS selectors
- CSS hover effects
- Table borders
- "border-collapse"
- Width and height
- Background colors
- Basic page layout

💡 Possible Improvements

The project could be improved by:

- Adding responsive table styling for mobile devices
- Using semantic HTML instead of the deprecated "border" attribute
- Formatting prices with the "₹" currency symbol
- Adding table padding and improved typography
- Calculating the total dynamically using JavaScript
- Adding sorting and filtering functionality
- Correcting the spelling of "Inveter" to "Inverter"

👨‍💻 Author

Created as a beginner-friendly HTML & CSS table project for practicing table structure and CSS styling.# Table
