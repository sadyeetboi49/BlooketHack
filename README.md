# One of the First Blooket Hacks Online

#### Original code by: kgsensei

## Development News:

#### New as of 10.21.21 [ M.D.Y ]

Hello everyone, a large issue has been going around with my cheat where, for some reason, text started to be encoded randomly for some blooket sets, however, it would be regular for other sets. With some help by Dumnersm I solved that issue. I haven't been able to replicate it on my computer (That's why it took so long to fix) but he had the issue so we worked it out. I think that all of these issues should be solved now. If anything else comes up please make an issue or join my discord server.

I did add a new library that is required for the hack to work now but if you haven't had any issues so far than you shouldn't even with this update. This is because the library I'm using comes with python by default. All you should need to do is run the cheat and have selenium and selenium-wire installed (also chrome).

Thank you for understanding!

## Features:

- View Correct Answer
- Auto Click Correct Answer
- Bypass Name Limit
- Works on most game modes:
  - Gold Quest (Tested - Working)
  - Tower Defense (Tested - Working)
  - Café (Tested - Working)
  - Factory (Tested - Working)
  - Racing (Tested - Working)
  - Classic (Tested - Working)
  - Crypto (Tested - Working)
- User Friendly (Mostly)
- 100% Free & Open Source
- ~100% Undetectable

## How to Use:

- First you must download python 3.7, you can do that from [This Link](https://www.python.org/downloads/release/python-377/).
  - On install you do need to check the "Add to path" option when you can do so.
- Second you must download the code here on GitHub.
- Third you need to extract the files from the `.zip` file you downloaded.
- Finally, just double click the `main.py` file.
  - If it still doesn't work run these commands in command prompt: (then run `main.py` again.)
   - `py -m pip install selenium`
   - `py -m pip install selenium-wire`
  - Be sure to update the `chromedriver.exe` file to the version that matches your chrome version.

## Issues + Bugs:

If there is an issue not shown here, please feel free to join my [Discord server](http://discord.gg/BdMbFYwjEf) and ask or make a [GitHub issue](https://github.com/kgsensei/BlooketHack/issues).

#### Known bugs:

- Failure to show correct answer with duplicate text-based questions.
  - Cannot use this cheat on sets like "Flags of the World".
- Colorama dependency install issue on Linux.
  - This is a Colorama issue, I don't think I can help. :(
- Chrome-driver fails to start.
  - This could be caused by a system administrator blocking unknown executable files/applications from running, in which case I highly recommend using glixzzy's cheat instead. Though it may require some JS console experience. [Link Here](https://github.com/glixzzy/blooket-hack).

## Patch Notes:

#### 10.23.21 Update 2
- Released auto-open chests cheat (Gold/Candy Quest)
- Released name limit bypass (Allows Longer Name)

#### 10.23.21 Update 1
- Thanks to Dumnersm for helping with an issue
- Added GZip library as a dependancy
- GZip was added to fix an issue while loading json data for some users

#### 10.19.21 Update
- Started working on more user friendly interface
- Chrome will now launch in windowed fullscreen
- Removed colorama depen.
- [ 10.19.21 ] Fixed the json load error?
- [ 10.20.21 ] Fixed json load error?

#### 9.24.21 Update
- Fixed basically everything broken.
- Added new chrome-driver file.
- Compressed all games into one simple script.
- Removed "otherTools" file, nothing worked.
- Modified readme.md file to something more current.
- Commented sections of the Blooket Hack script.
- Updated indentation on the Blooket Hack script.
  - Indentations off by three characters for some reason.
- Removed TheFinalWillow from production.

## Contributors + Thanks To:

- Copycat {Copycat#8110} {https://github.com/Copycat8110}
- DaAwesomeGuy {DaAwesomeGuy#9831}
- Dumnersm {Dumnersm#7039}

#### Copyright (c) 2021 kgsensei. All rights reserved.
