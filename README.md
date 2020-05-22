# forensic_vm


This repository works helps me configure and maintain my forensic_vm. It simplifies the effort of install a fresh forensic_vm by using boxstarter. Feel free to explore, learn and copy parts to your own boxstarter. Enjoy! :smile:

## Installation

**Warning:** If you want to give these configurations a try, you should first fork this repository, review the code, and remove things you don’t want or need. Don’t blindly use my settings unless you know what that entails. Use at your own risk!

To install and setup:

```
. { iwr -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force

Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/HansJoakimPersson/forensic_vm/master/bootstrap.ps1 -DisableReboots
```


## ¯\\_(ツ)_/¯ Warning / Liability
> Warning:
The creator of this repo is not responsible if your machine ends up in a state you are not happy with. If you are concerned, look at the code to review everything this will do to your machine :)

## Feedback

Suggestions/improvements
[welcome](https://github.com/HansJoakimPersson/dotfiles/issues)!

## Thanks to…



## License

The MIT License. Please see [the license file](license.md) for more information.
