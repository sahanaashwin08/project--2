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
    <title>Contact Us</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f2f2f2;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .contact-box {
            background: white;
            padding: 25px;
            width: 320px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
        }

        h2 {
            text-align: center;
            color: #f7497d;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        textarea {
            height: 80px;
        }

        button {
            width: 100%;
            margin-top: 15px;
            padding: 10px;
            background: #f7497d;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background: #e63a6d;
        }
    </style>
</head>

<body>

    <div class="contact-box">
        <h2>Contact Us</h2>

        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="text" placeholder="Subject" required>
            <textarea placeholder="Message" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </div>

</body>
</html>


Uploading Screen Recording 2026-01-28 192838.mp4…



#output
http://127.0.0.1:5500/git/html-css-javascript-website/e-commer-website/contact.html
