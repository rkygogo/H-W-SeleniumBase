# H-W-SeleniumBase [![H](https://github.com/mybdye/H-W-SeleniumBase/actions/workflows/H.yml/badge.svg)](https://github.com/mybdye/H-W-SeleniumBase/actions/workflows/H.yml) [![W](https://github.com/mybdye/H-W-SeleniumBase/actions/workflows/W.yml/badge.svg)](https://github.com/mybdye/H-W-SeleniumBase/actions/workflows/W.yml)
Project for SeleniumBase Study.
```diff
- [建议自定义schedule] 
.github/workflows/H.yml
.github/workflows/W.yml
例如：
schedule:
    # UTC (国内 UTC+8)
    - cron: '03 02 */2 * *'   
    # 每2天 10:03am 执行
+ 规则参考
  * * * * *
  | | | | |
  | | | | +----- day of week (0 - 7) (Sunday=0 or 7) OR sun,mon,tue,wed,thu,fri,sat
  | | | +------- month (1 - 12) OR jan,feb,mar,apr ...
  | | +--------- day of month (1 - 31)
  | +----------- hour (0 - 23)
  +------------- minute (0 - 59)
```
#### ✏️ NOTE
- 11.04 重新出发
  - ~~helium/selenium/Playwright~~ >> seleniumBase
  - ~~MacOS/Windows~~ >> Ubuntu

#### ㊙️ SECRET

  |YOU SECRET NAME|YOU SECRET VALUE|
  |-----|--|
  |`URL_BASE_H` or `URL_BASE_W`|网址，至少写一个，不要带有'https://' 或 '/'|
  |`USERNAME`|你的用户名|
  |`PASSWORD`|你的密码|
  |`BARK_TOKEN`|(可选) https://api.day.app/BARK_TOKEN/|
  |`TG_BOT_TOKEN`|(可选) `xxxxxx:xxxxxxxxxxxxx`|
  |`TG_USER_ID`|(可选) 给 bot `@userinfobot` 发送 `/start`|

#### 📚 THANKS
- [Python](https://www.python.org/)
- [selenium](https://www.selenium.dev/)
- [seleniumbase](https://github.com/seleniumbase)
- [PyCharm CE](https://www.jetbrains.com/pycharm/)
