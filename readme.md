# Daikoku Jar file CleverCloud template

This repo holds the build of Daikoku for CleverCloud

Otoroshi sources are located at https://github.com/MAIF/daikoku

Don't forget to add a prebuild hook on the CleverCloud app to trigger the build script

```
CC_PRE_BUILD_HOOK=./clevercloud/build.sh
```

If you want to customize the build script, edit `./clevercloud/build.sh`

If you want to customize the configuration [use env. variables](https://github.com/MAIF/daikoku)
