# Dom Manipulation Assignment

1. Webiste Name: [Dev To](https://dev.to/)

### Topics

    - Query Selctory, Inner HTML

### Sample Image

![Sample One](./Pic1.png)

### Tasks

        Target the Top description div and change the DEV Community to <Your_Name> and description to your passion


### code 
```
document.querySelector(".side-bar .crayons-card .crayons-subtitle-2").innerHTML = "iNeuron"



document.querySelector(".side-bar .crayons-card .color-base-70 ").innerHTML = "I Write Code"


```

### Output

![Output](./Pic2.png)



2. Website Name: [Apple](https://support.apple.com/en-in)

### Task

![Store](./Picture_3.png)

### Fetch all the product name and store in an array

### Output

['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']

3. Webiste Name: [Youtube Support](https://support.google.com/youtube/)

### Topics

    - Get Element By Id, Create Element, Create Text Node, Append Child

### Sample Image

![Sample One](./Pic4.png)

### Tasks

     Add another FAQ 'My New FAQ' to the list

### Output

![Output](./Pic5.png)

### code 

```
let value = document.createElement("div")
value.className = "parentclass";


var miandiv = document.querySelector(".accordion-homepage")

maindiv.appendchild(value)
value.textContent = "new accordian created";

value.style.padding = "20px 70px";
value.style.borderTop = "1px solid #444746;";


```

4. Webiste Name: [OnePlus](https://www.oneplus.in/support)

### Topics

     Query Selector, InnerText

### Sample Image

![Sample One](./Pic6.png)

### Tasks

      Change the contact number

 ### code
```
      document.querySelector(".customer-support .one-tel-number").innerText = "+91 9137897117"

```

### Output

![Output](./Pic7.png)

5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)

### Topics

       getElementById, createElement, InnerText, append, setAttribute

### Sample Image

![Sample One](./Pic8.png)

### Tasks

     Target the main div of card and change the Button text to Check out
### code 

```
document.querySelector(".feature-column-carousel__button .cta").innerText = "Check Out";

```

### Output

![Output](./Pic9.png)

6. Webiste Name: [Adidas](https://www.adidas.co.in/)

### Topics

    -   Query Selector, Event listeners, Changing Styles

### Sample Image

![Sample One](./Pic10.png)

### Tasks

     Target the search box and on hover change thebackground color to red.

### code

```

let value = document.querySelector(".searchinput-wrapper___18TsX .searchinput___zXLAR");

function setbackround() {
    value.style.backgroundColor = "red";
}

value.addEventListener("onmouseover",setbackround);

<!-- value.addEventListener("click",setbackround); -->

```

### Output

![Output](./Pic11.png)

7. Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Topics

       Form, Value, Submit

### Sample Image

![Sample One](./Pic12.png)

### Tasks

     To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM

### code 

```
let inputvalue = document.querySelector("#hp-search-input");
inputvalue.value = "javascript"

let formsubmit = document.querySelector("#hp-search-form");

formsubmit.submit()

```

### Output

![Output](./Pic13.png)

8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Sample Image

![Sample One](./Pic14.png)

### Tasks

     Remove alternate languages from the home page languages listed

### Code 

```

const lang = document.getElementById("SIvCob").children;
// loop over language array and remove 1/2 language
function remove(lang) {
  for (let i = 0; i < lang.length / 2; i++) {
    lang[i].remove();
  }
}
remove(lang);

```

### Output

![Output](./Pic15.png)

9. Webiste Name: [Code Wars](https://www.codewars.com/)

### Topics

       Change Font Family, Color of Text.

    

### Sample Image

![Sample One](./Pic16.png)

### Tasks

    Change the font family of the text to monospace and text color to the logo’s background color.

 ### code 

 ```
 const Heading = document.getElementsByClassName("display-heading-1")[0];
 Heading.style.color = "red"

Heading.style.fontFamily = "monospace"


 ```   

### Output

![Output](./Pic17.png)

10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

       querySelector, mouseover, click eventListener,  callback function, style,

### Sample Image

![Sample One](./Pic18.png)

### Tasks

    Target the button and change background colour on mouseover

 ### code 

 ```
 const button = document.querySelector(".col-lg-8 .btn-cta-big");
const buttonText = document.querySelector(
  ".col-lg-8 .btn-cta-big .login-btn-text"
);


button.addEventListener("mouseover", () => {
  buttonText.style.background = "red";
});

```

### Output

![Output](./Pic19.png)

11. Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Sample Image

![Sample One](./Pic20.png)

### Tasks

    change the realme logo to ineuron logo

### code

```
const logos = document.querySelector(".wrapper .logo .icon");

<!-- console.log(logos) -->

logos.style.backgroundImage = "url(https://ineuron.ai/images/ineuron-logo.png)";

```

### Output

![Output](./Pic21.png)

12. Webiste Name: [Github](https://github.com/)

### Topics

       querySelector,style,background-Color

### Sample Image

![Sample One](./Pic22.png)

### Tasks

     change the background colour of the button to blue.

### code 
```
document.querySelector(".border-bottom  [href='/new']").style.background =
  "blue";

```

### Output

![Output](./Pic23.png)

13. Webiste Name: [Hackerrank](https://www.hackerrank.com/)

### Topics

       querySelector,innerHtml

### Sample Image

![Sample One](./Pic24.png)

### Tasks

Target the top description and change “Matching developers with great companies” to ‘JSBOOTCAMP“.

### code 

```
let heading = document.querySelector(".fl-heading-text")

console.log(heading)
heading.innerHTML = "JSBOOTCAMP"
```

### Output


![Output](./Pic25.png)

14. Webiste Name: [Asus](https://www.asus.com/in/)

### Topics

      querySelector,style,font-size

### Sample Image

![Sample One](./Pic26.png)

### Tasks

       change the fontsize of “Hot Deals” to 80px

### Code 

```
let title = document.querySelector(".HotDealsAll__Heading__2fIbe")

title.style.fontSize = "80px"
```

### Output

![Output](./Pic27.png)

15. Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Topics

      querySelector,style.textAlign

### Sample Image

![Sample One](./Pic28.png)

### Tasks

       Convert the text “G15 Gaming Laptop” from left to right

### code 

```
let title = document.querySelector(".ps-title")

title.style.textAlign = "right"

```

### Output

![Output](./Pic29.png)

16. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Sample Image

![Sample One](./Pic30.png)

### Tasks

      change the heading “Start with the developer” to “Start with Scratch”

### code 

```
let value = document.querySelector(".section-title_title__VEDfK")

console.log(value)

value.innerHTML = "Start With Scratch"
```
### Output

![Output](./Pic31.png)

17. Webiste Name: [Sony](https://www.sony.co.in/)

### Topics

    querySelector,innerHTMl

### Sample Image

![Sample One](./Pic33.png)

### Tasks

     change the button text To current Date.

### code 

```
let btn =document.querySelector(".retailer_btn-align")

btn.textContent = new Date

```

### Output

![Output](./Pic32.png)

18. Webiste Name: [Philips](https://www.philips.co.in/)

### Topics

     querySelector,style,backgroundcolor

### Sample Image

![Sample One](./Pic34.png)

### Tasks

    change the background colour blue to orange

### code 

```
let getBg = document.querySelector(".p-f03-footer-container ")

getBg.style.background = "orange"
```

### Output

![Output](./Pic35.png)

19. Webiste Name: [Canon](https://in.canon/)

### Topics

          querySelector,src

### Sample Image

![Sample One](./Pic36.png)

### Tasks

    extract the canon logo

### code 

```
let logo = document.querySelector(".logo").getAttribute("src")

console.log(logo)
```

### Output

![Output](./Pic37.png)

20. Webiste Name: [Oppo](https://www.oppo.com/in/)

### Topics

          querySelector,style,color

### Sample Image

![Sample One](./Pic38.png)

### Tasks

      Change the description colour black to orange

### code

```
let value = document.getElementsByClassName("desc")[0];
value.style.color = "red"
```

### Output

![Output](./Pic39.png)
