Could be faster.

```
$ (echo ; mvn -Dmaven.tests.skip=true -DskipTests=true package 2>&1) | tai64n | tai64nlocal
2018-04-13 19:09:18.037794500 
2018-04-13 19:09:28.391974500 [INFO] Scanning for projects...
2018-04-13 19:09:28.715793500 [INFO] 
2018-04-13 19:09:28.716609500 [INFO] ------------------------------------------------------------------------
2018-04-13 19:09:28.717237500 [INFO] Building com.io7m.minimal 0.0.1
2018-04-13 19:09:28.717814500 [INFO] ------------------------------------------------------------------------
2018-04-13 19:09:29.773126500 [INFO] 
2018-04-13 19:09:29.776558500 [INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ com.io7m.minimal ---
2018-04-13 19:09:31.059296500 [WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
2018-04-13 19:09:31.060252500 [INFO] skip non existing resourceDirectory /home/someone/doc/dev/2018/04/minimal/src/main/resources
2018-04-13 19:09:31.071620500 [INFO] 
2018-04-13 19:09:31.072419500 [INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ com.io7m.minimal ---
2018-04-13 19:09:32.886313500 [INFO] Nothing to compile - all classes are up to date
2018-04-13 19:09:32.887177500 [INFO] 
2018-04-13 19:09:32.887709500 [INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ com.io7m.minimal ---
2018-04-13 19:09:32.897188500 [WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
2018-04-13 19:09:32.897616500 [INFO] skip non existing resourceDirectory /home/someone/doc/dev/2018/04/minimal/src/test/resources
2018-04-13 19:09:32.898377500 [INFO] 
2018-04-13 19:09:32.898985500 [INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ com.io7m.minimal ---
2018-04-13 19:09:32.915608500 [INFO] No sources to compile
2018-04-13 19:09:32.916394500 [INFO] 
2018-04-13 19:09:32.916923500 [INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ com.io7m.minimal ---
2018-04-13 19:09:33.810877500 [INFO] Tests are skipped.
2018-04-13 19:09:33.811629500 [INFO] 
2018-04-13 19:09:33.812615500 [INFO] --- maven-jar-plugin:2.4:jar (default-jar) @ com.io7m.minimal ---
2018-04-13 19:09:34.660484500 [INFO] ------------------------------------------------------------------------
2018-04-13 19:09:34.661087500 [INFO] BUILD SUCCESS
2018-04-13 19:09:34.661653500 [INFO] ------------------------------------------------------------------------
2018-04-13 19:09:34.662928500 [INFO] Total time: 6.401 s
2018-04-13 19:09:34.664209500 [INFO] Finished at: 2018-04-13T19:09:34Z
2018-04-13 19:09:34.915268500 [INFO] Final Memory: 11M/39M
2018-04-13 19:09:34.915270500 [INFO] ------------------------------------------------------------------------

```
