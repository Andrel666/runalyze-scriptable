# runalyze-scriptable
Uses scriptable app to show reanalyze data as widget on iOS

<img src="https://user-images.githubusercontent.com/45463445/195308981-7a57c321-19df-4561-be44-423db451da6e.png" alt="light mode" width="300"/>
<img src="https://user-images.githubusercontent.com/45463445/195309708-cc70e2e5-60b4-468b-8349-aaa19ac0b968.png" alt="dark mode" width="300"/>

Supports actomatically Dark Mode.

## Instructions
### 1- Before you start
Before you begin, ensure you have met the following requirements:
1.1 - Create your [Runalyze](https://runalyze.com/) account 
1.2 - Install [Scriptable](https://scriptable.app) on your phone

### 2 -Configure scriptable
2.1 - Open Scriptable app
2.2 - Create a new Script by Cliciking + on the scripts page
2.3 - Copy the content of runalyze.js
2.4 - Rename script to runalyze (optional)
2.5 - Change in line 117 if ( inputString == null ) { inputString = "username#password" } to be your user and password (not needed if setup on 3.2.2)
2.6 - Run script

### 3 - Add Wiget and Configure
3.1 - [Add widget to your home screen](https://support.apple.com/en-gb/HT207122) 
3.2 - Change configuration of the script.
3.2.1 - Script : Runalyze (or the nam chosen in previous section)
3.2.2 - Parameter : Your user + # + password (not needed if done on 2.5)

## Customizations
If you want to display different data, pick the avaialble data from lines 73-84 and change the values passed to variables on line 83 to 96

## When runing the first time, the login may take some time to return. If it doesn't retun, run again after a minute and it will be loggedin (need different login in the app and in the widget (different sessions)

