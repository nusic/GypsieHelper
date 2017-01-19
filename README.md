# GypsieHelper

A script used for filtering and highlighting ads in the Facebook Gypsie housing group.

## Warning: Self-XXS

As a general rule, don't blindly paste others code into your browser JavaScript console. 
This is how self-xxs attacks are done (https://en.wikipedia.org/wiki/Self-XSS).


## Usage
	1. Clone the repo or just save the file gypsie.js
	2. Security check
		i.  Read the code to make sure I'm not trying to hack you
		ii. The jQuery source is included in the file. However, you don't know 
			if there is some bad code in that blob, so you should include jQuery 
			by pasting in the original jQuery code yourself, as provided from the 
			jQuery website. 
	3. Edit your preferences (filterTriggers and highlightTriggers)
	4. Go to Facebook's Gypsie housing group
	5. Open JavaScript console and paste the code there
	6. Enter "start()" in the console to start filter/highlight
	7. Enter "stop()" to stop