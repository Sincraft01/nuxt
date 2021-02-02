<template>
  <div class="container bg-gray-700">
    <div>
      <div
        class="max-w-none rounded-xl overflow-hidden bg-gray-100 shadow-lg py-5 px-5"
      >
        <h1 id="black" class="text-6xl font-black text-indigo-500">BLACK</h1>
        <h1 id="mail" class="text-6xl border-3 border-yellow-500 font-thin text-yellow-400">MAIL</h1>

        <div class="links">
          <a
            href="https://blackmail.wtf/webmail/index.php?postlogin"
            target="_blank"
            rel="noopener noreferrer"
            class="material-icons border-2 border-indigo-500 bg-purple-700 rounded-xl py-2 px-5"
          >
            inbox
          </a>
          <button
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
            rel="noopener noreferrer"
            class="material-icons border-2 text-yellow-200 border-indigo-500 rounded-xl py-2 px-5 bg-purple-700"
          >
            cloud
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/

#mail {
transform: rotate(45);
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  letter-spacing: 10px;
}
#black {
  animation: 6s appear;

  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  letter-spacing: 10px;
}
@keyframes appear {
  0% {
    opacity: 0;
  }
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
