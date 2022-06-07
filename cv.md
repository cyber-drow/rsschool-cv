# **SERGEY VORONIN**

### Contacts
___
* **_location_**: *Balakovo, Saratov area* 
* **_phone_**: *+7-937-147-21-97*
* **_email_:** *<cbr.drw@ya.ru>*
* **_site_**: *<http://balkomfin.ru/>*
* **_github_**: [*cyber-drow*](https://github.com/cyber-drow)  
&nbsp;


### About Me
___

*I am Sergey Voronin, an information technology specialist in a government organization. I am engaged in the development and technical support of information systems. I'm 33 and I want to change my field of activity to what I'm really interested in - programming. I plan to study frontend in rs-school, then backend - C# and .Net and become a first-class specialist in the field of web development. There is a lot of hard work ahead, but when, if not now?*
&nbsp;

### Skills
___
* _HTML&CSS_
* _JavaScript_
* _Java_
* _Python_
* _Git_
* _Figma, Photoshop_
* _Windows, Linux_
* _VSCode, SublimeText, IntelliJ Idea_
&nbsp;

### Code Example
___
_The user needs to enter the cell number of the chessboard in the required range. If successful, the program executes the code in other java classes, otherwise it is necessary to enter the correct value_

```java
import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;

public class Reader {
    public static Chivalry getCheck() throws IOException {

        BufferedReader reader = new BufferedReader(new InputStreamReader(System.in));
        String coordinates;

        while (true) {
            System.out.print("Enter number of cell: ");
            coordinates = reader.readLine();

            if ((coordinates.length() < 3) && (Constants.ALPHABET.contains(coordinates.substring(0, 1)) && (Constants.NUMERIC.contains(coordinates.substring(1))))) {
                System.out.println("Correct input");
                return new Chivalry(Constants.ALPHABET.indexOf(coordinates.substring(0, 1)) + 1 ,Constants.NUMERIC.indexOf(coordinates.substring(1)) + 1);
            }
            else System.out.println("Incorrect input, try again\n");
        }
    }
}
```

### Experience
___
+ _system administrator_
+ _specialist of information systems and technologies_
+ _development of an interactive educational web quest for children. The project took the first place among students at the All-Russian competition_ 
+ _freelance work, more than 10 ready projects created in HTML, CSS, JS_
+ _website of the Finance Committee of the administration of the Balakovo municipal district_
&nbsp;

### Education
___
* **_secondary vocational education_**: [_Balakovo Technical College_](https://bpt-balv.ru/)
* **_higher education_**: [_Balakovo Institute of Engineering and Technology - branch of NRNU MEPhI_](https://biti.mephi.ru/)
&nbsp;

### Language
___
* **_Russian_** - _native_
* **_English_** - _intermediate B1_
