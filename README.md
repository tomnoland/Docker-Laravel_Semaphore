# NEW_PROJECT_NAME_GOES_HERE

Template for new projects

https://github.com/tomnoland/New-Project-Template/generate

cd /Volumes/Data/Projects

cd ~

---

REPO_NAME=XXX

hub delete -y tomnoland/$REPO_NAME

git clone https://github.com/tomnoland/$REPO_NAME

cd $REPO_NAME

---

git add README.md

git commit -m "Changed README.md file"

git push origin master

---

git pull origin master

---

/usr/bin/open -a /System/Library/CoreServices/Finder.app .

"/Applications/NetBeans/Apache NetBeans 11.1.app/Contents/Resources/NetBeans/bin/netbeans" README.md

---

docker-compose down

docker rm -f $(docker ps -a -q)

docker volume rm $(docker volume ls -q)

[How To Remove Docker Images, Containers, and Volumes](https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes)




