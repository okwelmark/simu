<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="refresh" content="30">
    <title>Contact Edgar</title>
</head>
<style>
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding-top: 10px;
    padding-left: 20px;
    padding-bottom: 30px;
    padding-right: 30px;
    background-color: #1166f0;
    background-image: url('red.JPG');
    background-repeat: repeat-y;
    background-position: center center;
    background-attachment: fixed;
    opacity: 0.9;
    background-size: 100%;
}
      /* Style the navigation bar */
      .navbar {
    overflow: hidden;
    background-color: #041553;
  }
  .footer {
    overflow: hidden;
    background-color: indigo;
    text-align: center;
  }

  /* Style the links inside the navigation bar */
  .navbar a {
    float: right;
    display: block;
    color: rgba(225, 174, 174, 0.393);
    text-align: center;
    padding: 40px 22px;
    text-decoration: none;
  }
  .navbar p {
        float: left;
        padding: 30px 22px;
        color: lawngreen;
      }
  .navbar img{
    float: left;
    width: 80px;
    height: 80px;
    border-radius: 50%;
    padding: 22px;
  }

  /* Change the color of links on hover */
  .navbar a:hover {
    background-color: #706c67;
    color: black;
  }
  .container {
        overflow: hidden;
        margin: 0 auto;
        padding: 20px;
        background-color: #7bd9ea;
        display: flex;
        flex-wrap: wrap;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        opacity: 0.7;
      }
      .social-media {
        display: flex;
        justify-content: center;
        align-items: center;
        margin-top: 50px;
        padding: 100px 22px;
      }

      .social-media a {
        margin: 0 20px;
      }

      .social-media img {
        width: 40px;
        height: 40px;
      }

</style>
<body>
    <!-- Navigation bar -->
    <div class="navbar">
      <img src="profile.JPG" alt="edgar">
      <p>Okwel Edgar Mark</p>
      <a href="contact.html">Contact me</a>
      <a href="achievementsandexperience.html">Experience</a>
      <a href="education.html">Education</a>
      <a href="hobbies.html">Hobbies</a>
      <a href="about.html">About</a>
      <a href="homepage.html">Home</a>
      </div>
      <fieldset>
        <div class="container">
          <form action="mail:mcedgars190@gmail.com" method="post" align="center">
              <fieldset>
                <h1>Contact Form</h1>
                <p>
                  <label>FirstName
                    <input type="FirstName" placeholder="First name" size="29" />
                  </label>
                </p>
                <p>
                  <label>LastName
                    <input type="LastName" placeholder="Last name" size="29" />
                  </label>
                </p>
                <p>
                  <label>Email
                    <input type="Email" placeholder="Email" size="29" />
                  </label>
                </p>
                <p>
                  <label for="Contact" placeholder="Contact" size="29"> </label>
                </p>
                <p>
                  <label for="Date" size="29">
                    <br />
                  </label>
                </p>
                <p>
                  <strong>Gender</strong><br />
                  <label>male
                    <input type="radio" name="Gender" value="Male" />
                  </label>
                  <label>female
                    <input type="radio" name="Gender" value="Female" />
                  </label>
                </p>
                <p>
                  <input type="submit" />
                </p>
                </fieldset>
            </form>
          </fieldset>
        </form>
        </div>
      </fieldset> 
      <form action="mail:mcedgars190@gmail.com" method="post" align="center">
        <fieldset>
          <div class="container">
            <p>Connect with me on</p>
            <div class="social-media">
      <a href="https://okwelmark.github.io/simu/">Contact me</a>
      <a href="https://okwelmark.github.io/ngec/">Experience</a>
      <a href="https://okwelmark.github.io/somaa/">Education</a>
      <a href="https://okwelmark.github.io/mit/">Hobbies</a>
      <a href="https://okwelmark.github.io/amaka/">About</a>
      <a href="https://okwelmark.github.io/home/">Home</a>
            </div>
          </div>
        </fieldset>
      </form> 
      <div class="footer">
        <footer>
          <p>mcedgars <a href="mailto:mcedgars190@gmail.com">mcedgars190@gmail.com</a> <strong>A student of Software Engineering</strong></p>
        </footer>
      </div> 
</body>
</html>
