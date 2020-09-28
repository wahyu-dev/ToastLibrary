# Toast Library

Ini Library untuk menampilkan toast

## Installation

### Step 1. Add the JitPack repository to your build file

```
allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}
```
  
### Step 2. Add the dependency

```
dependencies {
	implementation 'com.github.wahyu-pro:toast-library:Tag'
}
```
  
## Usage example

``` ToasterMessage.show(this, "Message");```
