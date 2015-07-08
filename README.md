### Android development environment for ubuntu precise (12.04 LTS)

* Oracle Java JDK 6
* Android SDK r24.3.3
* Android NDK r10e
* Apache Ant 1.9.6

It also updates the SDK to android 19 (4.4.2) with platform tools and system images for that revision.

#### Install

You can either pull from `quicksign/android-sdk`:

```
docker pull quicksign/android-sdk
```

```
docker run -i -t quicksign/android-sdk /bin/bash
```

or add it to your Dockerfile:

```
FROM quicksign/android-sdk
```
