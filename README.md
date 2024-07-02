<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Listing</title>
    <style>
        /* CSS for basic styling */
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        th, td {
            padding: 10px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }
        img {
            max-width: 100px;
            height: auto;
        }
        .buy-now {
            text-align: center;
        }
    </style>
</head>
<body>
    <h1>Product Listing</h1>

    <!-- Product Table -->
    <table>
        <thead>
            <tr>
                <th>Image</th>
                <th>Product Name</th>
                <th>Description</th>
                <th>Price</th>
                <th>Buy Now</th>
            </tr>
        </thead>
        <tbody>
            <!-- Product Rows -->
            <tr>
                <td><img src="product1.jpg" alt="Product 1"></td>
                <td>Product 1</td>
                <td>Description of Product 1</td>
                <td>$19.99</td>
                <td class="buy-now"><a href="#">Buy Now</a></td>
            </tr>
            <tr>
                <td><img src="product2.jpg" alt="Product 2"></td>
                <td>Product 2</td>
                <td>Description of Product 2</td>
                <td>$24.99</td>
                <td class="buy-now"><a href="#">Buy Now</a></td>
            </tr>
            <tr>
                <td><img src="product3.jpg" alt="Product 3"></td>
                <td>Product 3</td>
                <td>Description of Product 3</td>
                <td>$14.99</td>
                <td class="buy-now"><a href="#">Buy Now</a></td>
            </tr>
        </tbody>
    </table>

</body>
</html>
