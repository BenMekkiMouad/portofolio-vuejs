<template>
    <section id="hero">
      <div class="hero-content">
        <h2>Welcome to My Web Dev Business</h2>
        <p>We create stunning websites and mobile apps.</p>
        <button>Get Started</button>
      </div>
    </section>
  </template>
  <script>
  export default {
      name: 'HeroComponent',
  }
</script>
  <style scoped>
  #hero {
    background: url('https://images.unsplash.com/photo-1461749280684-dccba630e2f6?w=500&auto=format&fit=crop&q=100&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MzB8fHdlYiUyMGRldiUyMGNvbnN1bHRpbmd8ZW58MHx8MHx8fDA%3D') no-repeat center center;
    background-size: cover;
    color: white;
    text-align: center;
    padding: 5rem 1rem;
  }
  .hero-content {
    max-width: 600px;
    margin: 0 auto;
  }
  button {
    background: #ff6600;
    color: white;
    border: none;
    padding: 1rem 2rem;
    margin-top: 1rem;
    cursor: pointer;
  }
  button:hover {
    background: #cc5200;
  }
  </style>
  