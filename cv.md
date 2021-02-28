# Sverdlov Rodion

## Contacts

* [Instagram](https://www.instagram.com/rodiomonsverdlov/)
* [Vkontakte](https://vk.com/rodimonsverdlov)
 
 
 ## Some information about me
 My goal of completing the courses is to gain a deeper knowledge of Front-End and subsequently find a job as a developer. My strengths are the ability to quickly find solutions to complex problems, the ability to google and understand new material myself. I have no experience in commercial website development, but on an amateur level I studied `ReactJS` and `Bootstrap` and wrote my own websites and web applications for myself. I also studied C++ and wrote labs and term papers in it.


## My skils
- HTML
- CSS
- JS (some)
- React (some)
- Bootstrap (some)
- React-Bootstrap (some)
- Adaptive layout
- С++ (OOP)
- VS Code
- Visual Studio

## Code examples
`JavaScript`
```JavaScript 
phosphor.onclick = function openalbum(){
    var PH = document.getElementById("myAlbumPhosphor");
    if(PH.className==="albumPhosphor"){
        PH.className += " responsive";
    }else{
        PH.className = "albumPhosphor";
    }
}

menu.onclick = function myFunction(){ // событие клик по блоку меню
    var x = document.getElementById("myTopnav");
    if(x.className === "topnav"){
        x.className += " responsive";
    }else{
        x.className = "topnav";
    }
} 

ReactJS
import React from "react";

class Form extends React.Component{
    render(){
        return(
            <form onSubmit={this.props.weatherMethod}>
                <input type="text" name="city" placeholder="Город"/>
                <button class="butt">Получить погоду</button>
            </form>
        );
    }
}

export default Form;
```

## Education
At the moment I am finishing the 2nd course of `BSUIR on the specialty Information systems and technologies`. Also took video courses on Front End on such channels as `Web Developer Blog` `Gosha Dudar` 

## My English
My level of English is enough to watch TV shows and films in the original, I can also speak English on general topics and know technical terms
