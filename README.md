## Unknown

Wasting my time on this project when boredom strikes.

Just a simple **Project and Issue Tracking Management System** - *for developers by developers*. 

It's not about the project itself but the code structure inside that makes me happy. :)




|   Commit type              | Emoji                                         |
|:---------------------------|:----------------------------------------------|
| Initial commit             | :tada: `:tada:`                               |
| Version tag                | :bookmark: `:bookmark:`                       |
| New feature                | :sparkles: `:sparkles:`                       |
| Bugfix                     | :bug: `:bug:`                                 |
| Metadata                   | :card_index: `:card_index:`                   |
| Documentation              | :books: `:books:`                             |
| Documenting source code    | :bulb: `:bulb:`                               |
| Performance                | :racehorse: `:racehorse:`                     |
| Cosmetic                   | :lipstick: `:lipstick:`                       |
| Tests                      | :rotating_light: `:rotating_light:`           |
| Adding a test              | :white_check_mark: `:white_check_mark:`       |
| General update             | :zap: `:zap:`                                 |
| Improve format/structure   | :art: `:art:`                                 |
| Refactor code              | :hammer: `:hammer:`                           |
| Removing code/files        | :fire: `:fire:`                               |
| Continuous Integration     | :green_heart: `:green_heart:`                 |
| Security                   | :lock: `:lock:`                               |
| Upgrading dependencies     | :arrow_up: `:arrow_up:`                       |
| Downgrading dependencies   | :arrow_down: `:arrow_down:`                   |
| Lint                       | :shirt: `:shirt:`                             |
| Translation                | :alien: `:alien:`                             |
| Text                       | :pencil: `:pencil:`                           |
| Critical hotfix            | :ambulance: `:ambulance:`                     |
| Deploying stuff            | :rocket: `:rocket:`                           |
| Fixing on MacOS            | :apple: `:apple:`                             |
| Fixing on Linux            | :penguin: `:penguin:`                         |
| Fixing on Windows          | :checkered_flag: `:checkered_flag:`           |
| Work in progress           | :construction:  `:construction:`              |
| Adding CI build system     | :construction_worker: `:construction_worker:` |
| Analytics or tracking code | :chart_with_upwards_trend: `:chart_with_upwards_trend:` |
| Removing a dependency      | :heavy_minus_sign: `:heavy_minus_sign:`       |
| Adding a dependency        | :heavy_plus_sign: `:heavy_plus_sign:`         |
| Docker                     | :whale: `:whale:`                             |
| Configuration files        | :wrench: `:wrench:`                           |
| Merging branches           | :twisted_rightwards_arrows: `:twisted_rightwards_arrows:` |
| Bad code / need improv.    | :hankey: `:hankey:`                           |
| Reverting changes          | :rewind: `:rewind:`                           |
| Breaking changes           | :boom: `:boom:`                               |
| Code review changes        | :ok_hand: `:ok_hand:`                         |
| Accessibility              | :wheelchair: `:wheelchair:`                   |
| Other                      | [Be creative](http://www.emoji-cheat-sheet.com/)  |



### How to view hierarchical / Tree view of a directory / folder in Windows
* Navigate into the folder in file explorer.
* Press Shift, right-click mouse, and select "Open command window here".
* Type tree /f /a > tree.txt and press Enter.
* Open the new tree.txt file in your favourite text editor/viewer.



### XAMPP Virtual Host for sub directory
Point all domains to root folder and one/specific domain to a subfolder in the root folder

1. Open this file.
<code>I:\xampp\apache\conf\extra\httpd-vhosts.conf</code>

2. Paste this code
```html
<VirtualHost *:80>
    DocumentRoot "I:/xampp/htdocs/projects"
    ServerName _default_
</VirtualHost>

<VirtualHost *:80>
    ServerAdmin webmaster@doamin.com
    DocumentRoot "I:/xampp/htdocs/projects/myProjectName/"
    ServerName student.breakoutedu.com
    ErrorLog "logs/sub.domin.com-error.log"
    CustomLog "logs/sub.domin.com-common.log" common
</VirtualHost>
```

3. Open this file.
<code>C:\Windows\System32\drivers\etc\hosts</code>

4. Paste this code <code>127.0.0.1 sub.domin.com</code>
