# Blizzard

Welcome to the GitHub repository for Blizzard!

## Purpose

Blizzard is designed to improve accessibility for Velocity-CTD. It also includes other expansions created by me.

## Goals

* A codebase that is easy to dive into and consistently follows best practices
  for Java projects as much as reasonably possible.
* High performance: handle thousands of players on one proxy.
* Features that expand the "all-in-one" experience offered by Velocity-CTD.

## Features

* Translations for other languages.
* Configurable `/ghelp` command that lists the commands you have access to.
* Advanced configuration for "/velocity:callback".

## Blizzard Permissions
* `blizzard.command.ghelp` [/ghelp] (Shows what commands you have access to).
* `velocity.command.callback` [/velocity:callback] (Allows executing "/velocity:callback", if you've enabled the permission node).
* `velocity.command.callback.output` [/velocity:callback] (Allows you to see diagnostic output, if you've enabled the feature).

## Special Notes
To proficiently review the stability and performance of your proxy in addition to spark,
consider utilizing JProfiler to enhance your experience and report any ongoing issues.

[![JProfiler](https://github.com/user-attachments/assets/d4f6a94b-8da2-484a-85c8-537a4d19d188)](https://www.ej-technologies.com/jprofiler)

## Building

Blizzard is built with [Gradle](https://gradle.org). We recommend using the
wrapper script (`./gradlew`) as our CI builds using it.

It is sufficient to run `./gradlew build` to run the full build cycle.

You can find new releases of Blizzard in our [releases](https://github.com/Mickey42302/Blizzard/releases) tab,
where our latest updates will be compiled and ready for use.

## Running

Once you've built Velocity, you can copy and run the `-all` JAR from
`proxy/build/libs`. Blizzard will generate a default configuration file,
and you can configure it from there.
