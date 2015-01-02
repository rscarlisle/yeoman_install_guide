<!DOCTYPE html>
<html lang="en">
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <meta http-equiv="Content-Style-Type" content="text/css">
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="">
  <meta name="author" content="">
  <title>Randall Carlisle</title>
  <style type="text/css">
    p.p1 {margin: 20.0px 0.0px 0.0px 0.0px; font: 12.0px Helvetica; color: #333233; min-height: 0.0px}
    p.p2 {margin: 10.0px 0.0px 0.0px 0.0px; font: 14.0px Helvetica; color: #333233; background-color: yellow; min-height: 0.0px}
    li.li1 {margin: 0.0px 0.0px 0.0px 0.0px; font: 18.0px Helvetica; color: #333233}
    li.li2 {margin: 0.0px 0.0px 0.0px 0.0px; font: 18.0px Helvetica; color: blue;}
    span.s1 {color: #ff0000}
    ul.ul1 {list-style-type: check}
    .jumbotron {padding: 100px!important;}
  </style>

    	<link rel="stylesheet" type="text/css" href="css/bootstrap.css">
	<!-- Latest compiled and minified CSS -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css">

	<!-- Optional theme -->
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap-theme.min.css">

	<!-- Latest compiled and minified JavaScript -->
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/js/bootstrap.min.js"></script>
</head>

<body>
    <div class="container">
    <nav class="navbar navbar-inverse navbar-fixed-top">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="#">Randall Carlisle - full stack web guy</a>
        </div>
        <div id="navbar" class="navbar-collapse collapse">
          <form class="navbar-form navbar-right">
            <div class="form-group">
              <input type="text" placeholder="Email" class="form-control">
            </div>
            <div class="form-group">
              <input type="password" placeholder="Password" class="form-control">
            </div>
            <button type="submit" class="btn btn-success">Sign in</button>
          </form>
        </div><!--/.navbar-collapse -->
      </div>
    </nav>
   </div>
   
   <div class="jumbotron">
      <div class="container">
      <h2>Installing Yeoman Correctly, The First Time</h2>
<p class="p1">"Installations are tricky. Just like deployments. You read an article or see a cool video on how to use cutting edge tools to optimize Javascript workflow development, and you decide to try it out. Suddenly it's 10 hours later and 3am in the morning, and you're completely lost in the woods! Somehow, the project that you were told was so simple, has totally wasted 10 hours of your life. You know, 10 hours here and another 10 there - really starts to add up!"</p>

<p class="p1">I'm writing the article I wish I had read before whimsically deciding to install Yeoman. Let's assume you're eager to get Yeoman installed on your Mac and don't have the luxury of burning 10 hours of time.<span class="Apple-converted-space"> </span></p>
<h3>Project Checklist:</h3>
<ul class="ul1">
  <li class="li1">System requirements - check the version of OS X. Some versions may be incompatible with a Yeoman install.</li>
  <li class="li1">List of software - brew, npm, nodejs, yeoman, bower, grunt. Check current and latest versions.<span class="Apple-converted-space"> </span></li>
  <li class="li1">Project management - create a project folder test purposes. Plus, track time with project mgt s/w ie chrometa &amp; trello.</li>
  <li class="li1">CLI navigation - know how to work from the command line, creating and editing configuration files and symlinks, etc.</li>
  <li class="li1">Permissions - should you be using sudo, and if so, what potential problems does it introduce? Better alternative(s)?</li>
  <li class="li1">Help resources - Stackoverflow, groups &amp; community help, helpful links and search strings… Post questions, bugs…</li>
  <li class="li1">Document tasks - logging your experiences, insights, terminal activity log, challenges, defeats, and victories.<span class="Apple-converted-space"> </span></li>
  <li class="li1">Time management - did you complete the install within a reasonable time frame - time expectations met?</li>
  <li class="li1">Conclusion - did this article properly guide you successfully through the install process? Are you confident? Pleased?</li>
  <li class="li2">Time/cost required to complete project - estimated @ 5 hours ~> professional time invested @ $500.</li>
</ul>

<p class="p1">My Macbook Pro 2009 is snow leopard - 10.6.8. Does my Mac meet the system requirements for installing Yeoman? If the answer is yes, I'm good to go. If not, I just saved myself a day of wasted time and frustration. Where are the best places to get that question answered? [<span class="s1">research this step, and return with details and answers…</span>].</p>
<p class="p1">While confirming system requirements you can also confirm the software you will need. Is there a different combination?</p>
<p class="p1">Sticking to my current list of software, I need to talk about software used to install target software. I was a bit unclear as to whether I should install with Brew or npm, etc. In other words, there are times when a stackoverflow answer says to install with a different software from your main instructions. So, you're following different advice, and may possibly be changing configuration files and adding to your troubles. This suggests that you have a good idea what brew<span class="Apple-converted-space">  </span>or npm does…</p>
<p class="p1">Looking at the list of softwares to be used, you'll want to review the basics of each principal software. You'll also want to understand each software from a configuration level, as well as how these softwares will integrate and play together. My suggestion would be to read up on these softwares while you're waiting for replies to your support tickets. You're already starting to understand what the most important questions are, and that will guide your decisions on what to read.<span class="Apple-converted-space"> </span></p>
<p class="p1">If your time is worth $100 an hour, you're investing $1,000 in any project that takes up 10 hours of your time and energy. You need to be able to confidently expect that your results will be several times greater than the time you invested. It is said and understood that in order to achieve an outcome, you need to measure time, resources, and effort. I agree, and use chrometa, nama, uml, git, mockingbird, and trello to manage this project. The vendors will also roved ideas &amp; support.</p>
<p class="p1">How does this software save you time and increase your bottom line? Let's start with wireframing the project tasks. Installing new software is a regular occurrence. You want to identify the patterns and devise a process that can be customized as needed. Having mockups will provide visual support needed to proceed in an organized, efficient manner. Many times you may be working with a team that can benefit from collaborating with install mockups. If size requires, tasks can be delegated to team members thus speeding up progress with much less strain on individuals.<span class="Apple-converted-space"> </span></p>
<p class="p1">Once you describe the tasks via mockups, and even uml, the team can work from the same blueprint. Updates are reposited in Git. Trello is used by team to manage the different tasks. Nama is used to manage the entire team and the specific project. Chrometa is used to track the time spent by each team member on their tasks. It helps to manage the time; to deliver completed project on time and within budget.<span class="Apple-converted-space"> </span></p>
<p class="p1">Software tools that help track projects are extremely important to a manager or owner that writes the check against a limited budget. In other words, how many developers could a manager afford to assign to a project; and what would be the time constraints to work within, in order to stay within budget, ie, time and cost?</p>
<p class="p1">Regarding the project management step, once the goals have been described, team members chosen, software chosen and configured for team's use, blueprint completed, tasks assigned, deadlines set, the process can begin.<span class="Apple-converted-space"> </span></p>
      </div>
   </div>
</body>
</html>