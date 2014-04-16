# How To Contribute

*Simple contribution guidelines to make open-source happy and organized*

It's difficult for us developers to stay organized and adequately track changes in our code. This difficulty is amplified on teams of more than one. It's further amplified by distributed teams and [time zones](http://xkcd.com/448/). It's even more amplified in open-source. With the guide below, open-source can be organized. It can be a happy place. Resist being a [lazy developer](http://1.bp.blogspot.com/-YD8Na5Mv4oY/USZJ0T5RKQI/AAAAAAAADnU/5U871_OaqRE/s1600/Ain-t-Nobody-Got-Time-Fo-Dat-sweet-brown-31241125-480-330.jpg), we can get through this together.


## Project Organization

* `master` branch is always stable and release-ready
* `develop` branch is not guaranteed to be stable, it is for development and merged into `master` when stable
* feature branches should be created for adding new features and merged into `develop` when ready
* bug fix branches should be created for fixing bugs and merged into `develop` when ready

## Step-by-step

1. Find an issue to work on, or create a new one (*avoid duplicates, please check existing issues!*)
2. Fork the repo
3. Create a new branch with a sweet fucking name: `git checkout -b issue_<##>_<featureOrFix>`
4. Do some motherfucking programming
5. Write [unit tests](http://nshipster.com/unit-testing), if possible
6. Keep your code nice and clean by adhering to coding standards & guidelines (*see below*)
7. Don't break shit, like unit tests
8. Update the documentation header comments, if needed
9. Merge the latest from the `develop` branch and **resolve any conflicts** (*before submitting a pull request!*)
10. Submit a pull request to the `develop` branch

# Style

Style and adherence to conventions is just as important as the code you write. *Don't be sloppy.* Your mother wouldn't like that.

## Objective-C style guidelines

The follow sets of guidelines compliment each other well and cover nearly everything.

* Google's [Objective-C Style Guide](http://google-styleguide.googlecode.com/svn/trunk/objcguide.xml)
* Apple's [Coding Guidelines for Cocoa](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/CodingGuidelines/CodingGuidelines.html)
* NYTimes [Objective-C Style Guide](https://github.com/NYTimes/objective-c-style-guide)

