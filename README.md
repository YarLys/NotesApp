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
- implementation "androidx.lifecycle:lifecycle-viewmodel-compose:2.4.0-beta01"
- implementation "androidx.navigation:navigation-compose:2.4.0-alpha09"
- implementation "androidx.compose.material:material-icons-extended:$compose_version"
- implementation "androidx.hilt:hilt-navigation-compose:1.0.0-alpha03"
### Coroutines
- implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-core:1.5.0'
- implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.5.1'
### Dagger - Hilt
- implementation "com.google.dagger:hilt-android:2.38.1"
- kapt "com.google.dagger:hilt-android-compiler:2.37"
- implementation "androidx.hilt:hilt-lifecycle-viewmodel:1.0.0-alpha03"
- kapt "androidx.hilt:hilt-compiler:1.0.0"
### Room
- implementation "androidx.room:room-runtime:2.3.0"
- kapt "androidx.room:room-compiler:2.3.0"
### Kotlin Extensions and Coroutines support for Room
- implementation "androidx.room:room-ktx:2.3.0"

Для запуска необходимо установить Android Studio для последующей сборки проекта из исходных данных с запуском на эмуляторе или же на своем смартфоне, либо скачать apk и запустить его на смартфоне непосредственно. 
