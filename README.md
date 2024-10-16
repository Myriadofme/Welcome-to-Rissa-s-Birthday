# Welcome-to-Rissa-s-Birthday
Birthday Website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to Rissa's Birthday!</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: url('https://your-flower-glitter-sage-background-url.com') no-repeat center center fixed;
            background-size: cover;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            text-align: center;
            padding: 50px;
            background-color: rgba(255, 255, 255, 0.8);
            margin-bottom: 50px;
        }
        header h1 {
            font-size: 3em;
            color: #006600; /* Sage color */
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.5em;
            color: #b565a7; /* Glitter accent */
        }
        section {
            width: 80%;
            margin: auto;
            background-color: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 50px;
        }
        .about {
            text-align: center;
        }
        .about img {
            border-radius: 50%;
            width: 200px;
            height: 200px;
        }
        .fun-facts ul {
            list-style: none;
            padding: 0;
        }
        .fun-facts ul li {
            font-size: 1.2em;
            margin: 10px 0;
        }
        .survey-form {
            background-color: rgba(240, 240, 240, 0.8);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
        .survey-form input, .survey-form select, .survey-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8);
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Rissa's Birthday Bash!</h1>
        <p>Celebrating Life, Friendship, and Fun</p>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <img src="your-photo-url.jpg" alt="Rissa's Photo">
        <p>Hi! I'm Rissa, and I'm so excited to have you celebrate with me. This journey has been full of amazing memories, and I can't wait to make more with all of you. Here's a bit about me and some fun facts!</p>
    </section>

    <section class="fun-facts">
        <h2>Fun Facts About Me</h2>
        <ul>
            <li>I love dancing and learning new dance styles.</li>
            <li>I'm a huge fan of Chamorro and Filipino food.</li>
            <li>Glitter is my favorite accessory to anything!</li>
            <li>I'm always ready for an adventure with friends!</li>
        </ul>
    </section>

    <section class="survey-form">
        <h2>Tell Me About You</h2>
        <form action="your-survey-endpoint.com" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="location">Where are you coming from?</label>
            <input type="text" id="location" name="location" required>

            <label for="drive">How was the drive?</label>
            <textarea id="drive" name="drive" rows="3"></textarea>

            <label for="guests">How many guests are with you?</label>
            <input type="number" id="guests" name="guests" min="1" required>

            <label for="arrival">What time did you arrive?</label>
            <input type="time" id="arrival" name="arrival" required>

            <label for="food">Have you tried Chamorro/Filipino food before?</label>
            <select id="food" name="food" required>
                <option value="yes">Yes</option>
                <option value="no">No</option>
            </select>

            <label for="party">Are you excited to party?</label>
            <select id="party" name="party" required>
                <option value="yes">Yes</option>
                <option value="no">No</option>
            </select>

            <label for="drink">Do you drink?</label>
            <select id="drink" name="drink" required>
                <option value="yes">Yes</option>
                <option value="no">No</option>
            </select>

            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>Can't wait to see you there! 🎉</p>
    </footer>
</body>
</html>
