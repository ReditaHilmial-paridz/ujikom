<template>
  <div class="home">
    <div class="main-text">
      <h1>Selamat Datang di<br />SMKN 4 TASIKMALAYA</h1>
    </div>
  </div>
  <section class="offers">
    <div class="offer-content">
      <div class="row">
        <i
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="16"
            height="16"
            fill="currentColor"
            class="bi bi-person-fill"
            viewBox="0 0 16 16"
          >
            <path
              d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6"
            /></svg
        ></i>
        <h3>1</h3>
        <p>GURU</p>
      </div>
      <div class="row">
        <i
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="16"
            height="16"
            fill="currentColor"
            class="bi bi-award-fill"
            viewBox="0 0 16 16"
          >
            <path
              d="m8 0 1.669.864 1.858.282.842 1.68 1.337 1.32L13.4 6l.306 1.854-1.337 1.32-.842 1.68-1.858.282L8 12l-1.669-.864-1.858-.282-.842-1.68-1.337-1.32L2.6 6l-.306-1.854 1.337-1.32.842-1.68L6.331.864z"
            />
            <path
              d="M4 11.794V16l4-1 4 1v-4.206l-2.018.306L8 13.126 6.018 12.1z"
            /></svg
        ></i>
        <h3>5</h3>
        <p>JURUSAN</p>
      </div>
      <div class="row">
        <i
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            width="16"
            height="16"
            fill="currentColor"
            class="bi bi-people-fill"
            viewBox="0 0 16 16"
          >
            <path
              d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6m-5.784 6A2.24 2.24 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.3 6.3 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1zM4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5"
            /></svg
        ></i>
        <h3>0</h3>
        <p>MURID</p>
      </div>
      <div class="row">
        <i class="bi bi-file-earmark-text"></i>
        <h3>6</h3>
        <p>TATA USAHA</p>
      </div>
    </div>
  </section>
  <section class="about" id="about">
    <div class="about-img">
      <img src="assets/kepsek.png" alt="" />
    </div>
    <div class="about-text">
      <h3>SAMBUTAN KEPALA SEKOLAH</h3>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque nemo
        maxime, eligendi nesciunt quis quaerat cupiditate rerum enim obcaecati
        eum totam facilis, sunt tempore libero officia. Ad, excepturi. Qui,
        voluptatem officia aspernatur iure nam, architecto quos molestiae
        assumenda nesciunt porro voluptatum dolorum consequatur odit. Laudantium
        saepe sunt perspiciatis dolores ex.
      </p>
    </div>
  </section>
  <section class="product" id="product">
    <div class="main-txt">
      <h3>BERITA TERBARU</h3>
    </div>
    <div class="card-content">
      <div class="row">
        <img src="assets/1.png" alt="" />
        <div class="card-body">
          <h3>Chair</h3>
          <p>Lorem ipsum dolor sit amet.</p>
          <button>Baca Selengkapnya</button>
        </div>
      </div>
      <div class="row">
        <img src="assets/2.png" alt="" />
        <div class="card-body">
          <h3>Chair</h3>
          <p>Lorem ipsum dolor sit amet.</p>
          <button>Baca Selengkapnya</button>
        </div>
      </div>
      <div class="row">
        <img src="assets/3.png" alt="" />
        <div class="card-body">
          <h3>Chair</h3>
          <p>Lorem ipsum dolor sit amet.</p>
          <button>Baca Selengkapnya</button>
        </div>
      </div>
      <div class="row">
        <img src="assets/4.png" alt="" />
        <div class="card-body">
          <h3>Chair</h3>
          <p>Lorem ipsum dolor sit amet.</p>
          <button>Baca Selengkapnya</button>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped>
.home {
  width: 100%;
  height: 100vh;
  background-image: linear-gradient(rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.1)),
    url(assets/bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 50%;
}
.home .main-text {
  text-align: center;
  padding: 150px 10% 10px;
}
.main-text h1 {
  font-size: 60px;
  color: #fff;
  text-shadow: 0px 0px 1px black;
}
.home .main-text p {
  color: white;
  margin-top: 5px;
}
#btn {
  width: 200px;
  height: 36px;
  font-weight: bold;
  background: white;
  color: #388b6f;
  letter-spacing: 1px;
  border: 2px solid #388b6f;
  border-radius: 5px;
  margin-top: 10px;
  transition: 0.5s;
  cursor: pointer;
}
#btn:hover {
  background-color: #388b6f;
  color: white;
}
/* Home Section End */

.profil {
  width: 100%;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 50%;
}
.profil .main-text {
  text-align: center;
  padding: 10px 10% 10px;
}
.profil .main-text h1 {
  font-size: 60px;
  color: #388b6f;
  text-shadow: 0px 0px 1px black;
}

/* Top Section Card Start */
.offers {
  padding: 10px 8% 20px;
  background: #f3f3f3;
}
.offer-content {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, auto));
  align-items: center;
  gap: 0.9rem;
  margin-top: 30px;
}
.offer-content .row {
  position: relative;
  overflow: hidden;
  border-radius: 10px;
  cursor: pointer;
}
.offer-content .row i {
  font-size: 50px;
  color: #388b6f;
}
.offer-content .row h3 {
  margin-left: 5px;
}
.offer-content .row p {
  margin-left: 5px;
}
@media (max-width: 920px) {
  .offer-content {
    grid-template-columns: 1fr;
  }
}
.about {
  padding: 150px 8% 120px;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  align-items: center;
  gap: 1.5rem;
}
.about-img img {
  max-width: 530px;
  height: auto;
  width: 100%;
  border-radius: 10px;
  box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
}
.about-text h3 {
  color: #388b6f;
  font-size: 30px;
  line-height: 1;
}
.about-text p {
  color: black;
  letter-spacing: 1px;
  margin-bottom: 4rem;
  margin-top: 10px;
}
#about-btn {
  width: 150px;
  height: 35px;
  background: white;
  border: 2px solid #388b6f;
  color: #388b6f;
  font-weight: bold;
  border-radius: 5px;
  transition: 0.5s;
  cursor: pointer;
}
#about-btn:hover {
  background: #388b6f;
  color: white;
}
@media (max-width: 920px) {
  .about {
    grid-template-columns: 1fr;
  }
  .about-img {
    text-align: center;
    order: 2;
  }
  .about-img img {
    width: 100%;
    height: auto;
    max-width: 100%;
  }
}
/* About Section End */

/* Product Section Start */
.product {
  padding: 10px 8% 120px;
}
.main-txt {
  text-align: center;
}
.main-txt h3 {
  font-size: 36px;
  text-transform: uppercase;
  font-weight: 600;
  color: #388b6f;
  text-shadow: 0px 1px 1px black;
}
.card-content {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, auto));
  align-items: center;
  gap: 0.9rem;
  margin-top: 30px;
}
.card-content .row {
  background: #f3f3f3;
  position: relative;
  overflow: hidden;
  border-radius: 10px;
  cursor: pointer;
}
.row img {
  width: 100%;
  display: block;
}
.card-body {
  padding: 10px;
}
.card-body h3 {
  margin-top: 10px;
  font-size: 30px;
  font-weight: 550;
  color: #388b6f;
  text-shadow: 0px 1px 1px black;
}
.card-body p {
  font-weight: 500;
  margin-top: 5px;
  letter-spacing: 1px;
}
.card-body h5 {
  margin-top: 5px;
  font-size: 18px;
}
.card-body button {
  width: 150px;
  height: 30px;
  font-weight: 550;
  margin-top: 5px;
  background: transparent;
  color: #388b6f;
  border-radius: 5px;
  border: 2px solid #388b6f;
  transition: 0.5s;
  cursor: pointer;
}
.card-body button:hover {
  background: #388b6f;
  color: white;
}
@media (max-width: 920px) {
  .card-content {
    grid-template-columns: 1fr;
  }
}
</style>
