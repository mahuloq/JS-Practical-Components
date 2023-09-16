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
