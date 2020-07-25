<div align=center>

# The Dotfiles-Project

A place to deposit and find Dotfiles
</div>

### Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Contributing](#adding-your-Dotfiles)
- [Getting Help](#getting-help)

## Introduction

>Since the dawn of time people have wondered how to find and steal configurations. From trawling github to scraping forums people have wanted and easy way to find and learn from others configuration or "dotfiles" The Dotfiles Project aims to bring us out of the Dark ages and into the light

The Dotfiles project wants to help by providing a single place for people to place and find dotfiles. If its just out of casual curiosity or your planning on building your own this is a good place to start!

## Getting Started

You can explore repository's and take what you want from each user. If you want to explore on your local machine then recursively clone this repository.

``` shell
git clone --recursive https://github.com/jeetelongname/Dotfiles-Project
```

## Contributing

Adding dotfiles is quite simple. all you need to do is clone this repository and add your dotfiles as a submodule.
To do this simply

``` shell
git clone --recursive https://github.com/jeetelongname/Dotfiles-Project
cd Dotfiles-Project/Repos
git submodule add *your dotfile repository* *your username*
```
E.g. 

``` shell
git submodule add https://github.com/jeetelongname/Dotfiles jeetelongname
```
make sure that its in the repository folder and that its called your username. This allows for better discoverability and less confusion. 

You should also have a [good README](https://github.com/matiassingers/awesome-readme) saying what you have configured and or what is in the repository. you should also include instructions on how to install (if you have got them...) Screenshots are preferred but not required. 

Once you have done all of that, make a [pull request](https://linuxhint.com/pull_request_github/) and your done! A more detailed list can be found in the [CONTRIBUTING.md](CONTRIBUTING.md) file

## Getting help
If your the kind of person that wants to sort out there own problems then i recommend [the unofficial guide to dotfiles](https://dotfiles.github.io/). If you have more resources do let me know (make an issue and or [email me!](mailto:jeetelongname@gmail.com))

If you want to talk to a human jump onto the [gitter](https://gitter.im/Dotfiles-Project) where we can help you out! 
If you found a bug then make an issue and tag the person!

<div align="center">

# Want to talk with the community?
join us on [gitter!](https://gitter.im/Dotfiles-Project)  where you can discuss the dotfiles or discuss 

[![Gitter](https://badges.gitter.im/Dotfiles-Project/community.svg)](https://gitter.im/Dotfiles-Project/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

</div>
    
