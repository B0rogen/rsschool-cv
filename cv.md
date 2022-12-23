# Borysov Roman
## Contacts
* **Discord:**
* **E-mail:**
* **Phone:**

***
## About Me

***
## Skills

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

***
## Languages
* **Ukrainian** - native speaker
* **Russian** - native speaker
* **Spanish** - B1
* **English** - A2
