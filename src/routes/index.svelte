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
    height: 13px; 
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
    .Box-14{
        grid-column: 1/3;
        grid-row: 7/10;
        z-index: 10;
        width: 300px;
        height: 100px;
        justify-self: center;
        

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
        height: 100%;
        /*width: 100%; */

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
            <div class="Box-3">Box 3</div>
            <div class="Box-4">Box 4</div> 
        </div>
        <div>
            <div class="Box-5">Box 5</div>
            <div class="Box-6">Box 6</div>
        </div>
        <div>
            
            <div class="Box-7">Box 7</div>
            <div class="Box-8">Box 8</div>
        </div>
        <div>
            <div class="Box-9">Box 9</div>
            <div class="Box-10">Box 10</div>
        </div>
    </div>
         
    

    <div class="Box-13">Box 13</div>

    <div class="Box-14">Box 14</div>
    <div class="Box-15">
        <div>footer1</div>
        <div>footer2</div>
        <div>footer3</div>

    </div>
</div>