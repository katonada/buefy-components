<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png" /> <BuefyComponents />
  </div>
</template>

<script>
import Vue from "vue";
import BuefyComponents from "./components/BuefyComponents";

// Import buefy components
import Autocomplete from "buefy/dist/components/autocomplete";
import Checkbox from "buefy/dist/components/checkbox";
import Collapse from "buefy/dist/components/collapse";
import Datepicker from "buefy/dist/components/datepicker";
import Dropdown from "buefy/dist/components/dropdown";
import Field from "buefy/dist/components/field";
import Icon from "buefy/dist/components/icon";
import Input from "buefy/dist/components/input";
import Loading from "buefy/dist/components/loading";
import Modal from "buefy/dist/components/modal";
import Pagination from "buefy/dist/components/pagination";
import Radio from "buefy/dist/components/radio";
import Snackbar from "buefy/dist/components/snackbar";
import Tabs from "buefy/dist/components/tabs";

// Buefy components
Vue.use(Autocomplete);
Vue.use(Checkbox);
Vue.use(Collapse);
Vue.use(Datepicker);
Vue.use(Dropdown);
Vue.use(Field);
Vue.use(Icon);
Vue.use(Input);
Vue.use(Loading);
Vue.use(Modal);
Vue.use(Pagination);
Vue.use(Radio);
Vue.use(Snackbar);
Vue.use(Tabs);

export default {
  name: "App",
  components: {
    BuefyComponents
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
