# BuycraftAutomation
[Buycraft](https://www.buycraft.net) package automation, automatically pulls data from a csv and sends packages for users through Buycraft.

# Setup
## Items needed
- Firefox
- Imacros
- Csv file in username,package format

## Instructions
1. Make sure Firefox is installed with [iMacros](https://addons.mozilla.org/en-US/firefox/addon/imacros-for-firefox/).
2. Navigate to [server.buycraft.net](http://server.buycraft.net) and login.
3. Ready your csv file, an example can be found [here](users.csv). Make sure to view the raw file.
4. Open up iMacros. 
5. Edit the #Current.iim to have the code from [BuycraftAutomation.iim](BuycraftAutomation.iim)
6. Put your users.csv in "C:\Users\Username\Documents\iMacros\Datasources"
7. Set the Repeat macro the the amount of users your in users.csv.
8. Click on Play(Loop).

## FAQ
- Do the package names need to be exactly what the package is named on buycraft?
  - Yes, package names need to be a direct match.
- It only executes on the first user and then stops?
  - Make sure you are using Play(Loop) and you have the correct number set, refer to steps 7 & 8.
- My users.csv isn't working.
  - Its likely a formatting issue or your file is not in the correct location, refer to step 3 and [users.csv](users.csv).
- How should I create my users.csv?
  - You are on your own for getting you data. If you want data converted to csv in bulk [contact me](https://github.com/virustotalop/Contact).
- Why is this so slow?
  - The delay is set at 10 seconds after each purchase sent to respect buycraft and not flood it. You can lower the delay in the code.
