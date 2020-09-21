<template> 
	
<div class="container">
<div class="card" style="width: 18rem;">
  <img :src="image" class="card-img-top" alt="...">
  <hr>
  <div class="card-body">
    <p class="card-title" :style="{fontSize: fontSize + 'px'}">{{ message ? message : "Menu"}}</p>
  </div>
</div>

<!-- Form --> 

<form>
  <div class="form-col">
    <div class="col">
    	<h4 class="title">title</h4>
      <input type="text" class="form-control" placeholder="" v-model="message">
    </div>
    <div class="col">
    	<h4>font-size</h4>
      <input type="text" class="form-control" v-model="fontSize" placeholder="font-size">
    </div>
  </div>
</form>

</div> 

</template>

<script>
  export default {
    data() {
    return {
        message: 'MENU',
        fontSize: 16,
        image: 'assets/apple.jpg',
    }
  },

  }
  </script>