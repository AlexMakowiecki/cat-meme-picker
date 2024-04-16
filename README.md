# Cat meme picker
## What is it? 
It's a website that let you pick a mood and then shows you a cat meme related to it. The meme can be a gif or an image
This project is part of Module 5, where they teach you essential Javascript concepts. 
## What did I use?
I used HTML, CSS, and Javascript.
## Concepts learned for this project and practiced during it
  - **for of** to iterate over every item inside an iterable object, like an Array.
    - ```Javascript
      for (let item of array)
        console.log(item)
      ```
  - use of **import** and **export** to separate variables for the main code when there are many of them.
  - **radio inputs** for when you have multiple options and only want to let the user select one of them
  - **checkbox inputs** for when you have multiple options and want to let the user check or uncheck them freely.
  - **querySelector** to select elements in the DOM using CSS syntax
    - ```Javascript
      document.querySelector("input[type='radio']:checked")
      ```
  - **getElementsByClassName** to select a group of elements in the DOM by their class name.
  - **classList.add** and **classList.remove** to add or remove a class of a DOM element
  - **includes()** to check if an array has the element passed as an argument.
    - ```Javascript
      const exampleArray = ['one', 'two', 'three']
      console.log(exampleArray.includes('two')) // returns 'True'
      ``` 
  - **filter()** to filter items of an array based of a logic inside a function and store them in a new array.
    - ```Javascript
      const exampleArray = ['one', 'two', 'three']
      const newArray = exampleArray.filter(function(itemInArray){ // newArray = ['two']
        return itemInArray === 'two'
      })
      ``` 
## Preview 
<img style="text-align:center" src="https://github.com/AlexMakowiecki/cat-meme-picker/assets/122258496/5ff41205-b8e3-43d5-ba59-ebe4b726ee78" width="500px"/> 


## About Scrimba!


At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Frontend Developer Career Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/allcourses)
- [The Frontend Career Path](https://scrimba.com/learn/frontend)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!
