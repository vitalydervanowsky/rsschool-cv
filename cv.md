### My name
Vitali Dzervanouski

### Contact Info
@dzrvnsk on Telegram or Discord

### Summary
I want to be Software Developer. I want to realize my intellectual potential. I like to learn something new and be good in it. I want that my family (my wife and my kids) be proud of me for my passing through my fear.

### Skills
* English Proficiency: Upper-intermediate (B2)
* Familiar with Terminology in Software Development
* Proficient understanding of web markup, including HTML5, CSS3
* Proficient understanding of JavaScript
* Proficient understanding of code versioning tools, such as Git, SVN

### Code examples (LATEST)
```
public class Triangle {
    double area;
    int height;
    int length;
    public static void main(String [] argd) {
        int x = 0;
        Triangle [] ta = new Triangle[4];
        while (x < 4) {
            ta[x] = new Triangle();
            ta[x].height = (x + 1) * 2;
            ta[x].length = x + 4;
            ta[x].setArea();
            System.out.print("triangle " + x + " , zone");
            System.out.println(" = " + ta[x].area);
            x = x + 1;
        }
        int y = x;
        x = 27;
        Triangle t5 = ta[2];
        ta[2].area = 343;
        System.out.print("y = " + y);
        System.out.println((", zone t5 = " + t5.area));
    }
    void setArea() {
        area = (height * length) / 2;
    }
}
```

### Education
* 2006-2011 - Belarusian State University of Informatics and Radioelectronics
* 2016 - HTML5 and CSS3 Basic intensive course on htmlacademy.ru
* 2016 - JavaScript Basic intensive course on htmlacademy.ru