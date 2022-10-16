# Custom-Toast-Library
## How to get a Git project into your build:
- **Step 1. Add to your build file**
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
- **Step 2. Add the dependency**
```
dependencies {
	        implementation 'com.github.khan-mujeeb:Custom-Toast-Library:v1.0.0'
	}
```

### Toast with short time durarion
```java
CustomToast.simpleToast(this,message);
```

### Toast with custom time durarion
```java
int time_duration;
time_duration = 0;	// for LENGTH_SHORT
time_duration = 1;	// for LENGTH_LONG
CustomToast.simpleToast(this,message,time_duration);
```
