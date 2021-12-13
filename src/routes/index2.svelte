<div class="top-page">
    <nav class="top-nav">
        <div class="top-logo-div">
            <img src="logo.svg" alt="Huddle logo">
        </div>
        <div>
            <a class="try-btn" href="/#">Try It Free</a>
        </div>
    </nav>


    <div class="page-layout">
        <div class="left-div">
            <h1 class="main-title">Build The Community Your Fans Will Love</h1>
            <p>Huddle re-imagines the way we build communities. You have a voice, but so does your audience. Create connections with your users as you engage in genuine discussion.</p>
            <a class="start-btn" href="/#">Get Started For Free </a>
        </div>

        <div class="right-div">
            <img class="topimg" src="./illustration-mockups.svg" alt="Community">
        </div>
    </div>    
</div>



<main class="content">
    <div class="togather-section">
        <img class="togather-img mid-img" src="./illustration-grow-together.svg" alt="Grow Togathe">
        <div class="togather">
            <h2>Grow Togather</h2>
            <p>Grow Together Generate meaningful discussions with your audience and build a strong, loyal community. Think of the insightful conversations you miss out on with a feedback form.</p>
        </div>
    </div>
    <div class="conversation">
        <div class="mid-text">
            <h2>Flowing Conversations</h2>
            <p>You wouldn't paginate a conversation in real life, so why do it online? Our threads have just-in-time loading for a more natural flow.</p>
        </div>
        <img src="./illustration-flowing-conversation.svg" alt="Flowing Conversations" class="conv-img mid-img">
    </div>
</main>

<style>
:root {
  --primary-color: hsl(322, 100%, 66%);
  --pale-cyan: hsl(193, 100%, 96%);
  --dark-cyan: hsl(0, 0%, 79%);
  --grayish-blue: hsl(208, 11%, 55%);
    font-family: 'Open Sans', sans-serif;
    font-family: 'Poppins', sans-serif;
}
.top-page {
    background-image: url(./bg-hero-desktop.svg);
    background-color: var(--pale-cyan);
    display: flex;
    flex-direction: column;
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
}
nav {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
}
.page-layout{
    display: grid;
    grid-template-columns: repeat(2, 1fr);

}

.start-btn{
    background-color: var(--primary-color);
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


}
.main-title{
    max-width: 17ch;
}
.right-div{

    padding: 2rem;
}
@media (max-width: 800px) {

    .page-layout{
        flex-direction: column;

    }
    
    
    .left-div{
        width: 450px;
    }
    
    .start-btn{
        margin-left: auto;
        margin-right: auto;
    }
}


main {
    background-color: white;
    margin: 4rem;
    gap: var(--gap, 1rem);
    margin-top: 2rem;
    justify-content: space-between;
}
.togather-section {

    display: flex;
    flex-direction: row-reverse;;
    align-items: center;
    justify-content: center;
    padding: 2rem;
    box-shadow: 0 0 25px rgba(128, 128, 128, 0.116);
    border-color: rgba(255, 255, 255, 0.322);
    border-radius: 22px;
}

.mid-img {
    width: 40%;
    display: block;
    margin-left: auto;
    margin-right: auto;

    }


.togather{

    align-items: center;
    justify-content: center;                      
    transform: translate(0, 5%);
    margin: 8rem;
}

.conversation {
    display: flex;
    flex-direction: row-reverse;;
    align-items: center;
    justify-content: center;
    padding: 2rem;
    box-shadow: 0 0 25px rgba(128, 128, 128, 0.116);
    border-color: rgba(255, 255, 255, 0.322);

}
@media (max-width: 50rem) {
    .togather-section{

    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 2rem;
    }

    .conversation{
        flex-direction: column-reverse;
        align-items: center;
        justify-content: center;
        padding: 2rem;
    }
    
}


.mid-text{
    align-items: center;
    justify-content: center;                      
    transform: translate(0, 5%);
    width: 500px;
}
</style>