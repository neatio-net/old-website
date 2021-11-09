<template>
  <div class="view-container">    
    <div class="hero">
      <div class="hero__content content-container">
        <div class="hero__header">
         <div class="hero"><img src="../assets/images/neat_empty.png" alt="" width="116" /></div>
          <h1 class="hero__title">{{ $t("pages.home.welcomeMsg") }}</h1>
          <div class="hero__subTitle">{{ $t("pages.home.welcomeNote") }}</div>
            <div class="btn"><router-link to="/features">
              <svg><rect x="0" y="0" fill="none" width="166" height="45"/></svg> DISCOVER</router-link>     
            </div>
          </div>
      </div>
    </div>
  </div>                                  
</template>

<script>
export default {
  name: "Home",
};
</script>