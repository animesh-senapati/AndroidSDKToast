> Step 1. Add the JitPack repository to your build file

dependencyResolutionManagement {
		repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
		repositories {
			mavenCentral()
			maven { url 'https://jitpack.io' }
		}
	}

> Step 2. Add the dependency
dependencies {
	        implementation 'com.github.animesh-senapati:AndroidSDKToast:1.0.0'
	}


Used For Java 11 and above java versions.
