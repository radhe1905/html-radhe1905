<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        main{
            background-color: yellow;
            background-size: cover;
        }
        .highlight{
            background-color: yellow;
            padding:3px;

        }
        #text{
            padding: 10px;
            color: rgb(60, 184, 234);
           
        }
        #title{
            padding: 30px;
            font-size: large;
        }
        #details-container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: flex-start;
    width: 100%;
}

        @media (max-width: 800px) {
            #details-container {
                flex-direction: column;
                align-items: stretch;
            }
            #detail1, #detail2 {
                padding: 20px 10px;
                text-align: left;
                flex: unset;
            }
            #detail2 {
                text-align: left;
                padding-top: 0;
            }
            #title {
                padding: 20px 10px;
                font-size: medium;
            }
            #text {
                padding: 10px 5px;
            }
            header img {
                width: 100%;
                max-width: 300px;
                height: auto;
            }
        }
        #detail1 {
    padding: 50px;
    flex: 1;
    text-align: left;
}
        #detail2 {
    flex: 1;
    text-align: right;
    padding: 50px 50px 50px 0;
}
    </style>
</head>
<body>
    <header  align="center">
        <img src="https://upload.wikimedia.org/wikipedia/en/4/4c/Logo_of_Purnea_College_of_Engineering.png">
        <h1 style="color:rgb(109, 179, 237) ;font-size:x-large;"><big>PURNEA COLLEGE OF ENGINEERING,PURNEA</big></h1>
    <span class="highlight"><b>A SEMINAR REPORT ON</b></span><br>
    <div id="text"><b>CYBER SECURITY</b></div>
    <div id="title"><b>BACHELOR OF TECKNOLOGY
    </b><br>In <br><u><b>COMPUTER SCIENCE AND ENGINEERING</b> </u></div>
  
    <div id="details-container">
    <div id="detail1" align="left"><b>Submitted by : <br>NAME :RADHESHYAM KUMAR</b><br>Reg. No :- 24105131023 <br>Branch :- CSE <br> Semester :- 2<sup>nd</sup> <br>Session :- 2024-28</div>
    
    <div id="detail2" align="left"><b>Submitted to: <br>Prof. RAJU KUMAR</b><br>(H.O.D OF CSE) <br>Internal Examiner : <br>External Examiner</div>
    </div>
    
    
</body>
</html>
