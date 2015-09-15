# HTTP/2 experiments with Spring Boot

This project is part of the ["HTTP/2 for the Web developer" talk given at SpringOne2GX 2015](https://2015.event.springone2gx.com/schedule/2015-09-15).

## Running this project

From the command line, run

    $ mvn spring-boot:run

In your IDE, you have to run the `Http2ExperimentsApplication` class and customize your run configuration to add a JVM argument:

    -Xbootclasspath/p:$HOME/.m2/repository/org/mortbay/jetty/alpn/alpn-boot/8.1.3.v20150130/alpn-boot-8.1.3.v20150130.jar

## License
This project is released under version 2.0 of the [Apache License](http://www.apache.org/licenses/LICENSE-2.0).