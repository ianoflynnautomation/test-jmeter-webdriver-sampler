# test-jmeter-webdriver-sampler

# Summary
Jmeter load test project to be run in an azure pipeline

## Repository Ownership

| Team | Contact Person |
| ---- | ------------------------------------|
|Team Owner| Ian O'Flynn|

## Dev Instructions

### Setup JMeter Instructions

Option 1: Install Java and Jmeter on own Machine.
Option 2: JMeter with Docker.

## Option 1

Offical JMeter resource: [Offical JMeter Website](https://jmeter.apache.org/)

1. Go to: https://www.java.com/en/download/
2. Click on 'Download' Java' button.
3. Open downloaded file.
4. Follow installation instructions.
5. Open command prompt.
6. Type 'java -version' > Press Enter.
7. You should get the Java version
```

```

### Download JMeter Guide

1. Go to Apache JMeter website: https://jmeter.apache.org/
2. Go to 'Download Releases' link located on the left side panal.
3. Scroll to 'Binaries' section.
4. Click on 'apache-jmeter-x-x.zip' link.


### Install JMeter

1. Go to Downloads.
2. Unzip folder downloaded in previous steps.
3. Open unziped folder.
4. Go to 'bin' folder.
5. Run 'Apache Jmeter' Executable Jar File.

Tip! Create a shortcut for 'Apache JMeter' file and place it in any suitable directory(e.g Desktop). You can use it to launch JMeter.

### Install JMeter Plugins Manager

1. Go to https://jmeter-plugins.org/wiki/PluginsManager/
2. Download 'plugins-manager.jar'
3. Copy downloaded file to 'lib/ext' directory.
4. Restart JMeter.
5. Click 'Options' tab.
6. Plugins Manager should be present.

### IDE

As Tests are written in Java/Groovy you will need an IDE to support this.

Note: During download please check and include 'bin' to path.

Download IntelliJ Community Edition. Free version. https://www.jetbrains.com/idea/download/#section=mac


### Run Jmeter Tests

1. Clone Repository.
2. Open Apache JMeter.
3. File > Open > Navigate to the directory with the cloned repo.
4. Select jmeter_seleium_tests.jmx file > Click 'Open' button.
5. Set Global Test Plan variables.
6. Select any test or a whole test plan and click 'Play' button.

### Run Jmeter Tests in ADO pipeline
