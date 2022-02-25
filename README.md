# Portfolio
Personal Portfolio Website
I make navigations and style it with some basic style sheet CSS.

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <section>
       ** <!-- navigation  ------------->**
        <nav>
            <!-- logo -->
            <a href="#" class="logo"> Portfolio</a>
            <!-- menu -->

            <ul>
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
                <li><a href="#">Work</a></li>
            </ul>
        </nav>

        **<!-- text -->**
        <div class="text-container">
            <p>Hello,</p>
            <p>I'M NEHA</p>
            <p>I am student of Web Design <br> & Development</p>
            <button class="hire-btn">Hire Me</button>
            <button class="down-cv">Download CV</button>

        </div>

        <!-- model -->
        <img src="/images/pic.jpeg" class="model" alt="model">
    </section>

    <!-- about-section -->

    <div class="about-container">
        <!-- img -->
        <img src="/images/pic1.jpeg" alt="model">
        <div class="about-text">
            <p>About Me</p>
            <p>Developer & Designer</p>
            <p>Hello, My name is Neha. I am a student of Web Design & Development. If you have any project or you want
                me to design your website So contact me. I will make it as soon as possible. I beleive you'll surely
                like my work and unfortunatly if you don't like it I will try my best to give you satisfaction</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet deleniti suscipit quaerat ipsa amet
                maiores necessitatibus dignissimos, adipisci distinctio iste, repellendus accusantium sapiente, eligendi
                inventore nesciunt deserunt ipsum earum quo?</p>
            <!-- button -->
            <button>Hire Me</button>
            <button>Download CV</button>
        </div>
    </div>

    <!-- services -->
    <div class="services">
        <!-- text -->
        <div class="services-text">
            <p>Services</p>
            <p>Services required</p>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Soluta, quisquam incidunt hic voluptas velit
                quaerat odit cumque corporis, earum natus at illum. Ullam, magni similique neque minus nulla possimus
                distinctio? Lorem ipsum dolor sit amet consectetur adipisicing elit. Iusto minus veritatis, recusandae
                obcaecati enim doloremque neque tempora molestiae dolorum voluptatum maxime! Quis sequi alias
                voluptatibus possimus rerum cumque ea reprehenderit.</p>

        </div>
        **<!-- box -->**
        <div class="box-container">
            <!-- 1 ----------------->
            <div class="box-1">
            <span>1</span>
            <p class="heading"> Web Design</p>
            <p class="details">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam, ad repellat. Expedita
                iste suscipit atque pariatur illo, ad sit corrupti corporis distinctio eum? Iure eligendi, quam eum
                vitae eos repellendus.</p>
            <button>Read More</button>  
            </div>  
            <!-- 2 ----------------->
            <div class="box-2">
                <span>2</span>
                <p class="heading"> Web Development</p>
                <p class="details">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam, ad repellat. Expedita
                    iste suscipit atque pariatur illo, ad sit corrupti corporis distinctio eum? Iure eligendi, quam eum
                    vitae eos repellendus.</p>
                <button>Read More</button> 
            </div>
            <!-- 3 ----------------->
            <div class="box-3">
                <span>3</span>
                <p class="heading"> Website Security</p>
                <p class="details">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam, ad repellat. Expedita
                    iste suscipit amtque pariatur illo, ad sit corrupti corporis distinctio eum? Iure eligendi, quam eum
                    vitae eos repellendus.</p>
                <button>Read More</button> 
            </div>
        </div>
    </div>

   ** <!-- contact me -->**
    <div class="contact-me">
        <p>If you have any project in your mind</p>
        <button>Contact Me</button>
    </div>
</body>

</html>

**<! Styling with CSS..>**
@charset "utf8";

body {
  background-color: #f6f5f5;
  margin: 0px;
  padding: 0px;
}

ul {
  list-style: none;
}

a {
  text-decoration: none;
}

section {
  width: 100%;
  height: 95vh;
  background-image: url();
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 60px;
  background-color: #ffffff;
  box-shadow: 2px 2px 12px rgba(0, 0, 0, 2);
  padding: 0px 5%;
}

nav ul {
  display: flex;
}

nav ul li {
  margin: 30px;
  font-family: Arial, Helvetica, sans-serif;
  color: #505050;
  font-size: 15px;
  font-weight: 700;
}

.logo {
  font-family: "Times New Roman", Times, serif;
  color: #000000;
  font-size: 22px;
}

.active {
  font-weight: bold;
  color: #2d2a2a;
}

.text-container p:nth-child(2) {
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  font-weight: bold;
  letter-spacing: 1px;
  color: #1a1a1a;
  font-size: 55px;
}

.text-container p:nth-child(3) {
  font-family: "Times New Roman", Times, serif;
  color: #403e3e;
  font-size: 25px;
  line-height: 30px;
}

.text-container p {
  line-height: 0px;
  margin: 45px 0px 25px;
}

.text-container {
  position: absolute;
  left: 13%;
  top: 42%;
  transform: translate(-13%, -42%);
}

.text-container button {
  width: 130px;
  height: 42px;
  border-radius: 10px;
  font-family: "Times New Roman", Times, serif;
  font-weight: bold;
  font-size: 14px;
  outline: none;
  margin: 0px 10px;
}

.hire-btn {
  border: 2px solid #373636;
  color: #373636;
}

.down-cv {
  background-color: #0b0b0b;
  color: #ffffff;
  border: none;
}

button:active {
  transform: scale(1.1);
}

.model {
  height: 560px;
  position: absolute;
  bottom: 5px;
  left: 70%;
  transform: translateX(-70%);
}

.about-container {
  width: 80%;
  height: 330px;
  background-color: #ffffff;
  border-radius: 20px;
  box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.2);
  display: flex;
  margin: 7% auto 20px auto;
  position: relative;
  justify-content: space-evenly;
  align-items: center;
}

.about-container img{
    height:250px;
}

.about-text{
    width:550px;
}

.about-text p:nth-child(1){
    color: #403e3e;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: bold;
    font-size: 23px;
    line-height: 0px;
}

.about-text p:nth-child(2){
    color: #3e3d3d;
    font-size: 13px;
    font-family: 'Courier New', Courier, monospace;
    font-weight: bold;
    line-height: 5px;
}

.about-text p:nth-child(3),
.about-text p:nth-child(4){
    color: #7e7d7d;
    font-family: 'Times New Roman', Times, serif;
    font-size: 16px;
}

.about-text button{
    width: 120px;
    height: 40px;
    color: #FFFFFF;
    outline: none;
    border: none;
    font-family: 'Times New Roman', Times, serif;
    background-color: #262525;
}

.services{
    height: 600px;
    background-color: #FFFFFF;
    padding: 2% 10% 0px 10%;
}

.services-text p:nth-child(1){
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    color: #3e3d3d;
    font-size: 30px;
    line-height: 0px;

}

.services-text p:nth-child(2){
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
    color: #3e3e3d;
    font-size: 15px;
    line-height: 5px;
}

.services-text p:nth-child(3){
    font-family: 'Times New Roman', Times, serif;
    color: #7e7d7d;
}

.services-text{
    width: 500px;
    margin: 50px 0px;
}

.box-1,.box-2,.box-3{
    width: 300px;
    height: 320px;
    background-repeat: no-repeat;
    background-size: cover;
    box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.3);
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;

}

.box-container{
    display: flex;
    justify-content: space-between;
}

.box-1{
  background-color: #262525;
}

.box-2{
  background-color: #262525;;
}

.box-3{
  background-color: #262525;;
}

.box-1 span,
.box-2 span,
.box-3 span{
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background-color: #FFFFFF;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;
}

.box-1 p:nth-child(2),
.box-2 p:nth-child(2),
.box-3 p:nth-child(2){
    color: #FFFFFF;
    font-family: 'Times New Roman', Times, serif;
    font-size: 23px;
    line-height: 0px;
}

.box-1 p:nth-child(3),
.box-2 p:nth-child(3),
.box-3 p:nth-child(3){
    font-family: 'Times New Roman', Times, serif;
    text-align: center;
    width: 230px;
    margin: 0px 0px 20px 0px;
    color: #8f8f8f;
}

.box-1 button,
.box-2 button,
.box-3 button{
    width: 100px;
    height: 30px;
    background-color: #FFFFFF;
    border: none;
    outline: none;
    border-radius: 5px;
}

.contact-me{
  width: 100%;
  height: 280px;
  background-image: url();
  background-size: cover;
  background-repeat: no-repeat;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.contact-me{
  color: #262525;;
  font-size: 30px;
  font-family: 'Times New Roman', Times, serif;
  font-weight: bold;
  border-bottom: 2px solid #FFFFFF;
}

.contact-me button{
  width: 200px;
  height: 40px;
  background-color: #FFFFFF;
  outline: none ;
  border: none;
  font-size: 14px;
  font-weight: bold;
}
