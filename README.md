
<p align="center" ><img 
 src="https://user-images.githubusercontent.com/22797857/90096298-b90f4b00-dd54-11ea-9a31-00ad53f8ec04.gif" width="40%"/></p>

<p align="center">
 🔥 🔥 🔥</br>
 Always busy, always grinding.<br>
 Let's go beyond our limits<br>
</p>


<h2 align="center"> <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"> Hi there! I'm Max Dmytrenko</h2>

```
package tehcman.com;

import java.util.ArrayList;

public class RealTehcMan {
    private static String name = "Max Dmytrenko";
    private static String university = "Uniwersytet Adama Mickiewicza (UAM)";
    private static String degree = "Bachelor of Computer Science";
    
    private String CurrentFocus = "Developing backend apps/webapps using Java";

    enum TechStack {
        JAVA, JPA, MVC, SQL, SPRINGBOOT, JUINT4, CRUD, REST, C, PYTHON;


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

    public ArrayList<Activity> ambitions() {
        ArrayList<Activity> activities = new ArrayList<>(
                "Crypto investor",
                "Owner of delivery company (sp. z.o.o)",
                "Productivity nerd");
        return activities;
    }
}

```
