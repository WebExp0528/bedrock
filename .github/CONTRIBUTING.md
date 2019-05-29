# How to contribute to the project

## The flow

### 1. Setup the project according to [README.md](/README.md)

### 2. [You take an issue](https://github.com/prometheonsystems/bedrock-client2/projects/1?fullscreen=true)

[You take an issue](https://github.com/prometheonsystems/bedrock-client2/projects/1?fullscreen=true), assign it to yourself (note, it's not any issue - only these that are in the github project called "Development", i.e. verified issues - feel free to take any of these)

### 3. Create your branch along with PR

When you start doing something, create a branch & PR for it from `master` branch.

> Have a look for this cli helper: [`git-pr`](https://github.com/JerryGreen/git-pr). You can simply do `git-pr foo` in terminal, and it will create a branch, create a blank commit with a message, and will open a github link to create a PR. Quite useful. You should do the same, whether you're using the cli or not

### 4. You code, make commits, push it to your branch

Please, regularly make `git pull origin master` to have your branch stay up to date.

### 5. We discuss it, fix it, untill it's merged

In Pull Request, please, note the issues you are fixing, in the description. Make descriptions like this (or, more detailed):

```txt
A lot of core functionality

Closes #11
```

Notice the `Closes #11`

You'll get something like this:

<p align="center">
  <img src="https://user-images.githubusercontent.com/13215662/57336429-4bcb3e00-713f-11e9-8231-8ff795658585.png" width="384">
</p>

You may specify several issues per PR. As soon as your PR will be merged, the issues will be automatically closed.
