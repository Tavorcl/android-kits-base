# Android Kits Base

[![javadoc](https://javadoc.io/badge2/me.tatiyanupanwong.supasin.android.libraries.kits.base/base-core/javadoc.svg)](https://javadoc.io/doc/com.tavorlabs.android.libraries.kits.base/base-core)
[![license](https://img.shields.io/github/license/SupasinTatiyanupanwong/android-kits-base.svg)](https://www.apache.org/licenses/LICENSE-2.0)

Base APIs for libraries in Android Kits collections

## Declaring dependencies

Add the dependencies for the artifacts you need in the ```build.gradle``` file for your app or module:

```groovy
dependencies {
    // Only if the vendor-specific implementation is not needed
    implementation 'com.tavorlabs.android.libraries.kits.base:base-core:1.0.0'

    // Google-specific implementation
    implementation 'com.tavorlabs.android.libraries.kits.base:base-google:1.0.0'

    // Lost-specific implementation
    implementation 'com.tavorlabs.android.libraries.kits.base:base-lost:1.0.1'

    // Huawei-specific implementation
    implementation 'com.tavorlabs.android.libraries.kits.base:base-huawei:1.0.0'
}
```

It should be noted that there is no need to explicitly declare dependencies for this.

For more information about dependencies, see [Add build dependencies](https://developer.android.com/studio/build/dependencies).

## License

Please note that is repo has been forked from [this one](https://github.com/SupasinTatiyanupanwong/android-kits-base).
This fork only adds the "lost" module.
```
Copyright (C) 2020 Supasin Tatiyanupanwong

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
