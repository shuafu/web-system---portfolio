<template>
    <div class="wrapper">
        <div class="main-container">
            <div class="container-one">
                <div class="profile">
                    <img src="../assets/profilepic.jpg" alt="">
                    <h3 style="color: #64ffda;">Joshua Pino</h3>
                    <p style="color: #64ffda;">Professional Software Developer</p>
                </div>
                <div class="social-link">
                    <div class="link">
                        <a href="https://github.com/shuafu" target="blank">
                            <img src="../assets/github.jpg" alt="">
                            <h2 style="color: #64ffda;">Github Repository</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.facebook.com/shuapoo/" target="blank"> 
                            <img src="../assets/facebook.jpg" alt="">
                            <h2 style="color: #64ffda;">Facebook</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.instagram.com/shua.po/?hl=en" target="blank">
                            <img src="../assets/instagram.png" alt="">
                            <h2 style="color: #64ffda;">Instagram</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://twitter.com/shua_po" target="blank">
                            <img src="../assets/x.png" alt="">
                            <h2 style="color: #64ffda;">𝕏</h2>
                        </a>
                    </div>
                </div>
            </div>
            <div class="container-two">
                <div class="about me ">
                    <h1 style="color: #64ffda;">About Me</h1>
                    <p style="color: #64ffda;">Hey there! I'm Joshua Pino, a motivated and dynamic individual with a burning passion for IT. At just 22 years old, I've already honed my skills in HTML, CSS, JavaScript, Vue.js, and Node.js, making me a versatile asset in the world of web development. My journey into IT began with a curiosity about how websites work, and since then, I've immersed myself in learning and mastering various programming languages and frameworks. Beyond my technical skills, I bring a strong work ethic, excellent communication skills, and a collaborative spirit to any team. I thrive in environments where ideas are freely exchanged, feedback is welcomed, and innovation is encouraged. I'm not just looking for a job; I'm seeking opportunities to contribute my expertise, grow professionally, and make a meaningful impact in the world of IT. Beyond my technical skills, I bring a strong work ethic, excellent communication skills, and a collaborative spirit to any team. I thrive in environments where ideas are freely exchanged, feedback is welcomed, and innovation is encouraged. I'm not just looking for a job; I'm seeking opportunities to contribute my expertise, grow professionally, and make a meaningful impact in the world of IT.
                    </p>
                    <div class="Language-Section">
                        <h2 style="color: #64ffda;">Coding Languages Trained</h2>
                        <div class="logos">
                            <img src="../assets/html-5-plex-adobe-flash-csssprites-css3-cascading-style-sheets-javascript-mobile-app-development-web-application-html.png" alt="">
                            <img src="../assets/java-logo-7833D1D21A-seeklogo.com.png" alt="">
                            <img src="../assets/Vue.png" alt="">
                            <img src="../assets/5968322.png" alt="">
                            <img src="../assets/985px-Laravel.svg.png" alt="">
                            <img src="../assets/appledev.png" alt="">
                            <img src="../assets/androiddev.png" alt="">
                            <img src="../assets/php.png" alt="">
                            <div class="button-container">
                                <div class="project-button">
                                    <a href="" style="color: #64ffda;">Mobile: 09876543210</a>
                                </div>
                                <div class="project-button">
                                    <a href="" style="color: #64ffda;">Landline: 032 123 4567</a>
                                </div>
                                <div class="project-button">
                                    <a href="" style="color: #64ffda;">Email: joshua.haha@icloud.com</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>


<style scoped>
@font-face {
    font-family: 'Product Sans';
    src: url('../fonts/ProductSans-Regular.ttf') format('truetype'),

}
body {
    background-color: #0a192f !important;
}

.wrapper {
    display: flex;
    justify-content: center;
}

img {
    height: 40px;
}

.container-one {
    background-color: rgb(23, 42, 70);
    width: 99%; /* Take full width */
    padding: 10px; /* Add padding */
    border-radius: 35px;
    margin-bottom: 20px; /* Add margin-bottom for spacing */
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.profile img {
    height: 80px; /* Adjust height for profile image */
    border-radius: 50%; /* Make the profile image circular */
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.link a {
    text-decoration: none;
    color: #d20e56;
    font-size: 14px; /* Increase font size for links */
    margin-bottom: 10px; /* Add margin bottom for spacing */
    display: block; /* Display links as block elements */
    
}

.link img {
    height: 50px; /* Adjust height for social media icons */
}

.container-two {
    background-color: rgb(23, 42, 70);
    margin: 0; /* Remove default margin */
    padding: 5px; 
    border-radius: 30px;
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.about-me {
    text-align: center; /* Center align the text */
    margin-bottom: 20px; /* Add margin bottom for spacing */
}

.logos img {
    height: 50px; /* Adjust height for language logos */
    margin-right: 10px; /* Add margin-right for spacing between logos */
    border-radius: 10%; /* Make the logos circular */
}

.button-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center; 
}

.project-button {
    background-color: #d20e56;
    border-radius: 10px;
    padding: 10px 20px; 
    margin: 50px; 
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.project-button a {
    text-decoration: none;
    color: #000407;
    font-size: 20x;
}

@media only screen and (min-width: 880px) {
    .main-container {
        width: 80%; 
    }
}
</style>
