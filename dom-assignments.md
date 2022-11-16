### DOM assignments from Fun with DOM sandbox

## Assignment 01

Problem statement:
- Webiste Name: [Dev To](https://dev.to/)
- Change the heading of right top card

Solution code:

```
document.querySelector(".side-bar .crayons-subtitle-2").innerText = "Govind Magar"
document.querySelector("aside div p").innerText = "My passion is coding and learning new skills"
```

## Assignment 02

Problem statement:
- Website Name: [Apple](https://support.apple.com/en-in)

- Fetch all the product name and store in an array

Solution:

```
let elements = document.querySelectorAll(".as-imagegrid-item-title")
let arr = [];
for(item of elements){
   const temp = item.innerText.replace("\nSupport", " ");
     arr.push(temp);
    console.log(temp);
}
console.log(arr);

Output:
 ['iPhone ', 'Mac ', 'iPad ', 'Watch ', 'AirPods ', 'Music ', 'TV ']
```

## Assignment 03

Problem statement:

- Webiste Name: [Youtube Support](https://support.google.com/youtube/)

- Get Element By Id, Create Element, Create Text Node, Append Child

Solution:

```
const nav_item = document.querySelector(".parent");
let temp_ele = nav_item;
temp_ele.firstChild.innerText = "My new FAQ";
document.getElementById("myparent").appendChild(temp_ele);
```

## Assignment 04

Problem statement:

- Webiste Name: [OnePlus](https://www.oneplus.in/support)
- Change the contact number

Solution:

```
const one_plus_cont = document.querySelector(".oneplus-footer--contact__list")
one_plus_cont.firstChild.firstChild.innerText = "+91 88888 88888";
```


## Assignment 05

Problem statement:

5. Webiste Name: [Samsung](https://www.samsung.com/in/offer/online/samsung-fest/)

### Topics

       getElementById, createElement, InnerText, append, setAttribute

### Tasks

     Target the main div of card and change the Button text to Check out
Solution:

```

```

## Assignment 06

Problem statement:

6. Webiste Name: [Adidas](https://www.adidas.co.in/)

### Topics

    -   Query Selector, Event listeners, Changing Styles

### Tasks

     Target the search box and on hover change thebackground color to red.

Solution:
```
const searchEle = document.getElementsByClassName("searchinput___19uW0")[0];
searchEle.addEventListener('mouseover', ()=> {
    searchEle.style.backgroundColor = "red";
});
```

## Assignment 07

Problem statement:

- Webiste Name: [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Topics

       Form, Value, Submit

### Tasks

     To Search a topic in the MDN Search bar.
     First add a text to search in the search bar and then hit the submit search button to search the docs using DOM

Solution:
```
document.getElementById("top-nav-search-input").value = "CSS selectors";
document.getElementById("top-nav-search-form").submit();
});
```

## Assignment 08

Problem statement:

- Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Tasks

     Remove alternate languages from the home page languages listed

Solution:
```

```

## Assignment 09

Problem statement:

- Webiste Name: [Code Wars](https://www.codewars.com/)

### Topics

       Change Font Family, Color of Text.
### Tasks

    Change the font family of the text to monospace and text color to the logo’s background color.


Solution:
```
codewars_headline_span = document.getElementsByClassName("text-color-hero-gradient");
codewars_headline = document.getElementsByClassName("text-color-white");
codewars_headline[0].style.color = "red"
codewars_headline_span[0].style.backgroundImage = "linear-gradient(90deg, #FF0000, #FF0000)"
codewars_headline[0].style.fontFamily = "Impact,Charcoal,sans-serif";
```


## Assignment 10

- Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

     querySelector, mouseover, click eventListener,  callback function, style,

### Tasks

    Target the button and change background colour on mouseover

Solution:
```
free_code_camp_btn = document.getElementsByClassName("btn-cta-big btn-block signup-btn btn-cta btn btn-default")[0];
free_code_camp_btn.addEventListener("mouseover", (e)=>{
    e.target.style.backgroundColor = "red";
})
```

## Assignment 11

- Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Tasks

    change the realme logo to ineuron logo

Solution:
```
realme_logo = document.getElementsByClassName("icon icon-logo in")[0];
realme_logo.style.backgroundImage = "url('https://ineuron.ai/images/ineuron-logo.png')";
```


## Assignment 12

- Webiste Name: [Github](https://github.com/)

### Topics

       querySelector,style,background-Color

### Tasks

     change the background colour of the button to blue.

Solution:
```
let git_btn = document.getElementsByClassName("btn btn-sm btn-primary btn mb-2")[0];
git_btn.style.backgroundColor = "blue";
```

## Assignment 13

- Webiste Name: [Asus](https://www.asus.com/in/)

### Topics

     querySelector,style,font-size

### Tasks

     change the fontsize of “Hot Deals” to 80px

Solution:
```
let asus_hot_deal = document.getElementsByClassName("HotDealsAll__Heading__2fIbe")[0];
asus_hot_deal.style.fontSize = "80px";
```

## Assignment 14

- Webiste Name: [Dell](https://www.dell.com/en-in/shop/deals/laptop-deals?gacd=10415953-9016-5761040-285981356-0&dgc=ST&gclid=Cj0KCQjwguGYBhDRARIsAHgRm4-XUDMhhVNyHXb3s1gY4ZBzORr_d9Se-buhJwy7asyUe7YdqEA11eEaAt6UEALw_wcB&gclsrc=aw.ds&nclid=BxjBlpBQsX6pjSHh-L8YYSU77EpfXRkG1AGMB5Wbeu386ykspfrPDnfx_DdFau20)

### Topics

     querySelector,style.textAlign

### Tasks

     Convert the text “G15 Gaming Laptop” from left to right

Solution:
```
let offer_card = document.getElementById("d560822win9b").getElementsByTagName("h3")[0];
offer_card.style.textAlign = "right";
```

## Assignment 15

16. Webiste Name: [Vercel](https://vercel.com/)

### Topics

     querySelector,innerHTMl

### Tasks

      change the heading “Start with the developer” to “Start with Scratch”

Solution:
```
let vercel_heading = document.getElementsByClassName("section-title_title__VEDfK")[0];
vercel_heading.innerText = "Start with Scratch";
```
