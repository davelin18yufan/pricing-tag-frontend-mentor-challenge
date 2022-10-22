# pricing-tag-frontend-mentor-challenge
An implementation of frontend mentor code challenge.
<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=:1.0" />
        <meta charset="UFT-8" />
        <title>Frontend Mentor | Single Price Grid Component</title>
        <link rel="stylesheet" type="text/css" href="pricing component.css" />
        <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
        <link rel="preconnect" href="https://fonts.googleapis.com"> 
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
        <link href="https://fonts.googleapis.com/css2?family=Karla&display=swap" rel="stylesheet">
        <style>
            .attribution { font-size: 11px; text-align: center; }
            .attribution a { color: hsl(228, 45%, 44%); }
        </style>
        <script>
            function signup(){
                alert("Hi");
            }
        </script>
    </head>
    <body>
        <div id = "body">
            <div id = "top">
                <h2>Join our community</h2>
                <h3 class = "yellow">30-day,hassle-free money back gurantee</h3>
                <p class ="grey">Gain access to our full library of tutorials along with expert code reviews. Perfect for any developers who are serious about honoring their skills</p>
            </div>
            <div id = "below">
                <div id = "bottom-left">
                    <h3>Monthly Subscription</h3>
                    <span class="dollar">&dollar;29</span><span class = "whyus">per month</span>
                    <p>Full access for less than &dollar;1 a day</p>
                    <button onclick = signup()>Sign Up</button>
                </div>
                <div id = "bottom-right">
                    <h3>Why Us</h3>
                    <div class = "whyus">
                        <p>Tutorials by industry experts</p>
                        <p>Peer & expert code review</p>
                        <p>Coding exercises</p>
                        <p>Access to our GitHub repos</p>
                        <p>Community forum</p>
                        <p>Flashcard decks</p>
                        <p>New videos every week</p>
                    </div>
                    
                </div>
            </div>
            
        </div>
        <footer>
            <p class="attribution">
              Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
              Coded by <a href="#">Dave Lin</a>.
            </p>
        </footer>
    </body>
</html>
