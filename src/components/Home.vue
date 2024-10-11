<template>
    <div class="home">
      <header>
        <nav>
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Portfolio</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">About</a></li>
          </ul>
        </nav>
      </header>
      <hero>
        <img src="./assets/profile.jpg" alt="Profile Picture">
        <h1>Welcome to my website</h1>
        <p>I'm a student persuing a developer carrer.</p>
      </hero>
      <footer>
        <p>&copy; 2024 My Website</p>
      </footer>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Home'
  }
  </script>
  
  <style scoped>
  .home {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
  }
  
  header {
    background-color: #3498db;
    color: #f9f9f9;
    padding: 10px;
    text-align: center;
  }
  
  nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
  }
  
  nav li {
    margin-right: 20px;
  }
  
  nav a {
    color: #f1c40f1;
    text-decoration: none;
  }
  
  hero {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
  }
  
  hero img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin-bottom: 10px;
  }
  
  footer {
    background-color: #3498db;
    color: #f9f9f9;
    padding: 10px;
    text-align: center;
    clear: both;
  }





  .home {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
}

@media (max-width: 768px) {
  .home {
    flex-direction: row;
  }
}

@media (max-width: 480px) {
  .home {
    flex-direction: column;
  }
}

  </style>


