bt7.7去除登录框请运行
```Bash
sed -i "s|if (bind_user == 'True') {|if (bind_user == 'REMOVED') {|g" /www/server/panel/BTPanel/static/js/index.js
```
```Bash
rm -rf /www/server/panel/data/bind.pl
```
