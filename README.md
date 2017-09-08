# My Pinch ImageView [![Release](https://jitpack.io/v/mayojava/statlib.svg)](https://jitpack.io/#moizest89/mypinchimageview)
Statistics library for Android

# Download
Add it in your root `build.gradle` at the end of repositories:

```
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```
Add the dependency to your add module `build.gradle` file:

```
dependencies {
	compile 'com.github.moizest89:mypinchimageview:v1.0'
}

```
# Usage

Add Custom ImageView into layout

```

<com.moizest89.android.mypinchimageview.MyPinchImageView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="centerCrop" />
        

```

# License
```
Copyright 2017 Moises Portillo

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```