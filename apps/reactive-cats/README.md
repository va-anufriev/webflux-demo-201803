How to build:

```shell script
$ gradle :apps:reactive-cats:shadowJar
```

How to run:

```shell script
$ java -jar \
  -Xms512m \
  -Xmx512m \
  -Djava.net.preferIPv4Stack=true \
  -Djava.net.preferIPv6Addresses=false \
  -Dspring.output.ansi.enabled=ALWAYS \
  apps/reactive-cats/build/libs/reactive-cats.jar
```
