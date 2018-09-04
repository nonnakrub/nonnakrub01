<template lang="html">

<div class="">

  <div><h1><center>Profile</center></h1>

  <div><center><img src="pic/ko.jpg" hight="500" width=""></center>

  <div><h1><center>นายอานนท์ ปานทอง</center></h1></div>

  <div><h1><center>อายุ 21 ปี</center></h1></div>

  <div><h1><center>ที่อยู่ 28  ต.กระสัง อ.กระสัง จ.บุรีรัมย์ 31160 </center></h1></div>

  <div><h1><center>ห้อง ทล.บ.11 รหัสนักศึกษา 6142040619</center></h1></div>

  </div>

  </div>

  </div>

  </template>  

  <script>
  export default {
    data() {
      return {
        id:1
      }
    }
  }
  </script>



<script>
import AppLogo from '~/components/AppLogo.vue'
export default {
  components: {
    AppLogo
  }
}
</script>



<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links {
  padding-top: 15px;
}
</style>