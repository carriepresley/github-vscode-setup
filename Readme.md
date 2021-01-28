### How to use Git inside VSCode (Mac)


*Where you see the email/username for "presleymath", sub in with yours!*


###### 1.) Download Git:
Using Homebrew, let's install git:
```javascript
    brew install git
```
*If you don't have Homebrew, check out [this video](https://youtu.be/0poFbaGGDvI)*
_________________________
        
###### 2.) Set Git username:
The username you create here will be associated with all Git commits. 

*(This username does not have to be the same as your GitHub username)*

```javascript
     git config --global user.name "unicornsandcoffee"
```
Check to see if it worked!
```javascript
    git config user.name
    > unicornsandcoffee
```
_______________________

###### 3.) Set your commit email in Git:
The email you create here will be associated with all Git commits. 

*(The email should be the same as your GitHub email)* 

```javascript
    git config --global user."email@unicornsandcoffee.com"
```

Check to see if it worked!
```javascript
    git config --global user.email
    email@unicornsandcoffee.com
```
__________________________________

###### 4.) Generate an SSH key
```javascript
    ssh-keygen -t ed25519 -C "email@unicornsandcoffee.com"
```

_________________________________
###### 5.) Add SSH key to ssh-agent

______________________________________