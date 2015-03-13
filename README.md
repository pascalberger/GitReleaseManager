![Icon](https://raw.github.com/gep13/GitHubReleaseManager/develop/Icons/package_icon_no_credit.png)

Do you detest creating release notes for your software applications hosted on GitHub?  If so, this is the tool for you.  

Using a simple set of configuration properties, you can fully automate the creation and export of Release Notes from your GitHub hosted project.  

As an example see this [Release](https://github.com/chocolatey/ChocolateyGUI/releases/tag/0.12.0) for [ChocolateyGUI](https://github.com/chocolatey/ChocolateyGUI) which was created using GitHubReleaseManager.  

GitHubReleaseManager allows you to:

- Create Draft Releases from a milestone
- Attach assets to an existing release
- Close a milestone
- Publish a Draft Release
- Export all Release Notes for a Project

## Installation

You can install GitHubReleaseManager via Chocolatey by executing:

`choco install githubreleasemanager`

If you are interested in trying out the latest pre-release version of GitHubReleaseManager then you can use the following installation command:

`choco install githubreleasemanager -source https://www.myget.org/F/ghrm_develop/ -pre`

This uses the public GitHubReleaseManager feed which is hosted on [MyGet.org](https://www.myget.org/)

## Build Status

AppVeyor  
-------------
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/20hvqfnv6dlwqld7/branch/develop?svg=true)](https://ci.appveyor.com/project/GaryEwanPark/githubreleasemanager)

## Chat Room

Come join in the conversation about GitHubReleaseManager in our Gitter Chat Room

[![Join the chat at https://gitter.im/gep13/GitHubReleaseManager](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/gep13/GitHubReleaseManager?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Contributing

If you would like to contribute code or help squash a bug or two, that's awesome.  Please familiarize yourself with [CONTRIBUTING](https://github.com/gep13/GitHubReleaseManager/blob/develop/CONTRIBUTING.md).

## Committers

Committers, you should be very familiar with [COMMITTERS](https://github.com/gep13/GitHubReleaseManager/blob/develop/COMMITTERS.md).

## Credits

GitHubReleaseManager is brought to you by quite a few people and frameworks.  See [CREDITS](https://github.com/gep13/GitHubReleaseManager/blob/develop/Documentation/legal/CREDITS.md) for full information.

Full original credit has to go to the people at [Particular Software](http://www.particular.net/), without whom this project would not have been possible.  They originally created the [GitHubReleaseNotes](https://github.com/Particular/GitHubReleaseNotes) project, which GitHubReleaseManager is based on, and draws a lot of inspiration from.  

Where GitHubReleaseNotes uses a set of fixed configuration, based on Particular's internal usage requirements, GitHubReleaseManager attempts to be fully configurable, so that the end user can decide what should be done when creating and exporting Release Notes on GitHub.  Huge thanks to the people at Particular for their support in helping me create this project.  For more information about what has changed between GitHubReleaseNotes and GitHubReleaseManager, see this [issue](https://github.com/gep13/GitHubReleaseManager/issues/24).

In addition, a large thank you has to go to again [Particular Software](http://www.particular.net/) and the contributors behind the [GitVersion](https://github.com/ParticularLabs/GitVersion) Project.  GitHubReleaseManager draws on the work done in that project in terms of initializing and using a YAML configuration file to allow setting of configuration properties at run-time.

## Icon

<a href="http://thenounproject.com/term/pull-request/116189/" target="_blank">Pull-request</a> designed by <a href="http://thenounproject.com/richard.slater/" target="_blank">Richard Slater</a> from The Noun Project.