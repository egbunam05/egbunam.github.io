<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        main {
            display: flex;
            justify-content: center;

        }

        .cover {
            background-image: url("../img/heart2.jpg");
            background-repeat: no-repeat;
            background-position: left;
            background-size: cover;


            position: absolute;
            /* width: 80%; */
            height: 2050px;
            width: 64.5%;
            z-index: -10;

        }

        section {
            width: 65%;

            background: rgb(49, 111, 158);
            background: linear-gradient(135deg, rgba(49, 111, 158, 0.9) 9%, rgba(61, 168, 142, 0.9) 43%, rgba(22, 48, 81, 0.9) 92%);
        }

        .first {
            display: flex;
        }

        .first img {
            width: 300px;
            height: 400px;
        }

        .first h2 {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #0A1242;
            font-size: 50px;
            text-align: center;
        }

        .first h3 {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: white;
            font-size: 30px;
            text-align: center;
        }

        .first h4 {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: white;
            font-size: 20px;
            text-align: center;
            /* border: 1px solid red; */
            width: 700px;
        }

        .second h1 {
            /* position: absolute; */
            font-size: 350px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-shadow: -12px -3px #4C5B55;
            margin-left: -80px;
            margin-top: -150px;
        }

        .second h1 span {
            color: #17431F;
            font-size: 500px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            position: relative;
            left: 150px;
            /* border: 1px solid red; */
            text-shadow: -12px -3px #94BBB4;

        }

        .third h2 {
            margin-top: -350px;
            background-color: #1E6229;
            color: white;
            padding: 20px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 70px;
        }

        .forth {
            display: flex;
        }

        .forth p {
            display: flex;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            font-style: italic;
            margin-left: 120px;
            width: 600px;
            display: inline-block;
            font-size: 60px;
            line-height: 70px;
            color: white;
        }

        .forth span {
            font-size: 300px;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            /* font-style: italic; */
            position: absolute;
            top: 62%;
            left: 0;
            padding-top: 60px;
            /* border: 1px solid red; */
        }

        .forth .end {
            font-size: 300px;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            /* font-style: italic; */
            position: absolute;
            top: 85%;
            left: 46%;
            padding-top: 60px;

        }

        .sub-forth {
            display: flex;
            flex-direction: column;
            gap: 350px;
            position: relative;
        }

        .forth img {
            position: absolute;
            width: 700px;
            height: 1000px;
            left: 45%;
            top: -2%;
        }

        .forth {
            position: relative;
        }

        .forth h3 {
            border-radius: 21% 79% 22% 78% / 82% 20% 80% 18%;
            /* border: 1px solid red; */
            background-color: #245C43;
            color: #fff;
            font-size: 50px;
            width: 43%;
            padding: 40px 0;
            padding-left: 50px;
            margin-bottom: -230px;

            font-style: italic;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }

        .fifth {
            position: relative;
            width: 100%;
            font-size: 30px;
            z-index: 1;
            text-align: center;

        }

        .fifth h1 {
            position: absolute;
            width: 100%;
            font-size: 40px;
            top: 50%;
            text-align: center;
            color: white;
        }



        /* mobile phones */
        @media (max-width:414px) {


            main {
                margin-left: -75%;
                margin-top: -370px;
                margin-bottom: -500px;
                width: 250%;
                height: auto;
                overflow: hidden;
                transform: scale(0.4);
                /* justify-content: center; */
            }


            .cover {
                background-image: url("../img/heart2.jpg");
                background-repeat: no-repeat;
                background-position: left;
                background-size: cover;


                position: absolute;

                height: 1460px;
                width: 250%;
                z-index: -10;

            }

            section {
                width: 100%;

                background: rgb(49, 111, 158);
                background: linear-gradient(135deg, rgba(49, 111, 158, 0.9) 9%, rgba(61, 168, 142, 0.9) 43%, rgba(22, 48, 81, 0.9) 92%);
            }

            .first {
                display: flex;
            }

            .first img {
                width: 150px;
                height: 150px;
                margin-top: 30px;
                margin-left: 50px;

            }

            .first h2 {
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                color: #0A1242;
                font-size: 40px;
                text-align: center;
                width: 100%;
                /* border: 1px solid red; */
                font-weight: 700;
            }

            .first h3 {
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                color: white;

                font-size: 28px;
                text-align: center;
                width: 100%;
            }

            .first h4 {
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                color: white;

                font-size: 20px;
                text-align: center;
                /* border: 1px solid red; */
                width: 700px;
            }

            .second h1 {
                /* position: absolute; */
                font-size: 170px;

                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                color: white;
                text-shadow: -12px -3px #4C5B55;
                margin-left: -80px;
                margin-top: -150px;
                transform: translate(25px, 35px);
            }

            .second h1 span {
                color: #17431F;
                font-size: 300px;
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                position: relative;
                top: 0px;
                left: 90px;
                /* border: 1px solid red; */

                text-shadow: -12px -3px #94BBB4;


            }

            .third h2 {
                margin-top: -160px;
                /* margin-top: -350px; */
                background-color: #1E6229;
                color: white;
                padding: 20px;
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                font-size: 50px;
                width: 100%;
                padding-left: 40px;
            }

            .forth {
                display: flex;
            }

            .forth p {
                text-align: center;
                display: flex;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                font-style: italic;
                margin-left: -10px;
                width: 500px;
                display: inline-block;
                font-size: 40px;
                line-height: 70px;
                color: white;
            }

            .forth span {
                font-size: 150px;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                /* font-style: italic; */
                position: absolute;
                top: 55%;
                left: 30px;
                padding-top: 60px;
                /* border: 1px solid red; */
            }

            .forth .end {
                font-size: 150px;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                /* font-style: italic; */
                position: absolute;
                top: 81%;
                left: 41%;
                padding-top: 60px;

            }

            .sub-forth {
                display: flex;
                flex-direction: column;
                gap: 350px;
                position: relative;
            }

            .forth img {
                position: absolute;
                width: 700px;
                height: 1000px;
                left: 34%;
                top: -30%;
            }

            .forth {
                position: relative;
            }

            .forth h3 {
                margin-top: -20px;
                border-radius: 21% 79% 22% 78% / 82% 20% 80% 18%;
                /* border: 1px solid red; */
                background-color: rgba(36, 92, 67, 0.8);
                color: #fff;
                font-size: 45px;
                width: 43%;
                padding: 40px 0;
                padding-left: 50px;
                margin-bottom: -230px;

                font-style: italic;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            }

            .fifth {
                position: relative;
                width: 100%;
                font-size: 30px;
                z-index: 1;
                text-align: center;

            }

            .fifth h1 {
                position: absolute;
                width: 100%;
                font-size: 30px;
                top: 50%;
                text-align: center;
                color: white;
            }
        }
    </style>
</head>

<body>
    <main>

        <section>
            <div class="cover"></div>
            <div class="first">
                <img src="UNN-LOGO.png" alt="">
                <div>
                    <h2>UNIVERSITY OF NIGERIA, NSUKKA</h2>
                    <h3>FACULTY OF HEALTH SCIENCE AND TECHNOLOGY</h3>
                    <h4>DEPARTMENT OF MEDICAL RADIOGRAPHY AND RADIOLOGICAL
                        SCIENCES</h4>
                </div>
            </div>
            <div class="second">
                <h1> <span>V</span> OTE</h1>
            </div>
            <div class="third">
                <h2>
                    IKECHUKWU ZIKORA CHIMAOBI
                </h2>
            </div>
            <div class="forth">
                <div class="sub-forth">
                    <h3>FOR FACULTY FINANCIAL SECRETARY</h3>
                    <p><span>“</span>ACCOUNTABILITY, TRANSPARENCY AND
                        INNOVATION<span class="end">”</span></p>
                </div>
                <img src="Zik.png" alt="">

            </div>
            <div class="fifth">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
                    <path fill="#656EB9" fill-opacity="0.9"
                        d="M0,96L80,101.3C160,107,320,117,480,106.7C640,96,800,64,960,53.3C1120,43,1280,53,1360,58.7L1440,64L1440,320L1360,320C1280,320,1120,320,960,320C800,320,640,320,480,320C320,320,160,320,80,320L0,320Z">
                    </path>
                </svg>
                <h1>"A PENNY SAVED, IS A PENNY EARNED"</h1>
            </div>

        </section>

    </main>
</body>

</html>
