### Kotlin-Scala.js Hello World

This repository is a fully working demo of the [Kotlin-Scala.js](https://github.com/lionelfleury/Kotlin-Scala.js) project. We are compile `Main.kt` to JavaScript using the Scala.js compiler.

In order to build this project, you'll need to publish the [kotlin-scalajs-maven-plugin](https://github.com/ex0ns/kotlin-scalajs-maven-plugin) first.

You can run this example by using `mvn compile`, this will generate a file called `hello-world.js` inside the `target/sjs`
directory.

Once this file is generated, open `index.html` in you browser and `Hello World` should be displayed in the console.
