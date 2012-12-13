gcm-maven-repository
=========

A simple maven repository to host 1.0.2 of gcm.jar for android development with Maven.

Add these fellows to your pom.xml:

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-

<repositories>
	É
        <repository>
            <id>gcm-maven-repository</id>
            <url>https://raw.github.com/4impact/gcm-maven-repository/master/releases/</url>
        </repository>
	..
    </repositories>

    <dependencies>
	É        
         <dependency>
            <groupId>com.google.android.gcm</groupId>
            <artifactId>gcm</artifactId>
             <version>1.0.2</version>
        </dependency>
	...
    </dependencies>

=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-

Many thanks to:
SŽbastien Lorber for the inspiration - https://github.com/slorber/gcm-server-repository
Chas Emerick for the instructions - http://cemerick.com/2010/08/24/hosting-maven-repos-on-github/