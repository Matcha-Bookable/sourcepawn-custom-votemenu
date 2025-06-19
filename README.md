[![Compile Plugin](https://github.com/Matcha-Bookable/sourcepawn-custom-votemenu/actions/workflows/build.yaml/badge.svg)](https://github.com/Matcha-Bookable/sourcepawn-custom-votemenu/actions/workflows/build.yaml)

# sourcepawn-custom-votemenu
Minor modification from the popular custom votemenu, which are currently in service for Matcha Bookable.

> **PLEASE DO NOT CREATE PRs, I AM SIMPLY SHARING MY ROBUST SOLUTION TO THIS SPECIFIC SOLUTION.**

## Modifications from the original
Some `git revert` operations has been applied:
- [Commit 4563638](https://github.com/caxanga334/cvreduxmodified/commit/4563638915485d1bedc44343d5459def20e6fa56)
- [Commit f1bcc6f](https://github.com/caxanga334/cvreduxmodified/commit/f1bcc6f2731a87002f0be04bfd5c3179aaede37d)
- [Commit 9a11e7d](https://github.com/caxanga334/cvreduxmodified/commit/9a11e7d6b216e30d1e8598ae4ffb6ec29ba7e143)

### Goal
To move away from the original `ReadMapList()` function into a custom operation which will return the arraylist of map without the need to actually store them.

This is specifically modified to shrink the docker image size for [Matcha-Bookable/matcha-docker-tf2](https://github.com/Matcha-Bookable/matcha-docker-tf2) by using `changelevel`, relatively robust but seems to work as expected.

### Credits

- [caxanga334/cvreduxmodified](https://github.com/caxanga334/cvreduxmodified) - for the maintained version of cv and the workflow
- [ReFlexPoison/custom-vote](https://forums.alliedmods.net/showthread.php?t=235115) - for the original version of cv