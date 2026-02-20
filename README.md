✅ What is this code?

It is a combination of HTML, CSS, and a little JavaScript used to design a contact form where users can enter their details like name, email, subject, and message.

# 1.HTML Part (Structure):
    HTML creates the layout of the page.

 __In this code:__

*<html> → Starts the webpage*
*<head> → Contains title and links to styles*
*<body> → Shows the content on the screen*
*<form> → Creates the contact form*
*<input> → Used for name, email, subject*
*<textarea> → Used to type a message*
*<img> → Displays images*
*<input type="submit"> → Creates the submit button*

👉 Simple: HTML builds the page and form.

# 2.CSS Part (Design):
     CSS is written inside <style> and is used to make the page look beautiful.

__It does things like:__

*Adds background image*
*Styles the contact box*
*Changes colors*
*Makes rounded corners*
*Adds shadows*
*Designs the submit button*
Aligns everything properly

👉 Simple: CSS makes the webpage attractive.

# 3.JavaScript Part (Action):
    At the bottom:
    <script src="contact.js"></script>
    this connects a JavaScript file.

__JavaScript is used to:__

*Move labels when you click inside the input box*
*Check if the fields are filled*
*Improve user interaction*

👉 Simple: JavaScript makes the form interactive. 
### EXAMPLE: 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Food Menu</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ffecd2, #fcb69f);
      text-align: center;
      padding: 40px;
    }
    h1 {
      color: #333;
      margin-bottom: 20px;
    }
    table {
      width: 90%;
      margin: auto;
      border-collapse: collapse;
      font-size: 1.1em;
    }
    th, td {
      padding: 15px;
      text-align: center;
      border: 2px solid #fff;
    }
    th {
      background: #ff6f61;
      color: #fff;
    }
    tr:nth-child(even) {
      background: #ffe5d9;
    }
    tr:nth-child(odd) {
      background: #fff3e6;
    }
    .category {
      font-weight: bold;
      color: #ff6f61;
    }
    .price {
      color: #006400;
      font-weight: bold;
    }
    img {
      width: 80px;
      height: 80px;
      border-radius: 10px;
      object-fit: cover;
    }
  </style>
</head>
<body>
  <h1>🍴 Food Menu</h1>
  <table>
    <tr>
      <th>Photo</th>
      <th>Item</th>
      <th>Category</th>
      <th>Price</th>
    </tr>
    <tr>
      <td><img src="https://via.placeholder.com/80?text=Pizza" alt="Pizza"></td>
      <td>Margherita Pizza</td>
      <td class="category">Main Course</td>
      <td class="price">₹250</td>
    </tr>
    <tr>
      <td><img src="https://via.placeholder.com/80?text=Burger" alt="Burger"></td>
      <td>Veg Burger</td>
      <td class="category">Snacks</td>
      <td class="price">₹120</td>
    </tr>
    <tr>
      <td><img src="https://via.placeholder.com/80?text=Fries" alt="Fries"></td>
      <td>French Fries</td>
      <td class="category">Snacks</td>
      <td class="price">₹80</td>
    </tr>
    <tr>
      <td><img src="https://via.placeholder.com/80?text=Paneer" alt="Paneer Butter Masala"></td>
      <td>Paneer Butter Masala</td>
      <td class="category">Main Course</td>
      <td class="price">₹300</td>
    </tr>
    <tr>
      <td><img src="https://via.placeholder.com/80?text=IceCream" alt="Ice Cream"></td>
      <td>Chocolate Ice Cream</td>
      <td class="category">Dessert</td>
      <td class="price">₹90</td>
    </tr>
    <tr>
      <td><img src="https://via.placeholder.com/80?text=Shake" alt="Mango Shake"></td>
      <td>Mango Shake</td>
      <td class="category">Beverage</td>
      <td class="price">₹70</td>
    </tr>
  </table>

  <script>
    // Highlight expensive items
    const prices = document.querySelectorAll(".price");
    prices.forEach(price => {
      let value = parseInt(price.innerText.replace("₹",""));
      if(value >= 200){
        price.style.color = "red";
      }
    });
  </script>
</body>
</html>


#output
http://127.0.0.1:5500/git/html-css-javascript-website/e-commer-website/index.html

