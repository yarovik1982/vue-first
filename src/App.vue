<template>
  <nav class="teal darken-4" style="padding-top: 5px;height: 80px;">
    <div class="nav-wrapper">
      <a href="#" class="logo brand-logo center">
        <svg width="100" height="68" viewBox="0 0 100 68" fill="none" xmlns="http://www.w3.org/2000/svg">
					<rect x="2.12132" y="33.981" width="45.0566" height="45.0566" transform="rotate(-45 2.12132 33.981)"
						stroke="gold" stroke-width="3" />
					<rect x="34.159" y="33.981" width="45.0566" height="45.0566" transform="rotate(-45 34.159 33.981)"
						stroke="gold" stroke-width="3" />
					<text x="40" y="40" class="text-svg">42</text>
				</svg>
      </a>
    </div>
  </nav>
  <router-view/>
</template>

<style >
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.text-svg{
  fill: gold;
  font: bold 16px sans-serif;
}
.logo{
  padding: 7px 0;
}
</style>
