# sourcepawn-custom-votemenu
Forked from [caxanga334/cvreduxmodified](https://github.com/caxanga334/cvreduxmodified)

## Modifications from the original
Some `git revert` operation has been applied:
- [Commit 4563638](https://github.com/caxanga334/cvreduxmodified/commit/4563638915485d1bedc44343d5459def20e6fa56)
- [Commit f1bcc6f](https://github.com/caxanga334/cvreduxmodified/commit/f1bcc6f2731a87002f0be04bfd5c3179aaede37d)
- [Commit 9a11e7d](https://github.com/caxanga334/cvreduxmodified/commit/9a11e7d6b216e30d1e8598ae4ffb6ec29ba7e143)

### Goal
To move away from the original `ReadMapList()` function into a custom operation which will return the arraylist of map without the need to actually store them.