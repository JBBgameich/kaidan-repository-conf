# Kaidan apt repository config
To contribute to the apt repository at https://github.com/KaidanIM/packages, first create a local package database:
```
reprepro update sid
```
This will download the existing packages from our repository. You can now include new packages:
```
reprepro include sid /path/to/kaidan.changes
```
You can now copy the resulting dists/ and pool/ folders to a local checkout of https://github.com/KaidanIM/packages, commit, and push your new build.
