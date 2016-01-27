use Gradle:

```gradle
allprojects {  
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}

dependencies {
		compile 'com.github.locbvh:ExpandableLayout:1.0'
	}
```
