<template>

  <div class="container-fluid bg-gray-100 h-screen w-screen">
    <div class="grid grid-cols-3 gap-1">
      <div class="bg-white h-full w-full">
        <div>

        </div>
      </div>
      <div class="col-span-2 bg-white h-[100vh] w-full">
        <div class="m-20" style="text-align: -webkit-center">
          <div class="">
            <img src="https://vuely.theironnetwork.org/static/img/session.png ">
            <h2 class="text-[1.5rem] mb-[16px] font-bold mt-3">Login To Admin</h2>
            <p class="font-medium">Enter username and password to access control panel of Vuely.</p>
          </div>
          <div>
            <form>
              <div class="relative z-0 w-[50%] mb-10 group">
                <input type="email" name="floating_email" id="floating_email"
                       class="block py-2.5 px-0 w-full text-sm text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer"
                       placeholder=" " required/>
                <label for="floating_email"
                       class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:left-0 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6">Email
                  address</label>
              </div>
              <div class="relative z-0 w-[50%] mb-10 group">
                <input type="password" name="floating_password" id="floating_password"
                       class="block py-2.5 px-0 w-full text-sm text-gray-900 bg-transparent border-0 border-b-2 border-gray-300 appearance-none dark:text-white dark:border-gray-600 dark:focus:border-blue-500 focus:outline-none focus:ring-0 focus:border-blue-600 peer"
                       placeholder=" " required/>
                <label for="floating_password"
                       class="peer-focus:font-medium absolute text-sm text-gray-500 dark:text-gray-400 duration-300 transform -translate-y-6 scale-75 top-3 -z-10 origin-[0] peer-focus:left-0 peer-focus:text-blue-600 peer-focus:dark:text-blue-500 peer-placeholder-shown:scale-100 peer-placeholder-shown:translate-y-0 peer-focus:scale-75 peer-focus:-translate-y-6">Password</label>
              </div>
              <button type="submit"
                      class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
                Submit
              </button>
            </form>
          </div>
        </div>

      </div>
    </div>
  </div>
  <!--  <div>-->
  <!--    <div class="flex items-center justify-center h-screen px-6 bg-gray-200">-->
  <!--      <div class="w-full max-w-sm p-6 bg-white rounded-md shadow-md">-->
  <!--        <div class="flex items-center justify-center">-->

  <!--          <span class="text-2xl font-semibold text-gray-700">Cove Admin</span>-->
  <!--        </div>-->

  <!--        <form class="mt-5" @submit.prevent="LoginData">-->
  <!--          <label class="block">-->
  <!--            <span class="text-sm text-gray-700">Email</span>-->
  <!--            <input type="email" v-model="student.email" class="block w-full mt-1 border-gray-200 rounded-md focus:border-indigo-600 focus:ring focus:ring-opacity-40 focus:ring-indigo-500" />-->
  <!--          </label>-->

  <!--          <label class="block mt-3">-->
  <!--            <span class="text-sm text-gray-700">Password</span>-->
  <!--            <input type="password" v-model="student.password" class="block w-full mt-1 border-gray-200 rounded-md focus:border-indigo-600 focus:ring focus:ring-opacity-40 focus:ring-indigo-500"/>-->
  <!--          </label>-->

  <!--          <div class="flex items-center justify-between mt-4">-->
  <!--            <div>-->
  <!--              <label class="inline-flex items-center">-->
  <!--                <input type="checkbox" class="text-indigo-600 border-gray-200 rounded-md focus:border-indigo-600 focus:ring focus:ring-opacity-40 focus:ring-indigo-500" />-->
  <!--                <span class="mx-2 text-sm text-gray-600">Remember me</span>-->
  <!--              </label>-->
  <!--            </div>-->

  <!--            <div>-->
  <!--              <a class="block text-sm text-indigo-700 fontme hover:underline" href="#">Forgot your password?</a>-->
  <!--            </div>-->
  <!--          </div>-->

  <!--          <div class="mt-6">-->
  <!--            <button type="submit" @click="LoginData()" class="w-full px-4 py-2 text-sm text-center text-white bg-indigo-600 rounded-md focus:outline-none hover:bg-indigo-500">-->
  <!--              Login-->
  <!--            </button>-->
  <!--          </div>-->
  <!--        </form>-->
  <!--      </div>-->
  <!--    </div>-->
  <!--  </div>-->

</template>

<script>
// import { createApp} from 'vue';
// import axios from 'axios';
// import router from "@/router";
//
// // Vue.use(axios)
// export default {
//   name: 'Login',
//   data () {
//     return {
//       result: {},
//       student:{
//         email: '',
//         password: ''
//       }
//     }
//   },
//   created() {
//   },
//   mounted() {
//     console.log("mounted() called.......");
//     // this.LoginData();
//   },
//   methods: {
//     LoginData()
//     {
//       axios.post("http://127.0.0.1:8000/api/auth/login", this.student)
//           .then(
//               ({data})=>{
//                 console.log(data);
//                 try {
//                   this.result = data;
//                   localStorage.setItem('jwtToken', data.access_token)
//                   console.log(this.result);
//                   router.push('/')
//                 } catch (err) {
//                   alert("Error, please try again");
//                   router.push('/login');
//                 }
//               }
//           )
//     }
//   }
// }
</script>

<style scoped>

</style>
