#**Usage

**Download the script**
```
curl -o anki-addon-init-dev https://raw.githubusercontent.com/simgunz/anki-addon-init-dev/master/anki-addon-init-dev
chmod u+x anki-addon-init-dev
```

**Setup the project downloading the addon from a remote repository**
```anki-addon-init-dev -q -t my_project -a https://github.com/myuser/myaddonrepo.git```

**Setup the project copying an existing addon folder**
```
mkdir my_project
cp -r /path/to/myaddon/ my_project/addon/
anki-addon-init-dev -q -t my_project 
```

**Setup VSCode**
```anki-addon-init-dev -q -t my_project -c```

**Compile addon UI forms**
```anki-addon-init-dev -q -t my_project -f```

**Update Anki to the latest stable version**
```anki-addon-init-dev -q -t my_project -u```
