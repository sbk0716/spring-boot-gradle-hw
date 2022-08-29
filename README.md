# spring-boot-gradle-hw

## Run Spring Application

1. Gradle Task | build
```sh
admin@gw-mac demo % gradle build

BUILD SUCCESSFUL in 2s
7 actionable tasks: 7 executed
admin@gw-mac demo % 
```

2. Gradle Wrapper | build
```sh
admin@gw-mac demo % gradle wrapper --gradle-version 7.5  

BUILD SUCCESSFUL in 316ms
1 actionable task: 1 executed
admin@gw-mac demo % ./gradlew build                      

BUILD SUCCESSFUL in 2s
7 actionable tasks: 7 executed
admin@gw-mac demo % 
```

## Run Spring Application

1. Gradle Task | bootRun
```sh
admin@gw-mac demo % gradle bootRun

> Task :bootRun
...
...
```

2. Spring Boot Dashboard
```sh
admin@gw-mac demo %  /usr/bin/env /Library/Java/JavaVirtualMachines/temurin-17.jdk/Contents/Home/bin/java -XX:+ShowCodeDetailsInExceptionMes
sages @/var/folders/8w/wn51c09s4dn4g55_90gtn_3w0000gn/T/cp_dkulqfg9xs0k4ll3rlryxeml8.argfile com.example.demo.DemoApplication 

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::                (v2.7.3)
...
...
admin@gw-mac demo % 
```