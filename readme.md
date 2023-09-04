#hotel Project

this project is created to help user to find a best hotel.
developed by using html css and javascript

html code:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotels.com</title>
    <link rel="stylesheet" href="./style.css">
    <script src="https://kit.fontawesome.com/7b74057654.js" crossorigin="anonymous"></script>
</head>
<body>
    <nav class="navbar">
        <div class="logo">
            <div>
            <h1>Hotels.com</h1>
            </div>
            <div class="more-travel">
                <a href="">More Travel<i class="fa-solid fa-angle-down"></i></a>
            </div>
            </div>
            <div class="menu">
                <a href=""><i class="fa-solid fa-earth-americas"></i> English</a>
                <a href="">List your property</a>
                <a href="">Support</a>
                <a href="">Trips</a>
                <a href="">Sign in</a></li>
            </div>
        
    </nav>
    <div class="container">
        <div class="top-section">
                <div>
                    <input type="text" class="inputbox" placeholder="  going to">
                    <input type="date" class="inputbox">
                </div>
                <div>
                    <i class="fa-solid fa-magnifying-glass icon"></i>
                </div>
            </div>
            <div class="middle-section">
                <div class="line">
                    <hr>
                </div>
                <div style="margin-left: -25%;">
                    <p>905 properties</p>
                    <p>What are paid impacts our sort order</p>
                </div>
                <div class="select-box">
                    <select name="" id="" style="height: 40px;width: 250px;">
                        <option value=""><p><sup>Sort by</sup>Recommended</p></option>
                    </select>
                </div>
            </div>
        
            <div class="main-container">
                <div class="left-side">
                    <h2 class="heading">Search by property name</h2>
                    <input type="search" style="width: 250px; height: 40px;">
                    <hr class="hrr">
                    <h2 class="subheading">Filter by</h2>
                    <form action="/action_page.php">
                        <p class="ratings"><b>Guest rating</b></p>
                       <input type="radio" id="any" name="rating" value="any">
                       <label for="any">Any</label><br><br>
                       <input type="radio" id="wonderful" name="rating" value="wonderful">
                       <label for="wonderful">Wonderful 9+</label><br><br>
                       <input type="radio" id="verygood" name="rating" value="verygood">
                       <label for="verygood">Very good 8+</label><br><br>
                       <input type="radio" id="good" name="rating" value="good">
                       <label for="good">Good 7+</label>
                      
                       <h3 class="prop">Property class</h3>
                       <button type="button">1<i class="fa-solid fa-star star"></i></button>
                       <button type="button">2<i class="fa-solid fa-star star"></i></button>
                       <button type="button">3<i class="fa-solid fa-star star"></i></button>
                       <button type="button">4<i class="fa-solid fa-star star"></i></button>
                       <button type="button">5<i class="fa-solid fa-star star"></i></button>
                   
                </div>
                <div class="right-side">
                    <div class="card">
                        <div class="img">
                            <img src="./29bfb31ee26811e4be23001ec9b85d13.jfif" alt="" style="height: 200px; width: 200px;">
                        </div>
                        <div class="img-desc">
                            <h3>Holiday Inn New Delhi International Airport, an IHG Hotel</h3>
                            <p>Areocity</p>
                            <p>Pool  WiFi included  Air conditioned</p><br>
                            <p><b>Stay with Confident at IHG Hotels</b></p>
                            <p> now and take advantage of flexible booking options and IHG clean Promise. For wherever you go. For however you stay.</p>
                        </div>
                    </div><br>
                    <div class="card">
                        <div class="img">
                            <img src="./holiday-inn-new-delhi-3492356108-4x3.jpeg" alt="" style="height: 200px; width: 200px;">
                        </div>
                        <div class="img-desc">
                            <h3>Holiday Inn New Delhi International Airport, an IHG Hotel</h3>
                            <p>Areocity</p>
                            <p>Pool  WiFi included  Air conditioned</p><br>
                            <p><b>Stay with Confident at IHG Hotels</b></p>
                            <p> now and take advantage of flexible booking options and IHG clean Promise. For wherever you go. For however you stay.</p>
                        </div>
                    </div>
                    
                </div>
                
            </div>
    </div>
</body>
</html>