<template>
  <div>
    <form action="" method="">
      <input type="text" v-model="msg" @input="input=true">
    </form>
    <div> {{msg}} </div>
  </div>
</template>

<script>

var input;

if(input == true){
  document.querySelector('form').submit();

  document.addEventListener('submit',(e)=>{
    e.preventDefault;
  })

  input = false;
}

export default {
  name: "HelloWorld",
  data(){
    return{
      msg: ''
    }
  }
}
</script>