<template>
  <div class="error-page-details">
    <img style="width:100%" src="@/assets/Daily-UI-008-404-Error-Page-1.jpg" class="rounded d-block mx-auto h400" />
    <div style="align-item:center">
      <button type="button" @click="goBack()" class="btn btn-secondary" >
        Go Back
      </button>
    </div>
  </div>
</template>
<script>



export default {
  name: 'ErrorPage',
  components: {},
  methods:{
    goBack(){
      this.$router.push({name:'Home'})
    }
  }
};
</script>
<style scoped>
.h400{
  height: 400px;
  margin-top: 5px;
}

</style>