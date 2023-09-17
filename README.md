# JS-Practical-Components

1. DOM & DOM Events

Three ways to manipulate buttons, best way is to addEventListeners. It is the cleanest way to read the code.

const lalaButton = document.querySelector(".lala-btn");

      function notListening() {
        document.body.style.backgroundColor = "#1a1a1a";
      }

      lalaButton.addEventListener("click", notListening);
      lalaButton.addEventListener("mouseenter", goCoocoo);
      const buttons = document.querySelectorAll("button");
      buttons.forEach((button) =>
        button.addEventListener("mouseleave", notListening)
      );

2. Building a Pricing Calculator

Learned how to setup basic program, and process.

    grab everything we need from dom
      const priceInput = document.querySelector("[name=price]");

      // create the functions that we'll need
      function calculatePieCost() {
        const price = priceInput.value;

      }

      // on first run
      calculatePieCost();

      // add our event listeners
      priceInput.addEventListener("input", calculatePieCost);

3.  Crazy Buttons
    Learned how to modify CSS with eventlistners, using this or other ways to target multiple of same class. All needed on query selector. ForEach needed on EventListener

4.  Code pen video was just how to use a Code Pen, nothing about making one.

5.  Stopwatch
    learned about using data- to select HTMl elements instead of numerous classes. Userd variables, terinary opperator.
    Use is running boolean.

6.  Accodrion

        Learned how to make an accordion with closing and opening texts.
        Was not able to get glyphicon to work, used V, but letter doesnt seem to rotate

7.  Scrolling Progress Bar
    Learned about some window quesry selectors, and about using debounce on functions that may interact or run too often.

8.  Reflection

    A. The practice with query selectors and Event listeners was the most helpful. Only through repetition is stuff learned, so seeing it used over and over was helpful.

    B. Each component ranked with difficulty. 1. Stopwatch 2. Pricing 3. Crazy Buttons 4. Accordian 5. Scrolling

    C.The organization of the script elements was very useful. Knowing that you should pull down what you need, then add event listeners, then define the functions lets you break down the problem into easier and smaller problems.
