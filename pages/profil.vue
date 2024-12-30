<template>
      <div class="profil">
        <div class="main-text">
            <h1>visi & misi<br>SMKN 4 TASIKMALAYA</h1>
        </div>
        <section class="visimisi" id="about">
            <div class="visi-text">
                <h3>visi</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque nemo maxime, eligendi nesciunt quis quaerat cupiditate rerum enim obcaecati eum totam facilis, sunt tempore libero officia. Ad, excepturi. Qui, voluptatem officia aspernatur iure nam, architecto quos molestiae assumenda nesciunt porro voluptatum dolorum consequatur odit. Laudantium saepe sunt perspiciatis dolores ex.</p>
    
            </div>
            <div class="misi-text">
                <h3>misi</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque nemo maxime, eligendi nesciunt quis quaerat cupiditate rerum enim obcaecati eum totam facilis, sunt tempore libero officia. Ad, excepturi. Qui, voluptatem officia aspernatur iure nam, architecto quos molestiae assumenda nesciunt porro voluptatum dolorum consequatur odit. Laudantium saepe sunt perspiciatis dolores ex.</p>
    
            </div>
            
        </section>
    </div>
</template>
<style scoped>
.profil{
    width: 100%;
    height: 100vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 50%;
}
.profil .main-text{
    text-align: center;
    padding: 10px 10% 10px;
}
.profil .main-text h1{
    font-size: 60px;
    color: #388b6f;
    text-shadow: 0px 0px 1px black;
}
  .visimisi{
    padding: 30px 8% 120px;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    align-items: center;
    gap: 1.5rem;
}
.visi-text h3{
    color: #388b6f;
    font-size: 30px;
    line-height: 1;
}
.misi-text h3{
    color: #388b6f;
    font-size: 30px;
    line-height: 1;
}
.visi-text p{
    color: black;
    letter-spacing: 1px;
    margin-bottom: 4rem;
    margin-top: 10px;
}
.misi-text p{
    color: black;
    letter-spacing: 1px;
    margin-bottom: 4rem;
    margin-top: 10px;
}

</style>