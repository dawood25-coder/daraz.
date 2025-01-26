<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daraz Clone</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <header>
        <div class="header-web">
            
            <!-- Top NavBar -->
            <div class="nav-top-info">
                <div class="nav-top-links">
                    <a href="#" class="nav-link">Become A Seller</a>
                    <div class="link">
                        <a href="#" class="nav-link">Daraz Affiliate Program</a>
                    </div>

                    <!-- NavLink Dropdown -->
                    <div class="link" id="help-nav-link">
                        <a href="#" class="nav-link">Help & Support</a>
                        <div id="nav-help-dropdown">
                            <div id="nav-triangle"></div>
                            <div class="help-container">
                                <div class="nav-list-ele">
                                    <i class="fa-solid fa-headset"></i>
                                    <a>Help Center</a>
                                </div>
                                <div class="nav-list-ele">
                                    <i class="fa-brands fa-rocketchat"></i>
                                    <a>Chat with Us</a>
                                </div>
                                <div class="nav-list-ele">
                                    <i class="fa-solid fa-cube"></i>
                                    <a>Order</a>
                                </div>
                                <div class="nav-list-ele">
                                    <i class="fa-solid fa-truck-fast"></i>
                                    <a>Shipping & Delivery</a>
                                </div>
                                <div class="nav-list-ele">
                                    <i class="fa-solid fa-money-bill"></i>.
                                    <a>Payment</a>
                                </div>
                                <div class="nav-list-ele">
                                    <i class="fa-solid fa-money-check-dollar"></i>
                                    <a>Returns & Refunds</a>
                                </div>
                                <div class="nav-list-ele">
                                    <i class="fa-solid fa-shield-heart"></i>
                                    <a>Purchase Protection</a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <a href="#" class="nav-link">Daraz Logistics Partner</a>
                </div>
            </div>

            <!-- NavBar Rest Elements -->
            <div class="outer-nav-bottom-info">
                <div class="inner-nav-bottom-info">
                    <div class="nav-logo">
                        <div class="daraz-logo"></div>
                    </div>
                    <div class="search-bar">
                        <input placeholder="Search in Daraz" class="search">
                        <div class="search-icon">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </div>
                    </div>
                    <div class="user-login select-ele">
                        <i class="fa-solid fa-user"></i>
                        <span class="ele-text">Login</span>
                    </div>
                    <div class="nav-hr">
                        <span class="ele-text">|</span>
                    </div>
                    <div class="sign-up select-ele">
                        <span class="ele-text">Sign Up</span>
                    </div>
                    <div class="lang-select select-ele">
                        <i class="fa-solid fa-globe"></i>
                        <span class="lang-select-text">EN</span>
                    </div>
                    <div class="cart select-ele">
                        <i class="fa-solid fa-cart-shopping"></i>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <main>

        <!-- Main Hero Section -->
        <div class="hero-section">

            <!-- Image Slider -->
            <div id="slider">
                <figure>
                    <img src="images/Hero Main/hero-section.jpg">
                    <img src="images/Hero Main/hero-section2.jpg">
                    <img src="images/Hero Main/hero-section3.jpg">
                    <img src="images/Hero Main/hero-section4.jpg">
                    <img src="images/Hero Main/hero-section.jpg">
                </figure>
            </div>

            <!-- Hero Tag -->
            <div class="hero-tag">
                <div class="hero-tag-ele">
                    <img src="images/Hero Element/Safe Payments.png">
                    <span>Payments</span>
                </div>
                <div class="main-hr">|</div>
                <div class="hero-tag-ele">
                    <img src="images/Hero Element/NationWide Delivery.png">
                    <span>Nationwide Delivery</span>
                </div>
                <div class="main-hr">|</div>
                <div class="hero-tag-ele">
                    <img src="images/Hero Element/Free & Easy Returns.png">
                    <span>Free & Easy Returns</span>
                </div>
                <div class="main-hr">|</div>
                <div class="hero-tag-ele">
                    <img src="images/Hero Element/Best Price Guaranteed.png">
                    <span>Best Price Guaranteed</span>
                </div>
                <div class="main-hr">|</div>
                <div class="hero-tag-ele">
                    <img src="images/Hero Element/Authentic Products.png">
                    <span>100% Authentic Products</span>
                </div>
                <div class="main-hr">|</div>
                <div class="hero-tag-ele">
                    <img src="images/Hero Element/Daraz Verified.png">
                    <span>Daraz Verified</span>
                </div>
            </div>
        </div>

        <!-- Category Section -->
        <div class="all-categories">
            <div class="main-text"><h2>Popular Categories</h2></div>
            <div class="category-first-section">
                <div class="categories item">
                    <div class="category-img" id="category-wardrobe"></div>
                    <span class="category-text">Wardrobe Organizers</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-moisturizers"></div>
                    <span class="category-text">Moisturizers</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-shampoo"></div>
                    <span class="category-text">Shampoo</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-kitchen-tools"></div>
                    <span class="category-text">Kitchen Tools</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-art-easels"></div>
                    <span class="category-text">Art Easels</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-smart-watches"></div>
                    <span class="category-text">Smart Watches</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-tshirts"></div>
                    <span class="category-text">T-Shirts</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-fashion"></div>
                    <span class="category-text">Fashion</span>
                </div>
            </div>
            <div class="category-second-section">
                <div class="categories item">
                    <div class="category-img" id="category-business"></div>
                    <span class="category-text">Business</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-suits"></div>
                    <span class="category-text">Suits</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-space-savers"></div>
                    <span class="category-text">Space Savers</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-headphones"></div>
                    <span class="category-text">Studio Headphones</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-wallpaper"></div>
                    <span class="category-text">Wallpaper</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-bottles"></div>
                    <span class="category-text">Bottles and Containers</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-clips"></div>
                    <span class="category-text">Clips, Pins & Tacks</span>
                </div>
                <div class="categories item">
                    <div class="category-img" id="category-dispenser"></div>
                    <span class="category-text">Water Dispensers</span>
                </div>
            </div>
        </div>

        <!-- For You Section -->
        <div class="for-you">
            <div class="main-text"><h2>Just for You</h2></div>
            <div class="cards-row">
                <div class="item-card item">
                    <img src="images/Just for You/Hexagon Wall Shelf.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">Lifestyle Glory Brand Hexagon Wall Shelf</p>
                        <p class="price-tag">Rs.1,500</p>
                        <span class="discount" id="discounted-price">Rs.3,000</span>
                        <span class="discount" id=discount-percent>-50%</span>
                    </div>
                </div>
                <div class="item-card item">
                    <img src="images/Just for You/Mini Bicycle.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">Mini 1:8 Model Alloy Bicycle Toy Diecast Metal Finger Mountain Bike Racing Bend Road Simulation Collection Toys for Kids Gift</p>
                        <p class="price-tag">Rs.2,298</p>
                        <span class="discount" id="discounted-price">Rs.5,750</span>
                        <span class="discount" id=discount-percent>-60%</span>
                    </div>
                </div>
                <div class="item-card item">
                    <img src="images/Just for You/Royal Watch_.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">Stainless Steel Strap For Samsung Galaxy Watch 6 5 4 44mm 40mm 5 Pro 4 Classic 20mm 22mm Bracelet Huawei GT 2 3 4 Pro 46mm Band</p>
                        <p class="price-tag">Rs.1,182</p>
                        <span class="discount" id="discounted-price">Rs.3,000</span>
                        <span class="discount" id=discount-percent>-62%</span>
                    </div>
                </div>
                <div class="item-card item">
                    <img src="images/Just for You/Fan Air Conditioner.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">Portable Fan Air Conditioners USB Electric Fan LED Night Light Water Mist Fun 3 In 1 Air Humidifie For Home</p>
                        <p class="price-tag">Rs.1,554</p>
                        <span class="discount" id="discounted-price">Rs.3,978</span>
                        <span class="discount" id=discount-percent>-61%</span>
                    </div>
                </div>
                <div class="item-card item">
                    <img src="images/Just for You/Stereo Headphones.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">P47 Wireless Headset Bluetooth Foldable Headphone (Connect with All Smart Cell Phones / Laptops / Computer Systems).</p>
                        <p class="price-tag">Rs.759</p>
                        <span class="discount" id="discounted-price">Rs.3,600</span>
                        <span class="discount" id=discount-percent>-79%</span>
                    </div>
                </div>
                <div class="item-card item">
                    <img src="images/Just for You/Small Speakers.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">M3 Mini Portable Wireless Blutooth And Rechargeable Speaker With High Quality Sound</p>
                        <p class="price-tag">Rs.529</p>
                        <span class="discount" id="discounted-price">Rs.999</span>
                        <span class="discount" id=discount-percent>-47%</span>
                    </div>
                </div>
            </div>
            <div class="cards-row">
                <div class="item-card item">
                    <img src="images/Just for You/Facial Hair Remover.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">Original Rechargeable Flawless Facial Hair Remover Machine For Womens High Quality Pocket Sized Painless Face Hair Removing Women Flawless Trimmer Razor Finishing Touch Epilator Trimmer for Women Upper Lips Flawless hair Removal Lipstick Shape</p>
                        <p class="price-tag">Rs.665</p>
                        <span class="discount" id="discounted-price">Rs.1,600</span>
                        <span class="discount" id=discount-percent>-58%</span>
                    </div>
                </div>
                <div class="item-card item">
                    <img src="images/Just for You/TrackSuit.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">TRACKSUIT - Yellow & Black Summer Printed Tracksuit For Mens & Boys - Soft and Comfortable Fabric Round Neck T Shirt For Mens and Terry Trouser For Mens Summer Printed Tracksuit</p>
                        <p class="price-tag">Rs.899</p>
                        <span class="discount" id="discounted-price">Rs.1,500</span>
                        <span class="discount" id=discount-percent>-40%</span>
                    </div>
                </div>
                <div class="item-card item">
                    <img src="images/Just for You/Hair Fiber.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">Toppik Hair Fiber 27.5g BLACK</p>
                        <p class="price-tag">Rs.699</p>
                        <span class="discount" id="discounted-price">Rs.899</span>
                        <span class="discount" id=discount-percent>-22%</span>
                    </div>
                </div>
                <div class="item-card item">
                    <img src="images/Just for You/Tripod.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">Original Wireless Selfie Stick / Tripod R1S (WITH LIGHT) R1 (WITHOUT LIGHT) 70CM / 2.29 FEET Tripod Bluetooth Shutter selfie Light foldable Selfie stick for all Phone Extendable Foldable With charging Cable Detachable Bluetooth Shutter</p>
                        <p class="price-tag">Rs.899</p>
                        <span class="discount" id="discounted-price">Rs.1,200</span>
                        <span class="discount" id=discount-percent>-25%</span>
                    </div>
                </div>
                <div class="item-card item">
                    <img src="images/Just for You/IPhone Cover.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">Official Original Phone Casing Tecno Spark 20 Pro Plus Case Shockproof Phone Liquid Silicone Soft Cover</p>
                        <p class="price-tag">Rs.496</p>
                        <span class="discount" id="discounted-price">Rs.1,299</span>
                        <span class="discount" id=discount-percent>-62%</span>
                    </div>
                </div>
                <div class="item-card item">
                    <img src="images/Just for You/Water Bottles.webp" width=190>
                    <div class="card-desc">
                        <p class="product-name">2 Liters Straw Plastic Water Bottle Large Portable Travel Bottle Sports Fitness Cup High Value Big Fat Cup Adult Universal</p>
                        <p class="price-tag">Rs.1,728</p>
                        <span class="discount" id="discounted-price">Rs.4,378</span>
                        <span class="discount" id=discount-percent>-61%</span>
                    </div>
                </div>
            </div>
        </div>
    </main>
    <footer>

        <!-- Footer -->
        <div class="mainfooter">
            <div class="footpanel">
                <!-- Footer Panel 1 -->
                <div class="foot-section1">
                    <h4>Customer Care</h4>
                    <a>Help Center</a>
                    <a>How to Buy</a>
                    <a>Corporate & Bulk Purchasing</a>
                    <a>Returns & Refunds</a>
                    <a>Daraz Shop</a>
                    <a>Contact Us</a>
                    <a>Purchase Protection</a>
                    <a>Daraz Pick up Points</a>
                    <h4>Make Money With Us</h4>
                    <a>Daraz University</a>
                    <a>Sell on Daraz</a>
                    <a>Join Daraz Affiliate Program</a>
                </div>
                <!-- Footer Panel 2 -->
                <div class="foot-section2">
                    <h4>Daraz</h4>
                    <a>About Us</a>
                    <a>Digital Payments</a>
                    <a>Daraz Donates</a>
                    <a>Daraz Blog</a>
                    <a>Terms & Conditions</a>
                    <a>Privacy Policy</a>
                    <a>NTN Number : 4012118-6</a>
                    <a>STRN Number : 1700401211818</a>
                    <a>Online Shopping App</a>
                    <a>Online Grocery Shopping</a>
                    <a>Daraz Exclusive</a>
                </div>
                <!-- Footer Panel 3 -->
                <div class="foot-section3">
                    <div class="footarea1-s3">
                        <h4>Daraz International</h4>
                        <div class="countries-footer">
                            <div class="country-section">
                                <div class="country-image" id="pakistan"></div>
                                <a>Pakistan</a>
                            </div>
                            <div class="country-section">
                                <div class="country-image" id="bangladesh"></div>
                                <a>Bangladesh</a>
                            </div>
                            <div class="country-section">
                                <div class="country-image" id="sri-lanka"></div>
                                <a>Sri Lanka</a>
                            </div>
                            <div class="country-section">
                                <div class="country-image" id="myanmar"></div>
                                <a>Myanmar</a>
                            </div>
                            <div class="country-section">
                                <div class="country-image" id="nepal"></div>
                                <a>Nepal</a>
                            </div>
                        </div>
                    </div>
                   
                    <div class="footarea3-s3">
                        <h4>Verified by</h4>
                        <img src="images/Footer/Payment Methods/Verified by.png" width="100">
                    </div>
                </div>
                <!-- Footer Panel 4 -->
                <div class="foot-section4">
                    <div class="exclusive-deals">
                        <h4>Exclusive Deals and Offers!</h4>
                        <img src="images/Footer/QR Code.png" width="220">
                        <img src="images/Footer/Daraz-Happy-Shopping.png" id="daraz-shopping" width="220">
                    </div>
                    <div class="follow-panel">
                        <h4>Follow Us</h4>
                        <img src="images/Footer/Socials/footer-socials.png" width="220">
                    </div>
                </div>
            </div>
        </div>
    </footer>
</body>
</html>
