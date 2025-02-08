# Maven Toolchains descriptor

* `.m2/toolchains.xml`
  * 👀default location 👀
* := preconfigured object /
  * uses
    * Maven plugins -- use it, for retrieving -- tool configuration (location and other information)
  * _Example:_ `jdk` toolchain
    * -> ALL plugins use the SAME JDK instance / WITHOUT 
      * hardcoding absolute paths | pom.xml
      * configuring plugin / require path to JDK tools
* see 
  * [Apache Maven Toolchains Plugin](https://maven.apache.org/plugins/maven-toolchains-plugin/)
  * [Guide to using Toolchains](https://maven.apache.org/guides/mini/guide-using-toolchains.html)
* 👀syntax 👀
  ```
  <toolchains xmlns="http://maven.apache.org/TOOLCHAINS/1.1.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:schemaLocation="http://maven.apache.org/TOOLCHAINS/1.1.0 http://maven.apache.org/xsd/toolchains-1.1.0.xsd">
    <toolchain>
      <type/>
      <provides>
        <key>value</key>
      </provides>
      <configuration/>
    </toolchain>
  </toolchains>
  ```
  * `<toolchains>`
    * TODO: