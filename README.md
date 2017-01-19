# GypsieHelper

A script used for filtering and highlighting ads in the Facebook Gypsie housing group.

## Warning: Self-XXS

As a general rule, don't blindly paste others code into your browser JavaScript console. 
This is how self-xxs (https://en.wikipedia.org/wiki/Self-XSS) attacks are done. 


## Usage
	1. Clone the repo or just save the file gypsie.js
	2. Security check
		i.  Read the code to make sure I'm not trying to hack you
		ii. The jQuery source is included in the file, you don't know if there is some bad code in that blob, so you should include jQuery by pasting in the original jQuery code yourself, as provided from the jQuery website. 
	3. Edit your preferences (filterTriggers and highlightTriggers)
	3. Go to Facebook's Gypsie housing group
	4. Open JavaScript console and paste the code there
	5. Enter "start()" in the console to start filter/highlight
	6. Enter "stop()" to stop