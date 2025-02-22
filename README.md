## Me

<div>
  <img alt="Static Badge" src="https://img.shields.io/badge/JAVA-red">
  <img alt="Static Badge" src="https://img.shields.io/badge/MYSQL-blue">
  <img alt="Static Badge" src="https://img.shields.io/badge/MONGODB-green">
  <img alt="Static Badge" src="https://img.shields.io/badge/DOCKER-blue">
  <img alt="Static Badge" src="https://img.shields.io/badge/JS-yellow">
  <img alt="Static Badge" src="https://img.shields.io/badge/GO-blue">
  
</div>

```java
package com.developer.jf;

import lombok.AllArgsConstructor;
import lombok.Getter;

@Getter
@AllArgsConstructor
public class AboutMe {
    private final String name;
    private final int age;
    private final String focusOn;
    
    public void showSomeAboutMe() {
        System.out.println("🖥️ Systems Development Student at SENAC");
        System.out.println("🔭 I'm interested in Back-end Development");
        System.out.println("🌱 I’m currently learning Java Swing");
        System.out.println("⚡ Fun fact: I'm a hardware maintenance technician");
        System.out.println("🔎 Looking for: System Development Job");
    }

    public static void main(String[] args) {
        AboutMe me = new AboutMe("Juan Fabian", 27, "Back-End");
        me.showSomeAboutMe();
    }
}
```

<div align="right">
  <img align="center" alt="DJF-CSS" display="flex" height="50" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg">  
  <img align="center" alt="DJF-HTML" height="50" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg">
  <img align="center" alt="DJF-CSS" height="50" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg">  
  <img align="center" alt="DJF-CSS" height="50" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg">
</div>
