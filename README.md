# imas765probot-v2
Version 2.0 of [imas765probot](https://github.com/Kikugumo/imas765probot) on Node.js

The following Twitter image bots currently run on Heroku using this code.

[~~@makomakorin_bot~~](https://twitter.com/makomakorin_bot) [@makorin_bot2](https://twitter.com/makorin_bot2)  
[~~@harurun_bot_~~](https://twitter.com/harurun_bot_) [@harurun_bot2](https://twitter.com/harurun_bot2)  
[~~@chiichan_bot~~](https://twitter.com/chiichan_bot) [@chiichan_bot2](https://twitter.com/chiichan_bot2)  
[~~@yayoicchi_bot~~](https://twitter.com/yayoicchi_bot) [@yayoicchi_bot2](https://twitter.com/yayoicchi_bot2)  
[~~@iorin_bot_~~](https://twitter.com/iorin_bot_) [@iorin_bot2](https://twitter.com/iorin_bot2)  
[~~@amimami_bot~~](https://twitter.com/amimami_bot)[@amimami_bot4](https://twitter.com/amimami_bot4)  
[~~@yukipyon_bot~~](https://twitter.com/yukipyon_bot) [@yukipyon_bot3](https://twitter.com/yukipyon_bot3)  
[~~@ohimechin_bot~~](https://twitter.com/ohimechin_bot) [@ohimechin_bot2](https://twitter.com/ohimechin_bot2)  
[~~@mikimiki_bot_~~](https://twitter.com/mikimiki_bot_) [@mikimiki_bot3](https://twitter.com/mikimiki_bot3)  
[~~@hibikin_bot_~~](https://twitter.com/hibikin_bot_) [@hibikin_bot3](https://twitter.com/hibikin_bot3)  
[@azusasan_bot](https://twitter.com/azusasan_bot/)  
[~~@ricchan_bot_~~](https://twitter.com/ricchan_bot_) [@ricchan_bot3](https://twitter.com/ricchan_bot3)  

#### Why the change from Python 3 to Node.js?
v1 used a forked version of the tweepy library to access the Twitter API, but due to some issues with uploading large video files, I made the decision to move to another platform with a better Twitter library. At this time, the [imas765probot web app](https://imas765probot.herokuapp.com) had already been in production for several months using a Node.js backend, so it was a natural decision to port imas765probot to the Node.js platform.

Should be obvious, but `bot.js` and `imas765probot.js` in v2 correspond to `bot.py` and `imas765probot.py` respectively in v1. API keys are now stored in environment variables instead of a config file.

Feel free to send me feedback, suggestions, or bug reports [@Kikugumo](https://twitter.com/Kikugumo)
