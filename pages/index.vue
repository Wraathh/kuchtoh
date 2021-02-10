<template>
<body>
<!-- JUMBOTRON for Company name and tagline. start -->
  <div class=""> 
  <b-jumbotron id="header" align="center" text-variant="info" >
    <h1>KuchToh Technologies Pvt. Ltd.</h1><br>
     <p>
      A centralized platform for Doctors, to enhance pratice and enhance reach.
    </p>
  </b-jumbotron>
</div>
<!-- JUMBOTRON end -->

<div id="seperator">_</div><br><br>

<!-- ABOUT Section start -->
<div>
  <about_us/>
</div>
<!-- ABOUT Section end -->

<div id="seperator">_</div><br><br>

<!-- SERVICES Section start -->
<div>
  <services/>
</div>
<!-- SERVICES Section end -->

<div id="seperator">_</div><br><br>

<!-- CAREERS Section start -->
<div>
  <h5>CAREERS</h5><br>
  <p>KuchToh Technologies Pvt. Ltd. is an upcoming Startup into Healthcare sector. We welcome you to join & be part of the change,
     along with exciting work ranging from planning to final shaping of the product.</p>
  <div class="center"> <button class="btn btn-primary" @click="loadUser" >Let's Go</button></div>
</div>
<!-- CAREERS Section end -->

<div id="seperator">_</div><br><br>

<!-- DOCTOR Section start -->
<div>
  <doctor/>
</div>
<!-- DOCTOR Section end -->

<div id="seperator">_</div><br><br>

<!-- FOOTER start -->
<div>
  <foot/>
</div>
<!-- FOOTER end -->


</body>
</template>
<script>
import about_us from '@/components/About_us/about_us'
import services from '@/components/Services/services'
import doctor from '@/components/Doctor/doctor'
import foot from '@/components/Footer/foot'


export default {
  components:{
    about_us,
    services,
    doctor,
    foot
  },
  methods:{
    loadUser(){
      this.$router.push('/Careers')
    
  }
}
}
</script>
