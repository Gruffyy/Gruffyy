<div style="background-color: #f5f5f5; padding: 30px; font-family: 'Arial', sans-serif; border-radius: 10px;">
  <div align="center">
    <h1 style="color: #24292e; font-size: 3em; margin-bottom: 0;">Greetings mortals 👋, I'm Gruffyy</h1>
    <h3 style="color: #586069; font-size: 1.5em;">Fullstack Dev from Finland! Always learning something new! Open source and Linux advocate. <br> Also a rustacean!</h3>  
  </div>

  <p align="center" id="quote"></p>

  <p align="center">
    <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=gruffyy&theme=onedark" alt="gruffyy" /></a>
  </p>

  <div style="display: flex; justify-content: space-around; margin-bottom: 30px;">
    <div>
      <h3 style="color: #24292e;">Languages and Tools:</h3>
      <p style="display: flex; flex-wrap: wrap; justify-content: center;"> 
          <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40" style="margin: 5px;"/> 
      </p>
    </div>
    <div>
      <p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=gruffyy&show_icons=true&locale=en&layout=compact&theme=dark" alt="gruffyy" /></p>
    </div>
  </div>

  <div style="display: flex; justify-content: center;">
    <img src="https://github-readme-stats.vercel.app/api?username=gruffyy&show_icons=true&locale=en&theme=dark" alt="gruffyy" style="margin-right: 20px;" />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=gruffyy&theme=dark" alt="gruffyy" />
  </div>
  
  <script>
  // Wait for the DOM to load before executing the script
  document.addEventListener("DOMContentLoaded", function() {

    const quotes = [
      "The only way to do great work is to love what you do. - Steve Jobs",
      "Strive not to be a success, but rather to be of value. - Albert Einstein",
      "Your time is limited, so don't waste it living someone else's life. - Steve Jobs"
    ];
    const quoteElement = document.getElementById("quote");
    let currentQuoteIndex = 0;

    function displayQuote() {
      quoteElement.textContent = quotes[currentQuoteIndex];
      currentQuoteIndex = (currentQuoteIndex + 1) % quotes.length;
    }

    displayQuote(); 
    setInterval(displayQuote, 5000); 

  });
  </script>

</div>
