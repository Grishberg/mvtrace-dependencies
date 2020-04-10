Forked AOSP libraries for access to mvtrace tools

#How to install:
1) add to build.gradle
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

2) add dependency

```
dependencies {
   implementation 'com.github.Grishberg:mvtrace-dependencies:Tag'
}
```