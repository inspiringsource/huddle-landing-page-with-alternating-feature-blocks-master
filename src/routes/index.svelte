<style land="scss">
    h1,
    h2,
    h3, 
    p {
        text-align: left;
        margin: 3rem;
        width: 26rem;
    }
  
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
        z-index: -1;
        height: 100%;
    }
    .nav-1{
        padding: 1em;
    }
    .nav-2{
        padding: 1em;
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
    box-shadow: 0 0 4px rgba(128, 128, 128, 0.567);
    border-color: white;

    margin-left: auto;
    }
    .try-btn:hover{
        box-shadow: 0 0 4px rgba(128, 128, 128, 0.167);
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
    .main-title{
        width: 21rem;
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
    .start-btn:hover{
    
        opacity: 65%;
        box-shadow: 0 0 25px rgba(36, 36, 36, 0.9);
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
        box-shadow: 0 0 12px rgba(36, 36, 36, 0.767);
        border-color: white;
        color: white;

        margin-left: auto;
        margin-right: auto;
        margin-top: -20px;
    }
    .footer-btn:hover{
        opacity: 65%;
        box-shadow: 0 0 25px rgba(36, 36, 36, 0.9);
    }
    .Box-1{

        grid-column: 1/3;
        background-color: white !important;  
       
    }
    .Box-1 > div{

        display: flex;

        grid-gap: 1em;
        text-align: center;
        justify-content: space-around;
        margin-top: 1rem;
        box-shadow: 0 0 5px rgba(128, 128, 128, 0.2);
        border-radius: 28px;
        background-color: rgb(255, 255, 255);
        border: 1px solid rgba(204, 204, 204, 0.534);
    }
    .main-img {
    width: 40%;
    display: block;
    margin-left: auto;
    margin-right: auto;

    }



    .Box-14{
        grid-column: 1/3;
        grid-row: 5/10;
        z-index: 10;
        width: 470px;
        height: 140px;
        justify-self: center;
        box-shadow: 0 0 5px rgba(128, 128, 128, 0.2);
        border-radius: 28px;
        background-color: rgb(255, 255, 255) !important;
        border: 1px solid rgba(204, 204, 204, 0.534);
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
        background-color: rgba(0, 37, 46, 1) !important;
        z-index: 1;
        height: 100%;
    }
    .Box-15 > div {
        
        background-color: transparent;
        height: 300px;
        /*width: 100%; */
        color: white;
        margin-top: 100px;
        padding: 2.5rem;


    }

    .footerLogo{
        -webkit-filter: brightness(0) invert(1);
        filter: brightness(0) invert(1); 
        padding: 1rem;
    }
    address {
        padding: 0.6rem;
    }
    .contacInfo{
        padding: 0.8rem;
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
    .footerinfolist a{
        color: white;
        text-decoration: none;
    }
    .footerinfolist a:hover{
        color: white;
        text-decoration: underline;
    }

    .rightFooter{
        display: flex;
        justify-content: center; /* align horizontal */
        align-items: center; /* align vertical */

    }

    
    .footerinfolist2 li{
        display: inline;
        margin-left: 1rem;  
        font-size: 2rem;
        color: white;
    }
    .footerinfolist2 li:hover{
        color: hsl(322, 100%, 66%);
    }
    .footerinfolist2 a{
        color:inherit;
    }
    .attribution{
        margin-top: 2rem;
    }
    
</style>

<div class="grid">
    <div class="header-bg"></div>
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

    </div>
         
    

    <div alt="Footer BG" class="Box-13">Box 13</div>

    <div class="Box-14">
        <h3>Ready To Build Your Community?</h3>
        <a class="footer-btn" href="www.frontendmentor.io">Get Started For Free</a>
    </div>
    <div class="Box-15">
        <div class="leftFooter"> <img class="footerLogo" src="logo.svg" alt="footer logo">
        

            <address>
                <img class="icons" src="/icon-location.svg" alt="location">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</address>
            <div class="contacInfo">
                <img class="icons" src="/icon-phone.svg" 
            alt="phone">
            +1-543-123-4567</div>
            <div>
                <img class="icons" src="/icon-email.svg" alt="email">
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
        <div class="rightFooter">
            <ul class="footerinfolist2">
                <li><a href=/#><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 20 20"><path d="M10 .4C4.698.4.4 4.698.4 10s4.298 9.6 9.6 9.6s9.6-4.298 9.6-9.6S15.302.4 10 .4zm2.274 6.634h-1.443c-.171 0-.361.225-.361.524V8.6h1.805l-.273 1.486H10.47v4.461H8.767v-4.461H7.222V8.6h1.545v-.874c0-1.254.87-2.273 2.064-2.273h1.443v1.581z" fill="currentColor"/></svg></a></li>
                
                
                <li><a href=/#><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 20 20"><path d="M10 .4C4.698.4.4 4.698.4 10s4.298 9.6 9.6 9.6s9.6-4.298 9.6-9.6S15.302.4 10 .4zm3.905 7.864c.004.082.005.164.005.244c0 2.5-1.901 5.381-5.379 5.381a5.335 5.335 0 0 1-2.898-.85c.147.018.298.025.451.025c.886 0 1.701-.301 2.348-.809a1.895 1.895 0 0 1-1.766-1.312a1.9 1.9 0 0 0 .853-.033a1.892 1.892 0 0 1-1.517-1.854v-.023c.255.141.547.227.857.237a1.89 1.89 0 0 1-.585-2.526a5.376 5.376 0 0 0 3.897 1.977a1.891 1.891 0 0 1 3.222-1.725a3.797 3.797 0 0 0 1.2-.459a1.9 1.9 0 0 1-.831 1.047a3.799 3.799 0 0 0 1.086-.299a3.834 3.834 0 0 1-.943.979z" fill="currentColor"/></svg> </a></li>


                <li><a href=/#><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 20 20"><path d="M13 10a3 3 0 1 1-6 0c0-.171.018-.338.049-.5H6v3.997c0 .278.225.503.503.503h6.995a.503.503 0 0 0 .502-.503V9.5h-1.049c.031.162.049.329.049.5zm-3 2a2 2 0 1 0-.001-4.001A2 2 0 0 0 10 12zm2.4-4.1h1.199a.301.301 0 0 0 .301-.3V6.401a.301.301 0 0 0-.301-.301H12.4a.301.301 0 0 0-.301.301V7.6c.001.165.136.3.301.3zM10 .4A9.6 9.6 0 0 0 .4 10a9.6 9.6 0 0 0 9.6 9.6a9.6 9.6 0 0 0 9.6-9.6A9.6 9.6 0 0 0 10 .4zm5 13.489C15 14.5 14.5 15 13.889 15H6.111C5.5 15 5 14.5 5 13.889V6.111C5 5.5 5.5 5 6.111 5h7.778C14.5 5 15 5.5 15 6.111v7.778z" fill="currentColor"/></svg></a></li>

                <footer class="attribution">
                    Challenge by
                <a href="https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100/hub/huddle-landing-page-with-alternating-feature-blocks-Xjm83bc1q" target="_blank">
                  Frontend Mentor
                </a>
                . Coded by
                <a href="https://www.frontendmentor.io/profile/inspiringsource" target="_blank">Avi B</a>
                </footer>
            </ul>
        </div>

    </div>

</div>