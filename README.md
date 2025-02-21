
# Jenkins-Learn

![Jenkins Logo](https://i0.wp.com/cyclelabs.io/wp-content/uploads/2022/08/Jenkins-1.png?resize=860%2C506&ssl=1)

Jenkins is an open-source automation server that is widely used for continuous integration (CI) and continuous delivery (CD). It helps automate the process of building, testing, and deploying software projects. Jenkins is highly extensible, with a vast range of plugins that allow you to integrate with different tools, platforms, and environments.

Jenkins automates software build, testing, and deployment processes, enabling continuous integration and delivery with easy configuration and a wide range of plugins.

## Java and Jenkins install in LINUX UBUNTU

### Following initial command
sudo apt update refreshes the package list, and sudo apt upgrade installs the latest versions of installed packages

``` bash
sudo apt update && sudo apt upgrade
```

Jenkins requires Java to run, yet not all Linux distributions include Java by default. Additionally,[not all Java versions are compatible with Jenkins](#supported-java-versions)

### Installation of Java

```bash
1. sudo apt install fontconfig openjdk-17-jre

2. java -version
    openjdk version "17.0.13" 2024-10-15
    OpenJDK Runtime Environment (build 17.0.13+11-Debian-2)
    OpenJDK 64-Bit Server VM (build 17.0.13+11-Debian-2, mixed mode, sharing)
```

## Supported Java Versions

| **Java Version**         | **LTS Release**       | **LTS Release Date**   | **Weekly Release**     | **Weekly Release Date** |
|--------------------------|-----------------------|------------------------|------------------------|-------------------------|
| Java 17 or Java 21       | 2.479.1               | October 2024           | 2.463                  | June 2024              |
| Java 11, Java 17, or Java 21 | 2.426.1               | November 2023          | 2.419                  | August 2023            |
| Java 11 or Java 17       | 2.361.1               | September 2022         | 2.357                  | June 2022              |
| Java 8, Java 11, or Java 17 | 2.346.1               | June 2022              | 2.340                  | March 2022             |
| Java 8 or Java 11        | 2.164.1               | March 2019             | 2.164                  | February 2019          |
| Java 8                   | 2.60.1                | June 2017              | 2.54                   | April 2017             |
| Java 7                   | 1.625.1               | October 2015           | 1.612                  | May 2015               |

