<template>
  <section class="all-content">
    <div class="container-body font-gill">
      <div class="body">
        <h1 class="header">
          RICHARD MICHELS
        </h1>
        <p class="italic">
          Software developer
        </p>
      </div>
    </div>
    </br>
    <div class="container-body font-gill">
      <div class="body">
        <div class="profile-about">
        <div class="outsideWrapper">
          <div class="insideWrapper">
            <img src="/15_by_15 orthogonal maze.svg" alt="maze" class="profile resize"/>
            <canvas id="mazeCanvas"></canvas>
          </div>
        </div>
          <div class="about">   
            <h2 class="title mobile-margin-top">
              About
            </h2>
            <div class="content">
            Objectively innovate empowered manufactured products whereas parallel platforms. Holisticly predominate extensible testing procedures for reliable supply chains. Dramatically engage top-line web services vis-a-vis cutting-edge deliverables.
            </div>
          </div>
        </div>
        </br>
        </br>
        </br>
        <div>
          <h3 class="title">
            Experience
          </h3>
          </br>
          <h4>
            Blue Corner Solutions (2016-now)
          </h4>
          </br>
          <p class="italic">
            Lead software developer
          </p>
          </br>
          <ul>
            <li class="content">
              Leverage agile frameworks to provide a robust synopsis for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition. Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment.
            </li>
            <li class="content">
              Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.
            </li>
            <li class="content">
              Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide with additional clickthroughs from DevOps. Nanotechnology immersion along the information highway will close the loop on focusing solely on the bottom line.
            </li>
          </ul>
          </br>
          </br>
          </br>
          <h3 class="title">
            Story
          </h3>
          <div class="content">
                        I am a relative newcomer to software development who has 
attained a position in the field driven by my passion 
for technology. My journey has taken me from earning a BA 
in Film to working at Yellowstone National Park, to delivering 
coffee in Manhattan, to attending Fullstack Academy of Code in NYC
and eventually being hired as a full time developer. In my current 
position I work autonomously and independently
across the stack supporting existing application deployments 
and implementing new custom features. I am currently looking to 
join and learn from a strong core of diverse engineers. 
I believe the next step in my journey is to gain as much knowledge 
as possible from an experienced mentor and offer my own dedicated
work ethic. 
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
#mazeCanvas{
  position:absolute;
}

.all-content{
  margin-top:2em;
  margin-bottom:2em;
}
.header{ 
  font-weight: 500;
  letter-spacing: 5px;
  font-size:50px;
  text-align:justify;
  margin-top:.5em;
}
.container-body{
  display: flex;
  width:100%;
  height:100%;
  justify-content: center;
}
.body{
  display:flex;
  justify-content: center;
  flex-direction:column;
  width:55%;
  height:auto;
}
.menu{
  width:20%;
  height:100px;
}
.nav{
  display:flex;
  justify-content: center;
  width:55%;
  height:auto;
  text-align:right;
}
.nav-menu{
  width:90%;
  position:relative;
  top:50%;
  transform: translateY(-18px);
}
.title{
  display: block;
  font-weight: 200;
  font-size:30px;
  letter-spacing: 5px;
  border-bottom:1px solid;
}
.content{
  margin-top: 1em;
  text-align:justify;
  font-size:13px;
  line-height: 200%;
}
.profile-about{
  display:flex;
  justify-content:space-between;
  flex-direction: row;
}

.grey{ 
  background-color:gray;
}
.blue{
  background-color:blue;
}
.red{
  background-color:red;
}
.profile{
  background-color: gray;
}
.about{
  width:70%;
}
.italic{
  font-style: italic;
}
img.resize{
  align-self: center;
}
.font-gill{
  font-family: Gill Sans Extrabold, sans-serif;  
}

@media (max-width:1600px){
  .about{
    width:60%;
  }
}

@media (max-width:1400px){
  .about{
    width:50%;
  }
}

@media (max-width:1200px){
  .about{
    width:40%;
  }
}

@media (max-width:1000px){
  .about{
    width:30%;
  }
}

@media (max-width:768px){
  .profile-about{
    flex-direction:column
  }
  .about{
    width:100%;
  }
  .body{
    width:70%;
  }
  .mobile-margin-top{
    margin-top: 1em;
  }
}
</style>
