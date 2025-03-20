<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements</title>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to Our Website</h1>
    </header>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Important Steps</h2>
        <ol type="I">
            <li>Step One: Research</li>
            <li>Step Two: Development</li>
            <li>Step Three: Testing</li>
            <li>Step Four: Launch</li>
            <li>Step Five: Maintenance</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Featured Image</h2>
        <img src="https://images.pexels.com/photos/167699/pexels-photo-167699.jpeg" alt="Beautiful Landscape" width="500">
    </section>

    <!-- Contacts Table -->
    <section>
        <h2>Contact Information</h2>
        <table border="1">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>John Doe</td>
                    <td>123 Main St</td>
                    <td>(123) 456-7890</td>
                    <td>johndoe@email.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Oak Ave</td>
                    <td>(987) 654-3210</td>
                    <td>janesmith@email.com</td>
                </tr>
                <tr>
                    <td>Michael Johnson</td>
                    <td>789 Pine Rd</td>
                    <td>(555) 123-4567</td>
                    <td>mikejohnson@email.com</td>
                </tr>
                <tr>
                    <td>Emily Davis</td>
                    <td>101 Maple Dr</td>
                    <td>(444) 789-0123</td>
                    <td>emilydavis@email.com</td>
                </tr>
                <tr>
                    <td>Chris Lee</td>
                    <td>202 Birch Blvd</td>
                    <td>(333) 654-9876</td>
                    <td>chrislee@email.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <!-- Name Field -->
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <br><br>

            <!-- Email Field -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>

            <!-- Password Field -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Create a password" required minlength="8">
            <br><br>

            <!-- Date Field -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>

            <!-- Dropdown (Select) -->
            <label for="gender">Gender:</label>
            <select id="gender" name="gender" required>
                <option value="">Select Gender</option>
                <option value="male">Male</option>
                <option value="female">Female</option>
                <option value="other">Other</option>
            </select>
            <br><br>

            <!-- Radio Buttons -->
            <label>Preferred Contact Method:</label>
            <input type="radio" id="emailContact" name="contactMethod" value="email" required>
            <label for="emailContact">Email</label>
            <input type="radio" id="phoneContact" name="contactMethod" value="phone" required>
            <label for="phoneContact">Phone</label>
            <br><br>

            <!-- Checkboxes -->
            <label>Interests:</label>
            <input type="checkbox" id="news" name="interests" value="news">
            <label for="news">News</label>
            <input type="checkbox" id="offers" name="interests" value="offers">
            <label for="offers">Special Offers</label>
            <input type="checkbox" id="events" name="interests" value="events">
            <label for="events">Events</label>
            <br><br>

            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Multimedia: Audio and Video -->
    <section>
        <h2>Multimedia</h2>

        <!-- Audio Element -->
        <h3>Audio Player</h3>
        <audio controls>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>
        <br><br>

        <!-- Video Element -->
        <h3>Video Player</h3>
        <video controls width="500">
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>

</body>
</html>
