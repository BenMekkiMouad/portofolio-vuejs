<template>
    <header>
      <nav>
        <h1>My Web Dev Business</h1>
        <ul>
          <li><a href="#hero">Home</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#portfolio">Portfolio</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
  </template>

  <script>
    export default {
        name: 'HeaderComponent',
    }
  </script>
  
  <style scoped>
  header {
    background: #333;
    color: white;
    padding: 1rem 0;
    padding: 1rem;
  }
  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  ul {
    list-style: none;
    display: flex;
  }
  li {
    margin-left: 1rem;
  }
  a {
    color: white;
    text-decoration: none;
  }
  </style>
  