# Android Logs

An Android Logging library. You can find your logs with the line number.

## Usage

### Step 1

Add below dependency in your **build.gradle** file.

```groovy
dependencies {
    implementation 'com.github.vishwakarmasunil68:tagutil:1.0'
}
```
```groovy
maven { url 'https://jitpack.io' }
```


### Step 2

Use TagView in your code.
```java
        Log.d(TagUtils.getTag(),"debug log");
        Log.i(TagUtils.getTag(),"information log");
        Log.v(TagUtils.getTag(),"verbose log");
        Log.e(TagUtils.getTag(),"error log");
```

