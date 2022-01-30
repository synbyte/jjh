<template>
  <div class="animate__animated animate__flipInX animate__delay-1s">
  
    <b-navbar class="header" toggleable="md" type="dark" >
      <b-navbar-brand class="animate__animated animate__pulse animate__infinite animate__slow" href="/" id="brand">JJHM</b-navbar-brand>

      <b-button class="toggle" v-b-toggle.nav-collapse></b-button>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="/contact">Contact </b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        
      </b-collapse>
    </b-navbar>
  </div>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Big+Shoulders+Stencil+Text:wght@700&display=swap');

html {
  font-family:"Big Shoulders Stencil Text";
  font-size:22px;
}
#brand {
  font-family:"Big Shoulders Stencil Text";
}
</style>
