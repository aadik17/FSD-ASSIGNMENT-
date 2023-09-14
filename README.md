# FSD-ASSIGNMENT-
Assignment 2
#page1

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>European Tourism</title>
</head>
<body align="center" bgcolor="neon-green">
  <h1>Welcome to European Tourism</h1>
  <p>Plan your dream vacation in Europe!</p>
  
  <form action="map.html" method="get">
    <label for="destination">Select a destination:</label>
    <select id="destination" name="destination">
      <option value="paris">Paris</option>
      <option value="rome">Rome</option>
      <option value="barcelona">Barcelona</option>
    </select>
    <button type="submit">Show Map</button>
  </form>

  <img src="rome.jpg" alt="rome" width="60%" height="40%">
  
  <p>Explore the beauty of Europe!</p>
  <a href="about.html">Learn more</a>
</body>
</html>

#page2

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>European Tourism - Map</title>
</head>
<body>
  <h1>Explore Your Destination</h1>
  <p>Here's a map of your selected destination:</p>
  
  <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d83998.96777906356!2d2.2646345498851583!3d48.85882549210955!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47e66e1f06e2b70f%3A0x40b82c3688c9460!2sParis%2C%20France!5e0!3m2!1sen!2sin!4v1692246852606!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  
  <p>Ready to explore?</p>
  <a href="index.html">Go back</a>
  <a href="about.html">Learn more</a>
</body>
</html>


#page3

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About European Tourism</title>
</head>
<body>
  <h1>About European Tourism</h1>
  <p>Discover the charm and diversity of European destinations. From historic landmarks to vibrant cultures, Europe has something for everyone.</p>
  
  <p>Plan your next adventure with us!</p>
  <a href="index.html">Home</a>
  <a href="map.html">Explore</a>
</body>
</html>


#page4

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>European Tourism</title>
</head>

<body align="center" bgcolor="yellow"></body>
<table border="2" align="center">
    <thread>
        <th>studentid</th>
        <th>name</th>
        <th>age</th>
    </thread>
    <tbody>\
        <tr>
            <td>00</td>
            <td colspan="3">bog</td>
            
        </tr>
        <tr>
            <td>01</td>
            <td>Zeeshan</td>
            <td rowspan="3">2</td>
        </tr>
        <tr>
            <td>02</td>
            <td>Aman</td>
        </tr>
        <tr>
            <td>03</td>
            <td>Anuj</td>
        </tr>
    </tbody>
</table>
<br><br><br>

<form>
    <label for="email">enter email</label><br>
    <input type="text"id="email" placeholder="enter email">
    <br>
    <br>
   
    <label for="password">enter password</label><br>
    <input type="text" id="password" placeholder="enter password"><br>
    
   
    <input type="checkbox" name="game" id="school">bgmi<br>
    <input type="radio" name="fav lang" id="java" value="java">java <br><br><br>
    <input type="submit" value="click here to submit"><br>
</form>

</body>
</html>
