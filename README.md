<img src="http://img.jcabi.com/logo.png" width="200px" height="48px" />

Simple Useful Java Components
=====

See [www.jcabi.com](http://www.jcabi.com/) website for more details.

## Release Notes ##

0.8: upcoming release

 * #257: `Logger.stream()` and `Logger.log()` methods introduced (`jcabi-log`)
 * #252: `jcabi-dynamo` introduced
 * #250: `Aether(Collection<RemoteRepository>, File)` constructor added (`jcabi-aether`)
 * #240: `skipArgs` and `skipResult` arguments of `@Loggable` (`jcabi-aspects`)
 * #239: `@Valid` ignores NULL references (`jcabi-aspects`)
 * #236: `Logger.format()` compresses texts in a nicer way (`jcabi-log`)
 * #235: format of log output of `@Loggable` optimized (`jcabi-aspects`)
 * #234: `@Cacheable.FlushBefore` and `@Cacheable.FlushAfter` (`jcabi-aspects`)
 * #233: `ant-contrib` added as a plugin dependency for `maven-antrun-plugin` (`parent`)
 * #227: `@Loggable` reports full stack of a stuck thread (`jcabi-aspects`)
 * #222: class name is reported when DEBUG or TRACE (`jcabi-maven-slf4j`)
 * #209: thread name is reported when waiting (`jcabi-aspects`)
 * #207: default time limit for `@Loggable` set to one minute (`jcabi-aspects`)
 * #202: verbosity flag in VerboseRunnable (`jcabi-log`)
 * #201: `@RetryOnFailure` shows full text of chained exceptions (`jcabi-aspects`)
 * #200: `ignore` attribute in `@Loggable` annotation (`jcabi-aspects`)
 * #197: `Classpath` class introduced (`jcabi-aether`)
 * #193: `jcabi-maven-plugin:ajc` goal introduced
 * #192: `@Loggable` throws for interrupted thread (`jcabi-aspects`)
 * #189: `Runnable` cleans interrupted status (`jcabi-log`)
 * #188: `@ScheduleWithFixedDelay` introduced (`jcabi-aspects`)
 * #186: `@Timeable` annotation to terminate stuck methods (`jcabi-aspects`)
 * #182: `@Loggable` logs long-running methods in process (`jcabi-aspects`)
 * #179: `jcabi-maven-plugin` supplementary plugin created
 * #171: Java packages are versioned with text file (`parent`)
 * #151: silently ignore absence of Maven Log (`jcabi-maven-slf4j`)
 * #147: methods can be annotated with `@NotNull` (`jcabi-aspects`)
 * #145: fixed defect with SNAPSHOT artifacts (`jcabi-heroku-maven-plugin`)
 * #143: Lombok annotations used in almost every class
 * #134: APT and AspectJ work together (`jcabi-aspects`)
 * #133: `@Immutable` annotation added (`jcabi-aspects`)
 * #130: `@RetryOnFailure` has a time limit (`jcabi-aspects`)
 * #124: `@Loggable` has a time limit (`jcabi-aspects`)
 * #122: UTF-8 is a default encoding (`jcabi-velocity`)
 * #119: dependency management fixed (`parent`)
 * #118: sonatype repository is in default list in `pom.xml` (`parent)
 * #115: wrong resources filtering fixed (`jcabi-heroku-maven-plugin`)
 * #112: `xml-maven-plugin` added to `qulice` profile (`parent`)
 * #111: `maven-docck-plugin` added to `qulice` profile (`parent`)
 * #110: `git status` is shown before commit (`jcabi-heroku-maven-plugin`)
 * #104: `parent` project introduced
 * #105: `@Cacheable` annotation added (`jcabi-aspects`)
 * #103: checksum to differ versions (`jcabi-beanstalk-maven-plugin`)
 * #102: UPDATE method added (`jcabi-beanstalk-maven-plugin`)
 * #101: `@Loggable` annotation added (`jcabi-aspects`)

[0.7](#100):

 * #99: [Manifests](http://www.jcabi.com/jcabi-manifests/apidocs-0.7/com/jcabi/manifests/Manifests.html) introduced

[0.6](#98):

 * #97: [URN](http://www.jcabi.com/jcabi-urn/apidocs-0.6/com/jcabi/urn/URN.html) introduced
 * #74: [jcabi-maven-skin](http://www.jcabi.com/jcabi-maven-skin/) introduced
 * many bug fixes for [jcabi-beanstalk-maven-plugin](http://www.jcabi.com/jcabi-beanstalk-maven-plugin/)

[0.5](#77):

 * #76: [VerboseProcess](http://www.jcabi.com/jcabi-log/apidocs-0.5/com/jcabi/log/VerboseProcess.html) introduced
 * #76: [jcabi-ssl-maven-plugin](http://www.jcabi.com/jcabi-ssl-maven-plugin) introduced

[0.4](#71):

 * #70: [jcabi-heroku-maven-plugin](http://www.jcabi.com/jcabi-heroku-maven-plugin) introduced

[0.3](#69):

 * #65: [jcabi-beanstalk-maven-plugin](http://www.jcabi.com/jcabi-beanstalk-maven-plugin) introduced

[0.2.0](#60):

 * #59: custom [JSR-303 constraints](http://www.jcabi.com/jcabi-aspects/jsr-303.html) in jcabi-aspects
 * #55: [jcabi-aether](http://www.jcabi.com/jcabi-aether) supports S3 wagon

[0.1.10](#46):

 * #34: [jcabi-aspects](http://www.jcabi.com/jcabi-aspects)
 * #37: started to use maven-duplicate-finder-plugin
 * #39: `@RetryOnException` aspect
 * #41: `VerboseRunnable(Callable<?>, Boolean)` ctor added
 * #42: full compliance with JDK 7
 * #44: `MulticolorLayout` for LOG4J

[0.1.9](#33):

 * #28: [jcabi-jdbc](http://www.jcabi.com/jcabi-jdbc)
 * #29: `Utc` helper in `jcabi-jdbc`

[0.1.6](#22):

 * #19: [jcabi-aether](http://www.jcabi.com/jcabi-velocity)
 * #20: [jcabi-maven-slf4j](http://www.jcabi.com/jcabi-maven-slf4j)
 * #21: [jcabi-aether](http://www.jcabi.com/jcabi-ether)

[0.1.5](#18):

 * #17: `TextDecor` for `com.jcabi.log.Logger`

[0.1.3](#14):

 * #13: `VerboseRunnable` in `jcabi-log`

[0.1.2](#12):

 * #11: `ThreadFactory` in `jcabi-log`

[0.1.1](#10):

 * jcabi-log
 * jcabi-assembly
