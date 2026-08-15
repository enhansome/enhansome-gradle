# Awesome Gradle with stars

> A curated list of awesome Gradle plugins and resources for a better development workflow automation.

Inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 495,922 | 🐛 100 | 📅 2026-06-30, [awesome-gulp](https://github.com/alferov/awesome-gulp) ⭐ 624 | 🐛 4 | 🌐 JavaScript | 📅 2022-04-12 and some other awesome lists.

## Table of contents

* [Plugins](#plugins)
  * [Language](#language)
  * [Code quality](#code-quality)
  * [Code generation](#code-generation)
  * [Java application development](#java-application-development)
  * [Web application development](#web-application-development)
  * [Android application development](#android-application-development)
  * [iOS and Mac application development](#ios-and-mac-application-development)
  * [Editor and IDE integration](#editor-and-ide-integration)
  * [Templating](#templating)
  * [Database](#database)
  * [Dependency management](#dependency-management)
  * [Debugging](#debugging)
  * [Testing](#testing)
  * [Building](#building)
  * [Packaging](#packaging)
  * [Releasing](#releasing)
  * [Notification](#notification)
  * [Cloud services](#cloud-services)
  * [SCM](#scm)
  * [CI](#ci)
  * [VM and container](#vm-and-container)
* [Boilerplates](#boilerplates)
* [Resources](#resources)
  * [General Resources](#general-resources)
  * [Official Documentation](#official-documentation)

## Plugins

> Notice: in the following descriptions, "Official plugin" means that it's provided as a builtin plugin by Gradle.

### Language

* [gradle-retrolambda](https://github.com/evant/gradle-retrolambda) ⭐ 5,254 | 🐛 76 | 🌐 Java | 📅 2023-07-24 - Get Java lambda support in Java 6, 7 and Android.
* [clojurephant](https://github.com/clojurephant/clojurephant) ⚠️ Archived - Clojure/ClojureScript support for Gradle
* [java](https://docs.gradle.org/current/userguide/java_plugin.html) - Official plugin that adds Java compilation, testing and bundling capabilities.
* [groovy](https://docs.gradle.org/current/userguide/groovy_plugin.html) - Official plugin that adds support for building Groovy projects.
* [scala](https://docs.gradle.org/current/userguide/scala_plugin.html) - Official plugin that adds support for building Scala projects.
* [antlr](https://docs.gradle.org/current/userguide/antlr_plugin.html) - Official plugin that adds support for generating parsers using [Antlr](http://www.antlr.org/).
* [assembler](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds native assembly language capabilities to a project.
* [c](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds C source compilation capabilities to a project.
* [cpp](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds C++ source compilation capabilities to a project.
* [objective-c](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds Objective-C source compilation capabilities to a project.
* [objective-cpp](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds Objective-C++ source compilation capabilities to a project.

### Code quality

* [spotless](https://github.com/diffplug/spotless/tree/master/plugin-gradle) ⭐ 5,609 | 🐛 267 | 🌐 Java | 📅 2026-08-12 - Checks and applies formatting rules using the Eclipse, google-java-format, ktlint, scalafmt, and also user-defined rules.
* [gradle-errorprone-plugin](https://github.com/tbroyer/gradle-errorprone-plugin) ⭐ 402 | 🐛 4 | 🌐 Java | 📅 2026-08-14 - Use the [error-prone](https://github.com/google/error-prone) ⭐ 7,223 | 🐛 515 | 🌐 Java | 📅 2026-08-15 compiler for Java.
* [coveralls-gradle-plugin](https://github.com/kt3k/coveralls-gradle-plugin) ⚠️ Archived - Send coverage data to [coveralls.io](https://coveralls.io/).
* [gradle-cobertura-plugin](https://github.com/stevesaliman/gradle-cobertura-plugin) ⭐ 119 | 🐛 37 | 🌐 Groovy | 📅 2022-05-21 - Use cobertura.
* [gradle-scoverage](https://github.com/scoverage/gradle-scoverage) ⭐ 54 | 🐛 46 | 🌐 Java | 📅 2026-07-19 - Enable the use of Scoverage in a Gradle Scala project.
* [gradle-modernizer-plugin](https://github.com/simonharrer/gradle-modernizer-plugin) ⚠️ Archived - Detect uses of legacy Java APIs.
* [gradle-spelling-plugin](https://github.com/ksoichiro/gradle-spelling-plugin) ⭐ 5 | 🐛 0 | 🌐 Groovy | 📅 2016-03-14 - Inspect spelling using custom blacklist.
* [findbugs](https://docs.gradle.org/current/userguide/findbugs_plugin.html) - Official plugin that performs quality checks on Java source files using [FindBugs](http://findbugs.sourceforge.net/).
* [spotbugs](https://plugins.gradle.org/plugin/com.github.spotbugs) - Official plugin that performs quality checks on Java source files using [SpotBugs](https://spotbugs.github.io/).
* [checkstyle](https://docs.gradle.org/current/userguide/checkstyle_plugin.html) - Official plugin that performs quality checks on Java source files using [Checkstyle](http://checkstyle.sourceforge.net/index.html).
* [pmd](https://docs.gradle.org/current/userguide/pmd_plugin.html) - Official plugin that performs quality checks on your project's Java source files using [PMD](http://pmd.sourceforge.net/).
* [jdepend](https://docs.gradle.org/current/userguide/jdepend_plugin.html) - Official plugin that performs quality checks on your project's source files using [JDepend](http://clarkware.com/software/JDepend.html).
* [codenarc](https://docs.gradle.org/current/userguide/codenarc_plugin.html) - Official plugin that Performs quality checks on Groovy source files using [CodeNarc](http://codenarc.sourceforge.net/index.html).
* [jacoco](https://docs.gradle.org/current/userguide/jacoco_plugin.html) - Official plugin that provides integration with the [JaCoCo](http://www.eclemma.org/jacoco/) code coverage library for Java.

### Code generation

* [querydsl-plugin](https://github.com/ewerk/gradle-plugins/tree/master/querydsl-plugin) ⚠️ Archived - Generate [Querydsl](http://www.querydsl.com/) classes.
* [gradle-protobuf-plugin](https://github.com/tcawley/gradle-protobuf-plugin) ⭐ 12 | 🐛 3 | 🌐 Groovy | 📅 2014-05-11 - Compile [Google Protocol Buffers](https://developers.google.com/protocol-buffers/) files.

### Java application development

* [gradle-apt-plugin](https://github.com/tbroyer/gradle-apt-plugin) ⚠️ Archived - Make it easier/safer to use Java annotation processors.
* [vertx-gradle-plugin](https://github.com/darylteo/vertx-gradle-plugin) ⚠️ Archived - Unofficial plugin for starting Vert.x projects.

### Web application development

* [gradle-node-plugin](https://github.com/srs/gradle-node-plugin) ⭐ 865 | 🐛 187 | 🌐 Groovy | 📅 2021-03-25 - Run NodeJS scripts.
* [gretty](https://github.com/akhikhl/gretty) ⭐ 649 | 🐛 234 | 🌐 Groovy | 📅 2023-12-28 - Run web apps on jetty and tomcat.
* [gradle-tomcat-plugin](https://github.com/bmuschko/gradle-tomcat-plugin) ⚠️ Archived - Support deployment of your web application to an embedded Tomcat web container.
* [gradle-js-plugin](https://github.com/eriwen/gradle-js-plugin) ⚠️ Archived - Manage JavaScript.
* [asset-pipeline](https://github.com/bertramdev/asset-pipeline) ⭐ 198 | 🐛 36 | 🌐 JavaScript | 📅 2026-08-14 - Manage and process static assets in JVM applications.
* [gradle-grunt-plugin](https://github.com/srs/gradle-grunt-plugin) ⭐ 106 | 🐛 15 | 📅 2016-12-02 - Run Grunt tasks.
* [gradle-gulp-plugin](https://github.com/srs/gradle-gulp-plugin) ⭐ 69 | 🐛 15 | 📅 2016-12-02 - Run Gulp tasks.
* [gradle-compass](https://github.com/robfletcher/gradle-compass) ⭐ 60 | 🐛 36 | 🌐 Groovy | 📅 2020-01-10 - Compile and watche SASS files.
* [gradle-jrebel-plugin](https://github.com/zeroturnaround/gradle-jrebel-plugin) ⭐ 52 | 🐛 1 | 🌐 Java | 📅 2025-09-05 - Generate rebel.xml configuration file.
* [rest-gradle-plugin](https://github.com/noamt/rest-gradle-plugin) ⭐ 48 | 🐛 14 | 🌐 Groovy | 📅 2016-10-26 - Perform REST requests.
* [apina](https://github.com/EvidentSolutions/apina) ⭐ 31 | 🐛 9 | 🌐 Kotlin | 📅 2026-06-16 - Creates client-side TypeScript from server-side APIs.
* [bower-installer-plugin](https://github.com/craigburke/bower-installer-gradle) ⭐ 28 | 🐛 0 | 🌐 Groovy | 📅 2016-12-06 - Manage client-side dependencies.
* [gradle-web-resource-plugin](https://github.com/ksoichiro/gradle-web-resource-plugin) ⭐ 21 | 🐛 7 | 🌐 Groovy | 📅 2018-06-27 - Use CoffeeScript, LESS and Bower libraries without Node.js/npm.
* [gradle-jslint-plugin](https://github.com/kellyrob99/gradle-jslint-plugin) ⭐ 15 | 🐛 4 | 🌐 Groovy | 📅 2012-09-27 - Run JSLint static analysis against JavaScipt code.
* [spring-boot](http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#build-tool-plugins-gradle-plugin) - Provide Spring Boot support.

### Android application development

* Dependency management
  * [sdk-manager-plugin](https://github.com/JakeWharton/sdk-manager-plugin) ⚠️ Archived - Download and manage Android SDK.
  * [android-native-dependencies](https://github.com/nhachicha/android-native-dependencies) ⭐ 200 | 🐛 10 | 🌐 Groovy | 📅 2017-08-14 - Gradle plugin for resolving and downloading Android native dependencies (.so)
* Alternative language
  * [groovy-android-gradle-plugin](https://github.com/groovy/groovy-android-gradle-plugin) ⚠️ Archived - Support the Groovy language for building Android apps.
* APK handling
  * [dexcount-gradle-plugin](https://github.com/KeepSafe/dexcount-gradle-plugin) ⭐ 3,072 | 🐛 1 | 🌐 Java | 📅 2025-11-26 - Report the number of method references in APK.
  * [gradle-android-apk-size-plugin](https://github.com/vanniktech/gradle-android-apk-size-plugin) ⚠️ Archived - Gradle plugin that generates CSV files with apk size per output and variant of an apk.
  * [android-gradle-mulchannel-plugin](https://github.com/ihrthk/android-gradle-mulchannel-plugin) ⭐ 43 | 🐛 5 | 🌐 Groovy | 📅 2016-01-25 - Generate multiple apks from different channel.
* Build variant handling
  * [gradle-advanced-build-version](https://github.com/moallemi/gradle-advanced-build-version) ⭐ 608 | 🐛 10 | 🌐 Kotlin | 📅 2026-02-21 - Generate the Android version code and version name automatically.
  * [gradle-config](https://github.com/tmiyamon/gradle-config) ⚠️ Archived - Handle variant specific settings with yaml format.
* Icons
  * [gradle-android-ribbonizer-plugin](https://github.com/gfx/gradle-android-ribbonizer-plugin) ⭐ 352 | 🐛 8 | 🌐 Java | 📅 2023-10-10 - Add a ribbon to launcher icons of Android apps.
  * [gradle-mdicons](https://github.com/tmiyamon/gradle-mdicons) ⚠️ Archived - Manage material design icons.
  * [gradle-android-appiconoverlay](https://github.com/splatte/gradle-android-appiconoverlay) ⭐ 66 | 🐛 2 | 🌐 Groovy | 📅 2017-11-25 - Automatically overlay the app icon with the current git commit SHA1.
* Releasing
  * [gradle-play-publisher](https://github.com/Triple-T/gradle-play-publisher) ⭐ 4,310 | 🐛 23 | 🌐 Kotlin | 📅 2026-08-11 - Manage your complete Play Store presence in your repository: Listing, Release Notes, APKs and App Bundles.
  * [testfairy-gradle-plugin](https://github.com/testfairy/testfairy-gradle-plugin) ⭐ 92 | 🐛 10 | 🌐 Groovy | 📅 2021-12-20 - Official plugin to upload signed builds to TestFairy.
  * [gradle-deploygate-plugin](https://github.com/deploygate/gradle-deploygate-plugin) ⭐ 90 | 🐛 7 | 🌐 Groovy | 📅 2026-08-05 - Build and deploy apps to DeployGate.
* Testing
  * [unmock-plugin](https://github.com/bjoernQ/unmock-plugin) ⭐ 327 | 🐛 13 | 🌐 Java | 📅 2026-06-20 - Allow you to use selected classes from a real Android-Jarfile for Android unit testing.
  * [gradle-plugin-robospock](https://github.com/Centril/gradle-plugin-robospock) ⭐ 20 | 🐛 4 | 🌐 Groovy | 📅 2014-12-31 - Configure robospock (gradle + spock + roboelectric) easily.
  * [gradle-monkey-plugin](https://github.com/AutoScout24/gradle-monkey-plugin) - Run Android monkey tests.
* Miscellaneous
  * [Shot](https://github.com/Karumi/Shot) ⭐ 1,206 | 🐛 63 | 🌐 Kotlin | 📅 2026-01-16 - Shot is a Gradle plugin that simplifies the execution of screenshot tests using [Screenshot Tests For Android by Facebook](http://facebook.github.io/screenshot-tests-for-android/).
  * [gradle-eclipse-aar-plugin](https://github.com/ksoichiro/gradle-eclipse-aar-plugin) ⭐ 125 | 🐛 8 | 🌐 Groovy | 📅 2017-07-09 - Use Android AAR libraries on Eclipse.
  * [ormlite-android-gradle-plugin](https://github.com/stephanenicolas/ormlite-android-gradle-plugin) ⭐ 101 | 🐛 10 | 🌐 Java | 📅 2019-02-02 - Generate an ORMLite configuration file and boost DAOs creations.
  * [gradle-android-git](https://github.com/ksoichiro/gradle-android-git) ⭐ 22 | 🐛 4 | 🌐 Groovy | 📅 2014-10-26 - Manage Git dependency for Android apps.

### iOS and Mac application development

* [gradle-xcodePlugin](https://github.com/openbakery/gradle-xcodePlugin) ⭐ 464 | 🐛 26 | 🌐 Groovy | 📅 2025-07-03 - Build iOS and Mac projects.
* [j2objc-gradle](https://github.com/j2objc-contrib/j2objc-gradle) ⭐ 139 | 🐛 57 | 🌐 Groovy | 📅 2018-06-18 - Enable Java source to be part of an iOS application's build.

### Editor and IDE integration

* [goomph](https://github.com/diffplug/goomph) ⭐ 137 | 🐛 12 | 🌐 Java | 📅 2026-03-12 - Downloads an Eclipse IDE with all required plugins and creates a workspace with specified settings and projects.
* [gradle-syntastic-plugin](https://github.com/Scuilion/gradle-syntastic-plugin) ⭐ 47 | 🐛 6 | 🌐 Groovy | 📅 2023-08-22 - Integrate Java project with Vim and Syntastic.
* [gradle-sublimetext-plugin](https://github.com/phildopus/gradle-sublimetext-plugin) ⭐ 18 | 🐛 3 | 🌐 Groovy | 📅 2013-05-16 - Generate Sublime Text 2 project file.
* [eclipse](https://docs.gradle.org/current/userguide/eclipse_plugin.html) - Official plugin that generates files that are used by [Eclipse IDE](http://eclipse.org/).
* [idea](https://docs.gradle.org/current/userguide/idea_plugin.html) - Official plugin that generates files that are used by [Intellij IDEA IDE](http://www.jetbrains.com/idea/index.html).
* [visual-studio](https://docs.gradle.org/current/userguide/native_software.html) - Official plugin that adds integration with Visual Studio.

### Templating

* [markdown-gradle-plugin](https://github.com/aalmiray/markdown-gradle-plugin) ⭐ 73 | 🐛 9 | 🌐 Groovy | 📅 2022-01-01 - Convert Markdown to HTML.
* [gradle-twirl](https://github.com/67726e/gradle-twirl) ⭐ 11 | 🐛 1 | 🌐 Groovy | 📅 2015-11-04 - Provide [Twirl](https://github.com/playframework/twirl) ⭐ 561 | 🐛 33 | 🌐 Scala | 📅 2026-08-14 template compilation and integration.

### Database

* [liquibase-gradle-plugin](https://github.com/liquibase/liquibase-gradle-plugin) ⭐ 213 | 🐛 10 | 🌐 Groovy | 📅 2026-04-25 - Use [Liquibase](http://liquibase.org/) to manage your database upgrades.
* [ml-gradle](https://github.com/marklogic-community/ml-gradle) ⭐ 73 | 🐛 17 | 🌐 Java | 📅 2026-08-11 - Automate everything involving [MarkLogic](https://developer.marklogic.com/).
* [gradle-migrations-plugin](https://github.com/marceloemanoel/gradle-migrations-plugin) ⭐ 17 | 🐛 10 | 🌐 Shell | 📅 2019-08-04 - Provide gradle build integration with [mybatis migrations](https://code.google.com/p/mybatis/wiki/Migration).
* [flyway-gradle-plugin](http://flywaydb.org/documentation/gradle/) - [Flyway](http://flywaydb.org/) database migration tasks.

### Dependency management

* [gradle-versions-plugin](https://github.com/ben-manes/gradle-versions-plugin) ⭐ 4,079 | 🐛 64 | 🌐 Groovy | 📅 2026-08-10 - Provide a task to determine which dependencies have updates.
* [buildSrcVersions](https://github.com/jmfayard/buildSrcVersions) ⭐ 1,709 | 🐛 129 | 🌐 Kotlin | 📅 2025-08-16 - Painless dependencies management.
* [gradle-dependency-lock-plugin](https://github.com/nebula-plugins/gradle-dependency-lock-plugin) ⭐ 303 | 🐛 29 | 🌐 Groovy | 📅 2026-08-10 - Allow people using dynamic dependency versions to lock them to specific versions.
* [gradle-nuget-plugin](https://github.com/Ullink/gradle-nuget-plugin) ⭐ 22 | 🐛 14 | 🌐 Groovy | 📅 2026-03-27 - Execute NuGet.exe from Gradle.
* [gradle-dependency-analyze](https://github.com/wfhartford/gradle-dependency-analyze) ⭐ 0 | 🐛 0 | 🌐 Groovy | 📅 2021-02-02 - Dependency analysis plugin for gradle.
* [gradle-git-repo-plugin](https://github.com/layerhq/gradle-git-repo-plugin) - Use a private git repo as a Maven repository.

### Debugging

* [gradle-groovysh-plugin](https://github.com/tkruse/gradle-groovysh-plugin) ⭐ 42 | 🐛 3 | 🌐 Groovy | 📅 2022-07-12 - Start an interactive groovy shells.

### Testing

* [gradle-test-logger-plugin](https://github.com/radarsh/gradle-test-logger-plugin) ⭐ 887 | 🐛 35 | 🌐 Groovy | 📅 2026-03-15 - A Gradle plugin for printing beautiful logs on the console while running tests.
* [gradle-console-reporter](https://github.com/ksoichiro/gradle-console-reporter) ⭐ 56 | 🐛 8 | 🌐 Groovy | 📅 2021-08-12 - Report test result to console.
* [gradle-itest-plugin](https://github.com/Softeq/itest-gradle-plugin) ⭐ 18 | 🐛 0 | 🌐 Groovy | 📅 2021-08-31 - This plugin adds integration testing support to the project
* [gradle-gatling-plugin](https://github.com/alphagov/gradle-gatling-plugin) ⚠️ Archived - Run [Gatling](http://gatling.io/) scenarios.

### Building

* [build-time-tracker-plugin](https://github.com/passy/build-time-tracker-plugin) ⭐ 1,207 | 🐛 21 | 🌐 Groovy | 📅 2019-05-28 - Continuously track and report your build times.
* [gradle-metrics-plugin](https://github.com/nebula-plugins/gradle-metrics-plugin) ⚠️ Archived - Collect Gradle build metrics and persist them to an external datastore.
* [nebula-plugin](https://nebula-plugins.github.io/) - A collection of Gradle plugins providing repeatable builds, immutable deployments and helping eliminate boilerplate code.

### Packaging

* [gradle-one-jar](https://github.com/rholder/gradle-one-jar) ⭐ 218 | 🐛 18 | 🌐 Groovy | 📅 2024-05-10 - Build self-contained executable jars that include all dependencies.
* [gradle-build-info-plugin](https://github.com/ksoichiro/gradle-build-info-plugin) ⭐ 39 | 🐛 3 | 🌐 Groovy | 📅 2017-01-02 - Include build information such as Git commit ID to your JAR.
* [gradle-replacer](https://github.com/ksoichiro/gradle-replacer) ⭐ 6 | 🐛 0 | 🌐 Groovy | 📅 2015-02-05 - Provide a minimalistic template engine feature.

### Releasing

* [gradle-bintray-plugin](https://github.com/bintray/gradle-bintray-plugin) ⭐ 1,272 | 🐛 165 | 🌐 Groovy | 📅 2021-01-15 - Publish artifacts to Bintray.
* [gradle-release](https://github.com/researchgate/gradle-release) ⭐ 887 | 🐛 137 | 🌐 Groovy | 📅 2026-06-18 - Automate releasing process. Similar to the Maven release plugin.
* [gradle-ssh-plugin](https://github.com/int128/gradle-ssh-plugin) ⭐ 325 | 🐛 55 | 🌐 Groovy | 📅 2026-08-09 - Provide SSH facilities for continuous delivery.
* [gradle-nexus-plugin](https://github.com/bmuschko/gradle-nexus-plugin) ⚠️ Archived - Configure and upload artifacts to Sonatype Nexus.
* [spotless-changelog](https://github.com/diffplug/spotless-changelog) ⭐ 49 | 🐛 12 | 🌐 Java | 📅 2024-07-06 - Parses changelog to calculate next version, then updates changelog on publish.
* [maven](https://docs.gradle.org/current/userguide/maven_plugin.html) - Official plugin that adds support for publishing artifacts to Maven repositories.
* [plugin-publish](https://plugins.gradle.org/plugin/com.gradle.plugin-publish) - Publish plugins to the Gradle Plugin Portal.

### Notification

* [announce](https://docs.gradle.org/current/userguide/announce_plugin.html) - Official plugin that publishes messages to platforms such as Twitter or Growl.
* [gradle-slack-plugin](https://github.com/Mindera/gradle-slack-plugin) ⭐ 153 | 🐛 4 | 🌐 Java | 📅 2019-11-05 - Send messages to Slack after each build.

### Cloud services

* [gradle-aws-plugin](https://github.com/classmethod-aws/gradle-aws-plugin) ⭐ 277 | 🐛 57 | 🌐 Java | 📅 2023-03-30 - Manage AWS resouces.
* [gradle-s3-plugin](https://github.com/skhatri/gradle-s3-plugin) ⭐ 34 | 🐛 4 | 🌐 Groovy | 📅 2021-09-24 - Upload files to / download files from S3.
* [gradle-stash-plugin](https://github.com/nebula-plugins/gradle-stash-plugin) ⚠️ Archived - Interact with the Stash SCM.
* [gradle-cf-plugin](https://github.com/melix/gradle-cf-plugin) ⭐ 13 | 🐛 2 | 🌐 Groovy | 📅 2014-01-13 - Interact with CloudFoundry.

### SCM

* [gradle-git](https://github.com/ajoberstar/gradle-git) ⚠️ Archived - Set of plugin to interact with Git repositories, publish files to gh-page, etc.
* [gradle-svntools-plugin](https://github.com/martoe/gradle-svntools-plugin) ⭐ 32 | 🐛 7 | 🌐 Groovy | 📅 2020-08-22 - Provide various SVN-related tasks.
* [gradle-snapshot-plugin](https://github.com/novabyte/gradle-snapshot-plugin) ⭐ 16 | 🐛 1 | 🌐 Java | 📅 2015-02-23 - Generate build metadata from SCM tools.

### CI

* [build-info](https://github.com/jfrogdev/build-info) ⭐ 153 | 🐛 41 | 🌐 Java | 📅 2026-07-02 - Artifactory's open integration layer for the CI servers and build tools.

### VM and container

* [bmuschko/gradle-docker-plugin](https://github.com/bmuschko/gradle-docker-plugin) ⭐ 1,239 | 🐛 19 | 🌐 Java | 📅 2025-10-30 - Gradle plugin for managing Docker images and containers.
* [palantir/gradle-docker](https://github.com/palantir/gradle-docker) ⭐ 755 | 🐛 129 | 🌐 Groovy | 📅 2026-08-10 - Build and push Docker images.
* [Transmode/gradle-docker](https://github.com/Transmode/gradle-docker) ⭐ 650 | 🐛 83 | 🌐 Groovy | 📅 2020-08-20 - Build Docker images.
* [gradle-vagrant-plugin](https://github.com/bmuschko/gradle-vagrant-plugin) ⭐ 48 | 🐛 6 | 🌐 Groovy | 📅 2021-03-21 - Manage Vagrant boxes.
* [nebula-docker-plugin](https://github.com/nebula-plugins/nebula-docker-plugin) ⚠️ Archived - Nebula gradle plugin for reducing boilerplate in creating docker images.

## Boilerplates

* [android-gradle-template](https://github.com/nenick/android-gradle-template) ⭐ 379 | 🐛 1 | 🌐 Java | 📅 2021-01-01 - Template project for developing Android app.
* [vertx-gradle-template](https://github.com/vert-x/vertx-gradle-template) ⭐ 86 | 🐛 9 | 🌐 Java | 📅 2016-11-02 - Template project for developing Vert.x module.
* [gradle-plugin-starter](https://github.com/int128/gradle-plugin-starter) ⭐ 37 | 🐛 2 | 🌐 Groovy | 📅 2021-05-14 - Template project for developing Gradle plugin.
* [gatling-with-gradle](https://github.com/RallySoftware/gatling-with-gradle) - Sample project that demonstrates how to automate load testing with [Gatling](http://gatling.io/).

## Resources

### General Resources

* [GitHub Repository](https://github.com/gradle/gradle) ⭐ 18,777 | 🐛 3,464 | 🌐 Groovy | 📅 2026-08-15
* [Gradle Forums](https://discuss.gradle.org/)
* [Gradle Plugin Portal](https://plugins.gradle.org/)

### Official Documentation

* [User Guide](https://docs.gradle.org/current/userguide/userguide.html)
* [DSL Reference](https://docs.gradle.org/current/dsl/)

## Contribution

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Soichiro Kashima](https://github.com/ksoichiro) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
