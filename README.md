# index-html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website</title>
    <link rel="stylesheet" href="style.css">
   <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #3a3939;
            padding: 2em;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #7a7878;
            padding: 0.5em;
        }

        nav a {
            color: rgb(51, 50, 50);
            text-decoration: none;
            padding: 0.5em 1em;
            margin: 0 1em;
            
           
        }

        section {
            padding: 10em;
            background-color: #615f5f;
        }

        footer {
            background-color: #333;
            color: rgb(102, 102, 102);
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
            ;
        }
    </style>
</head>

<body>
    <header>
        <h1>my Website</h1>
    </header>
    
    <nav style="font-family:'Roboto', sans-serif; display: inline;">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#work">Work</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
    </nav>
    

    
    <section id="home">
        <h2>home</h2>
      <img src="https://media.tenor.com/bu0w-cRvyU8AAAAd/welcome.gif" alt="">
   
   
   
   </style>
    </section>
<hr/>

    <section id="about">
        <article>
        <h2>About</h2>
       <h4>self presentation</h4>
<p>ahmed belhassen from sfax , i am 20 years old , a basketball player in club sportif sfaxien  and i study in secondary school and now in the process of learning programming</p>
<img height="200px" src="https://instagram.ftun15-1.fna.fbcdn.net/v/t1.15752-9/399810692_665354532333171_3702203397376690360_n.jpg?stp=dst-jpg_p320x320&_nc_cat=104&ccb=1-7&_nc_sid=510075&_nc_ohc=RPZHxlnNZVoAX-czopc&_nc_ht=instagram.ftun15-1.fna&oh=03_AdRjoa8OjPCG6vPIsBvBBeWD622ljhC4-YTh2b5kS07Q_Q&oe=65779303" alt="">
    
</article>
<table border="2">
    <tr>
        <th>name</th>
        <th>age</th>
        <th>profession</th>
    </tr>
    <tr>
        <th>ahmed</th>
        <th>20</th>
        <th>FS JS DEV</th>
    </tr>
</table>
</section>
<hr/>
    <section id="work">
        <h2>Work</h2>
       <form action="">
        <label for="">english</label>
        <input type="range" name="" id="" min="0" max="100" value="80" />
        <label for="">francais</label>
        <input type="range" name="" id="" min="0" max="100" value="40" />
       </form>
       

    </section>
    <hr/>
    <section id="resume">
        <h2>Resume</h2>
      
    </section>
    <hr/>
    <section id="contact">
        <h2>Contact</h2>
       
        <form action="your_form_handler.php" method="post">
           
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <input type="submit" value="Submit">
        </form>
    </section>

    <footer>
    
    
 
</body>

</html>



