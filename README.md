<center><h1>Voting Bot</h1></center>
<hr>
Code is private because of security reasons.
<hr>
<b>BASICS:</b><br>
This project was made as a freelacing project for a guy from Houston, California.<br>
The idea was to get an author from: https://www.quotes.net/ and then type number of #5 star votes to be given to each quote.<br><br>

<b>1.ST VERSION PRINCIPLE:</b>
User gets the profile url from quotes.net and pushes button "Go".<br>
Quotes from a web page are loaded into table below:
<ol>
  <li>st column -> Quote Number -> Unique ID of quote.</li>
  <li>nd column -> Quote -> WebScrapped quote from given URL.</li>
  <li>rd column -> # Of 5 Star Votes -> Number of 5 star votes that will be given to quote from column 2.</li>
  <li>th column -> ID -> Unique ID of quote from website.</li>
  <li>th column -> # Of Current Votes -> Number of current votes on quote from column 2.</li>
</ol>
User must press button "Vote" and the vote starts. After some time, all the votes from column 3 will be voted on quote from column 2.<br><br>

<b>2.ND VERSION PRINCIPLE:</b>
The task was to make order of quotes manually movable and saveable.
So the user is able to switch quotes manually after getting quotes from URL.
User must enter which rows he would like to switch and then press button "Switch".
Rows will be switched and their positions will be saved next time he searches this URL.<br><br>

<b>Technology used</b>: C#
