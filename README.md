This is a simple hello world test of native-image with a Java executable jar (does not need shadow) and Kotlin (does need shadow)

Basically:
```
sdk install java 20.3.1.r11-grl 
gu install native-image
./gradlew build
native-image -jar build/libs/foo-all.jar
./foo
```
