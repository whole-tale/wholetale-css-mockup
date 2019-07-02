# Whole Tale Dashboard Mockups

To clone:
```
git clone https://github.com/whole-tale/wholetale-css-mockup
```

To checkout a particular tag:
```
cd wholetale-css-mockup
git checkout tags/f2018
```

To create a new tag:
```
cd wholetale-css-mockup
git tag <tag name>
git push origin --tags
```

To add/commit files and push to Github:
```
cd wholetale-css-mockup
git add <file folder pattern>
git commit
git push origin master
```

To run via Docker:
```
docker run --rm -d -p 8080:80 -v `pwd`/src:/usr/share/nginx/html nginx
```
