# HTML-Lecture-1-2-3-4

LECTURE #1

    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8" />
        <title></title>
    </head>
    <body>

        <a href="https://www.google.com/">
            <img src="C:\Users\Carmella Rei Van\Downloads\Download (1)\Wallpaper\wp7191324.png"
                 style="width:100px;height:100px;border:0;">
        </a>

        <pre>
    I live in UAE
    I live in Philippines
    </pre>

    </body>
    </html>

------------------------------------------------

LECTURE #2

    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8" />
        <title></title>
    </head>
    <body style="background-color:lightgrey;">
        <h1>This is a heading</h1>
        <p>This is a paragraph.</p>

        <h1 style="color:blue;">This is a heading</h1>
        <p style="color:red;">This is aparagraph.</p>

        <h1 style="font-family:Verdana;">This a heading</h1>
        <p style="font-family:courier;">This is a paragraph.</p>

        <h1 style="font-size:300%;">This is a heading</h1>
        <p style="font-size:160%;">This is a paragraph.</p>

        <h1 style="text-align:center;">Centered Heading</h1>

    </body>
    </html>

    <!-- Write your comments here -->

------------------------------------------------

    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8" />
        <title></title>

            <link rel="stylesheet" href="name.css">
        <style>
            body *{
                text-align: center;
            }

            body {
                background-color: black;
            }

            h1 {
                text-align: center;
                font-size: 50px;
                color: lightpink;
            }

            #id1 {
                font-style: italic;
                color: aquamarine;
            }

            .class1 {
                font-style: unset;
                color: cyan;
            }

            div, p {
                color: white;
            }
        </style>

    </head>
    <body>
        <h1 id="id1">The heading have a id and font-size of 50</h1>
        <h2 class="class1">The heading have a font style of unset</h2>
        <div>
            <p>
                This paragraph is in div section and will have a text color of white
            </p>
        </div>


    </body>
    </html>

------------------------------------------------

LECTURE #3

    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8" />
        <title></title>
    </head>
    <body>

        <img src="C:\Users\Carmella Rei Van\Downloads\Download (1)\Wallpaper\wp7191324.png" style="width:42px;height:50px">

        <img src="C:\Users\Carmella Rei Van\Downloads\Download (1)\Wallpape\wp7191324.png" style="width:100px;height:100px;border:0;">

        <p><a href="#lec1">Jump to Chapter 1</a></p>
        <p><a href="#lec2">Jump to Chapter 2</a></p>
        <p><a href="#lec3">Jump to Chapter 3</a></p>
        <br /> <br /> <br /> <br /> <br /> <br /> <br />
        <br /> <br />
        <h2 id="lec1">Chapter 1</h2>
        <p>This chapter explains UAE</p>
        <br /> <br /> <br /> <br /> <br /> <br /> <br />
        <br /> <br />
        <h2 id="lec2">Chapter 2</h2>
        <p>This chapter about Dubai</p>
        <br /> <br /> <br /> <br /> <br /> <br /> <br />
        <br /> <br />
        <h2 id="lec3">Chapter 3</h2>
        <p>This chapter about Ajman</p>

        <a href="https://www.google.com/">
            <img src="C:\Users\Carmella Rei Van\Downloads\Download (1)\Wallpaper\wp7191324.png"
                 style="width:100px;height:100px;border:0;">
        </a>

        <table>
            <tr>
                <th>NAME OF UNIVERSITY</th>
                <th>LOCATION</th>
                <th>FIELD OF STUDY</th>
            </tr>
            <tr>
                <td>BSU</td>
                <td>RAK</td>
                <td>COMPUTING</td>
            </tr>
            <tr>
                <td>BSU</td>
                <td>RAK</td>
                <td>COMPUTING</td>
            </tr>
            <tr>
                <td>BSU</td>
                <td>RAK</td>
                <td>COMPUTING</td>
            </tr>
            <tr>
                <td>BSU</td>
                <td>RAK</td>
                <td>COMPUTING</td>
            </tr>
        </table>

        <style>
            table {
                font-family: arial, sans-serif;
                border-collapse: collapse;
                width: 100%;
            }

            td, th {
                border: 1px solid green;
                text-align: left;
                padding: 8px;
            }
            /* row can be even or odd*/
            tr:nth-child(even) {
                background-color: blueviolet;
            }
        </style>

        <table style="width:100%">
            <tr>
                <th>Name:</th>
                <td>Zainab Muhammad</td>
            </tr>
            <tr>
                <th rowspan="2">Telephone:</th>
                <td>056666</td>
            </tr>
            <tr>
                <td>05234</td>
            </tr>
        </table>

        <ul style="list-style-type:disc">
            <li>Coffee</li>
            <li>Tea</li>
            <li>Water</li>
        </ul>

        <ol type="I">
            <li>Coffee</li>
            <li>Tea</li>
            <li>Water</li>
        </ol>

    </body>
    </html>


------------------------------------------------

LECTURE #4 MENU BAR

    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="utf-8" />
        <title></title>
    </head>
    <body>

        <div class="menu">
            <a class="active" href="htmlpage.html">Home</a>
            <a href="contact.html">Contact Us</a>
            <a href="about.html">About Us</a>
        </div>
        <h1>This is the home page</h1>

        <style>
            .menu {
                background-color: cadetblue;
                overflow: hidden;
            }

                .menu a {
                    float: right;
                    color: white;
                    text-align: center;
                    padding: 15px 17px;
                    text-decoration: none;
                    font-size: 17px;
                }

                    .menu a:hover {
                        background-color: antiquewhite;
                        color: black;
                    }

                    .menu a.active {
                        background-color: darkcyan;
                        color: white;
                    }

            h1 {
                color: cadetblue;
            }

            footer {
                margin-top: 500px;
                background-color: cadetblue;
                overflow: hidden;
                color: white;
            }

            .footer {
                margin-top: 500px;
                background-color: cadetblue;
                overflow: hidden;
                color: white;
            }
        </style>

        <footer>
            <p>Author: XYZ </p>
            <p>
                <a href="mailto:info@example.com?subject=subject&cc=cc@example.com">mail link</a>
            </p>
        </footer>

        <div class="footer">
            <p>Author: XYZ </p>
            <p>
                <a href="mailto:info@example.com?subject=subject&cc=cc@example.com">mail link</a>
            </p>
        </div>

    </body>
    </html>




























