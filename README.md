# change-color

change-color and working with array!






const button = document.querySelector('.button'),
      wind = document.querySelector('.allWind'),
      output = document.querySelector('.output');


      const colors = ['red', 'black', 'yellow'];

      button.addEventListener('click', ()=>{
        const random = getRandom();
        
        console.log(random);
        wind.style.background = colors[random];
      });
      function getRandom (){
        return Math.floor(Math.random() * colors.length);
      }
