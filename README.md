# FixPress
Fix Wordpress permission to get things running

This is my method/approach on setting up the basic/simple permission to get WordPress running on my vps/dedicated server/vm . It's fairly just a simple script to set the right file/dir permission and group. Security wise? It's up to you to modify it right after, according to you preference. If you want something robust, you might need something else such as ACL.

### Installation
```code
sudo curl -LJO https://raw.githubusercontent.com/anazhd/FixPress/master/fixpress && sudo chmod +x fixpress && sudo mv fixpress /usr/local/bin/
```

### Example
```
lorem@ipsum:~ sudo fixpress
What is your wordpress absolute path? e.g /var/www/path
[]/var/www/html/blog
```
