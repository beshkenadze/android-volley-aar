android-volley-aar
========================

Volley library built with gradle in aar format for usage with android gradle build system. 

How to use
=======================
Before you can get aar you should checkout [volley](https://android.googlesource.com/platform/frameworks/volley) submodule.:
```bash
  $ git submodule update --init
  ...
  $ ./gradlew build
  ...
```

When build is finished aar file will be located in `build/libs`.

Maven artifact in local repo
======================

```bash
  $ ./gradlew clean build uploadArchives
```
