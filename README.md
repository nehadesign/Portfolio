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
        <!-- navigation  ------------->
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

        <!-- text -->
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
        <!-- box -->
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
                    iste suscipit atque pariatur illo, ad sit corrupti corporis distinctio eum? Iure eligendi, quam eum
                    vitae eos repellendus.</p>
                <button>Read More</button> 
            </div>
        </div>
    </div>

    <!-- contact me -->
    <div class="contact-me">
        <p>If you have any project in your mind</p>
        <button>Contact Me</button>
    </div>
</body>

</html>
