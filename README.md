# Sublime-Text-3

install package controll
``` sh
ctrl+`

import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
```


import settings
``` sh
cd /Users/ user name /Library/Application\ Support/Sublime\ Text\ 3/Packages/
git init
git remote add origin https://github.com/TakuroOnoda/Sublime-Text-3_Packages.git
git pull origin master
```

initial commited
``` sh
cd /Users/ user name /Library/Application\ Support/Sublime\ Text\ 3/Packages/
git init
git add .
git commit -m "initial commit."
git remote add origin https://github.com/TakuroOnoda/Sublime-Text-3_Packages.git
git pull origin master
git push origin master
```
