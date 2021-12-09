<div class="top-page">
    <nav>
        <img src="logo.svg" alt="Huddle logo">
        <a class="try-btn" href="/#">Try It Free</a>
    </nav>
    <div class="page-layout">
        <div class="left-div">
            <h1 class="main-title">Build The Community Your Fans Will Love</h1>
            <p>Huddle re-imagines the way we build communities. You have a voice, but so does your audience. Create connections with your users as you engage in genuine discussion.</p>
            <a class="start-btn" href="/#">Get Started For Free </a>
        </div>

        <div class="right-div">
            <img class="topimg" src="illustration-mockups.svg" alt="Community">
        </div>
    </div>    
</div>



<main class="content">
    <div class="togather">
        <h2>Grow Togather</h2>
        <p>Grow Together Generate meaningful discussions with your audience and build a strong, loyal community. Think of the insightful conversations you miss out on with a feedback form.</p>
    </div>

</main>

<style lang="scss";>
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
}
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1rem;
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
.page-layout{
    display: flex;
    gap: var(--gap, 1rem);
    
}
.left-div{
    max-width: 510px;
    padding: 2rem;
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
@media (max-width: 45rem) {
    .page-layout{
        display: block;
    }
}

main {
    background-color: white;
}
</style>