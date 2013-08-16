See sub-folders for documentation.

## Maven repository

#### Use with Maven
``` xml
<repositories>
   ...
   <repository>
      <id>bintray-jcenter</id>
      <url>http://jcenter.bintray.com</url>
      <snapshots>
         <enabled>false</enabled>
      </snapshots>
   </repository>
   ...
</repositories>
```

#### Or with Gradle
```groovy
   repositories {
      ...
      maven { url 'http://jcenter.bintray.com' }
      ...
   }
```

## License

Copyright 2013 AnjLab

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
