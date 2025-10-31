<template>
  <div>
    <nav class="navbar">
      <div class="nav-container">
        <h2>🚀 Enut+</h2>
        <div class="nav-links">
          <NuxtLink to="/">Início</NuxtLink>
          <NuxtLink to="/sobre">Sobre</NuxtLink>
          <NuxtLink to="/contato">Contato</NuxtLink>
        </div>
      </div>
    </nav>
    
    <NuxtPage />
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
}

.navbar {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  padding: 20px;
  color: white;
}

.nav-container {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-links {
  display: flex;
  gap: 20px;
}

.nav-links a {
  color: white;
  text-decoration: none;
  padding: 10px 20px;
  border-radius: 5px;
  transition: background 0.3s;
}

.nav-links a:hover {
  background: rgba(255, 255, 255, 0.2);
}

.nav-links a.router-link-active {
  background: rgba(255, 255, 255, 0.3);
  font-weight: bold;
}
</style>