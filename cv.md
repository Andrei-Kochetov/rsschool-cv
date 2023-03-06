# CV
## 1. Name 
###   Andrei Kochetov
## 2. Contacts
###  ● tel: +79198372526 
###  ● email: andrei.glava03@gmail.com
## 3. About me
### I am a young and ambitious person. I set myself the goal of becoming a junior front-end developer before the end of this year. Extensive experience in various fields (sales, bank customer support, courier, oil industry in the north)
## 4. Skills
### ● JS (beginner)
### ● HTML5
### ● CSS3
### ● Figma
### ● git
### ● BEM methodology
## 5. Code examples
    function showSlide(){
        if(indexImg > images.length - 1){
            indexImg = 0;
        }
        if(indexImg < 0){
            indexImg = images.length - 1;
        }
        images.forEach((img) =>{
            img.style.display = ' none';
        })
       dots.forEach((dot)=>{
            dot.classList.remove('activity');
        })
        dots[indexImg].classList.add('activity');
        images[indexImg].style.display = 'block';
    }
## 6. Experience
## 7. Education
### Higher Law (SSLA), 2 courses by Ivan Petrichenko on Udemi (HTML5 and CSS3, JS)
## 8. English level A2
