JMeter Kickstarter project.

A quick way to get started with JMeter tests.  Automatically downloads and 
installs JMeter for you.

To start JMeter, run (prerequisite to have Java):

    ./gradlew jmGui

This will open the src/test/jmeter/jmeter-test1.jmx test script in the JMeter UI and you can modify/run tests from there.
To add things like JDBC drivers, add them as dependencies to the build.gradle script.

Documentation on JMeter can be found here: http://jmeter.apache.org/usermanual/
