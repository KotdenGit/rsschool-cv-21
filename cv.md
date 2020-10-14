 Resume Junior Developer
 
1. Voschenchuk Yuri Nikolaevich
2. +375256140194 E-mail: kotde09@gmail.com
3. I always had a dream of being a programmer, I knew that this requires a lot of skills. And for me to be a programmer is the desire and passion to learn new information, to be in search of adventures, to feel the need for new discoveries. This is a fresh sphere where you can be a pioneer like Christopher Columbus or Vasco da Gama. Finding new ways to make life easier give people new opportunities. For everything else, studying has always been easy for me, at a university college or school.
4. My skills: HTML, CSS, JS, JSON API, SQL and C#(basic knowledge); frameworks such as: SASS, bootstrap, Vue; version control - Git.
5. Input battleship:

   function parseGuess(guess) {
	var alphabet = ["A", "B", "C", "D", "E", "F", "G"];

	if (guess === null || guess.length !== 2) {
		alert("Oops, please enter a letter and a number on the board.");
	} else {
		var firstChar = guess.charAt(0);
		var row = alphabet.indexOf(firstChar);
		var column = guess.charAt(1);
		
		if (isNaN(row) || isNaN(column)) {
			alert("Oops, that isn't on the board.");
		} else if (row < 0 || row >= model.boardSize ||
		           column < 0 || column >= model.boardSize) {
			alert("Oops, that's off the board!");
		} else {
			return row + column;
		}
	}
	return null;
  }

6. You can see the attempts in my repository to pass the tests. I studied at school RS(IT Shark) before in 2018/19. Passed a course on creating websites from *Newton*.
7. I had the opportunity to learn on my own. I was helped by online schools and courses such as: freeCodeCamp, codecademy, w3schools, and YouTube video tutorials.
8. Personal language classes with a teacher. IMHO my level: A2 (pre intermediate).
