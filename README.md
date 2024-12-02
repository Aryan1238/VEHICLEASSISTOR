# VEHICLEASSISTOR
PROJECT OF TEAM HACKINATORS

![home-pop-up-mob (1)](https://github.com/user-attachments/assets/a9bd8bf8-4e11-4533-a672-5690ba4cfc64)

![WhatsApp Image 2024-12-01 at 20 27 13_8f00c787](https://github.com/user-attachments/assets/0c1feb27-a8fb-488e-8b3d-6f4fd4845969)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VEHICLE ASSISTOR</title>

    <link rel="shortcut icon" href="WhatsApp Image 2024-12-01 at 20.27.13_8f00c787.jpg" type="image/x-icon">
    <STYLE type="text/css">
        *{
            text-decoration: none;
        }
        body{
            background-color: rgb(245,245,220);
        }
        .navbar{
            background: green; font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; padding-left: 15px; padding-right: 15px;
        }
        .navid{
            display: flex; align-items: center; justify-content: space-between;
        }
        .logo{
            font-size: 35px; font-weight: 600; color: red;
        }
        li{
            list-style: none; display: inline-block;
        }
        li{
            font-size: 18 px; font-weight: bold; margin-right: 25px; color: rgb(78, 225, 132);
        }
        button{
            background-color: rgb(79, 243, 96); margin-left: 10px; border-radius: 10px; padding: 10px; 
        }
        .container{
            display: flex;
            align-items: center;
            justify-content: center;
            height: 80vh;
            gap: 50px;
        }
        .arrow{
            height: 150px;
            cursor: pointer;
        }
        .leftarrow{
            transform: rotate(180deg);
        }
        .frame{
            width: 800px;
            height: 500px;
            overflow: hidden;
            box-shadow: -1px 1px 10px rgba(0, 0, 0, .5);
        }
        .slider{
            display: flex;
        }
        .picture1{
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .picture2{
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .picture3{
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .picture4{
             width: 100%;
             height: 100%;
             object-fit: cover;
        }
        .whoweare{
            color: maroon;
        }
        footer{
            background-color: darkcyan;
        }
    </STYLE>
</head>
<body>
    <nav class="navbar" >
        <div class="navid">
            <div class="logo" >VEHICLE ASSISTOR</div>
            <ul>
                <li> <a href="#whoweare">WHO WE ARE </a> </li>
                <li> <a href="#services">SERVICES </a> </li>                
                <li><a href="#aboutus">ABOUT US</a></li>
                <li><a href="#contact">HELPLINE</a></li>

                
            </ul>
        </div>
    </nav>
    <section>
        <img src="home-pop-up-mob (1).png" alt="">
    </section>

    
    <section id="whoweare">
        <h4>INTRODUCTION</h4>
        <div class="div1">
            WE ARE HERE TO PROVIDE YOU WITH ROADSIDE ASSISTANCE. OUR ULTIMATE AIM IS TO BE THE BIGGEST ROADSIDE ASSISTOR ACROSS INDIA. FROM WEAR AND TEAR TO MAJOR ENGINE BREAK DOWN WE PROVIDE EVERY SOLUTION TO YOUR VEHICLE AT YOUR EASE.SOME OF OUR KEY SERVICES CONTAIN
            <UL>
                <LI>HOME SERVICING</LI>
                <LI>PICKUP AND DROP SERVICING</LI>
                <LI>ROADSIDE ASSISTANCE</LI>
                <LI>TOW SERVICES</LI>
            </UL>
        </div>
    </section>

    <section id="services">
        <h4>BREAKDOWN! WORRY NOT FILL THE FORM</h4>
        <div class="form">
            <LABEL FOR="NAME">ENTER YOUR NAME :</LABEL>
        <BR/>
        <INPUT type="TEXT" ID="NAME"></INPUT>
        <BR/>
        <LABEL for="EMAIL">EMAIL:</LABEL>
        <BR/>
        <INPUT type="email" id="EMAIL"></INPUT>
        <BR/>
        <LABEL FOR="PHONE">PHONE:</LABEL>
        <BR/>
        <INPUT type="tel" id="PHONE"></INPUT>
        <BR/>
        <LABEL for="FILE">UPLOAD IMAGE OF CAR:</LABEL>
        <BR/>
        <INPUT type="file" ID="FILE" value="CHOOSEFILE"></INPUT>
        <BR/>
        <LABEL for="YEARS">VEHICLES AGE:</LABEL>
        <BR/>
        <INPUT type="number" ID="YEARS" min="0" max="100"></INPUT>
        <BR/>
        <BR/>
        <FIELDSET>
            <LEGEND>WHAT YOU NEED</LEGEND>
            <BR/>
            <INPUT type="radio" NAME="RADIO" ID="RADIO1"></INPUT>
            <BR/> 
            <LABEL FOR="RADIO1">HOME SERVICING</LABEL>
            <BR/>
            <INPUT type="radio" NAME="RADIOA" ID="RADIO2"></INPUT>
            <BR/> 
            <LABEL FOR="RADIO2">INSTANT BREAKDOWN SERVICES</LABEL>
            <BR/>
            <INPUT type="radio" NAME="RADIOB" ID="RADIO3"></INPUT>
            <BR/> 
            <LABEL FOR="RADIO3">PICKUP AND DROP</LABEL>
            <BR/>
            <INPUT type="radio" name="radioc" id="RADIO4"></INPUT>
            <BR/>
            <LABEL for="RADIO4">TOW</LABEL>
            <BR/>


            
        </FIELDSET>

        <BR/>
        <BR/>
        <LABEl for="CAR COMPANY">HIGHEST EDUCATION:</LABEl>
        <BR/>
        <select id="CAR COMPANY">
            <OPTION value="MARUTI SUZUKI">MARUTI SUZUKI</OPTION>
            <OPTION value="MAHINDRA">MAHINDRA</OPTION>
            <OPTION value="TATA">TATA</OPTION>
            <OPTION value="OTHERS">OTHERS</OPTION>
        </select>

        <BR/>
        <LABEL for="TXTAREA">CAR COMPANY AND MODEL:</LABEL>
        <BR/>
        <INPUT type="text" id="TXTAREA" placeholder="IF OTHER SPECIFY YOUR CARBRAND AND MODEL" ></INPUT>
        <INPUT type="submit" value="SUBMIT"></INPUT>

        <BR/>

        <BR/>
        <FIELDSET>
            <legend>ISSUE YOU ARE FACING</legend>

        <INPUT type="radio" name="AVAILABILITY" id="AVAILABILITY"></INPUT>
        <BR/>
        <LABEL for="AVAILABILITY">WEAR AND TEAR</LABEL>
        <BR/>
        <INPUT type="RADIO" name="AVAILABILITY" id="AVAILABILITY1"></INPUT>
        <BR/>
        <LABEL for="AVAILABILITY1">ENGINE CLUTCH GEAR</LABEL>
        </FIELDSET>

        <BR/>
        <BR/>
        <LABEL for="TXTAREA">ADDITIONAL COMMENTS:</LABEL>
        <BR/>
        <INPUT type="text" id="TXTAREA" placeholder="TYPE YOUR COMMENT:" ></INPUT>
        <INPUT type="submit" value="SUBMIT"></INPUT>                 
        </div>
        <INPUT type="submit" value="SUBMIT"></INPUT>
    </section>
    <BR/>
    <BR/>
    <H4>ABOUT US</H4>
    <section id="aboutus">
      WE ARE THE INDIA'S LEADING CAR ASSISTOR TEAM ! WE PROVIDE YOU WITH 24X7 HOURS OF <ul>
        <li>RSA (ROAD SIDE ASSISTANCE)</li>
        <LI>HOME SERVCES</LI>
        <LI>PICK AND DROP SERVICES</LI>
      </ul>
      AND MUCH MORE....... 
      <BR/>
      WITH EACH DAY WE ARE EXTENDING OUR SERVICES ALL ACROSS INDIA AND WORKING ON BETTERMENT OF OUR SELF!
    </section>

    <footer id="contact">
        <section>
            <h4>HELPLINE</h4>
            <ul>
                <li><a href="mailto:helpline@vehicleassistor.com">EMAIL</a></li>
                <li><a href="tel:+918090489914">CALLUS</a></li>
            </ul>
            <br/>
            <p>&#169; 2024 VEHICLE ASSISTOR. ALL RIGHTS RESERVED</p>
            
        </section>
    </footer>
    
    <script src="attach.js"></script>
</body>
</html>
