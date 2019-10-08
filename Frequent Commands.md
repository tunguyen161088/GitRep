## Geting started
#### 1. Check git version
```
$ git --version
```
#### 2. View all settings and where they are coming from
```
$ git config --list --show-origin
```
#### 3. Setup username and email
```
$ git config --global user.name "name"
$ git config --global user.email name@email.com
```
#### 4. heck your setting
```
$ git config --list
```
or
```
$ git config user.name
```
#### 5. Getting help
```
$ git <verb> --help
$ git config --help #full reference
$ git config -h #quick reference
```

## Git basics
#### 6. Initializing a repository in an existing directory
```
$ git init
```
#### 7. Cloning an existing repository
```
$ git clone https://github.com/rep
```
#### 8. Checking the status of your files
```
$ git status
```
#### 9. Tracking new files: After add a new file:
```
$ git add README
```
#### 10. Staging modified files (for already tracked file), similar as above
```
$ git add CONTRIBUTING.md
```
