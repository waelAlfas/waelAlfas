<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Wael's Animated README</title>
<style>
    body {
        background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
        color: white;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0;
        overflow: hidden;
    }
    .container {
        background: rgba(255, 255, 255, 0.1);
        border-radius: 20px;
        padding: 30px;
        max-width: 600px;
        box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
        animation: fadeIn 2s ease-in-out;
    }
    h1 {
        color: #00e6e6;
        animation: glow 1.5s infinite alternate;
    }
    @keyframes glow {
        from { text-shadow: 0 0 10px #00e6e6, 0 0 20px #00e6e6; }
        to { text-shadow: 0 0 20px #00ffcc, 0 0 40px #00ffcc; }
    }
    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(-20px); }
        to { opacity: 1; transform: translateY(0); }
    }
    .skills, .contact {
        margin-top: 20px;
        padding-left: 20px;
    }
    li {
        margin-bottom: 5px;
    }
    .highlight {
        color: #ffcc00;
    }
</style>
</head>
<body>
    <div class="container">
        <h1>Hi there, I'm Wael Saeed Sagheer Al-Fasli 👋</h1>
        <p>🎓 <span class="highlight">Information Systems Student</span> at Amran University – Yemen.</p>
        <p>💡 Passionate about technology, programming, and problem-solving.</p>
        <p>📚 Constantly learning and building a strong foundation in <b>Programming, Databases, and Networking</b>.</p>
        <p>🎯 Aspiring to establish a tech company that makes a real difference in my community.</p>
        <div class="skills">
            <h2>🛠 Skills</h2>
            <ul>
                <li>Programming Languages: Java, HTML, CSS, JavaScript</li>
                <li>Databases: Oracle, MySQL</li>
                <li>Concepts: OOP, Data Structures, Algorithms</li>
                <li>Tools: Git, GitHub, VS Code, NetBeans</li>
            </ul>
        </div>
        <div class="contact">
            <h2>📫 Contact Me</h2>
            <ul>
                <li>Email: <a href="mailto:YOUR_EMAIL@example.com">YOUR_EMAIL@example.com</a></li>
                <li>GitHub: <a href="https://github.com/USERNAME" target="_blank">USERNAME</a></li>
                <li>LinkedIn: Add link if available</li>
            </ul>
        </div>
        <p><i>"Continuous learning and practical application are the keys to success."</i></p>
    </div>
</body>
</html>
