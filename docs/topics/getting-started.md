[//]: # (title: Get started with Kotlin)

Kotlin is a modern but already mature programming language designed to make developers happier.
It's concise, safe, interoperable with Java and other languages, and provides many ways to reuse code between multiple platforms for productive programming.

To start, why not take our tour of Kotlin? This tour covers the fundamentals of the Kotlin programming language and can
be completed entirely within your browser.

<a href="kotlin-tour-welcome.md"><img src="start-kotlin-tour.svg" width="700" alt="Start the Kotlin tour" style="block"/></a>

## Install Kotlin

Kotlin is included in each [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) and [Android Studio](https://developer.android.com/studio) release.
Download and install one of these IDEs to start using Kotlin.

## Choose your Kotlin use case
 
<tabs>

<tab id="console" title="Console">

Here you'll learn how to develop a console application and create unit tests with Kotlin.

1. **[Create a basic JVM application with the IntelliJ IDEA project wizard](jvm-get-started.md).**

2. **[Write your first unit test](jvm-test-using-junit.md).**

3. **Join the Kotlin community:**

   * ![Slack](slack.svg){width=25}{type="joined"} Slack: [get an invite](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up).
   * ![StackOverflow](stackoverflow.svg){width=25}{type="joined"} StackOverflow: subscribe to the ["kotlin"](https://stackoverflow.com/questions/tagged/kotlin) tag.

4. **Follow Kotlin** on:

   * ![Twitter](twitter.svg){width=18}{type="joined"} [Twitter](https://twitter.com/kotlin)
   * ![Reddit](reddit.svg){width=25}{type="joined"} [Reddit](https://www.reddit.com/r/Kotlin/)
   * ![YouTube](youtube.svg){width=25}{type="joined"} [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw)

If you encounter any difficulties or problems, report an issue in our [issue tracker](https://youtrack.jetbrains.com/issues/KT).

</tab>

<tab id="backend" title="Backend">

Here you'll learn how to develop a backend application with Kotlin server-side.

1. **Create your first backend application:**

     * [Create a RESTful web service with Spring Boot](jvm-get-started-spring-boot.md).
     * [Create HTTP APIs with Ktor](https://ktor.io/docs/creating-http-apis.html).

2. **[Learn how to mix Kotlin and Java code in your application](mixing-java-kotlin-intellij.md).**

3. **Join the Kotlin server-side community:**

   * ![Slack](slack.svg){width=25}{type="joined"} Slack: [get an invite](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up).
   * ![StackOverflow](stackoverflow.svg){width=25}{type="joined"} StackOverflow: subscribe to the ["kotlin"](https://stackoverflow.com/questions/tagged/kotlin) tag.

4. **Follow Kotlin** on:

   * ![Twitter](twitter.svg){width=18}{type="joined"} [Twitter](https://twitter.com/kotlin)
   * ![Reddit](reddit.svg){width=25}{type="joined"} [Reddit](https://www.reddit.com/r/Kotlin/)
   * ![YouTube](youtube.svg){width=25}{type="joined"} [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw)

If you encounter any difficulties or problems, report an issue in our [issue tracker](https://youtrack.jetbrains.com/issues/KT).

</tab>

<tab id="cross-platform-mobile" title="Cross-platform">

Here you'll learn how to develop and improve your cross-platform application using [Kotlin Multiplatform](https://kotlinlang.org/lp/multiplatform/).

1. **[Set up your environment for cross-platform development](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-setup.html).**

2. **Create your first application for iOS and Android:**

   * To start from scratch, [create a basic cross-platform application with the project wizard](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-create-first-app.html).
   * If you have an existing Android application and want to make it cross-platform, complete the [Make your Android application work on iOS](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-integrate-in-existing-app.html) tutorial.
   * If you prefer real-life examples, clone and play with an existing project, for example the networking and data storage project from the [Create a multiplatform app using Ktor and SQLdelight](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-ktor-sqldelight.html) tutorial or any [sample project](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-samples.html).

3. **Use a wide set of multiplatform libraries** to implement the required business logic only once in the shared module. Learn more about [adding dependencies](multiplatform-add-dependencies.md).

   | Library       | Details                                                                                                                                                            |
   |---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------| 
   | Ktor          | [Docs](https://ktor.io/docs/client.html)                                                                                                                           | 
   | Serialization | [Docs](serialization.md) and [sample](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-ktor-sqldelight.html#create-an-application-data-model) |
   | Coroutines    | [Docs](coroutines-guide.md) and [sample](coroutines-and-channels.md)                                                                                               |
   | DateTime      | [Docs](https://github.com/Kotlin/kotlinx-datetime#readme)                                                                                                          |
   | SQLDelight    | Third-party library. [Docs](https://cashapp.github.io/sqldelight/)                                                                                                 |

   > You can also find a multiplatform library in the [community-driven list](https://libs.kmp.icerock.dev/).
   >
   {style="tip"}

4. **Learn more about Kotlin Multiplatform:**
   * Learn more about [Kotlin Multiplatform](multiplatform-intro.md).
   * Look through [samples projects](https://www.jetbrains.com/help/kotlin-multiplatform-dev/multiplatform-samples.html).
   * [Publish a multiplatform library](multiplatform-publish-lib.md).
   * Learn how Kotlin Multiplatform is used at [Netflix](https://netflixtechblog.com/netflix-android-and-ios-studio-apps-kotlin-multiplatform-d6d4d8d25d23), [VMware](https://kotlinlang.org/lp/multiplatform/case-studies/vmware/), [Yandex](https://kotlinlang.org/lp/multiplatform/case-studies/yandex/), and [many other companies](https://kotlinlang.org/lp/multiplatform/case-studies/).

5. **Join the Kotlin Multiplatform community:**

   * ![Slack](slack.svg){width=25}{type="joined"} Slack: [get an invite](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up) and join the [#getting-started](https://kotlinlang.slack.com/archives/C0B8MA7FA) and [#multiplatform](https://kotlinlang.slack.com/archives/C3PQML5NU) channels.
   * ![StackOverflow](stackoverflow.svg){width=25}{type="joined"} StackOverflow: Subscribe to the ["kotlin-multiplatform" tag](https://stackoverflow.com/questions/tagged/kotlin-multiplatform).

6. **Follow Kotlin** on:

   * ![Twitter](twitter.svg){width=18}{type="joined"} [Twitter](https://twitter.com/kotlin)
   * ![Reddit](reddit.svg){width=25}{type="joined"} [Reddit](https://www.reddit.com/r/Kotlin/)
   * ![YouTube](youtube.svg){width=25}{type="joined"} [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw)

If you encounter any difficulties or problems, report an issue to our [issue tracker](https://youtrack.jetbrains.com/issues/KT).

</tab>

<tab id="android" title="Android">

To start using Kotlin for Android development, read [Google's recommendation for getting started with Kotlin on Android](https://developer.android.com/kotlin/get-started).

Follow Kotlin on ![Twitter](twitter.svg){width=18}{type="joined"} [Twitter](https://twitter.com/kotlin), ![Reddit](reddit.svg){width=25}{type="joined"} [Reddit](https://www.reddit.com/r/Kotlin/), and ![YouTube](youtube.svg){width=25}{type="joined"} [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw), and don't miss any important ecosystem updates.

</tab>

<tab id="data-analysis" title="Data analysis">

From building data pipelines to productionizing machine learning models, Kotlin is a great choice for working with data and getting the most out of it.

1. **Create and edit notebooks seamlessly within the IDE:**

   * [Get started with Kotlin Notebook](get-started-with-kotlin-notebooks.md).

2. **Explore and experiment with your data:**

   * [DataFrame](https://kotlin.github.io/dataframe/overview.html) – a library for data analysis and manipulation.
   * [Kandy](https://kotlin.github.io/kandy/welcome.html) – a plotting tool for data visualization.

3. **Get the latest updates about Kotlin for Data Analysis:**

   * ![Slack](slack.svg){width=25}{type="joined"} Slack: [get an invite](https://surveys.jetbrains.com/s3/kotlin-slack-sign-up) and join the [#datascience](https://kotlinlang.slack.com/archives/C4W52CFEZ) channel.
   * ![Twitter](twitter.svg){width=18}{type="joined"} Twitter: follow [KotlinForData](http://twitter.com/KotlinForData).

4. **Follow Kotlin** on:
   * ![Twitter](twitter.svg){width=18}{type="joined"} [Twitter](https://twitter.com/kotlin)
   * ![Reddit](reddit.svg){width=25}{type="joined"} [Reddit](https://www.reddit.com/r/Kotlin/)
   * ![YouTube](youtube.svg){width=25}{type="joined"} [Youtube](https://www.youtube.com/channel/UCP7uiEZIqci43m22KDl0sNw)

</tab>

</tabs>

## Is anything missing?

If anything is missing or seems confusing on this page, please [share your feedback](https://surveys.hotjar.com/d82e82b0-00d9-44a7-b793-0611bf6189df).
