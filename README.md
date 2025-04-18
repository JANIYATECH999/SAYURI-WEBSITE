<!DOCTYPE html><html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sayurii Official Website</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #7f00ff, #e100ff);
            background-size: 400% 400%;
            animation: gradientBG 10s ease infinite;
            color: white;
        }@keyframes gradientBG {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }

    header {
        background-color: rgba(0, 0, 0, 0.6);
        padding: 20px;
        text-align: center;
        animation: glow 2s ease-in-out infinite alternate;
    }

    @keyframes glow {
        from { text-shadow: 0 0 10px #ff33cc, 0 0 20px #ff33cc, 0 0 30px #ff33cc; }
        to { text-shadow: 0 0 20px #ff99ff, 0 0 30px #ff99ff, 0 0 40px #ff99ff; }
    }

    nav ul {
        display: flex;
        justify-content: center;
        list-style: none;
        padding: 0;
        margin: 10px 0 0;
    }

    nav ul li {
        margin: 0 15px;
    }

    nav ul li a {
        color: #fff;
        text-decoration: none;
        font-weight: bold;
        transition: 0.3s;
    }

    nav ul li a:hover {
        color: #ffccff;
    }

    section {
        padding: 40px 20px;
        text-align: center;
    }

    .photo-gallery img {
        width: 200px;
        height: auto;
        margin: 10px;
        border: 2px solid white;
        border-radius: 10px;
    }

    form {
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 10px;
    }

    input, textarea {
        width: 80%;
        padding: 10px;
        border-radius: 8px;
        border: none;
        outline: none;
        background: #ffffffaa;
        color: #000;
    }

    button {
        padding: 10px 20px;
        background: #ff33cc;
        color: #fff;
        border: none;
        border-radius: 8px;
        cursor: pointer;
        transition: background 0.3s;
    }

    button:hover {
        background: #ff66ff;
    }

    footer {
        text-align: center;
        padding: 20px;
        background: rgba(0, 0, 0, 0.5);
        font-size: 14px;
    }
</style>

</head><body>
    <header>
        <h1>Sayurii Official Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#photos">Photos</a></li>
                <li><a href="#lyrics">Lyrics</a></li>
                <li><a href="#news">News</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header><section id="home">
    <h2>Welcome to Sayurii's World</h2>
    <p>This is the official digital home of MY PRINCES272 and Sayurii.</p>
</section>

<section id="photos">
    <h2>Photo Gallery</h2>
    <div class="photo-gallery">
        <img src="img1.jpg" alt="Photo 1">
        <img src="img2.jpg" alt="Photo 2">
    </div>
</section>

<section id="lyrics">
    <h2>Lyrics</h2>
    <p>Song lyrics and emotional verses will be updated here daily.</p>
</section>

<section id="news">
    <h2>Latest News</h2>
    <p>Updates about Sayurii, events, and creations will appear here.</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <form action="chat.html" method="GET">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
    </form>
    <p>Email: janiduinduwera900@gmail.com | Phone: +94728141271</p>
</section>

<footer>
    <p>© 2025 Sayurii Official | Designed by MY PRINCES272</p>
</footer>

</body></html>
