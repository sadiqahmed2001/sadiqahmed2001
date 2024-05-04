- 👋 Hi, I’m @sadiqahmed2001
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ....
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
sadiqahmed2001/sadiqahmed2001 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sadiq Ahmed - Portfolio</title>
    <style>
        /* Reset default margin and padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            line-height: 1.6;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        h1, h2 {
            margin: 0;
        }

        nav {
            background-color: #444;
            text-align: center;
            padding: 10px 0;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #555;
        }

        section {
            padding: 20px;
            background-color: #fff;
            margin: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            color: #333;
            border-bottom: 1px solid #ccc;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        a {
            color: black;
            text-decoration: none;
        }
        #navbar a {
          color: white;
          text-decoration: none;
          display: 5px;
          padding: none;
          transition: transform 0.3s ease; /* Add animation to navbar links */
        }
        #navbar a:hover {
            text-decoration: underline;
            transform: translate3d(-5px); /* Add hover effect */
        }
        /* Initially hide the contact information */
        #contact {
            display: 5px;
        }
        /* Style for active navbar link */
        #navbar a.active {
            background-color: #555;
        }
        .linkedin_icon{
            height: 20px;
            border-radius: 5px;
        }
        .github_icon{
            height: 20px;
            border-radius: 5px;
        }
        .linktree_icon{
            height: 20px;
            border-radius: 5px;
        }
        .hackerrank_icon{
            height: 20px;
            border-radius: 5px;
        }
        .container {
            display: flex;
            justify-content: space-around;
            margin-top: 50px;
        }
        .box {
            width: 30%;
            background-color: #f0f0f0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .box:hover {
            transform: scale(1.05);
        }

        .box h2 {
            color: #333;
        }

        .box p {
            color: #666;
        }
        /* HTML: <div class="loader"></div> */
        .loader {
            width: 70px;
            height: 50px;
            box-sizing: border-box;
            background:
            conic-gradient(from 135deg at top,#0000, #fff 1deg 90deg,#0000 91deg) right -20px bottom 8px/18px 9px,
            linear-gradient(#fff 0 0) bottom/100% 8px,#000;
            background-repeat: no-repeat;
            border-bottom: 8px solid #000;
            position: relative;
            animation: l7-0 2s infinite linear;
        }
        .loader::before 
        {
            content: "";
            position: absolute;
            width: 10px;
            height: 14px;
            background: lightblue;
            left: 10px;
            animation: l7-1 2s infinite cubic-bezier(0,200,1,200);}
            @keyframes l7-0
            {
                100% { background-position: left -20px bottom 8px,bottom}
            }
            @keyframes l7-1{
                0%,50%   {bottom: 8px}
                90%,100% {bottom: 8.1px}
            }
    </style>
</head>
<body>
    <header>
        <h1>Sadiq Ahmed - Web Developer</h1>
    </header>

    <nav id="navbar">
        <a href="#education">Education</a>
        <a href="#work-experience">Work Experience</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="education">
        <div>
        <h2>Education</h2>
        <p>
            <strong>Bachelor of Engineering (B.E), Mechanical Engineering</strong><br>
            Visvesvaraya Technological University<br>
            2018 - 2022<br>
            CGPA: 8.06/10
        </p>
        <p>
            <strong>Senior Secondary (XII), Science</strong><br>
            DAIMOND PUC SCIENCE COLLAGE BHALKI KARNATAKA INDIA<br>
            Year of completion: 2018<br>
            Percentage: 74.00%
        </p>
        <p>
            <strong>Secondary (X)</strong><br>
            EMBASSY PUBLIC SCHOOL BIDAR KARNATAKA INDIA<br>
            Year of completion: 2016<br>
            Percentage: 76.00%
        </p>
     </div>
    </section>

    <section id="current">
        <h2>Current</h2>
        <p>
           Full Stack Web Development with AWS  <br>
           Itvedant Education Pvt Ltd Pune <br>
        </p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>
                <strong>Mini_Projects_on_C</strong>
                <a href="https://github.com/sadiqahmed2001/Mini_projects_On_C_ProgrammingLanguage">---- view</a>
            </li>
        </ul>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>C -Advanced</li>
            <li>C++ -Advanced</li>
            <li>HTML -Advanced</li>
            <li>CSS -Advanced</li>
            <li>Java Script -intermediate</li>
            <li>SQL - Intermediate</li>
            <li>Python - Advanced</li>
            <li>MS-Excel - Intermediate</li>
            <li>Tableau - Advanced</li>
        </ul>
    </section>

    <section id="work-experience">
        <h2>Work Experience</h2>
        <p>
            <strong>Data Analytics</strong><br>
            Data Lumina, Pimpri-Chinchwad<br>
            Sep 2023 - Nov 2023 (1 month)<br>
            Responsibilities: Converting unstructured data into structured data, working on AI tools, machine learning, etc.
        </p>
    </section>

    <section>
        <h2>Certificates</h2>
        <ul>
            <li>
                <strong>Secondary (X)</strong>
                <a href="https://drive.google.com/file/d/1nVNiqDaQmGSn48Ydujcn9naTz6QNNqbX/view?usp=sharing">--- view</a>
            </li>
            <li>
                <strong>Senior Secondary (XII), Science</strong>
                <a href="https://drive.google.com/file/d/1cukwDoq5r-W6WaLyKvzLNI-VLbFsjcyr/view?usp=sharing">---- view</a>
            </li>
            <li>
                <strong>Degree_Certificate</strong>
                <a href="https://drive.google.com/file/d/1BhoSh6i1_U8EM197zjYreghtK1Y8hfAB/view?usp=sharing">---- view</a> <br>
                <strong>Transcript</strong>
                <a href="https://drive.google.com/file/d/1S3ThEyZv2O_NwON-TakiO1N1Nj1glnSG/view?usp=sharing">----- view</a>
            </li>
            <li>
                <strong>Google Data Analytics</strong>
                <a href="https://drive.google.com/drive/folders/1NocLtvWPuLjWsL2SIAyJb-W5mLcVy94r?usp=sharing">---- view</a>
            </li>


        </ul>
    </section>


    <section id="contact">
        <h2>Contact</h2>
        <p>
            Email: <a href="sadiqahmed05012001@gmail.com">sadiqahmed05012001@gmail.com</a> <br>
            Phone: <a href="tel:+918880136045">+91 8880136045</a> <br>
            Location: Pune, Maharastra
        </p>
    </section>

    <div class="container">
        <div class="box">
            <h2>Main</h2>
            <p><a href="#">Home</a></p>
            <p><div class="loader"></div></p>
        </div>
        <div class="box">
            <h2>Contact Us</h2>
            <p>Phone: 123-456-789<br>
                Email: contact@example.com <br>
                <a href="#">Contact</a></p>
        </div>
        <div class="box">
            <h2>Connect With Me</h2>
            <ul>
                <li>
                    <a href="#"><img src="github.png" alt="Github" class="github_icon"></a>
                    <a href="#">----Github</a>
                </li>
                <li>
                    <a href="https://www.linkedin.com/in/sadiq-ahmed-713a17289/"><img src="linkedin.png" alt="linkedin" class="linkedin_icon"></a>
                    <a href="https://www.linkedin.com/in/sadiq-ahmed-713a17289/">----Linkedin</a>
                </li>
                <li>
                    <a href="https://linktr.ee/SADIQAHMED2001"><img src="linktree.png" alt="linktree" class="linktree_icon"></a>
                    <a href="https://linktr.ee/SADIQAHMED2001">----Linktree</a>
                </li>
                <li>
                    <a href="https://www.hackerrank.com/profile/sadiqahmed050121"><img src="hackerrank.png" alt="hackerrank" class="hackerrank_icon"></a>
                    <a href="https://www.hackerrank.com/profile/sadiqahmed050121">Hackerrank</a>
                </li>
            </ul>
        </div>
    </div>

    <br><br><br><br>
    <br><br><br>

    <footer>
        <p>&copy; 2024 Sadiq Ahmed - Portfolio</p>
    </footer>

    <script>
        // JavaScript functionality to toggle the visibility of contact information
        const contactSection = document.getElementById('contact');
        const contactHeader = contactSection.querySelector('h2');

        contactHeader.addEventListener('click', function() {
            if (contactSection.style.display === 'none') {
                contactSection.style.display = 'block';
            } else {
                contactSection.style.display = 'none';
            }
        });

        // JavaScript functionality to highlight the active section in the navbar
        const sections = document.querySelectorAll('section');
        const navbarLinks = document.querySelectorAll('#navbar a');

        window.addEventListener('scroll', () => {
            let current = '';
            
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                if (pageYOffset >= sectionTop - sectionHeight / 3) {
                    current = section.getAttribute('id');
                }
            });

            navbarLinks.forEach(link => {
                link.classList.remove('active');
                if (link.getAttribute('href').substring(1) === current) {
                    link.classList.add('active');
                }
            });
        });
    </script>
</body>
</html>


