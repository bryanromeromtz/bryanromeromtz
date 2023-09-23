<h2><img src="https://media.giphy.com/media/l0Iy2u0RfcJ769kdi/giphy.gif" width="80"> Hi, I'm Bryan Madzilla!</h2>
<img align='right' src="https://media.giphy.com/media/5eLDrEaRGHegx2FeF2/giphy.gif" width="250">


```js
public class GitHubProfile {
    public static void main(String[] args) {
        WebDeveloper bryanRomeroMtz = new WebDeveloper("Bryan Romero Mtz", "Web Developer", "Cooking");
        bryanRomeroMtz.displayBio();

        Skills bryanSkills = new Skills();
        bryanSkills.displaySkills();
    }
}

class WebDeveloper {
    private String name;
    private String title;
    private String hobby;

    public WebDeveloper(String name, String title, String hobby) {
        this.name = name;
        this.title = title;
        this.hobby = hobby;
    }

    public void displayBio() {
        System.out.println("Name: " + name);
        System.out.println("Title: " + title);
        System.out.println("Hobby: " + hobby);
    }
}

class Skills {
    private String[] code;
    private String[] tools;
    private String[] databases;

    public Skills() {
        this.code = new String[]{"Typescript", "PHP", "Java", "Python"};
        this.tools = new String[]{"React", "Redux", "Node", "Express", "Docker", "Jenkins", "K8S"};
        this.databases = new String[]{"MySQL", "MongoDB", "PostgreSQL"};
    }

    public void displaySkills() {
        System.out.println("Programming Languages: " + String.join(", ", code));
        System.out.println("Development Tools: " + String.join(", ", tools));
        System.out.println("Databases: " + String.join(", ", databases));
    }
}

```


<em><b>I'm not just cooking code, but also love connecting with different people.</b> So if you want to say <b>hi, I'll be thrilled to meet you!</b> 😁</em>

---

⭐️ From [@BryanMadzilla](http://bryansepia.me)
