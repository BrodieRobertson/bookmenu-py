<div align=center>

# Bookmenu-py

[![Badge Pull Requests]][Pull Requests] 
[![Badge Issues]][Issues] 
[![Badge License]][License] 
![Badge Language] 

Bookmenu-py is a Python rewrite of my old browser bookmark script.

It provides the ability to quickly access your bookmarks from launchers like dmenu and rofi to allow easy switching between browsers without the need to worry about migrating bookmarks.

---

**[<kbd> <br> Install <br> </kbd>][Install]** 
**[<kbd> <br> Quick Start <br> </kbd>][Quick Start]** 
**[<kbd> <br> Configure <br> </kbd>][Configure]** 

---

</div>

## Features

- Seperate bookmarks out from your web browser
- Suitable for quickly accessing files as well
- Support for both JSON and custom seperator bookmark files
- All command line options can be set in the config file
- Support for adding and removing bookmarks from the script
- Support for XDG_CONFIG_PATH
- Works with most dmenu style launchers (tofi, rofi, etc)
- Works with most browsers (if something breaks, let me know)

## FAQ

#### What was wrong with the original script?

I was once a fan of writing everything in shell script but coming back it now, I found it to be a maintenance nightmare. 
For me it was a lot easier just to rewrite the script in a language I'm better at.

#### Why don't you just use Buku/other bookmark scripts?

Don't want to, I've had this script for so long I have no interest in changing how it's formatted, if you like what you see
feel free to try it out, otherwise feel free to move along.

#### Can you implement X feature?

I wrote this script for my own use case, I'm happy to take suggestions but don't hold out too much hope. If you really
want something to be implemented feel free to open a PR.

#### Your Python is not very Pythonic, can I fix it?

If you want to do so, I guess go ahead and do it but this is just a quick script to solve my problem,
not meant to be a perfectly written codebase.


<!----------------------------------------------------------------------------->
[License]: LICENSE
[Pull Requests]: https://github.com/BrodieRobertson/bookmenu-py/pulls
[Issues]: https://github.com/BrodieRobertson/bookmenu-py/issues
[Configure]: https://github.com/BrodieRobertson/bookmenu-py/wiki/Configuration
[Install]: https://github.com/BrodieRobertson/bookmenu-py/wiki/Install-Guide
[Quick Start]: https://github.com/BrodieRobertson/bookmenu-py/wiki/Quick-Start

<!----------------------------------{ Badges }--------------------------------->
[Badge Issues]: https://img.shields.io/github/issues/BrodieRobertson/bookmenu-py
[Badge Pull Requests]: https://img.shields.io/github/issues-pr/BrodieRobertson/bookmenu-py
[Badge License]: https://img.shields.io/github/license/BrodieRobertson/bookmenu-py
[Badge Language]: https://img.shields.io/github/languages/top/BrodieRobertson/bookmenu-py