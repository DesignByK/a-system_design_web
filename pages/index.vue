<template>
  <section class="container">
    <div>
      <Logo/>
      <h1 class="title">
        A-SYSTEM DESIGN ON WEB
      </h1>
      <div class="comment">
        Strategy, Planning, Design, System, Create,<br>
        since 2018.
      </div>
      <div class="links">
        <a href="https://a-system-kk.co.jp" target="_blank" class="button--grey">Central office</a>
        <a href="#" class="button--grey">Design division</a>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  background: linear-gradient(250deg, #abffdb, #74c8e8);
  background-size: 400% 400%;
  -webkit-animation: AnimationName 6s ease infinite;
  -moz-animation: AnimationName 6s ease infinite;
  animation: AnimationName 6s ease infinite;
  min-height: 96vh;
  min-width: 98vw;
  margin: 2vh 1vw;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

@-webkit-keyframes AnimationName {
  0%{background-position:0% 54%}
  50%{background-position:100% 47%}
  100%{background-position:0% 54%}
}
@-moz-keyframes AnimationName {
  0%{background-position:0% 54%}
  50%{background-position:100% 47%}
  100%{background-position:0% 54%}
}
@keyframes AnimationName {
  0%{background-position:0% 54%}
  50%{background-position:100% 47%}
  100%{background-position:0% 54%}
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 1em;
  color: #35495e;
  letter-spacing: 1px;
  padding-top: 15px;
}

.comment {
  font-weight: 300;
  font-size: 1em;
  color: #35495e;
  padding-top: 15px;
  padding-bottom: 15px;
}


</style>
