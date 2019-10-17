# Bountysource App Requests
A place where users can request AppImages ports of missing applications not available for Nitrux.

## How does it work?

1. Open a *regular issue* in this repository and use this title format: [Nitrux] [App_Request] App_name.
2. Visit [Nitrux@Bountysource](https://www.bountysource.com/teams/nitrux/issues) and search for the application request that you created or that you're interested.
3. Click the like button and add a bounty to it. The bounty is a collective effort; the more people contribute to the pool, the better.
4. The minimum bounty for an application request is of **$250**. After this goal is met, we will begin porting the application to an AppImage with **amd64** as the target architecture.
5. After it has been adequately tested, it will be uploaded to [Pling.com](https://www.pling.com). Afterward, the opening issue will be closed.

We will ensure that the AppImages work on the newest and the oldest still supported versions of these distributions. Likely, the AppImage will also work on any derivative.

* Manjaro
* Fedora
* Ubuntu
* Debian
* openSUSE

# Will the AppImages that you generate work anywhere?

The AppImages that we create will target **amd64** primarily; however, if there are enough collective contributions, we can make sure that the AppImage will work on **aarch64** and **armhf** too.

## How does it work?

1. If there's enough demand for a given application to also work on other architectures, we will create a new issue, referencing the previous one and place a new minimum bounty goal.
2. The minimum bounty for this extended goal is of **$350**. As before, the bounty is a collective effort; the more people contribute to the pool, the better.
3. After it has been adequately tested, it will be uploaded to [Pling.com](PLing.com), in addition to the file for amd64. Afterward, the initial issue will be closed.

# Notes

* Application requests must not be, need or depend on i686 libraries.
* Electron applications may require extra work.
* Application requests closing comments will be accompanied by a link to the file at [Pling.com](https://www.pling.com), screenshots or a video of the AppImage functioning on (at least three of) the mentioned distributions.
* Bounties are paid off only until the issue (the application request) is solved, not before.

# Bugs

To report bugs with the provided AppImages, create a new issue and select *Bug Report* then click *Get started*.

©2019 Nitrux Latinoamericana S.C.
