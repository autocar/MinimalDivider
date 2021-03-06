# MinimalDivider

[![Download](https://api.bintray.com/packages/darkowlzz/maven/MinimalDivider/images/download.svg) ](https://bintray.com/darkowlzz/maven/MinimalDivider/_latestVersion)

A minimalist divider view component for android. Create simple and elegant horizontal dividers.

![Demo](/images/demo_screenshot.png)

## Usage

Add MinimalDivider to the project and add MinimalDivider to layout.

```xml
<space.darkowlzz.minimaldivider.MinimalDivider
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="10dp"
        minimaldivider:dividerLine_color="@android:color/holo_orange_dark"/>
```

Add the namespace as
```xml
xmlns:minimaldivider="http://schemas.android.com/apk/res-auto"
```

Learn more about the available view attributes from [here](https://github.com/darkowlzz/MinimalDivider/blob/master/minimaldivider/src/main/res/values/attrs.xml).


## Gradle

Add to build.gradle dependencies

```groovy
dependencies {
  compile 'space.darkowlzz:minimaldivider:0.1.0'
}
```

## LICENSE

MIT &copy; 2016 Sunny (darkowlzz)
