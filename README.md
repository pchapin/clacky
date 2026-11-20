# Clacky

Clacky is an educational stack-based calculator written in Java. It is similar to
[Clac](https://github.com/pchapin/clac), a more full-featured version of the program that is written
in C++. The Android application [aClac](https://github.com/pchapin/aclac) is yet another version.

Clacky differs from the other two forms in that it is intentionaly simple and made suitable for
student study. I've also used it as the bases for student exploration of using AI agents.

## Building

Clacky uses Maven as its build tool. It is configured for Java 25 or later, so you will need to have
that installed first. However, you do not need to install Maven separately. Run the command:

```bash
./mvnw compile
```

This runs the Maven wrapper which will first download the Maven tool into your Maven cache (which it
will create if necessary). You can then use the `mvnw` wrapper as if it was Maven; all the usual
Maven goals apply.

Peter Chapin  
spicacality@kelseymountain.org  

