<!DOCTYPE html>
<html>

<head>
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- NAVBAR -->

    <nav>

        <div>
            <div class="profile_name">
                Jane Doe
            </div>

            <div class="contact_info">
                jdoe@jeemail.com
            </div>

            <div class="contact_info">
                +13456764598
            </div>
        </div>

        <div class="topdiv">
            <a class="topmenu" href="#about-me">About Me</a>

            <a class="topmenu" href="#skills">Skills</a>

            <a class="topmenu" href="#projects">Projects</a>

            <a class="topmenu" href="#recommendations">Recommendations</a>
        </div>

    </nav>

    <!-- ABOUT -->

    <section id="about-me" class="container">

        <div>
            <img src="https://cdn-icons-png.flaticon.com/512/6997/6997662.png"
                 class="profile_image" />
        </div>

        <div>

            <h1>
                Hi, I'm Jane Doe!
            </h1>

            <p>
                I am a full stack developer with 2 years of experience in both
                application and presentation layers. I have worked on applications
                and microservices deployed on IBM Cloud.
            </p>

        </div>

    </section>

    <!-- SKILLS -->

    <section id="skills">

        <h2>Skills</h2>

        <div class="all_skills">

            <div class="skill">
                <img src="https://cdn-icons-png.flaticon.com/512/732/732212.png" />

                <h6>HTML</h6>

                <p>2 years experience</p>
            </div>

            <div class="skill">
                <img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" />

                <h6>JavaScript</h6>

                <p>1.5 years experience</p>
            </div>

            <div class="skill">
                <img src="https://cdn-icons-png.flaticon.com/512/226/226777.png" />

                <h6>Java</h6>

                <p>5 years experience</p>
            </div>

            <div class="skill">
                <img src="https://cdn-icons-png.flaticon.com/512/1126/1126012.png" />

                <h6>React</h6>

                <p>1 year experience</p>
            </div>

            <div class="skill">
                <img src="https://cdn-icons-png.flaticon.com/512/919/919825.png" />

                <h6>Node.js</h6>

                <p>1 year experience</p>
            </div>

            <div class="skill">
                <img src="https://cdn-icons-png.flaticon.com/512/732/732190.png" />

                <h6>CSS</h6>

                <p>2 years experience</p>
            </div>

        </div>

    </section>

    <!-- PROJECTS -->

    <section class="projects" id="projects">

        <h2>Projects</h2>

        <div class="project-container">

            <div class="project-card">

                <h3>Chatbot</h3>

                <ul>
                    <li>
                        Developed a secure website integrated with chatbot
                        for an automobile client using HTML, CSS,
                        JavaScript and IBM Watson Assistant
                    </li>
                </ul>

            </div>

            <hr>

            <div class="project-card">

                <h3>Sentiment Analyzer</h3>

                <ul>
                    <li>
                        Developed and deployed a sentiment analyzer
                        for the box reviews section of an eCommerce platform
                        using IBM NLU
                    </li>
                </ul>

            </div>

            <hr>

            <div class="project-card">

                <h3>Fashion Website</h3>

                <ul>
                    <li>
                        Created a styled multi-page website for a new player
                        in the fashion industry and integrated it with
                        a shopping cart using stripe payment gateway
                    </li>
                </ul>

            </div>

        </div>

    </section>

    <!-- RECOMMENDATIONS -->

    <section id="recommendations">

        <h2>Recommendations</h2>

        <div class="all_recommendations" id="all_recommendations">

            <div class="recommendation">
                “ Jane is a very quick learner and quickly grasps key concepts
                of Web development. ”
            </div>

            <div class="recommendation">
                “ Working with Jane has been an awesome experience.
                She is highly knowledgeable. ”
            </div>

            <div class="recommendation">
                “ She is a committed resource and excellent team player. ”
            </div>

        </div>

    </section>

    <!-- CONTACT -->

    <section id="contact">

        <div class="flex_center">

            <fieldset>

                <legend class="introduction">
                    Leave a Recommendation
                </legend>

                <input type="text"
                       placeholder="Name (Optional)">

                <textarea id="new_recommendation"
                          cols="50"
                          rows="10"
                          placeholder="Message"></textarea>

                <div class="flex_center">

                    <button id="recommend_btn"
                            onclick="addRecommendation()">
                        Submit
                    </button>

                </div>

            </fieldset>

        </div>

    </section>

    <!-- POPUP -->

    <div class="popup" id="popup">

        <img src="https://cdn-icons-png.flaticon.com/512/190/190411.png" />

        <h3>
            Thanks for leaving a recommendation!
        </h3>

        <button onclick="showPopup(false)">
            Ok
        </button>

    </div>

    <!-- HOME BUTTON -->

    <div class="iconbutton">

        <a href="#top">
            ⬆
        </a>

    </div>

    <script src="script.js"></script>

</body>

</html>
