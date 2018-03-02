<html>
<head>
<title>Project 1</title>
<style>
	/*----- Body style----- */
	body {
		font-family: "arcon", serif;
		background-color: #430C1D;
		font-size: 30px;
		color: #038C82;
		font-weight: lighter;
		line-height: 25px;
		padding: 30px;
		}
	
	/*----- results button style----- */
	#quizButton {
		position: relative;
		background-color: #038C82;
		border: none;
		font-size: 28px;
		color: #E7FBF5;
		padding: 20px;
		width: 400px;
		text-align: center;
		transition-duration: 1.4s;
		text-decoration: none;
		overflow: hidden;
		cursor: pointer;
		}
	/*----- heading style----- */	
	h1	{
		font-size: 70px;
		line-height: 1.4;
		color: #B9F7FB;
		text-align: center;
		}
		
	h2 {
		font-size: 30px;
		color: #B9F7FB;
		text-align: center;
		}
		
	input[type="radio"] {
		border: none;
		color: white;
		padding: 15px 32px;
		text-align: center;
		text-decoration: none;
		display: inline-block;
		margin: 8px 4px;
		cursor: pointer;
		}
	blockquote {
		font-size: 24px;
		color: #E7FBF5;
		line-height: 45px;
		}
	
	img {
		display: block;
		margin-left: auto;
		margin-right: auto;
		width: 40%;
		}
	

</style>
</head>

<body>
	<h1> What kind of Book are you?</h1>
	<img src="Book1.gif" alt="bookman">
	<h2> Find out what book you are by answering the below questions!</h2>
	<form>
		1. What stories do you mostly read?
		<blockquote>
			<input type="radio" name="story" id="creatures" value="creatures">
			<label for="creatures">Anything with fairies, vampires, werewolves, and or witches.</label>
			<br>
			<input type="radio" name="story" id="nonfiction" value="nonfiction">
			<label for="nonfiction">Mostly non-fiction stories, biographies, and or stories about wars. </label> <!--//allows you to click the word and select the button -label-->
			<br>
			<input type="radio" name="story" id="lovestories" value="lovestories">
			<label for="lovestories">Stories surrounding love.</label>
			<br>
			<input type="radio" name="story" id="none" value="none">
			<label for="none">I don't read stories. I have too much homework to do.</label>
		</blockquote>
		
		
		2. Are you a day dreamer?
		<blockquote>
		
			<input type="radio" name="daydreamer" id="lovedreams" value="lovedreams">
			<label for="lovedreams">Yes, but only about love related things.</label>
			<br>
			<input type="radio" name="daydreamer" id="impossible" value="impossible">
			<label for="impossible">Yes, all the time about the impossible! </label> 
			<br>
			<input type="radio" name="daydreamer" id="no" value="no">
			<label for="no">No, I can't concentrate on work if I do.</label>
			<br>
			<input type="radio" name="daydreamer" id="timetravel" value="timetravel">
			<label for="timetravel">Yes, usually about what it would be like to live in past historic times.</label>
		</blockquote>
		
		3. Which music choice is more appealing to you?
		<blockquote>
			<input type="radio" name="music" id="hamilton" value="hamilton">
			<label for="hamilton">Hamilton Musical sountrack</label>
			<br>
			<input type="radio" name="music" id="whitney" value="whitney">
			<label for="whitney">I will always love you by Whitney Houston </label> 
			<br>
			<input type="radio" name="music" id="instrumental" value="instrumental">
			<label for="instrumental">Something like coffee shop jazz/instrumental</label>
			<br>
			<input type="radio" name="music" id="edm" value="edm">
			<label for="edm">Any electronic dance music</label>
		</blockquote>
		
		4. Which photograph is more appealing to you?
		<blockquote>
			<input type="radio" name="photo" id="photoOne" value="photoOne">
			<label for="photoOne">Photo One</label>
			<br>
			<input type="radio" name="photo" id="photoTwo" value="photoTwo">
			<label for="photoTwo">Photo Two </label> 
			<br>
			<input type="radio" name="photo" id="photoThree" value="photoThree">
			<label for="photoThree">Photo Three</label>
			<br>
			<input type="radio" name="photo" id="photoFour" value="photoFour">
			<label for="photoFour">Photo Four</label>
		</blockquote>
		
		5. What do you drink while reading?
		<blockquote>
			<input type="radio" name="QFIVE" id="coffee" value="coffee">
			<label for="coffee">Coffee</label>
			<br>
			<input type="radio" name="QFIVE" id="Tea" value="Tea">
			<label for="Tea">Tea</label> 
			<br>
			<input type="radio" name="QFIVE" id="wine" value="wine">
			<label for="wine">Wine</label>
			<br>
			<input type="radio" name="QFIVE" id="water" value="water">
			<label for="water">Water</label>
		</blockquote>
		
		6. How do you get your books?
		<blockquote>
			<input type="radio" name="QSIX" id="friend" value="friend">
			<label for="friend">Friend recommendations</label>
			<br>
			<input type="radio" name="QSIX" id="articles" value="articles">
			<label for="articles">From articles I read.</label> 
			<br>
			<input type="radio" name="QSIX" id="teacher" value="teacher">
			<label for="teacher">Teacher required text</label>
			<br>
			<input type="radio" name="QSIX" id="author" value="author">
			<label for="author">Usually stick to favorite authors/series.</label>
		</blockquote>
		
		7. If you could have one wish what would it be?
		<blockquote>
			<input type="radio" name="QSEVEN" id="power" value="power">
			<label for="power">To have super powers!</label>
			<br>
			<input type="radio" name="QSEVEN" id="nohw" value="nohw">
			<label for="nohw">To have no more homework.</label> 
			<br>
			<input type="radio" name="QSEVEN" id="soulmate" value="soulmate">
			<label for="soulmate">To meet destined soulmate!</label>
			<br>
			<input type="radio" name="QSEVEN" id="dinner" value="dinner">
			<label for="dinner">To have dinner with a historical deceased of choice.</label>
		</blockquote>
		
		8. Pick the most interesting Book title:
		<blockquote>
			<input type="radio" name="QEIGHT" id="mirror" value="mirror">
			<label for="mirror">A Distant Mirror</label>
			<br>
			<input type="radio" name="QEIGHT" id="park" value="park">
			<label for="park">Eleanor & Park</label> 
			<br>
			<input type="radio" name="QEIGHT" id="flight" value="flight">
			<label for="flight">The Philospher's Flight</label>
			<br>
			<input type="radio" name="QEIGHT" id="js" value="js">
			<label for="js">Speaking Javascript</label>
		</blockquote>
		
		9. QUESTION 9
		<blockquote>
			<input type="radio" name="QNINE" id="mirror" value="mirror">
			<label for="mirror">A Distant Mirror</label>
			<br>
			<input type="radio" name="QNINE" id="park" value="park">
			<label for="park">Eleanor & Park</label> 
			<br>
			<input type="radio" name="QNINE" id="flight" value="flight">
			<label for="flight">The Philospher's Flight</label>
			<br>
			<input type="radio" name="QNINE" id="js" value="js">
			<label for="js">Speaking Javascript</label>
		</blockquote>
		
		10. QUESTION 10
		<blockquote>
			<input type="radio" name="QTEN" id="mirror" value="mirror">
			<label for="mirror">A Distant Mirror</label>
			<br>
			<input type="radio" name="QTEN" id="park" value="park">
			<label for="park">Eleanor & Park</label> 
			<br>
			<input type="radio" name="QTEN" id="flight" value="flight">
			<label for="flight">The Philospher's Flight</label>
			<br>
			<input type="radio" name="QTEN" id="js" value="js">
			<label for="js">Speaking Javascript</label>
		</blockquote>
		
		<input type="button" id="quizButton" value="Get My Results!">

	</form>
	<p id="resultArea"></p>
	<script>
	
	
//gain access to the quiz button and wait for a click
	var button = document.getElementById("quizButton");
	button.onclick = checkQuiz;
	
	function checkQuiz(){
		var fantasyScore = 0;
		var textScore= 0;
		var historyScore= 0;
		var romanceScore= 0;
		
		console.log("button pressed!");

//create a variable to store the user's Book
//-----QUESTION 1-------
	var story;
	
//get the input data
	var inputs = document.getElementsByName("story");
	
	story = findValue(inputs);
	document.getElementById("resultArea").innerHTML = story;
	
		switch(story)
	{
		case "none":
			textScore++;
			break;
		case "nonfiction":
			historyScore++;
			break;
		case "creatures":
			fantasyScore++;
			break;
		case "lovestories":
			romanceScore++;
			break;
		default: 
			document.getElementById("resultArea").innerHTML = "<br>Please answer question 1.<br>"
	}

//-----QUESTION 2-------	
	var dayrdream;
	inputs = document.getElementsByName("daydreamer");
	
	daydream = findValue(inputs);
	document.getElementById("resultArea").innerHTML += " " + daydream;
	
	
	switch(daydream)
	{
		case "no":
			textScore++;
			break;
		case "timetravel":
			historyScore++;
			break;
		case "impossible":
			fantasyScore++;
			break;
		case "lovedreams":
			romanceScore++;
			break;
		default: 
			document.getElementById("resultArea").innerHTML = "<br>Please answer question 2.<br>"
	}

//-----QUESTION 3-------	
	var music;
	inputs = document.getElementsByName("music");
	
	music = findValue(inputs);
	document.getElementById("resultArea").innerHTML += " " + music;
	
	
	switch(music)
	{
		case "instrumental":
			textScore++;
			break;
		case "hamilton":
			historyScore++;
			break;
		case "edm":
			fantasyScore++;
			break;
		case "whitney":
			romanceScore++;
			break;
		default: 
			document.getElementById("resultArea").innerHTML = "<br>Please answer question 3.<br>"
	}
	
//-----QUESTION 4-------	
	var photo;
	inputs = document.getElementsByName("photo");
	
	photo = findValue(inputs);
	document.getElementById("resultArea").innerHTML += " " + photo;
	
	
	switch(photo)
	{
		case "photoOne":
			textScore++;
			break;
		case "photoTwo":
			historyScore++;
			break;
		case "photoThree":
			fantasyScore++;
			break;
		case "photoFour":
			romanceScore++;
			break;
		default: 
			document.getElementById("resultArea").innerHTML = "<br>Please answer question 4.<br>"
	}

//-----QUESTION 5-------	
	var QFIVE;
	inputs = document.getElementsByName("QFIVE");
	
	QFIVE = findValue(inputs);
	document.getElementById("resultArea").innerHTML += " " + QFIVE;
	
	switch(QFIVE)
	{
		case "coffee":
			textScore++;
			break;
		case "Tea":
			historyScore++;
			break;
		case "water":
			fantasyScore++;
			break;
		case "wine":
			romanceScore++;
			break;
		default: 
			document.getElementById("resultArea").innerHTML = "<br>Please answer question 5.<br>"
	}

//-----QUESTION 6-------	
	var QSIX;
	inputs = document.getElementsByName("QSIX");
	
	QSIX = findValue(inputs);
	document.getElementById("resultArea").innerHTML += " " + QSIX;
	
	switch(QSIX)
	{
		case "teacher":
			textScore++;
			break;
		case "articles":
			historyScore++;
			break;
		case "friend":
			fantasyScore++;
			break;
		case "author":
			romanceScore++;
			break;
		default: 
			document.getElementById("resultArea").innerHTML = "<br>Please answer question 6.<br>"
	}

//-----QUESTION 7-------	
	var QSEVEN;
	inputs = document.getElementsByName("QSEVEN");
	
	QSEVEN = findValue(inputs);
	document.getElementById("resultArea").innerHTML += " " + QSEVEN;
	
	switch(QSEVEN)
	{
		case "nohw":
			textScore++;
			break;
		case "dinner":
			historyScore++;
			break;
		case "power":
			fantasyScore++;
			break;
		case "soulmate":
			romanceScore++;
			break;
		default: 
			document.getElementById("resultArea").innerHTML = "<br>Please answer question 7.<br>"
	}

//-----QUESTION 8-------	
	var QEIGHT;
	inputs = document.getElementsByName("QEIGHT");
	
	QEIGHT = findValue(inputs);
	document.getElementById("resultArea").innerHTML += " " + QEIGHT;
	
	switch(QEIGHT)
	{
		case "js":
			textScore++;
			break;
		case "mirror":
			historyScore++;
			break;
		case "flight":
			fantasyScore++;
			break;
		case "park":
			romanceScore++;
			break;
		default: 
			document.getElementById("resultArea").innerHTML = "<br>Please answer question 8.<br>"
	}
	
//-----QUESTION 9-------	
	var QNINE;
	inputs = document.getElementsByName("QNINE");
	
	QNINE = findValue(inputs);
	document.getElementById("resultArea").innerHTML += " " + QNINE;
	
	switch(QNINE)
	{
		case "js":
			textScore++;
			break;
		case "mirror":
			historyScore++;
			break;
		case "flight":
			fantasyScore++;
			break;
		case "park":
			romanceScore++;
			break;
		default: 
			document.getElementById("resultArea").innerHTML = "<br>Please answer question 9.<br>"
	}
	
//-----QUESTION 10-------	
	var QTEN;
	inputs = document.getElementsByName("QTEN");
	
	QTEN = findValue(inputs);
	document.getElementById("resultArea").innerHTML += " " + QTEN;
	
	switch(QTEN)
	{
		case "js":
			textScore++;
			break;
		case "mirror":
			historyScore++;
			break;
		case "flight":
			fantasyScore++;
			break;
		case "park":
			romanceScore++;
			break;
		default: 
			document.getElementById("resultArea").innerHTML = "<br>Please answer question 10.<br>"
	}
	
	//------------------SCORING SECTION--------------		
		if ((textScore >= historyScore) &&
			(textScore >= fantasyScore) &&
			(textScore >= romanceScore))
			{
				document.getElementById("resultArea").innerHTML = "You are a TextBook. You have a vast amount of knowledge to how to solve school related problems but most tend to stay away from you.";
			}
			else if ((historyScore >= textScore) &&
				(historyScore >= fantasyScore) &&
				(historyScore >= romanceScore))
				{
					document.getElementById("resultArea").innerHTML = "You are a History Book. You are wise and full of facts of the past but becareful, you tend to repeat yourself.";
				}
				else if ((fantasyScore >= textScore) &&
					(fantasyScore >= historyScore) &&
					(fantasyScore >= romanceScore))
					{
						document.getElementById("resultArea").innerHTML = "You are a Fantasy Book. You are wild and free from bounderies. Beware danger tends to lurk behind every corner.";
					}
					else {
						document.getElementById("resultArea").innerHTML = "You are a Romance Book. You are a hopeless romance filled with heart racing and tear jerking scenes but becareful of heart breaks.";
						}
	}
	
	function findValue(inputs)
	{
		var checkedValue;
		
		for (var i=0; i<inputs.length; i++)
		{
			if (inputs[i].checked)
			{
				checkedValue = inputs[i].value;
				console.log(checkedValue);
			}
		}
		
		return checkedValue;
	}
	

	</script>
</body>
</html>
