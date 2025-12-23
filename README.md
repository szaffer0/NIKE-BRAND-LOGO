# NIKE-BRAND-LOGO
I’ve created a React component that visually and textually describes the Nike brand logo (Swoosh) in a clean, professional layout.
import React from 'react'

const HeroSection = () => {
  return <main className="hero container">

    <div className="hero-content">

        <h1>YOUR FEET DESERVE THE BEST</h1>

        <p>
            A FOOTBALL EXPERIENCE
           THAT AMPLIFIES THE TRUE
           NATURE OF THE GAME AND
           THE DNA OF NIKE
        </p>

        <div className="hero-btn">
            <button>Shop Now</button>
            <button className="secondary-btn">
                Category</button>
        </div>

        </div>
    <div className="brand-icons">
                </div>
    <div className="hero-image">
        <img src="/images/hero-image.png" alt="hero-image" />
    </div>
    </main>


};
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');
body {
  margin: 0;
  font-family: 'Roboto', sans-serif;
  background-color: white;
  color: #333;
}
:root {
  --red: #ff4757;
  --gray: #2e2e2e;
}
*{
  margin: 0%;
}
button {
  font-family: 'Montserrat', sans-serif;
  background-color: var(--red);
  color: white;
  height: 32px;
  padding: 6px 16px;
  font-weight: 500;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
.container {
  margin: 0% auto;
  max-width: 1280px;
}
nav {
  display:flex;
  justify-content: space-between;
  background-color:white;
  height: 72px;
  align-items: center;
}
nav ul {
  display: flex;
  list-style: none;
  gap: 24px;
  margin-right: 24px;
}
img {
  max-width: 10%;
  height: auto;
  background-color: whitesmoke;
}
.hero{
  display: flex;
  align-items: center;
  height: 100vh-72px;
}
.hero-content{
  display: flex;
  flex-direction: column;
  gap: 24px;
}
.hero h1{
  font-weight: 800;
  font-size: 150px;
  line-height: 150px;
  color: black;
}
.hero p{
  font-weight: 800;
  color: var(--grey);
  max-width: 500px;
}
hero-btn {
  display: flex;
  gap: 40px;
  margin-top: 32px;
}
.hero button {
  width: 160px;
}

.secondary-btn {
  background: transparent;
  color: var(--gray);
  border: 1px solid var(--gray);
  gap: 40px;
}
.hero-image img {
  max-width: 140%;
  height: auto;
}


export default HeroSection;

