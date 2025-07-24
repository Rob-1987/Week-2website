1. Escaping
What happens when you want to write the words "<h1>" inside your HTML without making a new element? How can this be solved?
Can you write the word "Hello" with this technique?



2. Comments
Google (or use Dash for offline classrooms) HTML comment syntax and add comments on your HTML

<!-- this is my example of an html comment -->


3. Headlines
"h1-h6": find out about different levels of headlines, when and how often to use which.
ANSWER
h1-h6 is diffrent sizing of a headline you can use a headline how ever many times you need to put a heading on your page it really comes down to what sort of page you are createing h1 is the biggest and h6 is the smallest .

4. Tables
HTML has a <table> element. Find out how to use it and make a table that works as a restaurant menu. List 5 dishes, and for every dish make up and list both a normal price, and a discounted price.
ANSWER <!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My 5 Dishes </title></head>
<body>
    <h1>Special</h1>

    <table>
        <tr>
            <th>food item</th>
            <th>description</th>
            <th>price</th>
            <th>Special</th>
        </tr>
        <tr>
            <td>Pizza</td>
            <td>Cheese and tomato pizza with a crispy base</td>
            <td>$12.99</td>
            <td>Buy one get one free on Tuesdays</td>
            <tr>
                <td>burger </td>
                <td>Juicy beef burger with lettuce, tomato, and cheese</td>
                <td>$10.99</td>
                <td>Free fries with every burger on Wednesdays</td>
                <tr>
                    <td>pasta</td>
                    <td>Spaghetti with homemade marinara sauce</td>
                    <td>$9.99</td>
                    <td>20% off on Thursdays</td>
                    <tr>
                        <td>salad</td>
                        <td>Fresh garden salad with a variety of vegetables</td>
                        <td>$7.99</td>
                        <td>Free drink with every salad on Fridays</td>
                        <tr>
                            <td>ice cream</td>
                            <td>Assorted flavors of creamy ice cream</td>
                            <td>$4.99</td>
                            <td>Buy one scoop, get the second half price on weekends</td>
                </tr>
            </tr>
    </table>
    </body>
    
</html>

5. Misc
Browse the MDN docs (or Dash for offline classrooms) and write out one thing we haven't done in class. Prepare to introduce it in a short presentation to your class: talk about what it is, and showing an example both as source code and in the browser.
ANSWER <footer><article>
  <h1>How to be a wizard</h1>
  <ol>
    <li>Grow a long, majestic beard.</li>
    <li>Wear a tall, pointed hat.</li>
    <li>Have I mentioned the beard?</li>
  </ol>
  <footer>
    <p>© 2018 Gandalf</p>
  </footer>
</article>
this is a footer writen in code and it is when you get to the bottom of the page and is normal about telling you that you have reached the bottom of the page most of the time it will have addres on it and company names.The footer element <footer>

The <footer> HTML element represents a footer for its nearest ancestor sectioning content or sectioning root element. A <footer> typically contains information about the author of the section, copyright data or links to related documents.

6. Interactive Website Project
Create a website about your favourite travel destination or shop that demonstrates your understanding of hyperlinks and images.

Requirements:

Use at least three different headlines (<h1>, <h2>, <h3>)
Use at least three paragraph elements (<p>)
Include at least three hyperlinks (<a> tags) that link to:
One external website (e.g., Wikipedia, official tourism site)
One internal anchor link (create a section and link to it)
One email link (mailto:)
Include at least two images with proper alt attributes:
One image from an external URL (e.g., using picsum.photos)
One image that could be local (use a placeholder URL)
Use at least one table to display information (e.g., food nutritional values )
Add at least two HTML comments explaining your code
Use at least one div element to group related content
Example topics:

A shop you like
Your dream holiday destination
A city you'd love to visit
Your favourite type of cuisine
This website can be launched on GitHub Pages (in online classrooms) and should demonstrate proper use of hyperlinks and accessible images.
Answer
<!DOCTYPE html>
<html>
<head>
    <style> 
        body {
            font-family: Arial, sans-serif;
            background-image: url(canada-day-5370634_1280.jpg);
            color: #151313;
            margin: 20px;
        }
        h1 {
            color: #ee0909fd;
        }
        h2 {
            color: #e51010;
        }
        p {
            line-height: 1.6;
        }
        ul, ol {
            margin-left: 20px;
        }
        img {
            margin: 10px;
            border-radius: 8px;
        }
       
    </style>
    <link rel="icon" type="image/jpg" href="flag-canada.jpg">
    <title> Visit Canada</title>
</head>
<body>
    <h1>Visit Canada</h1>
    <p>Canada is a country in North America, known for its stunning natural beauty, multicultural cities, and friendly people. From the majestic Rocky Mountains to the vibrant streets of Toronto and Vancouver, Canada offers a diverse range of experiences for travelers.</p>
    <p>Whether you're interested in exploring national parks, experiencing cultural festivals, or enjoying outdoor activities like skiing and hiking, Canada has something for everyone.</p>
    <h2>Popular Destinations</h2>
    <ul>
        <li>Banff National Park</li>
        <li>Niagara Falls</li>
        <li>Toronto</li>
        <li>Vancouver</li>
        <li>Montreal</li>
    </ul>
    <h2>Activities</h2>
    <p>Visitors can enjoy a variety of activities such as:</p>
    <ol>
        <li>Skiing in Whistler</li>
        <li>Hiking in Jasper National Park</li>
        <li>Exploring the historic sites in Quebec City</li>
        <li>Tasting local cuisine in Toronto's diverse neighborhoods</li>
    </ol>
    <img src="lake-4697441_640.jpg" width="500" height="500" alt="">
    <img src="canoe-7541311_640.jpg" width="250" height="250"  alt="">
    <img src="lake-7541307_640.jpg" width="250" height="250"  alt="">
<p>
    If are looking to see what there is to do in Canada then you can check out the links below and see what you like and if you want to go there or not.
</p>
    <ul>
        <li><a href="https://www.destinationtoronto.com">Toronto</a></li>
        <li><a href="https://www.vancouver.ca">Vancouver</a></li>
        <li><a href="https://en.wikipedia.org/wiki/Rocky_Mountains">Rocky Mountains</a></li>
    <p>book with theses two travel agents and find out more deals  and places to check out while you visit this amazing and beuitful country where there is so much more to see then what you see on screen</p>
        <li><a href="https://www.expedia.com/Canada.d111.Destination-Travel-Guides">Expedia Canada</a></li>
        <li><a href="https://www.destinationtoronto.com">https://www.destinationtoronto.com</a></li>
    </ul>
    <p>Canada is a country that welcomes visitors from around the world, offering a unique blend of natural wonders and urban experiences. Whether you're looking for adventure, culture, or relaxation, Canada has it all.</p>
    <p>So pack your bags and get ready to explore the beauty and diversity of Canada!</p>
    <h2>Feedback</h2>
    <p>We would love to hear your thoughts on this page. Please leave your comments below and contact details so that one of the two travel agents above can contact you</p>
    <form action="https://example.com/submit" method="post">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br>
        <label for="phone">Phone:</label><br>
        <input type="tel" id="phone" name="phone" required><br>
        <label for="comments">Comments:</label><br>
        <textarea id="comments" name="comments" placeholder="please leave your comments here" rows="4" cols="50"></textarea><br>
        <input type="submit" value="Submit">
</body>
</html>