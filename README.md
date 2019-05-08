This is base scripts that I like to use

Feel free to download or fork this project

Future versions will have Linux distributions and Windows

To get running on Mac

1.) Open either bash or zsh terminal. Support for other terminals coming soon. 

2.) Download this repo. I recommend adding this to your 'home' directory, located at ~. However it will run wherever you decide to put it

3.) Then make contents in osx folder executable. chmod -R +x <path to osx>

4.) Inside of osx folder, run source ./initHomeSetup
This will copy over folders aliases, bin, and envvars to the ~ directory

Commands

* chrome: opens up chrome pointing to google.com
* chrome <url>: opens up that url in chrome 
* killchrome: will gracefully kill chrome
* google: After running you can input a search in the terminal, which will then open up a google search in chrome
* youtube: Will ask for a search and then open that search in youtube
* killapplications: Will kill all application found in /Applications
* createCommand: Create your own custom command. You can be in any directory to run this. It will make a copy of the command and hardlink that same file to ~/bin
* createCommandOpenUrl <command name> <url>: Will create a command which when called will open up the url specified
  
