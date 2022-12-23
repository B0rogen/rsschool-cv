# Borysov Roman
## Contacts
* **Discord:** b0r0geN
* **E-mail:** borysov.r.g@gmail.com
* **Phone:** +380633031632

***
## About Me
I want to learn Front-End Development in RSSchool
***
## Skills
* HTML
* CSS
* GitHub
* JavaScript (Basic)

***
## Code Example
```
var text = "Самопечатающийся текст Hello, World!";
var delay = 100; // cкорость
var elem = document.getElementById("result");
 
var print_text = function(text, elem, delay) {
    if(text.length > 0) {
        elem.innerHTML += text[0];
        setTimeout(
            function() {
                print_text(text.slice(1), elem, delay); 
            }, delay
        );
    }
}
print_text(text, elem, delay);
```
***
## Education and courses
* Horlivka Institute for Foreign Languages HSEE «Donbas State Pedagogical University»
* FreeCodeCamp
* 
***
## Languages
* **Ukrainian** - native speaker
* **Russian** - native speaker
* **Spanish** - B1
* **English** - A2
