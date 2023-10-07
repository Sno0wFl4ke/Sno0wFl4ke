```kotlin
package de.sno0wfl4ke.aboutme

class Sno0wFl4ke {
    val name = "Philip"
    val age = 18
    val occupation = Occupation("Student", "RUB")
    val origin = Countries.GERMANY
    val languages = listOf(Languages.GERMAN, Languages.ENGLISH, Languages.FRENCH, Languages.NORWEGIAN)
    val interests = listOf("Programming", "Illustration", "Biology", "Music", "Cooking")

    fun getCodingLanguages() : List<String> {
        return listOf("Kotlin", "Java", "SwiftUI")
    }

    fun getInTouch() : Contact {
        return Contact(
            Discord("sno0wfl4ke"),
            Mail("beeadev@outlook.com"),
            Twitter("@meSno0wFl4ke")
        )
    }
}
```

<!---
Sno0wFl4ke/Sno0wFl4ke is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
