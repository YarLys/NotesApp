# NotesApp
Мобильное приложение "Заметки" на Kotlin.
Использование Jetpack Compose, Dagger Hilt, Room. 
Архитектура: MVI с использованием принципов Clean Architecture.

В приложении можно просматривать созданные заметки, редактировать их, создавать новые, удалять, а также сортировать по параметрам и ключевым словам в строке поиска.

## Сборка и запуск
Для сборки проекта используется Gradle. 
### Необходимые зависимости и версии для запуска:
- Minimum SDK – 29
- CompileSDK – 35 
- TargetSDK – 35
- JDK Version – 17
- Kotlin Version – 1.9.0
### Compose dependencies
- implementation("androidx.lifecycle:lifecycle-viewmodel-compose:2.9.0-alpha10")
- implementation("androidx.navigation:navigation-compose:2.9.0-alpha06")
- implementation("com.google.accompanist:accompanist-flowlayout:0.17.0")
- implementation("androidx.compose.material:material:1.7.8")
### Coroutines
- implementation("org.jetbrains.kotlinx:kotlinx-coroutines-core:1.7.3")
- implementation("org.jetbrains.kotlinx:kotlinx-coroutines-android:1.7.3")
### Dagger - Hilt
- implementation("androidx.hilt:hilt-navigation-compose:1.2.0")
- implementation("com.google.dagger:hilt-android:2.51.1")
- kapt("com.google.dagger:hilt-android-compiler:2.51.1")
- kapt("androidx.hilt:hilt-compiler:1.2.0")
### Room
- implementation("androidx.room:room-runtime:2.6.1")
- kapt("androidx.room:room-compiler:2.6.1")
### Kotlin Extensions and Coroutines support for Room
- implementation("androidx.room:room-ktx:2.6.1")

Для запуска необходимо установить Android Studio для последующей сборки проекта из исходных данных с запуском на эмуляторе или же на своем смартфоне, либо скачать apk и запустить его на смартфоне непосредственно. 
