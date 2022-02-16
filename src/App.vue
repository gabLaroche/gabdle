<template>
  <div id="app">
    <word-grid />
	  <keyboard />
  </div>
</template>

<script>
import Keyboard from "./components/keyboard/Keyboard";
import WordGrid from "./components/word-grid/WordGrid";

export default {
  name: 'App',
  components: {
    Keyboard,
	  WordGrid,
  }
}
</script>
