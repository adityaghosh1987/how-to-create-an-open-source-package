# how-to-create-an-open-source-package
## Bellow steps will help you to create an open source project

##Steps for npm package registration:
1. npm init
2. npm adduser(if new user or login to https://npmjs.com/~.)
3. npm publish

###References :
[#Creating-node-modules](https://docs.npmjs.com/getting-started/creating-node-modules)
[#Publishing npm packages](https://docs.npmjs.com/getting-started/publishing-npm-packages#publishing-the-package)

---------------------------------------------------------------------------------------------------------

##Steps for bower package registration:
1. bower init
2. git add -A
3. git commit -m "Commit Message"
4. git push origin branch_name
5. git tag -a v1.0.0 -m "version 1.0.0"
6. git push origin v1.0.0
7. bower register <my-package-name> <git-endpoint>

####example : bower register example git://github.com/user/example.git
###References : 
[#Creating-packages](https://bower.io/docs/creating-packages/)
[#Git-Basics-Tagging](https://git-scm.com/book/en/v2/Git-Basics-Tagging)
[#Creating-and-maintaining-your-own-bower-package](http://bob.yexley.net/creating-and-maintaining-your-own-bower-package/)


