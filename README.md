# HTML-CSS-PROJECT-CLONE
clone website  of sales force
(HTML)--
<html >
<head>
    <link
    href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css"
    rel="stylesheet"
/>
    <link rel="stylesheet" href="style.css">
    <title>SalesForce</title>
</head>
<body>
   <div id="main">
    <div id="header">
        <div id="image">
            <img src="https://a.sfdcstatic.com/shared/images/c360-nav/salesforce-with-type-logo.svg">
        </div>
        <div class="texts"><P>Products</P></div>
        <div class="texts"><p>Industries</p></div>
        <div class="texts"><p>Customers</p></div>
        <div class="texts"><p>Learnings</p></div>
        <div class="texts"><p>Suport</p></div>
        <div style="display: flex;" class="texts"><p>More</p>
            <i class="ri-arrow-down-s-line"></i>
           
        </div>
        <div id="contact">
            <p><u>Contact Us</u></p>
            <p>128-1233-123</p>
        </div>
        <div class="icon"><i class="ri-search-line"></i></div>
        <div class="icon"> <i class="ri-global-line"></i></div>
        <div style="display: flex;" class="icon" id="log"><i class="ri-user-fill"></i>
            <p>login</p>
        </div>

        <div id="try">Try For Free</div>

    </div>
    <div id="fakeheader"></div>
    <div id="page1">
        <div id="strip">
            <p>JUST ANNOUNCED: See why Gartner® recognised Salesforce as a Leader in Customer Data Platforms.
            </p>
            <U>Read the report</U>
        </div>
        <div id="content">
            <div id="c1">
               <h1>  Try Salesforce <br> Starter Suite for <br>free.</h1>
               <p>Unite marketing, sales, and service in a single app. Try Salesforce Starter Suite today. There's nothing to install. No credit card required.</p>
               <div  id="button">
                <div id="b1">Start Free trial</div>
                <div id="b2">Watch Demo</div>
               </div>
                 </div>
            <div id="c2">
                <img id="m1" src="https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcT8s8XWJjiQpPjPZBKbZqnzUUATtM8wzL3jp9sY_5GAMJULVMSl">
                <img id="m2" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQxAfIcV9a6XW7Q_iMvUO1rRgmeOVEaH51yBz1GX2w7ff8Q4d1">1
            </div>
            
        </div>
        <div id="lowerheading"><h1>Learn what Salesforce products can do for you.</h1></div>
    </div>
    <div id="page2">
        
        <div class="card" id="card1">
            <img class="image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRDn4JhwoQoZktVERKAEHxLhgNaxYeWF1ws1LzU9gJA5qwVU5h7">
            <h2 class="h2">  Small Business</h2>
            <p class="para">Sales, service, and email <br>outreach tools in a single app.</p>
            <p class="para2" id="p2"><u>learn more</u></p>
        </div>
        <div class="card" id="card2">
            <img class="image" src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcTfwY0Ea-vF8DQCT_G8nFyM7GeAa5Crfv5WqpdwvkJnunf3AcTH">
            <h2 class="h2">  Sales Cloud</h2>
            <p class="para">Close more deals and speed<br> up growth with the #1 CRM.</p>
            <p class="para2" id="p3"><u>learn more</u></p>

        </div>
        <div class="card" id="card3">
            <img class="image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZskA_7gf8d3vEXweVkftnEmhTqr2bDs5xCUs8mBLuHmtoh-9x">
            <h2 class="h2">Service Cloud</h2>
            <p class="para">Make customers happy faster<br> and build loyalty with Service<br> Cloud.</p>
            <p class="para2"><u>learn more</u></p>
        </div>
        <div class="card" id="card4">
            <img class="image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSghPXmQldNaIp_q-OBr-S7TTsRu4JDShKT-JGfVns1GJUbWc_7">
            <h2 class="h2">Marketing Cloud</h2>
            <p class="para">Build customer relationships <br>for life with data-first digital<br> marketing.</p>
            <p class="para2"><u>learn more</u></p>
        </div>
        <img id="lastimg" src="https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcReg3ME7COx2Rr45PJNmwoPDx62ICk8ZkgAGcg-I9CTlxk_wbph">
       
    </div>
   </div>
    
</body>
</html>
/////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
(CSS)--

*{
    margin: 0%;
    padding: 0%;
}
#main{

}
#header{
    z-index: 100;
    background-color: white;

    display: flex;
    align-items: center;
    position: fixed;
    justify-content: space-around;
    width: 100%;
    height: 10%;
}
#fakeheader{
    width: 100%;
    height: 10%;
    
}
#page1{
    width: 100%;
    height: 90%;
    
}
#page2{
    width: 100%;
    height:90%;
    background-color: white;
}
#image{
    
    margin: 10px;
    width:68px ;
    height: 42px;
}

.texts{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: rgb(6, 85, 103);
}
.texts:hover{
    color: rgb(67, 158, 158);
}
#contact{
    color: rgb(30, 141, 34);
    font-weight: lighter;
}
#try{
    border-radius: 5px;
    padding-left: 10px;
    padding-left: 10px;
    padding: 10px;
    background-color: rgb(58, 164, 58);
}
#try:hover{
    background-color: rgb(24, 105, 24);
}
.icon{
    padding: 10px;    
}
#log:hover{
    background-color: rgb(22, 188, 207);
    border-radius: 5px;

}
.icon:hover{
    background-color: rgb(34, 147, 147);
    border-radius: 50%;
}
#strip{
    font-size: large;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: rgb(5, 5, 96);
    color: white;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    width: 100%;
    height: 7%;
}
#strip U{
    margin-left: 15px;
}
#content{
    display: flex;
    width: 100%;
    height: 76%;
    /* background-color: aqua; */
}
#lowerheading{
    font-weight: 500;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: rgb(6, 6, 132);
    display: flex;
    align-items: center;
    justify-content: center;

    width: 100%;
    height: 16%;
    
}
#d1{
    margin-top: 50px;
    font-size: larger;
    
}
#d2{
    translate: 7px;
}
#d3{
    translate: -55px;
}


#c1{
    
    margin: 30px;
    margin-left: 15%;
    
   
    color: rgb(7, 7, 123);
    text-align: center;
    font-size: xx-large;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    
    
    width: 40%;
    height: 90%;
    /* background-color: rgb(175, 28, 28); */
}
#c2{
    overflow: hidden;
    width:50%;
    height: 100%;
    /* background-color: chartreuse; */
}
#m1{
    border-radius: 25px;
    position: absolute;
width: 50%;
height: 60%;
object-fit: cover;
}
#m2{
    border-radius: 17px;
    position: absolute;
    
    margin-top:85px;
    display: flex;
    align-items: center;
    justify-content: center;
    /* position: fixed; */
    width: 30%;
    height: 38%;
    object-fit: cover;
}


#c1 h1{
    font-weight: lighter;
    margin-bottom: 15px;
    text-align: center;
}
#button{
    display: flex;
    margin-top: 25px;
    

}
#b1{
    padding: 15px;
    border-radius: 6px;
    margin: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: large;
    color: white;
background-color: rgb(21, 101, 147);
width: 140px;
}
#b1:hover{
    background-color: rgb(9, 64, 92);
}
#b2{
    padding: 15px;
    border-radius: 6px;
    margin: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: large;
    color: rgb(2, 84, 131);
background-color: rgb(240, 248, 252);
border-style: solid;
border-color:rgb(2, 84, 131); ;
width: 140px;
    }
    #b2:hover{
        background-color: rgb(195, 191, 191);
        color: rgb(4, 40, 61); 
        border-color: rgb(4, 40, 61); 
    }
    #page2{
        display: flex;
        align-items: center;
        justify-content: center;
    }
    
    .image{
        width: 100%;
        height: 37%;
        object-fit: cover;
    }
     .h2{
        color: rgb(7, 7, 123);
        margin-top: 50px;
        margin-left: 30px;
        

     }
    
    .para{
        border-radius: 10px;
       font-weight: lighter;
        font-size: large;
        margin-top: 16px;
        margin-left: 30px;
    }
   
    .para2{
        font-size: large;
        font-weight: normal;
        color: rgb(5, 5, 99);
        width: 50%;
         padding-top: 35px;
         margin-left: 30px;
    
    }
    .para2:hover{
        color: rgb(23, 100, 173);

    }
    
     
    .card{
        z-index: 80;
        border-radius: 25px;
        margin: 20px;
        width: 17%;
        height: 50%;
        background-color: white;

    }
    #lastimg{
        position: absolute;
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
