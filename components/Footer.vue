<template>
   <footer id="footer">
        <div class="footer-content">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et labore suscipit nisi non, laudantium delectus?
                <br>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt, molestias!
            </p>
            <div class="socail-links">
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-instagram"></i>
                <i class="fa-brands fa-youtube"></i>
                <i class="fa-brands fa-pinterest-p"></i>
            </div>
        </div>
        <hr>
        <div class="footer-bottom-content">
            <p>Designed By <a href="#">SA Coding</a></p>
            <div class="copyright">
                <p>&copy;Copyright <strong>SA Coding</strong>.All Rights Reserved</p>
            </div>
        </div>
    </footer>
    <!-- Footer End -->
    <a href="#" class="arrow"><i><svg xmlns="http://www.w3.org/2000/svg" width="50px" height="16" fill="currentColor" class="bi bi-arrow-up-circle-fill" viewBox="0 0 16 16">
  <path d="M16 8A8 8 0 1 0 0 8a8 8 0 0 0 16 0m-7.5 3.5a.5.5 0 0 1-1 0V5.707L5.354 7.854a.5.5 0 1 1-.708-.708l3-3a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708L8.5 5.707z"/>
</svg></i></a>
</template>
<style scoped>
  #footer{
    width: 100%;
    background: #f3f3f3;
}
.footer-content{
    text-align: center;
    padding-top: 5%;
}
.footer-content .logo img{
    width: 250px;
}
.footer-content p{
    font-weight: 550;
    letter-spacing: 1px;
}
.socail-links i{
    margin-top: 20px;
    padding: 10px;
    border-radius: 5px;
    font-size: 20px;
    background: black;
    color: white;
    margin-left: 10px;
    margin-bottom: 10px;
    transition: 0.5s ease;
    cursor: pointer;
}
.socail-links i:hover{
    background: #388b6f;
}
.footer-bottom-content{
    text-align: center;
    margin-top: 10px;
}
.footer-bottom-content p{
    font-size: 17px;
    font-weight: 550;
}
.footer-bottom-content p a{
    color: #388b6f;
    font-weight: 600;
}
/* Footer End */
html{
    scroll-behavior: smooth;
}
.arrow{
    position: fixed;
    background-color: #388b6f;
    border-radius: 50px;
    height: 50px;
    bottom: 40px;
    right: 50px;
    text-decoration: none;
    text-align: center;
    line-height: 50px;
}
</style>