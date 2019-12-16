# Version 3.4.8 (????-??-??)

* [chg] Fixes coveralls plugin reporting only Unit Test coverage. 

# Version 3.4.7 (2019-12-12)

* [chg] Upgrade spotbugs to 3.1.12

# Version 3.4.6 (2019-03-08)

* [chg] Add itArgLine property for completing integration tests command line arguments.

# Version 3.4.5 (2019-03-07)

* [fix] Downgrade Validation API to 1.1 as it is the minimal version required by SeedStack. 

# Version 3.4.4 (2019-01-18)

* [chg] Force Javadoc to use Java 8 source level.

# Version 3.4.3 (2018-12-03)

* [chg] Built and tested with OpenJDK 11 (minimum Java version still being 8).

# Version 3.4.2 (2018-08-02)

* [chg] Excludes JMockit from integration test classpath as it messes with classes by simply being present.
 
# Version 3.4.1 (2018-08-02)

* [chg] Avoid adding license header in `META-INF/resources` and `src/main/webapp` directories.

# Version 3.4.0 (2018-07-31)

* [chg] Update Bean Validation to 2.0.1.

# Version 3.3.2 (2018-06-06)

* [fix] Downgrade Servlet API to 3.0.1 as it is the minimal version required by SeedStack. 
* [fix] Downgrade WebSocket API to 1.0 as it is the minimal version required by SeedStack. 

# Version 3.3.1 (2018-05-07)

* [chg] Avoid adding license header in `node_modules` and `bower_components` directories.

# Version 3.3.0 (2018-05-06)

* [chg] Update Servlet API to 4.0.1.

# Version 3.2.1 (2018-03-16)

* [chg] Update Jackson to 2.9.4.

# Version 3.2.0 (2018-02-14)

* [new] Java 9 build support.
* [chg] Change from findbugs to spotbugs.
* [chg] Update testing dependencies to latest versions.
* [chg] Update JAX-RS to 2.1.
* [brk] Remove arquillian composite POM.

# Version 3.1.1 (2017-11-28)

* [new] Add non-failing checkstyle to quality check.

# Version 3.1.0 (2017-07-31)

* [chg] Add profile for quality check with findbugs.
* [chg] Update JTA to 1.2
* [chg] Update SLF4J to 1.7.25
* [chg] Update Jackson to 2.8.9
* [chg] Update Jansi to 1.16
* [chg] Update Logback to 1.2.3
* [chg] Update AssertJ to 3.8.0

# Version 3.0.1 (2017-04-29)

* [fix] Fix surefire and failsafe configuration which was preventing coverage instrumentation.

# Version 3.0.0 (2016-12-12)

* [brk] Requires Java 8 to build.
* [brk] Remove version for JAX-RS 1.
* [chg] Update Jansi to 1.14.
* [chg] Update AssertJ to 3.6.1.
* [chg] Add more memory for integration tests.

# Version 2.4.0 (2016-04-19)

* [chg] Update Javax EL API to 3.0.0
* [chg] Update Servlet API to 3.1.0
* [chg] Update WebSocket API to 1.1
* [chg] Update SLF4J to 1.7.19
* [chg] Update Jackson to 2.6.5
* [chg] Update Logback to 1.1.6
* [chg] Update JSONAssert 1.3.0
* [chg] Update Tomcat to 8.0.32
* [chg] Update AssertJ to 2.3.0
* [chg] Update REST Assured to 2.9.0
* [chg] Update JMockit to 1.22

# Version 2.3.0 (2016-01-14)

* [new] Releases are pushed directly to bintray with the `release` profile.

# Version 2.2.0 (2015-12)

This version was released due to build constraints and doesn't bring any change.

# Version 2.1.1 (2015-11-16)

* [chg] Remove exclusion of internal classes in Javadoc JAR.

# Version 2.1.0 (2015-11-13)

* [brk] `seedstack.poms.version` Maven property is no longer available. 
* [brk] Remove all BOM modules in favor of distribution-specific BOMs.
* [brk] Rename `parent` module as `parent-internal` to make room for eventual distribution-specific parent.  

# Version 2.0.0 (2015-07-30)

* [nfo] Initial Open-Source version 
