
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Samuel Service</title>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Samuel Service</h1>
        <p>Your trusted partner for multimedia solutions</p>
    </header>

    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#multimedia">Multimedia</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Main Content -->
    <main>
        <!-- Home Section -->
        <section id="home">
            <h2>Welcome to Samuel Service</h2>
            <p>We provide high-quality multimedia services including audio, video, and web development solutions.</p>
            <img src="https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885_1280.jpg" alt="Samuel Service" width="600">
        </section>

        <!-- Services Section -->
        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>High-quality audio production</li>
                <li>Professional video editing</li>
                <li>Web development & design</li>
                <li>Multimedia consulting</li>
            </ul>
        </section>

        <!-- Multimedia Section -->
        <section id="multimedia">
            <h2>Multimedia Showcase</h2>
            <h3>Sample Audio</h3>
            <audio controls>
                <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>

            <h3>Sample Video</h3>
            <video controls width="600">
                <source src="http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4" type="video/mp4">
                Your browser does not support the video tag.
            </video>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Register With Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required minlength="3"><br><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>

                <label for="password">Password:</label>
                <input type="password" id="password" name="password" 
                       required pattern="(?=.*\d)(?=.*[A-Z]).{6,}" 
                       title="Must contain at least one number, one uppercase letter, and be at least 6 characters"><br><br>

                <label for="age">Age:</label>
                <input type="number" id="age" name="age" min="18" max="100"><br><br>

                <input type="submit" value="Register">
            </form>
        </section>

        <!-- Schedule Section -->
        <section>
            <h2>Service Schedule</h2>
            <table border="1">
                <tr>
                    <th>Time</th>
                    <th>Service</th>
                    <th>Location</th>
                </tr>
                <tr>
                    <td>9:00 AM</td>
                    <td>Audio Production</td>
                    <td>Studio A</td>
                </tr>
                <tr>
                    <td>11:00 AM</td>
                    <td>Video Editing</td>
                    <td>Studio B</td>
                </tr>
            </table>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Samuel Service. All Rights Reserved.</p>
    </footer>
</body>
</html>
