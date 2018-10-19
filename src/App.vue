<templete>
  <div id="app">
    <Home v-if="!isLogin"></Home>
    <Editor v-if="isLogin"></Editor>
  </div>
</templete>

<script>
import Home from "./components/Home.vue";
import Editor from "./components/Editor.vue";

export default {
  name: "app",
  data() {
    return {
      isLogiin: false
    };
  },
  components: {
    Home: Home,
    Editor: Editor
  }
};
</script>
