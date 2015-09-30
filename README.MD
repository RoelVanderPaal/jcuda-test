Prerequisites
* JDK
* Maven
* cmake (command line)
* make (command line)


Checkout https://github.com/RoelVanderPaal/jcuda-common

Checkout https://github.com/RoelVanderPaal/jcuda
```
mvn install
```

Checkout https://github.com/RoelVanderPaal/jcublas
```
mvn install
```

```
mvn compile
mvn exec:java -Dexec.mainClass=JCudaDeviceQuery
mvn exec:java -Dexec.mainClass=JCudaBandwidthTest
mvn exec:java -Dexec.mainClass=JCublasSample
mvn exec:java -Dexec.mainClass=JCublas2Sample
```
