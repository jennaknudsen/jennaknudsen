## About Me

My name is Jonas Knudsen. I am 22 years old, and I am pursuing a bachelor's degree in Computer Science at Utah State University. 
I plan to graduate in December 2021. After graduation, I aspire to become a full-time, full-stack developer.

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jonasknudsen&layout=compact)](https://github.com/anuraghazra/github-readme-stats)
![My GitHub stats](https://github-readme-stats.vercel.app/api?username=jonasknudsen&hide_title=true&count_private=true&include_all_commits=true&hide_rank=true)

## Projects

<details>
 <summary>
Here are a few projects I am particularly proud of. 
 </summary>

### [Tetris](https://github.com/jonasknudsen/cs5410/tree/main/FinalProject-Tetris) 

<div> 
 <a href="https://docs.microsoft.com/en-us/dotnet/csharp/">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
 </a>
 <a href="https://dotnet.microsoft.com/">
  <img src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white" />
 </a>
 <a href="https://www.monogame.net/">
  <img src="https://img.shields.io/badge/MonoGame-D54B23?style=for-the-badge&logo=.net&logoColor=white" />
 </a>
</div>

<a href="https://github.com/jonasknudsen/cs5410/tree/main/FinalProject-Tetris">
 <img src="https://raw.githubusercontent.com/jonasknudsen/jonasknudsen/main/images/tetris-game.png" width="600" />
</a>

A Tetris game I created from scratch using C# and Monogame.
 
* The Tetris AI used in Attract Mode was based on results from Yiyuan Lee's Tetris AI training 
  (training details [here](https://codemyroad.wordpress.com/2013/04/14/tetris-ai-the-near-perfect-player/),
  GitHub repo [here](https://github.com/LeeYiyuan/tetrisai)).
* Game details:
  * Uses the [Original Nintendo scoring system](https://tetris.fandom.com/wiki/Scoring#Original_Nintendo_Scoring_System).
  * Uses [sticky gravity](https://tetris.fandom.com/wiki/Line_clear#Line_clear_gravity) on line clears.
  * New level reached after every 10 line clears.
* Persistent storage for this game stores high scores and control configs between sessions.
 
### [Lunar Lander](https://github.com/jonasknudsen/cs5410/tree/main/Assn3-LunarLander)

<div> 
 <a href="https://docs.microsoft.com/en-us/dotnet/csharp/">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
 </a>
 <a href="https://dotnet.microsoft.com/">
  <img src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white" />
 </a>
 <a href="https://www.monogame.net/">
  <img src="https://img.shields.io/badge/MonoGame-D54B23?style=for-the-badge&logo=.net&logoColor=white" />
 </a>
</div>
 
<a href="https://github.com/jonasknudsen/cs5410/tree/main/Assn3-LunarLander">
 <img src="https://raw.githubusercontent.com/jonasknudsen/jonasknudsen/main/images/lunar-lander-game.png" width="600" />
</a>

A Lunar Lander game I created from scratch using C# and Monogame. 
 
* Terrain for this game is generated using the [midpoint displacement algorithm](https://bitesofcode.wordpress.com/2016/12/23/landscape-generation-using-midpoint-displacement/).
* The lander's physics are calculated using a real-time physics simulation. 
  * Lander thrust acceleration: 7 m/s^2.
  * Moon's gravity acceleration: -1.62 m/s^2.
* Persistent storage for this game stores high scores and control configs between sessions.
 
### [Dan's Bagel Shop](https://github.com/jonasknudsen/cs3450-7even) 

<div>
 <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
 </a>
 <a href="https://www.w3.org/Style/CSS/Overview.en.html">
  <img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white" />
 </a>
 <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
 </a>
 <a href="https://www.djangoproject.com/">
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
 </a>
 <a href="https://www.python.org/">
  <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" />
 </a>
 <a href="https://www.sqlite.org/index.html">
  <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" />
 </a>
</div>

<a href="https://github.com/jonasknudsen/cs3450-7even">
 <img src="https://raw.githubusercontent.com/jonasknudsen/jonasknudsen/main/images/dans-bagel-shop.png" width="600" />
</a>

A website I created with two colleagues for a course project. It simulates a bagel shop from the perspective of 
a customer, an employee, a manager, and an owner. This webpage was created using the Django framework.

* Various actions such as customer/employee account creation, placing an order, adding more inventory stock,
  adding account funds to customer balances, etc. are supported.
  * Customer accounts can be created by anyone, but employee accounts must be created by a manager.
* The client sends various HTTP requests to the Django server, the Django server handles these requests using 
  Python programs, and the server returns a new webpage back to the client.
* This project uses an SQLite database to hold all information for customers, accounts, menu items, etc.

</details>

## Languages and Tools

<details>
 <summary>
  I am very proficient with these languages and tools and use them frequently.
 </summary>
<ul>
  <li> C# </li>
  <li> Java </li>
  <li> Android Studio </li>
  <li> Python </li>
  <li> HTML/CSS/JavaScript </li>
  <li> Anaconda/Juypter Notebook </li>
  <li> Ubuntu Server management using Bash and SSH </li>
  <li> Collaboration with other developers using Git and GitHub </li>
  <li> Developing using Windows, macOS, and Linux </li>
 </ul>
</details>

<details>
 <summary>
  In addition, I have used these languages and tools a moderate amount in the past.
 </summary>
 <ul>
  <li> Verilog </li>
  <li> C/C++ </li>
  <li> Kotlin </li>
  <li> Django </li>
  <li> D3.js </li>
  <li> Microsoft SQL Server </li>
 </ul>
</details>

## Interests

I am primarily interested in learning how to use:

* Node.js
* Docker
* Arduino

Outside of programming and software development, my interests include meal-prepping and playing competitive Super Smash Bros.

## Contact Me

I am best reached by email at jonas.a.knudsen@gmail.com.
