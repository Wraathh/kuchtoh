<template>
   <div>
        <b-navbar id="nav" toggleable="lg" type="dark" variant="black" >
    <b-navbar-brand href="">KuchToh</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#abt">About Us</b-nav-item>
       <b-nav-item href="#ser">Services</b-nav-item>
       <b-nav-item href="#careers">Careers</b-nav-item>
       
      </b-navbar-nav>

     <b-navbar-nav class="ml-auto">
        <b-nav-item-dropdown text="Take a Survey" right>
          <b-dropdown-item href="https://forms.gle/WJ7T1B4TEnM5ekUPA" target="_blank">For Consultants</b-dropdown-item>
          <b-dropdown-item href="https://forms.gle/vVDpKacMQdPkVGqx6" target="_blank">For Clinics/Hospitals</b-dropdown-item>
        </b-nav-item-dropdown>
     </b-navbar-nav>
    </b-collapse>
  </b-navbar>
   </div>
</template>
<style scoped>
#nav{
    position: fixed;
    top: 0;
    width: 100%;
    background-color: black;
    z-index: 1;
    
    
}
</style>