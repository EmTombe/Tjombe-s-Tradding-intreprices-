<html>
  <html>

  <head>
    <style>
      ul { list-style-type: none; margin: 0; padding: 0; overflow: hidden; background-color: #333; } li { float: left; } li a, .dropbtn { display: inline-block; color: white; text-align: center; padding: 14px 16px; text-decoration: none; } li a:hover, .dropdown:hover .dropbtn { background-color: #48d1cc; } li.dropdown { display: inline-block; } .dropdown-content { display: none; position: absolute; background-color: #f9f9f9; min-width: 160px; box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2); } .dropdown-content a { color: black; padding: 12px 16px; text-decoration: none; display: block; text-align: left; } .dropdown-content a:hover{background-color:#f1f1f1} .dropdown:hover .dropdown-content { display: block; }
    </style>
  </head>

  <body>
    <ul>
      <li><a href="#home">Home</a>
      </li>
      <li><a href="#news">About Us</a>
      </li>
      <li class="dropdown"> <a href="#" class="dropbtn">Dropdown</a>
        <div class="dropdown-content"> <a href="#">Link 1</a> <a href="#">Link 2</a> <a href="#">Link 3</a> </div>
      </li>
    </ul>
    <h3></h3>
    <p></p>
  </body>

  </html>

  <head>
    <dl><b><<h2 style="color:red"><center>DINOTJIES PROGRAME⚙️🔧</center></h2></b>
    </dl>
    <hr width="100%" color="White" size="2" />

    <body style="background-color:lightblue">
      <title> DropDown</title>

      <style media="screen" type="text/css">
        .clearfix:after {
            display:block;
            clear:both;
        }
         
        /*----- Menu Outline -----*/
        
        .menu a {
            transition:all linear 0.15s;
            color:#919191;
        }
         
        .menu .arrow {
            font-size:11px;
            line-height:0%;
        }
         
        /*----- Top Level -----*/
        .menu > ul > li {
            float:left;
            display:inline-block;
            position:relative;
            font-size:19px;
        }
         
        .menu > ul > li > a {
            padding:10px 40px;
            display:inline-block;
            text-shadow:0px 1px 0px rgba(0,0,0,0.4);
        }
         
        .menu > ul > li:hover > a, .menu > ul > .current-item > a {
            background:#2e2728;
        }
         
        /*----- Bottom Level -----*/
        .menu li:hover .sub-menu {
            z-index:1;
            opacity:1;
        }
         
        .sub-menu {
            width:160%;
            padding:5px 0px;
            z-index:-1;
            opacity:0;
            transition:opacity linear 0.15s;
            box-shadow:0px 2px 3px rgba(0,0,0,0.2);
            background:#2e2728;
        }
         
        .sub-menu li {
            display:block;
            font-size:16px;
        }
         
        .sub-menu li a {
            padding:10px 30px;
            display:block;
        }
         
        .sub-menu li a:hover, .sub-menu .current-item a {
        	color:red;
            background:#3e3436;
        	
        }
      </style>
  </head>

  <body>
    <nav class="menu">
      <ul class="clearfix">

        <li>
          <a href="#">Click here to see Mr Tjombes Specialties<span class="arrow">▼</span></a>

          <ul class="sub-menu">
            <li><a href="#">IT SPECIALIST</a>
            </li>{}
            <li><a href="#">SOFTWARE ENGENEERING</a>
            </li>
            <li><a href="#">SOFTWARE DEVELOPER</a>
            </li>
          </ul>
        </li>

      </ul>
    </nav>
  </body>

</html>
<html>
<!DOCTYPE html>
<html>

<head>
  <style>
    button.accordion { background-color: #eee; color: #444; cursor: pointer; padding: 18px; width: 100%; border: none; text-align: left; outline: none; font-size: 15px; transition: 0.4s; } button.accordion.active, button.accordion: hover { background-color: #ddd; } button.accordion:after { /* Unicode character for "plus" sign (+) is '\02795' */ content: '\02795'; font-size: 13px; color: #777; float: right; margin-left: 5px; } button.accordion.active:after { /* Unicode character for "minus" sign (-) is '\2796' */ content: "\2796"; } div.panel { padding: 0 18px; background-color: white; max-height: 0; overflow: hidden; transition: 0.6s ease-in-out; opacity: 0; } div.panel.show { opacity: 1; max-height: 500px; }
  </style>
</head>

<body>
  <h2>Introduction Of the Dinotjie Programe</h2>
  <p>In this Programe we have added different types of Security algorythems, this
    will truthefully guide you and protect your Windows from any attacters.</p>
  <button class="accordion"></button>
  <div class="panel">
    <p>The tiger is the largest cat species, most recognisable for their pattern of
      dark vertical stripes on reddish-orange fur with a lighter underside.</p>
  </div>
  <button class="accordion">Lion</button>
  <div class="panel">
    <p>The lion is one of the big cats in the genus Panthera and a member of the family
      Felidae.The commonly used term African lion collectively denotes the several
      subspecies in Africa.</p>
  </div>
  <button class="accordion">Cheetah</button>
  <div class="panel">
    <p>The cheetah, also known as the hunting leopard, is a big cat that occurs mainly
      in eastern and southern Africa and a few parts of Iran</p>
  </div>
  <script>
    var acc = document.getElementsByClassName("accordion");
    var i;
    for (i = 0; i < acc.length; i++)
    {
      acc[i].onclick = function()
      {
        this.classList.toggle("active");
        this.nextElementSibling.classList.toggle("show");
      }
    }
  </script>
</body>

</html>


<head>
  <title>HTML fieldset Tag</title>
</head>

<body>
  <form>
    <fieldset>

      <legend>Details</legend>

      Username :
      <input type="text">
      <br/></br>

      Password :
      <input type="password">
      <br/></br>

      <input type="submit" value="Submit">

    </fieldset>
  </form>
</body>

</html>

<!-- <input> Tag
Defines a password field (characters are masked).
-->

<!DOCTYPE html>
<html>

<head>
  <title> HTML input type Password</title>
</head>

<body>
  <form>
    Enter Passkey:
    <input type="password">
    <input type="submit">
  </form>
</body>

</html>
<!-- <input> Tag
Defines a radio button.
-->

<!DOCTYPE html>
<html>

<head>
  <title> HTML input type radio</title>
</head>

<body>
  <form>
    <input type="radio" name="gender" value="male"> Male
    <br>
    <input type="radio" name="gender" value="female"> Female
    <br>
    <br>
    <input type="submit" value="Submit">
  </form>
</body>

</html>
<!DOCTYPE html>
<html>

<body>

  <img src="bird.jpg" alt="be the change" width="104" height="142">

</body>

</html>
<html>

<head>
  <title>HTML video Tag</title>
</head>

<body>
  <form>
    <font color="Green">E-mail</font>:
    <input type="email" name="usremail">
    <input type="submit">
  </form>
</body>

<body>
  <h3> Video of advanced website Coding </h3>
  <html>

  <head>
    <title> HTML input type email </title>
  </head>

  </html>
  <br />
  <video width=500 height=400 controls autoplay>
    <source src="video.mp4" type="video/mp4">
  </video>
  <html>

  <head>
    <title>HTML video Tag</title>
  </head>


  </html>
</body>

</html>
<title> </title>
<br <body><b>Trust and progress</b>
</body>
<br <html>

<head>
  <title>HTML marquee Tag</title>
</head>

<body>
  <marquee> IT consultants. They are external anylyst Who evaluates the companies IT Systems
    to <b>help them meet thier bussiness objectives. Primary Duties: Analysing And
    diagnosing a companies IT infrustacture.</b> Understanding a clients business
    needs. Designing And implementing a technology solution.
  </marquee>
</body>

</html>
<html>

<head>
  <title>HTML Definition List</title>
</head>

<body>
  <dl>
    <dt><b>The types of Virtualization.</b>
    </dt>
    <dd>Virtualization can be implemented in several ways. If the simulated platform
      is not identical to the underlying hardware this known as paravirtualization.</dd>
    <!-- <link> Tag
The HTML <marquee> tag is used for scrolling piece of text or image displayed either horizontally
across or vertically down your web site page depending on the settings.-->

    <!DOCTYPE html>
    <html>

    <head>

      <title> Marquee Tag </title>

    </head>

    <body>


      <marquee bgcolor="#eeeeee" direction="right" scrollamount="10" width="100%" height="20">

        Creating whats not there!

      </marquee>
      <br>
      <p>
        <marquee bgcolor="skyblue" direction="down" scrollamount="5" width="49%" height="500">

          <center>keep doing whats best for you🍂</center>
          <center></center>
          <center></center>
        </marquee>
        <marquee bgcolor="skyblue" direction="up" scrollamount="5" width="49%" height="500">

          <center>DONT BOTHER</center>
          <center>WE DO WHATS RIGHT!</center>
          <center>PROUD NAMIBIAN!</center>
        </marquee>
      </p>
      <marquee bgcolor="#eeeeee" direction="left" scrollamount="10" width="100%" height="20">

        NAMIBIA ONE NATION!

      </marquee>

    </body>

    </html>
    <!-- <input> Tag
Defines a control for entering a number whose exact value is not important (like a slider control)
-->

    <!DOCTYPE html>
    <html>

    <head>
      <title> HTML input type range</title>
    </head>

    <body>
      <form>
        Points:
        <input type="range" name="points" min="0" max="100">
        <br>
        <br>
        <input type="submit">
      </form>
    </body>

    </html>
    <bl></bl>
    <!-- cellpadding Attribute
This attribute is used to set the space between the cell wall and the cell content.-->

    <!DOCTYPE html>
    <html>

    <head>
      <title> Cell Padding Example </title>
    </head>

    <body>

      <table cellpadding="20" border="1">
        <tr>
          <th>Name</th>
          <th>Age</th>
        </tr>
        <tr>
          <td>Tjombe</td>
          <td>22</td>
        </tr>
      </table>

    </body>

    </html>

    <!-- <input> Tag
Defines a date control (year, month and day (no time))
-->

    <!DOCTYPE html>
    <html>

    <head>
      <title> HTML input type date </title>
    </head>

    <body>
      <form>
        Select date of birth :
        <input type="date">
        <br>
      </form>
    </body>

    </html>
    <!-- <blockquote> tag

The HTML <blockquote> tag is used for indicating long quotations (i.e. quotations that span multiple lines). 
It should contain only block-level elements within it, and not just plain text.-->

    <!DOCTYPE html>
    <html>

    <head>
      <title> Blockquote Example </title>
    </head>

    <body>

      <b><body>

		<h1 style="font-size:150%">Manu Tjombe🌿</h1>
		<p style="font-size:100%">The only way you want to find out whats his busy with is just to know his busy.</p>

	</body>Motivation</b>
      <blockquote>"Debugging is twice as hard as writing the code in the first place. Therefore,
        if you write the code as cleverly as possible, you are, by definition,
        not smart enough to debug it. Em.tjombe"</blockquote>
      <br>
      <b>Inspiration</b>
      <blockquote>"It's not at all important to get it right the first time. It's vitally important
        to get it right the last time."</blockquote>
    </body>

    </html>
    <!-- bdi tag
Isolate the usernames from the surrounding text-direction settings.
-->
    <!DOCTYPE html>
    <html>

    <head>

      <title>HTML bdi tag</title>

    </head>

    <body>

      <head><b>Graduates</b>
      </head>

      <p>
        <font color="white">The information provided below has met the demanded requirements and thus
          has put the individuals in state to be rewarded for their outstanding
          results. They can now proceed with their Practical</font>
      </p>

      <ul>
        <li>User
          <bdi>John Janser</bdi>: 79 points</li>
        <li>User
          <bdi>Manu Tjombe</bdi>: 86 points</li>
        <li>User
          <bdi>Elzane Cloete</bdi>: 87 points</li>
        <li>User
          <bdi>Quently Van Wyk</bdi>: 89 points</li>
        <li>User
          <bdi>Shawnly Patrick</bdi>: 92 points</li>
      </ul>

    </body>
<br></br>
    </html>

    <head><b><font color="Yellow">Self taught Programing languadges.</font></b>
    </head>
    <bl></bl>
    <html>

    <head>
      <title>HTML Unordered List</title>
    </head>

    <body>
      <ul type="circle">
        <li>C</li>
        <li>C++</li>
        <li>Java</li>
        <li>HTML</li>
      </ul>
    </body>

    </html>




    <!--
Visual Code Mobile
Developed By Manish Nirmal
App Available on Play Store :-
https://play.google.com/store/apps/details?id=lk.visual.code.mobile
YouTube :-
https://youtube.com/ManishNirmal
-->
