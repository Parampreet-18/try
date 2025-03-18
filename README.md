# 🌟 Projecs

## 📌 Ready projects

## 🎨 Demo Preview (HTML & CSS)
Here is a simple **HTML & CSS** snippet from the project:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Design</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f5f5f5;
        }

        .navbar {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }

        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 50vh;
            background: #6200ea;
            color: white;
            text-align: center;
        }

        .hero h1 {
            font-size: 2.5rem;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
            gap: 20px;
        }

        .card {
            background: white;
            padding: 20px;
            width: 300px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            text-align: center;
        }

        @media (max-width: 768px) {
            .hero {
                height: 40vh;
            }
            .hero h1 {
                font-size: 2rem;
            }
            .container {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="navbar">Responsive Navbar</div>
    <div class="hero">
        <h1>Welcome to Our Responsive Website</h1>
    </div>
    <div class="container">
        <div class="card">Card 1</div>
        <div class="card">Card 2</div>
        <div class="card">Card 3</div>
    </div>
</body>
</html>

