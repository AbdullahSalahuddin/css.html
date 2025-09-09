/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  color: #333;
  background: #fff;
  line-height: 1.6;
}

/* Header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 50px;
  background: #f9f9f9;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.logo {
  height: 50px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
}

nav a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
}

/* Hero */
.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 60px 50px;
  background: linear-gradient(to right, #6dd5ed, #2193b0);
  color: #fff;
}

.hero-text {
  max-width: 50%;
}

.hero-text h1 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.hero-text p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.hero-text .buttons img {
  height: 50px;
  margin-right: 10px;
}

.hero-image img {
  max-width: 350px;
  border-radius: 20px;
}

/* Features */
.features {
  padding: 50px;
  text-align: center;
}

.features h2 {
  margin-bottom: 30px;
  font-size: 2rem;
}

.feature-items {
  display: flex;
  justify-content: center;
  gap: 40px;
}

.feature {
  width: 250px;
}

.feature img {
  height: 60px;
  margin-bottom: 15px;
}

.feature h3 {
  margin-bottom: 10px;
}

/* Screenshots */
.screenshots {
  padding: 50px;
  text-align: center;
  background: #f9f9f9;
}

.screenshots h2 {
  margin-bottom: 30px;
  font-size: 2rem;
}

.screens {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.screens img {
  max-width: 200px;
  border-radius: 10px;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  background: #222;
  color: #fff;
}
