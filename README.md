Libraries for JAXB extension example
------------------------------------

Set of libraries for OpenJDK MSI installer JAXB extension example:

 - `msiextend-jaxb-1.0.jar` - generated JAXB classes, [download](https://github.com/akashche/msiextend-jaxb/releases/tag/1.0)
 - `jaxb-api-2.3.1.jar` - [download](https://repo1.maven.org/maven2/javax/xml/bind/jaxb-api/2.3.1/)
 - `jaxb-impl-2.3.1.jar` - [download](https://repo1.maven.org/maven2/com/sun/xml/bind/jaxb-impl/2.3.1/)
 - `istack-commons-runtime-4.0.1.jar` - [download](https://repo1.maven.org/maven2/com/sun/istack/istack-commons-runtime/4.0.1/)
 - `activation-1.1.1.jar` - [download](https://repo1.maven.org/maven2/javax/activation/activation/1.1.1/)

Checkout this repo into `%TEMP%\installermsi_extend_jaxb_libs` and run the test with:

```
make run-test TEST=jdk/installermsi/ExtendJaxbTest.java JTREG="JOBS=1"
```
