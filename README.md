# web-app-front-end1 
Front end for a web app school project, I used html and css
<!DOCTYPE html>
<html>
    <head>
        <title>
            UA Clozit
        </title>
        <style>
            body{
                background-color: black;
            }
            .header {
                display: flex;         
                align-items: center;          
                justify-content: space-between;                 
                padding: 1rem;             
                background-color: black;                                               
                border-bottom: 1px solid rgb(0, 0, 0);
            }
            .logo {
                margin-right: 20px;
            }
            .logo img {
                width: 150px;
                height: 100px;
                object-fit: cover;
            }
            .search-bar {
                display: flex;
                align-items: center;
            }
            .search-bar input {
                padding: 0.5rem;
                border: 1px solid darkgray;
                border-radius: 0.25rem;
                width: 20rem;
            }

            .search-bar button {
                padding: 0.5rem 1rem;
                border: none;
                border-radius: 0.25rem;
                background-color: #4CAF50;
                color: #fff;
                cursor: pointer;
            }

            .search-bar button:hover {
                background-color: #3e8e41;
            }
            .categories-btn input[type="button"] {
                background-color: #4CAF50; /* green background color */
                color: #fff; /* white text color */
                padding: 10px 20px; /* add some padding */
                border: none; /* remove the default border */
                border-radius: 5px; /* add a rounded corner effect */
                cursor: pointer; /* change the cursor to a pointing hand */
            }
            .categories-btn input[type="button"]:hover {
                background-color: #3e8e41; /* darker green background color on hover */
            }
            .header2{
                color: #3e8e41;
                font-style: normal;
            }
            /*text on the picture */
            .image-container1 {
                position: relative;
            }
            .text-overlay {
                position: absolute;
                top: 0;
                right: 0;
                color: rgb(15, 173, 15); 
                padding: 10px;
            }
            /* round images */
            .round-image {
                border-radius: 50%;
                width: 170px; /* Adjust the width */
                height: 200px; /* Adjust the height */
                border: 5px solid white; /* Add a white border */
                box-shadow: 0 0 10px rgba(0, 0, 0, 0.2); /* Add a shadow */
            }
            .round-image {
                border-radius: 100%;
                margin: 30px; /* add a 10px margin around each image */
            }
            .image-container2 {
                display: inline-block;
                margin: 10px;
                text-align: center;
            }
            .image-container img {
                width: 100px;
                height: 100px;
                border-radius: 50%;
            }
            .image-container2 p {
                color: wheat; /* Add this line */
            }
            .link-categories {
                display: flex;
                justify-content: space-around;
            }
            .category {
                margin: 20px;
            }
            .category h2 {
                color: white;
                margin-bottom: 10px;
            }
            .category ul {
                list-style: none;
                padding: 0;
            }
            .category li {
                margin-bottom: 10px;
            }
            .category a {
                text-decoration: none;
                color: white;
            }
            .image-container2 a{
                text-decoration: none;
                color: white;
            }
        </style>
    </head>
    <body>
        <!--iframe src="file:///D:/Html/app2.html" frameborder="1" width="800" height="500"></iframe-->
        <div class="header">
            <div class="logo">
              <img src="logo.png" alt="Logo">
            </div>
            <div class="search-bar">
              <input type="text" placeholder="Search...">
              <button>Search</button>
            </div>
            <div class="categories-btn">
                <input type="button" value="categories">
            </div>
          </div>
    </body>
    <body>
        <div class="main-content">
            <div class="image-container1">
                <img src="success2.png" alt="Hero" width="100%" height="300">
                <div class="text-overlay">
                    <h2>"Wear kindness, wear sustainability"</h2>
                </div>
              </div>
        <div class="header2">
            <h1>Explore more options</h1>
        </div>
        <div class="image-container2">
            <img src="t-shirt.jpeg" alt="T-shirt" class="round-image">
            <ul>
                <li><a href="#">T-shirt</a></li>
            </ul>   
        </div>
        <div class="image-container2">
            <img src="trouser.jpeg" alt="Trouser" class="round-image">
            <ul>
                <li><a href="#">Trouser</a></li>
            </ul> 
        </div>
        <div class="image-container2">
            <img src="dress.jpeg" alt="Dress" class="round-image">
            <ul>
                <li><a href="#">Dress</a></li>
            </ul> 
        </div>
        <div class="image-container2">
            <img src="brouse.jpeg" alt="Blouse" class="round-image">
            <ul>
                <li><a href="#">Blouse</a></li>
            </ul> 
        </div>
        <div class="image-container2">
            <img src="shoes.jpeg" alt="shoes" class="round-image">
            <ul>
                <li><a href="#">Shoes</a></li>
            </ul> 
        </div>
        <div class="link-categories">
            <div class="category">
              <h2>Buy</h2>
              <ul>
                <li><a href="file:///D:/Html/Login.html?#">Registration</a></li>
                <li><a href="#">Company Info</a></li>
              </ul>
            </div>
            <div class="category">
              <h2>About UA Clozit</h2>
              <ul>
                <li><a href="#">Company info</a></li>
                <li><a href="#">News</a></li>
                <li><a href="#">Investors</a></li>
                <li><a href="#">Policies</a></li>
                <li><a href="#">Blog</a></li>
              </ul>
            </div>
            <div class="category">
              <h2>Help and Contact</h2>
              <ul>
                <li><a href="#">Seller information</a></li>
                <li><a href="#">Contact info</a></li>
              </ul>
            </div>
          </div>
    </body>
</html>
