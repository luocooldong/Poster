<template>
  <div id="app">
    <main>
      <h1>众乐乐代理海报系统</h1>
      <PosterLogo />
      <!-- <poster /> -->
      <!-- <app-typography-icon /> -->
      <app-animated-icon />
    </main>
  </div>
</template>

<script>
import AppTypographyIcon from './components/AppTypographyIcon'
import AppAnimatedIcon from './components/AppAnimatedIcon'
import Poster from './components/Poster'
import PosterLogo from './components/PosterLogo'

export default {
  components: {
    AppTypographyIcon,
    AppAnimatedIcon,
    Poster,
    PosterLogo
  }
}
</script>

<style>
body,
html {
  margin: 0;
}

#app {
  font-family: 'Nunito', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #222;
  font-weight: 300;
  background: #f1efef;
  width: 100vw;
  height: 100vh;
  font-size: 17px;
}

h1,
h2,
h3,
h4,
h5 {
  font-weight: 800;
  color: #5a5a5a;
}

main {
  /* width: 800px; */
  width: 100%;
  margin: 0 auto;
  display: table;
}

section {
  padding: 20px;
  padding-top: 5px;
  margin-top: 1px;
  background: #fff;
  border: 1px solid #eee;
}

h2 {
  margin-bottom: 0;
}

a,
a:visited,
a:hover {
  color: #949090;
  text-decoration: none;
  font-weight: 700;
}

.info {
  margin-top: 0;
  font-family: 'Lato', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  font-style: italic;
  color: #949090;
}
</style>
