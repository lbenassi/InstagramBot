# InstagramBot

---


### On 29-Sep-2018, The purpose of this script is to increase the Instagram followers . Those who want to get lots of followers in a few days , this script is the best option. In addition to increasing the follower there are some unique features such as the likes and Comment , and ... 

### Please do not clone this repo and publish it as your own. Fork the repo if you wish to publish any changes.

---

> We can follow the pages listed :)

[![Chat on Instagram](https://img.shields.io/badge/Chat%20on-Instagram-brightgreen.svg)](https://www.instagram.com/rzabm/)
[![Chat on Telegram](https://img.shields.io/badge/Chat%20on-Telegram-brightgreen.svg)](https://t.me/pcmohandes_ir)
[![Web Site](https://img.shields.io/badge/Visit%20the-Website-brightgreen.svg)](http://pcmohandes.ir)


## Parameters
| Parameter            | Type|                Description                           |        Default value             |
|:--------------------:|:---:|:----------------------------------------------------:|:--------------------------------:|
| login                | str | Your instagram username                              |      |
| password             | str | Your instagram password                              |      |
| start\_at\_h         | int | Start program at the hour                            | 0    |
| start\_at\_m         | int | Start program at the min                             | 0    |
| end\_at\_h           | int | End program at the hour                              | 23   |
| end\_at\_m           | int | End program at the min                               | 59   |
| database\_name       | str | change the name of database file to use multiple account | "follows\_db.db"   |
| like_per_day         | int | Number of photos to like per day (over 1000 may cause throttling) | 600 |
| media_max_like       | int | Maximum number of likes on photos to like (set to 0 to disable) | 0    |
| media_min_like       | int | Minimum number of likes on photos to like (set to 0 to disable) | 0    |
| follow_per_day       | int | Photos to like per day                               | 700    |
| follow_time          | int | Seconds to wait before unfollowing                   | 1 * 12 |
| unfollow_per_day     | int | Users to unfollow per day                            | 300    |
| comments_per_day     | int | Comments to post per day                             | 200    |
| comment_list         | [[str]] | List of word lists for comment generation        | [['this', 'your'], ['photo', 'picture', 'pic', 'shot'], ['is', 'looks', 'is really'], ['great', 'super', 'good'], ['.', '...', '!', '!!']] |
| tag_list             | [str] | Tags to use for finding posts by hasthag or location                     | ['happy','birthday','robatkarim','eshq'] |
| tag_blacklist        | [str] | Tags to ignore when liking posts                   | [] |
| user_blacklist       | {str: str} | Users whose posts to ignore                   | {} |
| max_like_for_one_tag | int | How many media of a given tag to like at once (out of 21) | 5 |
| unfollow_break_min   | int | Minimum seconds to break between unfollows           | 15 |
| unfollow_break_max   | int | Maximum seconds to break between unfollows           | 30 |
| log_mod              | int | Logging target (0 log to console, 1 log to file, 2 no log.) | 0 |
| proxy                | str | Access instagram through a proxy. (host:port or user:password@host:port) | |


## Usage examples
Basic bot implementation:
```py
bot = InstaBot('login', 'password')
```


## Video Tutorials
The following video tutorials demo setting up and running the bot:
* [Android](https://www.instagram.com/rzabm/)

## Community

- [Telegram Group](https://t.me/joinchat/JPdJCRAqYxZBExsYDLzCnQ)

