<template>
  <div class="container">
    <div class="row">
      <form>
        <fieldset>
          <legend>Legend</legend>
          <app-search @newDataSet="result = $event"></app-search>
        </fieldset>
      </form>
    </div>

    <div class="row">
      <div class="col-md-12">
        <app-result  :reList= "result"></app-result>
        
      </div>
    </div>
  </div>
</template>

<script>
import SearchArea from "./SearchArea";
import ReasulthArea from "./ResultArea";
export default {

data(){
  return{
result:[]
  }
},



  components: {
    "app-search": SearchArea,
    "app-result": ReasulthArea
  }
};
</script>

<style></style>
