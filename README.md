<html>
  <head>
    <style>
      h1 {
        text-align: center;
        color: blueviolet;
      }

      h2 {
        text-align: center;
        border-radius: 10px;
        border: 1px solid blueviolet;
        padding: 15px;
      }

      img {
        border-radius: 10px;
        width: 100%;
      }

      p {
        font-size: 14px;
        line-height: 1.5;
      }

      button {
        width: 100%;
        background: blueviolet;
        color: white;
        border: none;
        padding: 15px;
        font-size: 20px;
        border-radius: 30px;
        box-shadow: 0 15px 20px rgba(0, 0, 0, 0.3);
        margin: 20px 0;
      }

      footer {
        text-align: center;
        font-size: 12px;
      }
    </style>
  </head>
  <body>
    <h1>
      🧘‍♀️ Pilates
    </h1>
    <h2>
      Discipline + Concentration
    </h2>
    <img
      src="https://assets.vogue.com/photos/64a6c7863a74fead8c241866/4:3/w_5255,h_3941,c_limit/GettyImages-1306517212.jpg"
      alt=""
    />
    <p>
      Pilates is a type of exercise that focuses on core strength and body conditioning through precise movements, controlled breathing, and muscle engagement.Pilates is a form of strength training, but it doesn't look like some of the other strength training exercises you might be familiar with. Pilates focuses more on improving muscle tone than building muscles, but the result is similar: greater stability and endurance.
      <br />
      <br />
      <a href="https://www.nhs.uk/conditions/nhs-fitness-studio/pilates-and-yoga/pilates-for-beginners/">
        Learn more on NHS Website
      </a>
    </p>
    <button>
      Go to a Pilates class
    </button>
    <footer>
      Coded by 👩‍💻
      <a href="https://www.linkedin.com/in/shristi-k-24623924a/">
        Shristi Kalyan
      </a>
    </footer>

    <script>
      function subscribe() {
        let name = prompt("What is your name?");
        prompt("What is your email address?");

        alert(
          `Thanks, ${name}! We'll be in touch! Meanwhile, don't forget to breathe 🧘‍♀️`
        );
      }

      let button = document.querySelector("button");
      button.addEventListener("click", subscribe);
    </script>
  </body>
</html>
