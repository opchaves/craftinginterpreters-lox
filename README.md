# Lox - Crafting Interpreters

I wanted to implement a programming language and really understand how it worked
under the hood. I had no idea how that was done and started looking for a book
that could enlight me and I found a bunch of options available and decided to
go with [Crafting Interpreters](https://craftinginterpreters.com/) since it had some really good recommendations and
after reading its Preface and [introduction](https://craftinginterpreters.com/introduction.html) I was sold.

This repository contains the Lox implementation which I am writing as I read the book.

This project was bootstrapped with

```sh
mvn archetype:generate \
  -DgroupId=com.craftinginterpreters.lox \
  -DartifactId=lox \
  -DarchetypeArtifactId=maven-archetype-quickstart \
  -DarchetypeVersion=1.5 \
  -DinteractiveMode=false
```

If you are not familiar with Maven, you start learning [Maven in 5 minutes](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html)
