# AllureApi31

Issue reproduces on Android Emulator with x86_64 Android S image.

To reproduce the issue just run `./gradlew connectedDebugAndroidTest`

```
$ ./gradlew connectedDebugAndroidTest

> Task :app:connectedDebugAndroidTest
Starting 1 tests on Pixel_4_API_31(AVD) - 12

com.example.allureapi31.ExampleInstrumentedTest > useAppContext[Pixel_4_API_31(AVD) - 12] FAILED
io.qameta.allure.kotlin.AllureResultsWriteException: Could not create Allure results directory
at io.qameta.allure.kotlin.FileSystemResultsWriter.createDirectories(FileSystemResultsWriter.kt:61)

> Task :app:connectedDebugAndroidTest FAILED
```