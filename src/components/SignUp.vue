<template>
    <div>

 <input type="text" placeholder="enter yuor name" v-model="signup.username" /><br><br>
 <input type="password" placeholder="enter yuor password" v-model="signup.password"/><br><br>
  <p>Choose Hobbies</p>
 <input type="checkbox" id="circket" value="circket" v-model="signup.password" />
 <label for="circket">Cricket
 </label>
  <p>Choose Hobbies</p>
  <input type="checkbox" id="football" value="football" v-model="signup.hobbies" />
 <label for="football">Football
 </label>
 <p>Select Gender</p>
  <input type="radio" id="male" value="male" v-model="signup.gender" />
 <label for="male">Male
 </label>
 <p>Select Gender</p>
  <input type="radio" id="female" value="female" v-model="signup.gender" /><br><br>
 <label for="female">Female
 </label><br><br>
 <button v-on:click="signupUser">Sign Up</button>
    </div>
</template>

<script>
    export default {
     name:"SignUp",
      data(){
          return{
              signup:{
              username:null,
              password:null,
              hobbies:[],
              gender:null
              }
          }
      },
      methods:{
       signupUser(){
           consol.console.warn(this.signup)
       }
      }
    }
</script>

<style lang="scss" scoped>

</style>