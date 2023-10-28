<p align="center">
 <img src="https://user-images.githubusercontent.com/22797857/90096298-b90f4b00-dd54-11ea-9a31-00ad53f8ec04.gif" width="453" height="365"/><br>
 always busy, always on the grind</p>

<h2 align="center"> <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"> Hi there!</h2>
<!-- <h2 align="center"> 👋 Hi there! I'm Max</h2> -->

```java
package com.tehcman;

public class RealTehcMan implements AwesomeProgrammer {
    private final String fullFirstName = "Maksym";
    private final String university = "Uniwersytet Adama Mickiewicza (UAM), Poznan, Poland";
    private final String degree = "Engineer's degree";
    private final String workPlace = "Capgemini Polska Sp. z o.o.";

    private String currentFocus = "Full Stack Developer";

    enum TechStack {
        JAVA, ANGULAR, JS, TS, JPA, MVC, SQL, SPRINGBOOT, JUINT4, CRUD, REST
    }

    public String languagesISpeak(String environment) {
        switch (environment) {
            case "Poland":
                return "Polish";
            case "USA":
                return "English";
            case "Ukraine":
                return "Ukrainian";
            case "Russia":
                return "Russian";
            case "Italy":
                return "Italian";
            default:
                return "English";
        }
    }

    public ArrayList<String> activities() {
        return new ArrayList<>(Arrays.asList(
                "Productivity nerd",
                "Language enthusiast",
                "Crypto/stock investor"));
    }
}

```

<p align="center">Visit my <a href="https://tehcman.com/">website</a>!</p>
