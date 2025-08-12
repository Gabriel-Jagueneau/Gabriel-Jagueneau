# Hi there 👋

<p align="left">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />

  <br>
  
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
</p>

---

<div class="contained">
    <div class="line"></div>
    <div class="parags">

        <div class="inner">
            <div class="date">2005</div>
            <div class="parag">
                <div class="text">
                    <span class="bigger">Hello!</span>   <br>
                    My name is <span class="highlight-ang">Gabriel Jagueneau</span> <i class="smaller">(as you may have noticed already..)</i>
                </div>
            </div>
        </div>
        
        <div class="inner">
            <div class="date">2019</div>
            <div class="parag">
                <div class="text">
                    I started getting interested in coding in the early 2019, with a game called <i class="link" onclick="window.open('https://starblast.io/', '_blank');">Starblast.io</i>.  <br>
                    This game allows users to create custom game modes using a proprietary JavaScript editor.  <br>
                    This is where I developed much of my foundational knowledge in programming.
                </div>
                <div class="events">
                    <div class="mention smaller">National Brevet Diploma</div>
                </div>
            </div>
        </div>
        
        <div class="inner">
            <div class="date">2022</div>
            <div class="parag">
                <div class="text">
                    Around 2022, I started messing around websites for the first time.  <br>
                    This is where my passion for web development really started.  <br>
                    Since then, I’ve built numerous websites, including several commissioned by friends of mine.
                </div>
            </div>
        </div>

        <div class="inner">
            <div class="date">2023</div>
            <div class="parag">
                <div class="events">
                    <div class="mention smaller">French Baccalauréat</div>
                </div>
            </div>
        </div>

        <div class="inner">
            <div class="date">2024</div>
            <div class="parag">
                <div class="events">
                    <div class="mention smaller"><div class="highlight">60</div> eCTS Credit Certificate</div>
                </div>
            </div>
        </div>

        <div class="inner">
            <div class="date">2025</div>
            <div class="parag">
                <div class="text">
                    In July 2025, after successfully passing my preparatory exams and enrolling in an engineering school in Bordeaux.  <br>
                    My goal is to earn a double degree after my 3 years: an engineering diploma and a master’s degree in biology.
                </div>
                <div class="events">
                    <div class="mention smaller"><div class="highlight">120</div> eCTS Credit Certificate</div>
                </div>
            </div>
        </div>

        <div class="inner">
            <div class="date">2028</div>
            <div class="parag">
                <div class="text">
                    I wish in the future, after my getting my double degree,  <br>
                    to continue both programming and agronomy, to achieve my ambitious goals.
                </div>
            </div>
        </div>
    </div>
</div>

<style>
.contained {
    display: flex;
    flex-direction: row;
    gap: 20px;
    height: 750px;
}
.contained .line {
    display: flex;
    height: 105%;
    padding-left: 4px;
    padding-right: 4px;
    border-radius: 10px;
    background: linear-gradient(180deg, #eeff00 0%, #00aeff 45%, #ff00f2 90%, transparent 100%);
}
.contained .parags {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.contained .parags .inner {
    position: relative;
    display: flex;
    flex-direction: row;
    align-items: center;
}
.contained .parags .inner .date {
    position: absolute;
    left: -54px;
    min-width: 60px;
    padding: 4px 10px;
    background-color: rgba(81, 82, 83, 0.3);
    border: 1px rgba(65, 67, 68, 0.15) solid;
    backdrop-filter: blur(5px);
    border-radius: 10px;
    text-align: center;
    font-weight: 600;
    color: white;
}
.contained .parags .inner .parag {
    display: flex;
    flex-direction: column;
    gap: 5px;
    margin-left: 2vw;
    width: 70vw;
}
.contained .parags .inner .parag .text {
    font-size: 20px;
}
.contained .parags .inner .parag .link {
    cursor: pointer;
    color: #0077ff;
}
.contained .parags .inner .parag .link:hover {
    text-decoration: underline;
}
.contained .parags .inner .parag .bigger {
    font-size: 28px;
    font-weight: 600;
}
.contained .parags .inner .parag .smaller {
    font-size: 16px;
    color: rgba(240, 248, 255, 0.598);
}
.contained .parags .inner .parag .events {
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 8px;
}
.contained .parags .inner .parag .events .mention {
    display: flex;
    flex-direction: row;
    background-color: rgba(81, 82, 83, 0.3);
    border: 1px rgba(65, 67, 68, 0.15) solid;
    backdrop-filter: blur(5px);
    width: fit-content;
    padding: 3px 8px;
    border-radius: 10px;
    gap: 5px;
}
</style>
