<style>
    .grid{
        display: grid;
        /*grid-template-columns: repeat(3, minmax(200px, 1fr));*/
        grid-template-columns: repeat(2 1fr);
        /* grid-auto-rows: minmax(auto-fit, auto); */

        grid-gap: 1em;
        justify-items: stretch;
        align-items: stretch;
    }
    .grid > nav{
        display: grid;
        grid-template-columns: repeat(2, auto);
        grid-column: 1/3;
        grid-row: 1/3;
        background-color: orange;
        
        /* padding: 1em; */
        /*text-align: left;*/
        min-width: 100vw;
        margin-left: calc(50% - 50vw);
    }
    .header-bg{
        background-color: rgba(237, 251, 254, 1) !important;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-gap: 1em;
        grid-column: 1/3;
        grid-row: 1/4; /*you can overlap grids*/
        border: black solid 1px;;    
        z-index: -1;
        height: 100%;
    }
    .nav-1{
        padding: 1em;
        border: 1px solid black;
    }
    .nav-2{
        padding: 1em;
        border: 1px solid black;
        align-items: right;
        text-align: right;
        display: flex;
        justify-content: space-evenly;
    }


    .try-btn{
    background-color: white;
    border-radius: 22px;
    padding: 20px; 
    width: 130px;
    height: 5px; 
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    text-decoration: none;
    color: rgba(8, 36, 39, 1);
    box-shadow: 0 0 4px rgba(128, 128, 128, 0.267);
    border-color: white;

    margin-left: auto;
    }
    
    .grid > div{
        background-color: #eee;
        border: 1px solid transparent;
        padding: 1em;
        text-align: center;
    }
    .Box-2{
        grid-column: 1/3;
        grid-row: 3/4;
        background-color: transparent !important;
        text-align: center;
        min-width: 100vw;
        margin-left: calc(50% - 50vw);
    }
    .Box-2 > div{
        display: flex;
        background-color: transparent;
        grid-gap: 1em;

        justify-content: space-around;
    }
    .Box-2 p{
        text-align: left;
        font-size: 18px;
        width: 450px ;
    }
    .topimg{
        width:90%;
        height: auto;
    }
    .start-btn{
    background-color: hsl(322, 100%, 66%);
    border-radius: 28px;
    padding: 20px; 
    width: 250px;
    height: 10px; 
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
    text-decoration: none;
    color: rgba(8, 36, 39, 1);
    box-shadow: 0 0 5px rgba(128, 128, 128, 0.541);
    border-color: white;
    color: white;

    margin-left: auto;
    margin-right: auto;
    }
    .footer-btn{
        background-color: hsl(322, 100%, 66%);
        border-radius: 28px;
        padding: 20px; 
        width: 350px;
        height: 25px; 
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: center;
        text-decoration: none;
        color: rgba(8, 36, 39, 1);
        box-shadow: 0 0 5px rgba(128, 128, 128, 0.541);
        border-color: white;
        color: white;

        margin-left: auto;
        margin-right: auto;
        margin-top: -20px;
    }
    .Box-1{

        background-color: blueviolet !important;
        
        grid-column: 1/3;  
       
    }
    .Box-1 > div{

        display: flex;
        background-color: #eee;
        border: 1px solid #ccc;
        grid-gap: 1em;
        text-align: center;
        justify-content: space-around;
    }
    .main-img {
    width: 40%;
    display: block;
    margin-left: auto;
    margin-right: auto;

    }



    .Box-14{
        grid-column: 1/3;
        grid-row: 7/10;
        z-index: 10;
        width: 470px;
        height: 140px;
        justify-self: center;
    }
    .Box-14 h3{
        text-align: center;
        font-size: 20px;
        color: black;
        margin-top: 15px;
        margin-bottom: 50px;

    }
    /* footer background */
    .Box-13{
        display: grid;
        grid-gap: 1em;
        grid-column: 1/3;
        grid-row: 9/10; /*you can overlap grids*/  
        background-color: blue !important;
        z-index: -1;
        height: 100%;
        min-width: 100vw;
        margin-left: calc(50% - 50vw);
    }
    .Box-15{
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-gap: 1em;
        grid-column: 1/3;
        grid-row: 9/10; /*you can overlap grids*/
        border: black solid 1px;;    
        background-color: green !important;
        z-index: 1;
        height: 100%;
    }
    .Box-15 > div {
        
        background-color: red;
        height: 300px;
        /*width: 100%; */

    }
    .footerLogo{
        -webkit-filter: brightness(0) invert(1);
        filter: brightness(0) invert(1); 
    }
    .midFooter{
        display: flex;
        justify-content: center; /* align horizontal */
        align-items: center; /* align vertical */

    }
    .footerinfolist{
        list-style-type: disc;
        -webkit-columns: 2;
        -moz-columns: 2;
        columns: 2;
        list-style-position: inside;
        list-style-type: none;
    }

</style>

<div class="grid">
    <div class="header-bg">Box 13</div>
    <nav>
        <div class="nav-1">
            <img src="logo.svg" alt="header logo">
        </div>
        <div class="nav-2">
            <a class="try-btn" href="www.frontendmentor.io">Try It Free</a>
        </div>
    </nav>
    <div class="Box-2">
        <div class="page-layout">
            <div class="left-div">
                <h1 class="main-title">Build The Community Your Fans Will Love</h1>
                <p>Huddle re-imagines the way we build communities. You have a voice, but so does your audience. Create connections with your users as you engage in genuine discussion.</p>
                <a class="start-btn" href="www.frontendmentor.io">Get Started For Free </a>
            </div>
    
            <div class="right-div">
                <img class="topimg" src="./illustration-mockups.svg" alt="Community">
            </div>
        </div>     
    </div>  
    <div class="Box-1">
        <div>
            <div class="Box-3">
                <h2>Grow Togather</h2>
                <p>Grow Together Generate meaningful discussions with your audience and build a strong, loyal community. Think of the insightful conversations you miss out on with a feedback form.</p>
            </div>
            <div class="Box-4"><img class="togather-img main-img" src="./illustration-grow-together.svg" alt="Grow Togathe"></div> 
        </div>
        <div>
            <div class="Box-5">
                <img class="flowing-img main-img" src="./illustration-flowing-conversation.svg" alt="Flowing-conversation">
            </div>
            <div class="Box-6">
                <h2>Flowing Conversations</h2>
                <p>You wouldn't paginate a conversation in real life, so why do it online? Our threads have just-in-time loading for a more natural flow. </p>
            </div>
        </div>
        <div>
            
            <div class="Box-7">
                <h2>Your Users </h2>
                <p>It takes no time at all to integrate Huddle with your app's authentication solution. This means, once signed in to your app, your users can start chatting immediately.</p>
            </div>
            <div class="Box-8">
                <img class="users-img main-img" src="./illustration-your-users.svg" alt="Your-Users">
            </div>
        </div>
        <div>
            <div class="Box-9">Box 9</div>
            <div class="Box-10">Box 10</div>
        </div>
    </div>
         
    

    <div alt="Footer BG" class="Box-13">Box 13</div>

    <div class="Box-14">
        <h3>Ready To Build Your Community?</h3>
        <a class="footer-btn" href="www.frontendmentor.io">Get Started For Free</a>
    </div>
    <div class="Box-15">
        <div> <img class="footerLogo" src="logo.svg" alt="footer logo">
        

            <address>
                <img class="icons" src="static/icon-location.svg" alt="location">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</address>
            <div>
                <img class="icons" src="static/icon-phone.svg" 
            alt="phone">
            +1-543-123-4567</div>
            <div>
                <img class="icons" src="static/icon-email.svg" alt="email">
                example@huddle.com</div>
        </div>
        <div class="midFooter">

            <ul class="footerinfolist">
                <li><a href=/#>About Us</a></li>
                <li><a href=/#>What We Do</a></li>
                <li><a href=/#>FAQ</a></li>

                <li> <a href=/#>Career</a></li>
                <li><a href=/#>Blog</a></li>
                <li><a href=/#>Contact Us</a></li>
            </ul>

        </div>
        <div>footer3</div>

    </div>
</div>