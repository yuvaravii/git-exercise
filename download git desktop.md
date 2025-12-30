## Step-1: Use the link below to download the git desktop app
- [Git Desktop donwload](https://git-scm.com/install/windows)

## Step-2: Open command prompt
- Type in
```git --version```
- Output: 
```git version 2.49.0.windows.1```
- The above output confirms the successful installation in local desktop.

## Step-3: Configuration of Git account in the local desktop
- Within the terminal; to find the existing settings, type in
```git config --list --show-origin```
- Configuring your account; example below
```
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```