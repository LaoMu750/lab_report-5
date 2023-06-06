**Name:Chaklam Ng**

**Professor Joe**

**CSE 15L**

**06/05/2023**
# Lab Report 5
___

![image](https://github.com/LaoMu750/lab_report-5/assets/123420015/a5d347e3-d1a0-4289-96c7-94cf75924bf6)
![image](https://github.com/LaoMu750/lab_report-5/assets/123420015/78bf6416-1194-409b-b4c7-b307fdf9c1fc)
![image](https://github.com/LaoMu750/lab_report-5/assets/123420015/da47b812-a32a-41f0-b77c-e29a21601cec)
```
FILE = "/src/Epp.java"

if[[-f "$FILE"]]
    echo "1"
else 
    echo "0"
fi
```
```
import java.io.File;
public class App {
    public static void main(String[] args) throws Exception {

       File file = new File(args[0]);
       if (file.exists()) {
           System.out.println("File exists, yay!");
       }
       else {
           System.out.println("The file does not exist :(");
       }

    }
}
```
## Part 2 Reflection ##
Actually,I have learned that a lot about how to write autograder, using bash script files and Junit test to debug my
java programs. To be honest, this class helps me a lot on build up my knowledge on the computer science.
