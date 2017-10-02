<template>
  <section>
    <div class="container-body">
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
    <div class="container-body">
      <div class="body">
        <div class="profile-about">
          <img src="/15_by_15 orthogonal maze.svg" alt="maze" class="profile resize"/>
          <div class="about">   
            <h2 class="title">
              About
            </h2>
            <div class="content">
              Squid fixie live-edge, quinoa banh mi echo park 8-bit bespoke selfies chartreuse asymmetrical pug. Poutine jianbing leggings wolf snackwave, synth man bun swag. Intelligentsia meh fanny pack keffiyeh truffaut, austin kickstarter pop-up fashion axe typewriter retro narwhal coloring book vegan. Listicle PBR&B twee mixtape vegan kitsch gastropub vaporware asymmetrical venmo jean shorts authentic bespoke prism. Farm-to-table mustache stumptown gochujang.
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
        </div>
      </div>
    </div>
  </section>
</template>
<style>
.header{ 
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  font-weight: 100;
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
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
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
  width:60%;
}
.italic{
  font-style: italic;
}
img.resize{
  max-width: 13em;
  max-height: 13em;
}
</style>
