SoulOfChess - PRD

alice@
08/02/2015

GOAL

Use the lichess.org api to make a client app. With this app, users will be able to log in with their lichess credentials to have full access to what the API provides. 

http://en.lichess.org/


BACKGROUND

[Pre-Requisites, Flow]

ONBOARDING

1. [SENTIENCE] - The user has one of two options upon entering a new app. They can play a game with a human, or with an AI. This will take them down different paths, with the AI path being far shorter. We'll be referring to this choice as "Sentience".
	a. Each form of "Sentience" is described in depth below, but 

AI GAME

HUMAN GAME

1. User can provide their Username or Email, in combination with their unique "password"
	a. If the username/email and the password do not match, the user is told that there was not a match
	b. If the username/email doesn't exist, the user is told that the username/email doesn't exist. 
		i. "Sorry! This username doesn't exist."
	c. If the username/email exists, but the password doesn't match, the user is told that there was not a match.
		i. "Sorry! The username and password do not match."

2. User can "Create a Game"
	a. The user cannot select the "Variant" of the game. It is set to "Standard"
	b. The user can select a specific "Time Control" of the game: "Real Time", "Correspondence", and "Unlimited".
		i. Non-obstrusive definitions of each "Time Control".
			- Real Time: [Definition Required]
			- Correspondence: [Definition Required]
		ii. Illustrations depicting the difference between the "Time Control" options.
			- These should be inticing and detailed. A good source of inspiration would be the choices presented by Pottermore.
	c. The user can set the "Minutes Per Side"
		i. Increments are from 1 to 180.
	d. The user can select the "Increment in Seconds"
		i. Increments are from 0 to 180.
	e. Users can select Casual or Rated
		i. Users, can select the next option within either Casual or Rated to be "Members Only" or not.
			- If the user selects "Members Only", they have to select a "Rating Range" from between 800 - 2900.
		ii. If the user selected "Rated", they have to select a "Rating Range" from between 800 - 2900.
	f. Users can select their preferred Side. 
		i. They can choose to be Black, White, or Random Side.

	g. Creating a game puts the user into a queue.
		i. Resign, Draw



