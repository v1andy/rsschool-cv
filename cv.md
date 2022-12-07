# **rsschool-cv**
----
## **Andrew Vlasovets**
### ***Student of the rs-school***
----
Contact information:
1. discord: v1andy#7085
2. Telegram: @vlandy
3. GitHun: vlandy
----
## My biography:


----
## **Skills:**
* Java
* Git, Github
* VS Code, InteliJ IDEA
* HTML basics

----
## **Code example:**
```
import controller.Passport;
import java.util.ArrayList;
import java.util.HashMap;
import java.util.List;
import java.util.Map;

public class PassRep {

    List<Passport> passports = new ArrayList<>();
    Map<String,Passport> baseOfPassports = new HashMap<>();


    public void passAdd(Passport pass) {
        baseOfPassports.put(pass.getId(), pass);
    }

    public Passport passGet(String id){
        return baseOfPassports.get(id);
    }
}
```