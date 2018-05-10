## Unknown

Wasting my time on this project when boredom strikes.

Just a simple **Project and Issue Tracking Management System** - *for developers by developers*. 

It's not about the project itself but the code structure inside that makes me happy. :)





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