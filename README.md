<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cimage</title>
    <link rel="stylesheet" href="home.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<style>
  * {
        margin: 0;
        padding: 0;
        
    }
    /* Upper header icon and contacts  */

    .icon a:hover{
        background-color: rgb(11, 11, 11);
    }
    a{
        text-decoration: none;
        font-size: x-large;
        padding: 10px;
    }
    #insta{
        color: red;
    }
    .icon1{
        background-color: beige;
        display: flex;
        justify-content: space-between;
    }
    .icon1 i{
        padding: 10px;
    }

    /* navigation bar section */
    #apply{
        height: 40px;
        width: 100px;
        border-top-right-radius:20px ;
        border-bottom-left-radius: 20px;
        border-bottom-right-radius: 20px;
        background-color: red;
        font-size: 20px;
        color: aliceblue;
        margin-left: 30px;
        border: none;
    }
    ul{
        list-style: none;
    }
    nav{
        margin: 25px;
    }
    nav .menu{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .menu > li, .menu >a {
        display: inline-block;
    }
    .menu li{
        font-size:25px;
        padding-bottom: 20px;
        position: relative;
    }
    .menu a:hover{
        background-color: crimson;
        color: #fff;
    }
    .submenu{
        
        position: absolute;
        background-color: beige;
        width: 250px;
        left: 0;
        display: none;
    }
    .menu li:hover .submenu{
        display: block;
    }
    
   
    
    
/* introduction part starts and enquiry form starts here */

    .intro button{
        height: 40PX;
        margin: 20px;
        padding: 10px 0px;
        width: 150PX;
        border: none;
        color: #ffff;
        background-color: rgb(214, 18, 18);
        

    }
    .intro .button{
        display:inline ;
    }
   
    .form {
        height: 700px;
        background-color: rgb(80, 73, 220);
        display: flex;
        justify-content: space-around;
    }
    .applyform h3{
        text-align: center;
    }
   .applyform select{
        width: 350px;
        padding: 10px;
    }

    .applyform  {
        background-color: rgb(237, 236, 234);
        height: 500px;
        width: 26vw;
        margin: 23px 0px;
        border-radius: 35px;
        text-align: left;
        padding: 40px;
        font-size: 25px;

        color: rgb(1, 1, 11);

    }
    .intro {
        margin-top: 50px;
    }
    input{
        margin: auto 0px;
    height: 25px;
    width: 350px;
    line-height: 35px;
    padding-bottom: 10px;
    align-content: center;
    }
    
    /* about college education, results and placements */
    p{
        font-size: 25px;
    }

    
    .container{
        background-color: rgb(160, 164, 231);
        display: flex;
        justify-content: space-around;
        height: 450px;
    }
    .uu{
        background-color: rgb(233, 238, 241);
        height: 419px;
        width: 300px;
        border-radius: 30px;
        margin-top: 20px;
        text-align: center;
    }
    h3{
        color: black;
        font-size: 25px;
    }
    
    
    /* College achievements */
    h1{
        font-size: 50px;
        text-align: center;
        margin: 20px;
        
    }
    /* news section */
    .news{
        background-color: rgb(237, 236, 234);
        height: 500px;
        width: 400px;
        margin: 23px 12px;
        border-radius: 25px;
        text-align: center;
        font-size: 20px;
        color: rgb(1, 1, 11);
    }
    
    /* about college  */
    .extra{
        width: 60%;
    }

    /* toppers section */
    .toppers{
        text-align: center;
        align-items: center;
        height: 60vh;
        background-color: cornflowerblue;
        padding: 5px;
    }

    /* courses in college  */
    .course{
        display: flex;
        justify-content: space-around;
    }
    .cour{
     background-color: black;
     color: white;
     display: flex;
     justify-content: space-around;
        
    }

    /* footer section */
    .aboutus{
        background-color: rgb(57, 37, 37);
        height: 60vh;
        color: white;
    }
    ul{
       list-style: symbols(thumb);
    }
    .footer{
        background-color: black;
    }
    .lap{
        background-color: rgb(4, 4, 4);
        color: antiquewhite;
        display: flex;
        justify-content: space-around;
    }
    

    
</style>
<body>

    <!-- upper header section -->
    <div class="icon1">
        <div class="icon">
            <a href="https://in.linkedin.com/company/cimage"> <i class="fa fa-linkedin" aria-hidden="true"></i></a>
            <a id="insta" href="https://www.instagram.com/cimagecollege/?hl=en"><i class="fa fa-instagram"></i></a>

            <a href="https://www.facebook.com/cimage/"><i class="fa fa-facebook"></i></a>

            <a href="https://mobile.twitter.com/cimagecollege/status/1479346646785818627"><i
                    class="fa fa-twitter"></i></a>
        </div>

        <div class="icon">
            <i class="fa fa-whatsapp">-9599502025</i>|
            <i class="fa fa-mobile">-9599502025</i>
        </div>
    </div>
    <hr>
    <!-- cimage logo -->
    <center><img src="CIMAGE-Group-of-Institution.png" alt="cimage logo" width="50%" height="90px"></center>
    <hr>

    <!-- Navigation bar starts from here-->

    <nav>
        <ul class="menu">
            <li><a href="#"> Home</a></li>
            <li><a href="#"> About</a></li>
            <li><a href="#"> Academics</a>
                <ul class="submenu">
                    <li><a href="#">Courses</a></li>
                    <li><a href="#">Addmission</a></li>
                    <li><a href="#">Cimage Affliation</a></li>
                    <li><a href="#">Cimagr fee detail</a></li>
                    <li><a href="#">Student credit card</a></li>
                </ul>
            </li>
            <li><a href="#">Placements</a>
                <ul class="submenu">
                    <li><a href="#">College Placements</a></li>
                    <li><a href="#">Industry Interaction</a></li>
                </ul>
            </li>
            <li><a href="#">Cimage at Glance</a>
                <ul class="submenu">
                    <li><a href="#">Gallery</a></li>
                    <li><a href="#">Student Activity Club</a></li>
                    <li><a href="#">Events At Cimage</a></li>
                    <li><a href="#">Cimage in news</a></li>
                </ul>
            </li>
            <li><a href="#">pedagogy</a>
                <ul class="submenu">
                    <li><a href="#">Teaching pedagogy</a></li>
                </ul>
            </li>
            <li><a href="#">Social Initiative</a>
                <ul class="submenu">
                    <li><a href="#"></a>Our Social Initiative</li>
                </ul>
            </li>
            <li><a href="#"> Career</a></li>
            <li><a href="#"> Contact Us</a></li>
            <li><a href="#"> Blog</a></li>
            <button id="apply">Apply</button>
        </ul>
    </nav>

    <!-- Introduction part  -->
    <div class="form">
        <div class="intro">
            <h1>Welcome to <br> CIMAGE Group</h1>
            <br><br>
            <p>CIMAGE Group consist of three colleges under <br>
                patliputra university, and 1 college under <br>
                Aryabhatta Knowledge University.
            </p><br>
            <p>
                CIMAGE is the only Super Resourse Centre of <br>IIT
                Bombay in Bihar.
            </p><BR><BR></BR></BR>
            <div class="button">
                <button>APPLY NOW</button>
                <button>FEE PAY</button>
            </div>
        </div>

        <!-- Enquiry form  -->

        <div class="applyform">
            <form action="">
                <h3>Admision Enquiry</h3><br>
                <label for="">First Name</label><br>
                <input type="text" placeholder="Enter your first name..."><br>
                <label for="">Last Name</label><br>
                <input type="text" placeholder="Enter your last name...."><br>
                <label for="">E-mail</label><br>
                <input type="text" placeholder="Email address..."><br>
                <label for="">Phone Number</label><br>
                <input type="text" placeholder="mobile number" name="phone" size="10" /><br>
                <label for="">Course</label><br>
                <select name="course" id="course">
                   <option value="Bca">Choose your course...</option>
                   <option value="Bca">BCA</option>
                   <option value="Bca">BSC IT</option>
                   <option value="Bca">BBA</option>
                   <option value="Bca">BBM</option>
                   <option value="Bca">PGDM</option>
                </select><br>
                <button>Submit</button>
            </form>
        </div>
    </div>

    <!-- Time of excellence picture -->
    <center> <img src="Times-of-India-excellence-award-e1668600984858.webp" width="80%" alt=""></center>

    <!-- about college education, results and placements -->
    <div class="container">
        <div class="uu">
            <h3>Education</h3>
            <p>Being a Top BCA college in Bihar
                CIMAGE offers state-of-the-art and
                skill-based education. we focus on overall development
                of students to make them job-ready. India's
                leading newspaper Times Of India declared that Cimage is
                the No. 1 college in Bihar for IT, Management
                education.</p>
        </div>
        <div class="uu">
            <h3>Result</h3>
            <p>
                Every year CIMAGians are recieving GOLD MEDAL for
                University Topper in the course. Because of good
                academic results, it is popularly lnown as the best BCA
                college in BIhar. All across Bihar CImage is one
                of the Top college for BCA, BBA, and other IT-Management
                courses
            </p>
        </div>
        <div class="uu">
            <h3>Placement</h3>
            <p>
                5500+ Students are places ion 145+ companies including
                top MNC's. Over the Years CIMAGE has excellent
                campus placement record. One of the top 10 college in
                bihar offers job placement facility.
            </p>
        </div>
    </div>

    <!-- College achievements -->
    <h1>Times of India Declared, CIMAGE as No.1 College in Bihar</h1><br>
    <h1># * # * # * # * # * # * # * # * # * #</h1>

    <!-- about college  -->
    <div class="form">
        <div class="extra">
            <h2>Top BCA College in Bihar | Admission 2023</h2><br>
            <p>CIMAGE Group of Institutions is ranked as top BCA college
                in Bihar which offers state-of-the-art
                education and outstanding campus placement. It is one of
                the best colleges across Bihar for BCA BBA and
                other IT-Management Courses. For students who are
                seeking admission to a renowned institution for campus
                placement, CIMAGE is a perfect choice. When it comes to
                the Top BCA college in Bihar, CIMAGE has always
                been the first choice of students. Along with BCA course
                it also offers BBA, BBM, BSc.IT, PGDM, and
                B.Com Courses with job placement facility.</p><br>
            <p>CIMAGE Group is a prestigious institution founded in the
                year 2009 in Patna, Bihar. With a great
                reputation for quality education training in the fields
                of Management and Information Technology, the
                college has offered an unbeatable placement track
                record. The highest package has gone up to 22 LPA. It
                is Awarded as “Best B-School of India (East) Award” by
                ASSOCHAM, Association of Indian Universities &
                Ministry of HRD, Government of India. Student Credit
                Card facility is available for economically weaker
                students to pursue their studies.</p>
        </div>

        <!-- latest news section -->
        <div class="news">
            <h2>Latest Updates </h2>
            <hr><br>
            <marquee behavior="" direction="up"> <a href="#">CIMAGE
                    Students Industrial Visit to Jaipur : Learning
                    Beyond the Classroom</a>
                <hr>
                <a href="#">सिमेज के 300 छात्रों ने IIT-BHU में किया तीन
                    दिवसीय वर्कशॉप
                    | छात्रों ने CHAT-GPT, IOT, Ethical Hacking, Game
                    Development पर किया कोर्स</a>
                <hr>
            </marquee>
        </div>
    </div>

    <!-- breief about universities -->
    <p>CIMAGE college runs under AKU (Aaryabhatta knowledge University)
        & Patliputra university. Get Admission to CIMAGE
        college to achieve your dream job in campus placement. Its
        Add-on course will make you Job-Ready.
    </p><br>
    <p>CIMAGE is a Resource Center of IIT Mumbai for the study of
        Information Technology. We are collaborating with top
        IIT Colleges for advanced education and job-ready skills. The
        college also has established great relationships
        with corporate firms which take various candidates every year
        from this college. Once the student gets admission
        to CIMAGE college, we provide them with all the facilities for
        their study.</p><br>
    <p>“Knowledge, Skill, Success” the punch line of CIMAGE reflects its
        emphasis not only on knowledge but also on
        Skill Development, which finally leads to Success. Our success
        is evident from the Results, Placement, and
        phenomenal achievements of our students. Be it academics or
        extra-curricular activities, CIMAGEians have always
        proved themselves and achieved remarkable success.</p><br>
    <p>Getting admission to BCA or BBA courses at CIMAGE college Patna
        will be the best decision of your life as these
        two courses will open various job opportunities. Apart from
        classroom lectures, there are various types of
        activities such as Workshop, Industry Visit, Seminars, Project
        work, group discussions etc are done here. Being
        a top bca college in bihar, CIMAGE provides Job-ready Skills to
        the students that help them in the campus
        placement drive.</p>

    <!-- university topper section -->
    <div class="toppers">
        <h2>UNIVERSITY TOPPERS FROM CIMAGE GROUP</h2>
        <img src="Kumar-Shanu-AKU-BBA-Topper-2019-500x400.jpg" width="24%">
        <img src="Versha-Singh-BBA-2017-20-500x400.png" width="24%">
        <img src="Prashant-Kumar-AKU-BCA-Topper-2019-500x400.jpg" width="24%">
        <img src="AKU-BBA-Topper-Shruti-2018-min-500x400.jpg" width="24%">
    </div>

    <!--  courses in college  -->
    <center>
        <h3>TOP BCA COLLEGE IN BIHAR</h3>
    </center>
    <h1>Courses at CIMAGE Group of College</h1>
    <div class="course">
        <div class="uu">
            <h3>BCA</h3>
            <p>BCA Course admission at CIMAGE is complimented with
                several latest Add-On Courses, as per the
                requirements of the Industry, which keeps students ready
                to meet the Global Challenges in the field of
                Information Technology. Get job placement from Top BCA
                college in Bihar.</p>
        </div>
        <div class="uu">
            <h3>BBA</h3>
            <p>The BBA course empowers the students with Knowledge,
                Skills, and Confidence to carve a niche in the
                business environment. Get admission to the top BBA
                college in Bihar to avail campus placement facility.
                It is affiliated with the Aryabhatta Knowledge
                University (UGC Recognized). CIMAGE offers high-quality
                education with a global focus.</p>
        </div>
        <div class="uu">
            <h3>Bsc-IT</h3>
            <p>Bachelor of Science in Information Technology is a
                bachelor's degree awarded for an undergraduate course
                or program in the Information technology field. Best
                Bsc.it college in Bihar. The degree is normally
                required in order to work in the Information technology
                industry.</p>
        </div>
    </div>
    <div class="course">
        <div class="uu">
            <h3>BBM</h3>
            <p>Bachelor of Business Management (BBM) is an undergraduate
                program of three years. The BBM degree is
                designed to teach students the skills necessary to
                perform leadership roles in the business and
                corporate. Best BBM college in Bihar with good
                placement.</p>
        </div>
        <div class="uu">
            <h3>B.COM</h3>
            <p>B.Com is an undergraduate course offering a conceptual
                understanding in Accounting, Economics, Business
                Law, Taxation. Best B.com college in Bihar. It is a
                three year Undergraduate programme in the field of
                commerce.</p>
        </div>
        <div class="uu">
            <h3>PGDM</h3>
            <p>PGDM is a 2 years (4 Semesters) programme to prepare
                graduates for a dynamic career in the corporate &
                PSU sector. AIMA's PGDM is widely acclaimed for its
                strong curriculum in the industry and academic
                circles. Best PGDM college in Bihar offers good
                placements</p>
        </div>
    </div>

    <!-- footer section starts from here  -->

    <div class="footer">
        <div class="aboutus">
            <h1>About Us</h1>
            <center><img src="CIMAGE-Group-of-Institution.png" alt=""></center>
            <p>Top BCA College in Bihar offering an outstanding Job
                Placement. It is recognized as No.1 College in Bihar for
                IT & Management Courses such as BCA, BBA, BBM, BSc.IT
                etc. Over the years It has an excellent campus
                placement record. CIMAGE is affiliated to Aaryabhatta
                Knowledge University (AKU) & Patliputra University
                (PPU). Popularly known as best BBA college. It Achieved
                best B-School of East India award by ASSOCHAM.
                CIMAGE is the only remote center of IIT Bombay in Bihar.
            </p>
        </div>
    </div>
    <div class="cour">
        <h1>courses</h1>
        <h1>Quick links</h1>
        <h1>Reach us</h1>
    </div>
    <div class="lap">
        <div class="end">
            <ul>
                <li>BCA</li>
                <li>BBA</li>
                <li>BBM</li>
                <li>B.COM</li>
                <li>Bsc-IT</li>
                <li>PGDM</li>
            </ul>
        </div>
        <div class="end">
            <ul>
                <li>Career</li>
                <li>Blogs</li>
                <li>Downloads</li>
                <li>Admission Process</li>
                <li>FAQ</li>
                <li>Privacy policy</li>
            </ul>
        </div>
        <div class="end">
            <ul>
                <li>+91-7250767676</li>
                <li>+91-9835024444</li>
                <li>info@cimage.in</li>
                <li>S.K.Puri Park, Boring Road,Patna</li>
            </ul>
        </div>
    </div>

</body>

</html>
