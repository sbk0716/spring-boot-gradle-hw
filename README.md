# spring-boot-vsc-hw

## Usage

1. Spring Boot Dashboard
```sh
admin@gw-mac demo % /usr/bin/env /Users/admin/.vscode/extensions/redhat.java-1.9.0-darwin-arm64/jre/17.0.3-macosx-aarch64/bin/java -D
com.sun.management.jmxremote -Dcom.sun.management.jmxremote.port=49332 -Dcom.sun.management.jmxremote.authenticate=false -Dcom.sun.man
agement.jmxremote.ssl=false -Djava.rmi.server.hostname=localhost -Dspring.application.admin.enabled=true -Dspring.jmx.enabled=true -Ds
pring.boot.project.name=demo -XX:+ShowCodeDetailsInExceptionMessages @/var/folders/8w/wn51c09s4dn4g55_90gtn_3w0000gn/T/cp_dkulqfg9xs0k
4ll3rlryxeml8.argfile com.example.demo.DemoApplication 

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::                (v2.7.3)

2022-08-29 14:12:24.185  INFO 2157 --- [           main] com.example.demo.DemoApplication         : Starting DemoApplication using Java 17.0.3 on gw-mac.local with PID 2157 (/Users/admin/Desktop/spring/demo/bin/main started by admin in /Users/admin/Desktop/spring/demo)
2022-08-29 14:12:24.186  INFO 2157 --- [           main] com.example.demo.DemoApplication         : No active profile set, falling back to 1 default profile: "default"
2022-08-29 14:12:24.613  INFO 2157 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2022-08-29 14:12:24.618  INFO 2157 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2022-08-29 14:12:24.618  INFO 2157 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.65]
2022-08-29 14:12:24.672  INFO 2157 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2022-08-29 14:12:24.672  INFO 2157 --- [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 463 ms
2022-08-29 14:12:24.862  INFO 2157 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port(s): 8080 (http) with context path ''
2022-08-29 14:12:24.868  INFO 2157 --- [           main] com.example.demo.DemoApplication         : Started DemoApplication in 0.828 seconds (JVM running for 1.274)
admin@gw-mac demo % 
```