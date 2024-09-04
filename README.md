## Installation

To use this library in your Android project, follow the steps below:

### Step 1: Add the JitPack repository

Add the JitPack repository to your `settings.gradle` file at the end of the `repositories` block:

```gradle
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
}

```

### Step 2. Add the dependency

```gradle
dependencies {
    implementation 'com.github.bhupenderandroid007:monita_anroid_sdk_new:v1.0.0'
}



```
