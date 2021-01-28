### How to use Git inside VSCode (Mac)


###### 1.) Download Git:
Using Homebrew, let's install git:
```javascript
    brew install git
```
*If you don't have Homebrew, check out [this video](https://youtu.be/0poFbaGGDvI)*
_________________________
        
###### 2.) Set Git username:
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
Replace the email in the line below with the email that's connected to your GitHub account
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

_________________________________
###### 5.) Add SSH key to ssh-agent

______________________________________# github-vscode-setup
