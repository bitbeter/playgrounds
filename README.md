# Playgrounds
My all test and playground projects

### For all updating projects to last version
```bash
git submodule update --recursive --remote
```

### For add some submodule to project
```bash
# add some git url to its course folder.
git submodule add -b master <Git Url> <Project Name>
```

### Useful link
http://dan.mccloy.info/2015/06/11/Git-submodules/

### Useful commands
* push and if needed push submoduls too
```bash
git push origin master --recurse-submodules=on-demand
```
