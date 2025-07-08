# Product Table
## Date: 08.07.2025
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Product Table</title>
    <link href="style.css" rel="stylesheet">
</head>
<body>
    <h1>Styled Product Table</h1>
    <table>
        <thead class="thead">
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody class="tbody">
            <tr>
                <td>Laptop</td>
                <td>₹45,000</td>
                <td>High-speed performance</td>
            </tr>
            <tr>
                <td>Phone</td>
                <td>₹25,000</td>
                <td>Photo Quality</td>
            </tr>
            <tr>
                <td>Bike</td>
                <td>₹205,000</td>
                <td>Good Mileage</td>
            </tr>
            <tr>
                <td>Play Station</td>
                <td>₹25,000</td>
                <td>new Graphics card technology and ease of use</td>
            </tr>
            <tr>
                <td>Washing Machine</td>
                <td>₹51,000</td>
                <td>Handles more load and cleans Faster</td>
            </tr>
            <tr>
                <td>Trekking Bag</td>
                <td>₹8,000</td>
                <td>better durability and designed technology</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```
## CSS Code:
```
h1{
    font-family: sans-serif;
    text-align: center;
    color: rgb(0, 45, 30);
}
table {
    border-collapse: collapse;
    width: 80%;
    margin: 30px auto;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    font-family: Arial, sans-serif;
    text-align: center;
}

.thead {
    background-color: rgb(112, 148, 255);
    color: rgb(217, 217, 217);
    font-size: 1.6rem;
}

.tbody {
    background-color: #37d32b;
    font-size: 1.3rem;
}

td, th {
    padding: 12px;
    border: 2px solid #292929;
}

.tbody tr:nth-child(even) {
    background-color: #9eea80;
}

.tbody tr:hover {
    background-color: #ffc0c0;
    transition: background-color 0.3s;
}
```
## Output:
![image](https://github.com/user-attachments/assets/9878ddd2-2dc5-4adb-96e2-8ac1c98c10cd)
## Styled Output:
![image](https://github.com/user-attachments/assets/e9696b7f-84ee-46e3-85aa-6ba71a9b6b33)

## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
