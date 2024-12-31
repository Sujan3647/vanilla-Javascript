


# Project related  to DOM

## project link

[Click here](https://stackblitz.com/edit/dom-project-chaiaurcode?file=index.html)

# solution code

## project 1

```Javascript

const buttons = document.querySelectorAll('.button')
 const Body = document.querySelector('body')

 buttons.forEach( function (button){
   console.log(button)
   button.addEventListener('click', function (e){
     console.log(e);
     console.log(e.target);

     if (e.target.id === 'grey')
     {
       Body.style.backgroundColor = 'grey'
     }
     if (e.target.id === 'white')
     {
       Body.style.backgroundColor = 'white'
     }
     if (e.target.id === 'blue')
     {
       Body.style.backgroundColor = e.target.id
     }

     if (e.target.id === 'yellow')
     {
       Body.style.backgroundColor = e.target.id 
     }

   })
 })

```