<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mbui Media - Graphic Design Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2e;
            color: #ececec;
            margin: 0;
            padding: 0;
        }
        header {
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            color: #fff;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        header h1 {
            margin: 0;
            font-size: 3em;
            letter-spacing: 2px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #282a36;
            padding: 15px 0;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }
        nav a {
            color: #f1fa8c;
            margin: 0 20px;
            text-decoration: none;
            font-size: 1.3em;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #50fa7b;
        }
        .container {
            max-width: 1200px;
            margin: 30px auto;
            padding: 0 20px;
        }
        .recent-designs {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }
        .recent-designs img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .recent-designs img:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4);
        }
        .recent-designs h2 {
            text-align: center;
            margin-top: 10px;
            font-size: 1.8em;
            color: #ff79c6;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.4);
        }
        .contact {
            margin-top: 60px;
            text-align: center;
        }
        .contact h2 {
            font-size: 2.2em;
            margin-bottom: 25px;
            color: #bd93f9;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.4);
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            text-align: left;
        }
        .contact-form label {
            display: block;
            margin-bottom: 12px;
            font-weight: bold;
            color: #ffb86c;
        }
        .contact-form input, 
        .contact-form textarea {
            width: 100%;
            padding: 12px;
            margin-bottom: 25px;
            border: 1px solid #44475a;
            border-radius: 5px;
            background-color: #282a36;
            color: #f8f8f2;
            font-size: 1em;
        }
        .contact-form button {
            background: linear-gradient(135deg, #ff79c6, #bd93f9);
            color: #fff;
            padding: 12px 25px;
            border: none;
            border-radius: 5px;
            font-size: 1.3em;
            cursor: pointer;
            transition: background 0.3s;
        }
        .contact-form button:hover {
            background: linear-gradient(135deg, #ff5555, #ff79c6);
        }
        footer {
            background-color: #282a36;
            color: #f8f8f2;
            padding: 15px 0;
            text-align: center;
            margin-top: 60px;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.3);
        }
        footer p {
            margin: 0;
            font-size: 1em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mbui Media</h1>
        <p>Bringing Your Vision to Life Through Creative Design</p>
    </header>
    
    <nav>
        <a href="#recent-designs">Recent Designs</a>
        <a href="#contact">Contact</a>
        <a href="#inquiry">Inquiry</a>
    </nav>

    <div class="container">
        <section id="recent-designs">
            <h2>Recent Designs</h2>
            <div class="recent-designs">
                <div>
                    <img src="design1.jpg" alt="Recent Design 1">
                    <p>Description of Design 1</p>
                </div>
                <div>
                    <img src="design2.jpg" alt="Recent Design 2">
                    <p>Description of Design 2</p>
                </div>
                <div>
                    <img src="design3.jpg" alt="Recent Design 3">
                    <p>Description of Design 3</p>
                </div>
            </div>
        </section>

        <section id="contact" class="contact">
            <h2>Contact Us</h2>
            <form class="contact-form">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Message</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </section>

        <section id="inquiry" class="contact">
            <h2>Inquiry</h2>
            <form class="contact-form">
                <label for="project">Project Description</label>
                <textarea id="project" name="project" rows="5" required></textarea>

                <label for="budget">Estimated Budget</label>
                <input type="text" id="budget" name="budget" required>

                <label for="deadline">Deadline</label>
                <input type="date" id="deadline" name="deadline" required>

                <button type="submit">Submit Inquiry</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Mbui Media. All rights reserved.</p>
    </footer>
</body>
</html>
