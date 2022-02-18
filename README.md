
<p align="center" ><img 
 src="https://user-images.githubusercontent.com/22797857/90096298-b90f4b00-dd54-11ea-9a31-00ad53f8ec04.gif" width="40%"/><br>
 always busy, always on the grind</p>


<h2 align="center"> <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"> Hi there! I'm Max</h2>

```java
package com.tehcman;

public class RealTehcMan {
    private final String name = "Max";
    private final String university = "Uniwersytet Adama Mickiewicza (UAM)";
    private final String degree = "Bachelor of Computer Science";
    
    private String currentFocus = "Developing backend apps/webapps using Java";

    enum TechStack {
        JAVA, JPA, MVC, SQL, SPRINGBOOT, JUINT4, CRUD, REST, C,CPP
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
                "Crypto investor"));
    }
}

```
<p align="center">Visit my <a href="https://tehcman.com/">website</a>!</p>
