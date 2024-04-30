This example project is stale and unsupported. It has been replaced by [this](https://github.com/sonarsource-cfamily-examples) example project.

# C++ example project scanned on SonarCloud using Travis

[![Build status](https://travis-ci.org/SonarSource/sonarcloud_example_cpp-cmake-linux-travis.svg?branch=master)](https://travis-ci.org/SonarSource/sonarcloud_example_cpp-cmake-linux-travis)[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=sonarcloud_example_cpp-cmake-linux-travis&metric=alert_status)](https://sonarcloud.io/dashboard?id=sonarcloud_example_cpp-cmake-linux-travis)

#### This project is analysed on [SonarCloud](https://sonarcloud.io)!

It is very easy to run an analysis on a C/C++/Objective-C project and push it to SonarCloud:

1. Create a `sonar-project.properties` files to store your configuration
2. In your `.travis.yml` file:
   1. Activate the [Travis Add-on](https://docs.travis-ci.com/user/sonarcloud/)
   2. Wrap your compilation with the Build Wrapper
   3. Run `sonar-scanner` later on

You can take a look at the
[sonar-project.properties](https://github.com/SonarSource/sonarcloud_example_cpp-cmake-linux-travis/blob/master/sonar-project.properties)
and
[.travis.yml](https://github.com/SonarSource/sonarcloud_example_cpp-cmake-linux-travis/blob/master/.travis.yml)
files of this project to see it in practice.

## Links

- [Documentation of the C/C++/Objective-C plugin and its with Build Wrapper](http://docs.sonarqube.org/x/pwAv)
- [Documentation of the SonarCloud Travis Add-on](https://docs.travis-ci.com/user/sonarcloud/)
