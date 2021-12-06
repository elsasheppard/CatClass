This project contains a Cat class structure

Description:
	This class allows you to create your own pet cat! Name and customize your cat however you'd like (within class capabilities)

Class attributes:
	animal type

Data attributes:
	name: name of cat
	breed: type of breed
	owner: who owns cat
	has_dew_claws (bool): whether or not cat has two extra
				toes
	catchphrase: something funny your cat can say

Functions:
	get_name: returns name of cat
	get_breed: returns cat breed
	get_owner: returns cat's owner
	set_owner: takes in a name and changes cat's owner to
			name
	get_num_beans: returns number of beans based on whether
			cat has dew claws or not
	speak: prints out descriptive flavor text using class 
		and data attributes
	play: starts a shell where user can interact with cat
		if command is...

		pet: pet the cat (can only be pet once)
		feed: feed the cat (can only be pet once)
		play: starts another smaller shell
			if command is...

				mouse: have cat play with mouse 
					(timed flavor text)
				yarn: have cat play with yarn 
					(timed flavor text)
				box: have cat play with box 
					(timed flavor text)
		help: print inputs again
		exit: exit shell

Demo Program:
	Demo program comes with cat object already created
	Change existing cat or create your own!
	Run cat.speak() to hear your cat's description of
		itself
	Run cat.play() to play with your cat in real time!
