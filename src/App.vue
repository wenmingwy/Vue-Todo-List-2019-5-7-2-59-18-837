<template>
  <div id="app">
      <div>
         <h2>Jquery To Do List</h2>
        <!-- <h2 style="text-align:left">Jquery To Do List</h2> -->
          Simple Todo List with adding and filter by diff status.
         <div> 
            <input class="input-text" type="text" name="add" />
            <div id="button">Add</div>
          </div>
      </div>
              <div>
            <ul id="filters">
                <li>
                    <a href="#" data-filter="all">ALL</a>
                </li>
                <li>
                    <a href="#" data-filter="active">Active</a>
                </li>
                <li>
                    <a href="#" data-filter="complete">Complete</a>
                </li>
            </ul>
        </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    todolist
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
