Hello Ryan, welcome to the github readme for your own website.

Technologies involved in the building this website includes:

HTML
CSS3 + Sass + Compass
Gimp

In case you've managed to get yourself in a pickle, here are some pointers
Hosting provider: [whois]

to push changes to website:
$ git pushwebsite 

this assumes the following:
git-ftp is installed
pushwebsite is aliased to 'ftp push --user haines --passwd * ftp://[stuffhere]'

otherwise:
git add -A
git commit -m"message here"
git push origin master

then use ftp software to migrate changes to live website

http://ryahain.es
https://ryanhain.es
https://ourbenefactors.com

to clone repository:

$ git clone https://github.com/Ryan-Haines/homepage.git