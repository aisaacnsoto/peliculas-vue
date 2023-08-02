<template>
  <header>
    <router-link to="/" class="logo">
      <h1>Películas <span>Vue</span></h1>
    </router-link>
  </header>
  <main>
    <router-view />
  </main>
</template>

<style>
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}

#app {
  text-align: center;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px 0;
}

.logo {
  text-decoration: none;
  color: #fff;
}

.logo h1 {
  margin: 0;
  font-size: 24px;
}

.logo span {
  color: #ffc107;
}

main {
  padding: 20px;
}

.feature-card {
  max-width: 600px;
  margin: 0 auto;
  padding: 20px;
  background-color: #f5f5f5;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
}

.feature-card .movie-link {
  text-decoration: none;
  color: #333;
}

.featured-img {
  max-width: 100%;
  height: auto;
  margin-bottom: 10px;
}

.detail h3 {
  margin: 0;
  font-size: 24px;
  color: #333;
}

.detail p {
  margin: 10px 0;
  font-size: 16px;
  color: #666;
}

.search-box {
  display: flex;
  justify-content: center;
  margin: 20px 0;
}

.search-box input[type="text"] {
  padding: 10px;
  font-size: 16px;
}

.search-box input[type="submit"] {
  padding: 10px 20px;
  background-color: #007bff;
  color: #fff;
  border: none;
  font-size: 16px;
  cursor: pointer;
}
</style>