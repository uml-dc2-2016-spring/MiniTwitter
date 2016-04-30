# Project Goal

The goal of this project was to create a simple version of twitter that allowed user to login, post tweets, follow other people and send email notification to follower.
In order to acheive this, I need to apply the knowledge I already learn, and explore the framework and language I am not familiar with. More importantly, for personal preference, to get a hand-on experience in web development. 
Link to the final product(http://217.199.187.192/cctoys.com/twitter/).

# Project Design

The design process follows the MVC frame work, which allows better and easier code maintenance.
![alt text](https://github.com/uml-dc2-2016-spring/MiniTwitter/blob/master/MVC%20frame%20work.png)

The diagram above shows the design pattern and data flow once the user login.

# File structure

## views/
<ul>
  <li><i>header.php:</i> Header of the web page.</li>
  <li><i>footer.php:</i> Footer of the web page.</li>
  <li><i>home.php:</i> Layout of the homepage.</li>
  <li><i>publicprofiles.php:</i> Layout of the publicprofile page.</li>
  <li><i>search.php:</i> Layout of the search page.</li>
  <li><i>timeline.php:</i> Layout of the timeline page.</li>
  <li><i>yourtweets.php:</i> Layout of yourtweets page.</li>
</ul>

<li><i>actions.php:</i> Where all the actions are performed.(submit login, post tweet, toggle follow)</li>
<li><i>function.php:</i> Functions of the app. The controller part of MVC.(display time, tweets and users info)</li>
<li><i>index.php:</i> Central point of the website, every page will be generate from here.</li>
<li><i>styles.css:</i> General styles of the website.</li>



