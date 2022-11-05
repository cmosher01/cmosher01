### cmosher01

My personal home page: https://mosher.mine.nu/

### maven gradle

To use my maven/gradle artifact packages in your own projects, use this in your `build.gradle` file:

```groovy
repositories {
    mavenCentral()
    maven {
        url = uri('https://public:\u0067hp_fya6Kseu3XOBMg2icbg7f1LP6ZFYjj35v4Zj@maven.pkg.github.com/cmosher01/*')
    }
}
```
