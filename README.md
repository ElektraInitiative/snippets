# libelektra - shared snippets #

Welcome to the snippet repository! Here you find all snippets that have
been shared through the snippet sharing service on our
[website](https://www.libelektra.org).

This repository mainly serves two purposes:

- backups for ourselves
- easier download of all snippets for you!

For license details please see [LICENSE.md](LICENSE.md).

## FAQ ##

### What can I do with this files? ###

If you want, you can download the snippets and mount them locally. You
then have access to all the snippets even without internet connection.

When you try to export snippets from the mounted file, you should make
sure to use the format/plugin that was used during upload. You can look
this up in the meta data of a snippet, e.g.
```
// retrieve upload format/plugin
kdb getmeta /<mountpoint>/path/to/the/snippet plugin

// export snippet with right format
kdb export /<mountpoint>/path/to/the/snippet <format/plugin>
```
