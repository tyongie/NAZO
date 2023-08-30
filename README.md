<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>CodePen - Full-Screen Responsive Image Slider</title>
  <link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css'>
  <link rel="stylesheet" href="./style.css">
<style>
  @import url("https://fonts.googleapis.com/css2?family=Lexend:wght@400;700&display=swap");

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: "Lexend", sans-serif;
  background-color: #362a2b;
  color: #e5ebf3;
}

.slider {
  position: relative;
  width: 1400vw;
  height: 1400vh;
  overflow: hidden;
}

.slide {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  opacity: 0;
  transition: opacity 0.5s ease-in-out;
}

.slide.current {
  opacity: 1;
}


.slide:first-child {
  background: url("1.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(2) {
  background: url("2.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(3) {
  background: url("3.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(4) {
  background: url("4.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(5) {
  background: url("5.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(6) {
  background: url("6.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(7) {
  background: url("7.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(8) {
  background: url("8.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(9) {
  background: url("9.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(10) {
  background: url("10.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(11) {
  background: url("11.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(12) {
  background: url("12.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(13) {
  background: url("13.jpg") no-repeat
    center top/cover;
}

.slide:nth-child(14) {
  background: url("14.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(15) {
  background: url("15.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(15) {
  background: url("15.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(16) {
  background: url("16.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(17) {
  background: url("17.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(18) {
  background: url("18.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(19) {
  background: url("19.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(20) {
  background: url("20.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(21) {
  background: url("21.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(22) {
  background: url("22.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(23) {
  background: url("23.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(24) {
  background: url("24.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(25) {
  background: url("25.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(26) {
  background: url("26.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(27) {
  background: url("27.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(28) {
  background: url("28.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(29) {
  background: url("29.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(30) {
  background: url("30.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(31) {
  background: url("31.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(32) {
  background: url("32.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(33) {
  background: url("33.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(34) {
  background: url("34.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(35) {
  background: url("35.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(36) {
  background: url("36.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(37) {
  background: url("37.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(38) {
  background: url("38.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(39) {
  background: url("39.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(40) {
  background: url("40.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(41) {
  background: url("41.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(42) {
  background: url("42.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(43) {
  background: url("43.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(44) {
  background: url("44.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(45) {
  background: url("45.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(46) {
  background: url("46.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(47) {
  background: url("47.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(48) {
  background: url("48.jpg") no-repeat
    center top/cover;
}


.slide:nth-child(49) {
  background: url("49.jpg") no-repeat
    center top/cover;
}


.buttons button#prev {
  position: absolute;
  top: 50%;
  left: 1rem;
}

.buttons button#next {
  position: absolute;
  top: 50%;
  right: 1rem;
}

.buttons button {
  border: 2px solid #e5ebf3;
  background-color: transparent;
  color: #e5ebf3;
  cursor: pointer;
  padding: 13px 15px;
  border-radius: 50%;
  outline: none;
}

.buttons button:hover {
  background-color: #e5ebf3;
  color: #362a2b;
}

@media (min-width: 1400px) and (min-height: 1400px) {
  .slide .content {
    bottom: 70px;
    left: -600px;
    width: 600px;
    padding: 2rem;
    line-height: 1.6;
  }

  .slide .content h1 {
    font-size: 2rem;
  }

  .slide.current .content {
    transform: translateX(600px);
  }
}
</style>
</head>

<body>
  <!-- partial:index.partial.html -->
  <div class="slider">
    <div class="slide current"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>
    <div class="slide"></div>

  </div>
  <div class="buttons">
    <button id="prev"><i class="fas fa-arrow-left"></i></button>
    <button id="next"><i class="fas fa-arrow-right"></i></button>
  </div>
  <!-- partial -->
  <script>
    const slides = document.querySelectorAll(".slide");
    const nextButton = document.getElementById("next");
    const prevButton = document.getElementById("prev");
    const auto = true;
    const intervalTime = 5000;
    let slideInterval;

    const nextSlide = () => {
      const current = document.querySelector(".current");
      current.classList.remove("current");
      if (current.nextElementSibling) {
        current.nextElementSibling.classList.add("current");
      } else {
        slides[0].classList.add("current");
      }
    };

    const prevSlide = () => {
      const current = document.querySelector(".current");
      current.classList.remove("current");
      if (current.previousElementSibling) {
        current.previousElementSibling.classList.add("current");
      } else {
        slides[slides.length - 1].classList.add("current");
      }
    };

    nextButton.addEventListener("click", () => {
      nextSlide();
      if (auto) {
        clearInterval(slideInterval);
        slideInterval = setInterval(nextSlide, intervalTime);
      }
    });
    prevButton.addEventListener("click", () => {
      prevSlide();
      if (auto) {
        clearInterval(slideInterval);
        slideInterval = setInterval(nextSlide, intervalTime);
      }
    });

    if (auto) {
      slideInterval = setInterval(nextSlide, intervalTime);
    }

  </script>

</body>

</html>
