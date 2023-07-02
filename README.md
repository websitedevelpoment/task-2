# task-2
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv='cache-control' content='no-cache'>
    <meta http-equiv='expires' content='0'>
    <meta http-equiv='pragma' content='no-cache'>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Companies trust us One Page Template Live Demo</title>
    <link href="//fonts.googleapis.com/css?family=Roboto|Open+Sans:200,300,400,700,800,900&amp;subset=latin"
        rel="preload" as="font">
    <style>
        * {
            margin: 0;
            padding: 0;
            font-family: 'Open Sans', sans-serif;
        }
        @media screen and (min-width:1040px) and (max-width:none) {
            
        }
 BODY {
            max-width: 100%;
            min-height: 100%;
            background-color: #cbbee7;
        }

        .container {
            display: flex;
            justify-content: center;
            text-align: center;
            /* background-size: 50% 50%; */
            width: 100%;
            background-color: #cbbee7;
            align-items: stretch;
            /* height: 100%; */
        }

        .section1 {
            height: 100%;
            padding-top: 179px;
            padding-left: 46px;
        }


        .section2 {
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 30px;
            position: relative;
            box-sizing: border-box;
        }

        .heading {
            font-size: 3rem;
            width: 420px;
            color: white;
        }

        p {
            width: 460px;
            line-height: 1.5;
            color: white;
            margin: 21px 1px 0px;
            font-size: 1.125rem;
        }

        /* .emailandname{
            display: inline-block;
            column-count: 2;
            width: 100%;
            text-align: initial;
        } */
        .message {
            box-sizing: border-box;
            display: flex;
            width: 474px;
            align-items: flex-start;
            flex-direction: column;
        }

        .image {
            height: 474px;
            position: relative;
            bottom: 2rem;
        }

        /* .email{
            width: 50%;
        } */
        .name {
            width: 50%;
            /* position: relative;
            right: 39px; */
            text-align: start;
            left: 33px;
        }

        .email {
            width: 50%;
            text-align: start;
        }

        #box3{
            width: 465px;
            box-sizing: border-box;
        }
        #box1,
        #box2,
        #box3 {
            border: 7px solid white;
            border-radius: 10px;
            font-weight: lighter;
            font-size: 1rem;
            text-align: initial;
            padding: 10px 12px;
        }

        .label1,
        .label2,
        .label3 {
            font-size: 16px;
            position: relative;
            bottom: 4px;
            border-color: none;
        }

        .form {
            height: 347px;
            width: 510px;
            margin: 30px 0;
        }

        .form1 {
            background-color: #f2f2f2;
            /* margin-left: -10px; */
            padding: 20px;
            display: flex;
            justify-content: center;
            /* flex-direction: column; */
            flex-wrap: wrap;
            align-items: center;
            width: 478px;
            height: 300px;
        }

        .span {
            text-decoration: none;
            /* position: relative;
           left: 188px; */
            color: #ffff;
            font-weight: 700;
        }
        @media screen and (max-width:1024px) and (min-width:820px) {
            body {
                background-color: #cbbee7;
            }

            .container {
                display: flex;
                justify-content: center;
                text-align: center;
                /* background-size: 50% 50%; */
                width: 100%;
                /* background-color:#cbbee7 ; */
                align-items: flex-end;
                height: 100%;
            }

            .section1 {
                height: 100%;
                box-sizing: border-box;
                max-height: 668px;
                max-width: 470px;
            }

            .image {
                height: 407px;
                max-width: 470px;
                position: relative;
                bottom: 2rem;
            }

            .section2 {
                max-width: 470px;
                text-align: center;
                display: flex;
                flex-direction: column;
                align-items: center;
                padding: 30px;
                position: relative;
                box-sizing: border-box;
            }

            .heading {
                font-size: 3rem;
                width: 392px;
                margin: 0px 9px;
                color: white;
            }

            p {
                width: 379px;
                line-height: 1.5;
                color: white;
                margin: 21px 1px 0px;
                font-size: 1.125rem;
            }

            .message {
                display: flex;
                align-items: flex-start;
                box-sizing: border-box;
                flex-direction: column;
            }

            .name {
                width: 50%;
                /* position: relative;
            right: 39px; */
                text-align: start;
                left: 33px;
            }

            .email {
                width: 50%;
                text-align: start;
            }

            #box1 {
                max-width: 180px;
                max-height: 46px;
            }

            #box2 {
                max-width: 190px;
                max-height: 75px;
            }

            #box3 {
                max-width: 380px;
                max-height: 102px;
            }

            #box1,
            #box2,
            #box3 {
                border: 7px solid white;
                border-radius: 10px;
                box-sizing: border-box;
                font-weight: lighter;
                font-size: 1rem;
                text-align: initial;
                padding: 10px 12px;
            }

            .label1,
            .label2,
            .label3 {
                font-size: 16px;
                position: relative;
                bottom: 4px;
                border-color: none;
            }

            .form {
                height: 336px;
                width: 410px;
                margin: 30px 0;
            }

            .form1 {
                background-color: #f2f2f2;
                /* margin-left: -10px; */
                padding: 20px;
                display: flex;
                justify-content: center;
                /* flex-direction: column; */
                flex-wrap: wrap;
                align-items: center;
                width: 420px;
                box-sizing: border-box;

                height: 333px;
            }

            .span {
                text-decoration: none;
                /* position: relative;
           left: 188px; */
                color: #ffff;
                font-weight: 700;
            }
        }

        @media screen and (max-width:820px) and (min-width:640px) {
            body {
                background-color: #cbbee7;
            }

            .container {
                display: flex;
                justify-content: center;
                text-align: center;
                /* background-size: 50% 50%; */
                width: 100%;
                /* background-color:#cbbee7 ; */
                align-items: flex-end;
                height: 100%;
            }

            .section1 {
                height: 100%;
                box-sizing: border-box;
                max-height: 668px;
                max-width: 350px;
            }

            .image {
                height: 294px;
                max-width: 307px;
                position: relative;
                bottom: 6rem;
            }

            .section2 {
                max-width: 360px;
                text-align: -webkit-center;
                display: flex;
                flex-direction: column;
                align-items: center;
                padding: 30px;
                position: relative;
                box-sizing: border-box;
            }

            .heading {
                font-size: 2rem;
                width: 298px;
                max-height: 79px;
                margin: 0px 9px;
                color: white;
            }

            p {
                width: 298px;
                line-height: 1.5;
                color: white;
                margin: 21px 1px 0px;
                font-size: 1.125rem;
            }

            .message {
                display: flex;
                align-items: flex-start;
                max-width: 270px;
                max-height: 147px;
                box-sizing: border-box;
                flex-direction: column;
            }

            .name {
                width: 50%;
                /* position: relative;
            right: 39px; */
                text-align: start;
                left: 33px;
            }

            .email {
                width: 50%;
                text-align: start;
            }

            #box1 {
                max-width: 120px;
                max-height: 46px;
            }

            #box2 {
                max-width: 130px;
                max-height: 75px;
            }

            #box3 {
                max-width: 260px;
                max-height: 122px;
            }

            #box1,
            #box2,
            #box3 {
                border: 7px solid white;
                border-radius: 10px;
                box-sizing: border-box;
                font-weight: lighter;
                font-size: 1rem;
                text-align: initial;
                padding: 14px 3px;
            }

            .label1,
            .label2,
            .label3 {
                font-size: 16px;
                position: relative;
                bottom: 4px;
                border-color: none;
            }

            .form {
                height: 300px;
                max-width: 312px;
                box-sizing: border-box;
                margin: 30px 0;
            }

            .form1 {
                background-color: #f2f2f2;
                /* margin-left: -10px; */
                padding: 20px;
                display: flex;
                justify-content: center;
                /* flex-direction: column; */
                flex-wrap: wrap;
                align-items: center;
                width: 310px;
                box-sizing: border-box;

                height: 333px;
            }

            .span {
                text-decoration: none;
                /* position: relative;
           left: 188px; */
                color: #ffff;
                font-weight: 700;
            }
        }
        @media screen and (max-width:640px) and (min-width:440px ) {
            body {
                background-color: #cbbee7;
            }

            .container {
                display: flex;
                flex-wrap: wrap;
                justify-content: center;
                text-align: center;
                /* background-size: 50% 50%; */
                width: 100%;
                /* background-color:#cbbee7 ; */
                align-items: flex-end;
                height: 100%;
            }

            .section1 {
                height: 100%;
                box-sizing: border-box;
                max-height: 584px;
                max-width: 540px;
                padding: 0%;
            }

            .image {
                height: 468px;
                max-width: 540px;
                position: relative;
                bottom: 0;
                padding-TOP: 70PX;
                padding-bottom: 30PX;
            }

            .section2 {
                max-width: 540px;
                padding-left: 9px;
                padding-right: 9px;
                max-height:584px;
                text-align: -webkit-center;
                display: flex;
                flex-direction: column;
                align-items: center;
                padding-top: 30px;
                padding-bottom: 30px;
                position: relative;
                box-sizing: border-box;
            }

            .heading {
                font-size: 2rem;
                width: 370px;
                max-height: 39px;
                margin: 0px 9px;
                color: white;
            }

            p {
                width: 522px;
                line-height: 1.5;
                color: white;
                margin: 21px 1px 0px;
                font-size: 1.125rem;
            }

            .message {
                display: flex;
                align-items: flex-start;
                min-width: 490px;
                margin: 0px 0px 10px;
                padding: 0px 0px 0px 10px;
                min-height: 147px;
                box-sizing: border-box;
                flex-direction: column;
            }

            .name {
                width: 50%;
                /* position: relative;
            right: 39px; */
                text-align: start;
                left: 33px;
            }

            .email {
                width: 50%;
                text-align: start;
            }

            #box1 {
                min-width: 235px;
                min-height: 45px;
            }

            #box2 {
                min-width: 235px;
                min-height: 45px;
            }

            #box3 {
                min-width: 480px;
                margin-left: -10px;
                min-height: 122px;
            }

            #box1,
            #box2,
            #box3 {
                border: 7px solid white;
                border-radius: 10px;
                box-sizing: border-box;
                font-weight: lighter;
                font-size: 1rem;
                text-align: initial;
                padding: 10px 3px;
            }

            .label1,
            .label2,
            .label3 {
                font-size: 16px;
                position: relative;
                bottom: 4px;
                border-color: none;
            }

            .form {
                height: 333px;
                min-width: 530px;
                box-sizing: border-box;
                margin: 30px 0;
            }

            .form1 {
                background-color: #f2f2f2;
                /* margin-left: -10px; */
                padding: 20px;
                display: flex;
                justify-content: center;
                /* flex-direction: column; */
                flex-wrap: wrap;
                align-items: center;
                width: 530px;
                box-sizing: border-box;

                height: 333px;
            }

            .span {
                text-decoration: none;
                /* position: relative;
           left: 188px; */
                color: #ffff;
                font-weight: 700;
            }
        }
        @media screen and (max-width:440px) {
            body {
                background-color: #cbbee7;
            }

            .container {
                display: flex;
                flex-wrap: wrap;
                justify-content: center;
                text-align: center;
                /* background-size: 50% 50%; */
                width: 100%;
                /* background-color:#cbbee7 ; */
                align-items: flex-end;
                height: 100%;
            }

            .section1 {
                height: 100%;
                box-sizing: border-box;
                max-height: 355px;
                max-width: 340px;
                padding: 0%;
            }

            .image {
                height: 295px;
                max-width: 340px;
                position: relative;
                bottom: 0;
                padding-TOP: 70PX;
                padding-bottom: 30PX;
            }

            .section2 {
                max-width: 340px;
                padding-left: 9px;
                padding-right: 9px;
                max-height:699px;
                text-align: -webkit-center;
                display: flex;
                flex-direction: column;
                align-items: center;
                padding-top: 30px;
                padding-bottom: 30px;
                position: relative;
                box-sizing: border-box;
            }

            .heading {
                font-size: 1rem;
                width: 246px;
                max-height: 26px;
                margin: 0px 37.75px;
                color: white;
            }

            p {
                width: 321px;
                line-height: 1.5;
                min-height: 148px;
                color: white;
                margin: 21px 0px 0px 1px;
                box-sizing: border-box;
                font-size: 1.125rem;
            }

            .message {
                display: flex;
                align-items: flex-start;
                width: 490px;
                margin: 0px 0px 10px;
                padding: 0px 0px 0px 10px;
                min-height: 147px;
                box-sizing: border-box;
                flex-direction: column;
            }

            .name {
                width: 100%;
                /* position: relative;
            right: 39px; */
                text-align: start;
                left: 33px;
            }

            .email {
                width: 292px;
                height: 71px;
                text-align: start;
            }

            #box1 {
                min-width: 290px;
                min-height: 45px;
            }

            #box2 {
                min-width: 290px;
                min-height: 45px;
            }

            #box3 {
                max-width: 290px;
                margin-left: -10px;
                min-height: 122px;
            }

            #box1,
            #box2,
            #box3 {
                border: 7px solid white;
                border-radius: 10px;
                box-sizing: border-box;
                font-weight: lighter;
                font-size: 1rem;
                text-align: initial;
                padding: 10px 3px;
            }

            .label1,
            .label2,
            .label3 {
                font-size: 16px;
                position: relative;
                bottom: 4px;
                border-color: none;
            }
            .label1{
                height: 22px;
            }

            .form {
                height: 417px;
                width: 332px;
                box-sizing: border-box;
                margin: 30px 0;
            }

            .form1 {
                background-color: #f2f2f2;
                /* margin-left: -10px; */
                padding: 20px;
                display: flex;
                justify-content: center;
                /* flex-direction: column; */
                flex-wrap: wrap;
                align-items: center;
                width: 332px;
                box-sizing: border-box;
                height: 417px;
            }

            .span {
                text-decoration: none;
                /* position: relative;
           left: 188px; */
                color: #ffff;
                font-weight: 700;
            }
        }
    </style>
</head>

<BODY>
    <div class="container">
        <div class="section1">
            <section>
                <img class="image" src="https://assets.nicepagecdn.com/11a8ddce/4242949/images/Untit7led-1.png">
            </section>
        </div>
        <div></div>

        <div class="section2" style="padding-bottom: 0;">
            <section class="heading">
                Get Free SEO Analysis?
            </section>
            <p>
                Nec feugiat nisl pretium fusce id. Justo laoreet sit amet cursus sit amet. Porta non pulvinar neque
                laoreet suspendisse interdum consectetur libero.
            </p>
            <div class="form">
                <form class="form1">
                    <div class="email">
                        <div class="emalilabel" ><LABEL class="label1" for="emial-7d96">Email</LABEL></div>
                        <input id="box1" name="Email" type="Email" placeholder="Enter a Valid email address" required
                            style="height: 12px;">
                    </div>
                    <div class="name">
                        <div class="namelabel" ><label class="label2" for="name-7d96"> Name</label></div>
                        <input id="box2" type="NAME" placeholder="Enter your name" required style="height: 12px;">
                    </div>
                    <div class="message">
                        <div class="messagelabel" ><label class="label3" for="message-7d96" style="display: block;"> Message</label></div>
                        <textarea id="box3" name="message" cols="51" rows="5" placeholder="Enter your message"
                            required></textarea>
                    </div>
                    <div class="span"><a href="#" style="color: #ffffff;
                text-decoration: none;
                background-color:#876cc4;
                border-radius: 10px;
                padding: 14px 30px;
                margin: 1px 0px;
                ">
                            SUBMIT </a></div>
                </form>
            </div>
        </div>
    </div>
</BODY>

</html>
