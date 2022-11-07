<p align="center">
 <img src="https://user-images.githubusercontent.com/22797857/90096298-b90f4b00-dd54-11ea-9a31-00ad53f8ec04.gif" width="453" height="365"/><br>
 always busy, always on the grind</p>

<h2 align="center"> <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"> Hi there! I'm Max</h2>
<!-- <h2 align="center"> 👋 Hi there! I'm Max</h2> -->

```java
package com.tehcman;

public class RealTehcMan implements AwesomeProgrammer {
    private final String name = "Max";
    private final String university = "Uniwersytet Adama Mickiewicza (UAM), Poznan";
    private final String degree = "Engineer's degree";
    private final String workPlace = "Capgemini Polska Sp. z o.o.";
    
    private String currentFocus = "Full Stack Developer";

    enum TechStack {
        JAVA, ANGULAR, JS, TS, JPA, MVC, SQL, SPRINGBOOT, JUINT4, CRUD, REST
    }

    public String languages(String enviroment) {
        switch (enviroment) {
            case "Poland":
                return "Polish";
            case "USA":
                return "English";
            case "Ukraine":
                return "Ukrainian";
            case "Russia":
                return "Russian";
            default:
                return "English";
        }
    }

    public ArrayList<String> activities() {
        return new ArrayList<>(Arrays.asList(
                "Owner of delivery company (sp. z.o.o)",
                "Productivity nerd",
                "Crypto/stock investor"));
    }
}

```
<p align="center">Visit my <a href="https://tehcman.com/">website</a>!</p>
