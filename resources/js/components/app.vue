<template>
  <div class="todoContainer">
      <div class="heading">
          <h2 id="title">Todo List</h2>
          <add-item-form></add-item-form>
      </div>
        <list-view></list-view>
  </div>
</template>
<script>

import addItemForm from './addItemForm'
import listView from './listView';
import ListView from './listView.vue';

export default {
  components:{
      addItemForm,
       listView
    
  }
};
</script>
<style scoped>
.todoContainer{
    width:350px;
    margin:auto;
}

</style>