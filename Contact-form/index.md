<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TSCL - Contact Us</title>
</head>

<body>
    <main>
        <!-- Column Header Labels -->
        <div>
            <div>Contact Info Section</div>
            <div>Contact Form</div>
        </div>
    
        <!-- Glassmorphism Cards Container -->
        <div>
    
            <!-- Left Card: Contact Information -->
            <div>
                <div></div>
                <div>
                    <h1>Get in Touch</h1>
                    <p>
                        We're here to discuss your project and bring your ideas for life with premium design &amp; development.
                    </p>
                </div>
    
                <div>
                    <a href="mailto:hello@pixeldrift.io">
                        <span><i></i></span>
                        <span>ferdinandetchu@gmail.com</span>
                    </a>
    
                    <a href="#location">
                        <span><i></i></span>
                        <span>Molyko, Buea, Cameroon</span>
                    </a>
    
                    <a href="tel:+491529988411">
                        <span><i></i></span>
                        <span>+237 671 097 299</span>
                    </a>
                </div>
            </div>
    
            <!-- Right Card: Contact Form -->
            <div>
                <div></div>
                <form id="contactForm" autocomplete="off" novalidate>
                    <div>
                        <input type="text" id="name" placeholder="Your Name*" />
                        <div id="nameError">
                            <i></i>
                            <span>Please enter your name (at least 2 characters).</span>
                        </div>
                    </div>
    
                    <div>
                        <input type="email" id="email" placeholder="Email Address*" />
                        <i></i>
                        <div id="emailError">
                            <i></i>
                            <span>Please enter a valid email address.</span>
                        </div>
                    </div>
    
                    <div>
                        <input type="url" id="website" placeholder="Your Website (Optional)" />
                        <div id="websiteError">
                            <i></i>
                            <span>Please enter a valid website URL (e.g. https://example.com).</span>
                        </div>
                    </div>
    
                    <div>
                        <textarea id="message" placeholder="Write your message..."></textarea>
                        <div id="messageError">
                            <i></i>
                            <span>Your message must be at least 10 characters long.</span>
                        </div>
                    </div>
    
                    <button type="submit" id="submitBtn">
                        <span>Send Message</span>
                    </button>
                </form>
            </div>
    
        </div>
    </main>
    
    <!-- Footer Section -->
    <footer>
        <div></div>
        <div>
    
            <!-- Brand Column -->
            <div>
                <h3>TSCL</h3>
                <div>
                    ferdinandetchu@gmail.com<br>
                    +237 671 097 299
                </div>
                <div>
                    <a href="#" aria-label="Instagram"><i></i></a>
                    <a href="#" aria-label="LinkedIn"><i></i></a>
                    <a href="#" aria-label="Behance"><i></i></a>
                    <a href="#" aria-label="Facebook"><i></i></a>
                    <a href="#" aria-label="Twitter"><i></i></a>
                </div>
            </div>
    
            <!-- Blog Column -->
            <div>
                <h4>Blog</h4>
                <p>
                    Eessr yount edrest<br>parilhactoye einem
                </p>
            </div>
    
            <!-- About Column -->
            <div>
                <h4>About</h4>
                <p>
                    Sepprefiot adrest<br>tarre rond itergro to<br>biusterne a atah
                </p>
            </div>
    
            <!-- Product Column -->
            <div>
                <h4>Product</h4>
                <p>
                    Wegaintonte fedign.<br>youlet or domindiaing<br>pniater
                </p>
            </div>
    
            <!-- Download App Column -->
            <div>
                <h4>Download App</h4>
                <p>
                    Keposiitinaa tone your<br>compope damaslber
                </p>
            </div>
    
        </div>
    </footer>
    
    <!-- Success Toast Notification -->
    <div id="toast">
        <i></i>
        <span>Thank you! Your message has been sent successfully.</span>
    </div>

</body>

</html>
