<template>
      <div class="header">
        <nav >
            <input type="checkbox" id="show-search">
            <input type="checkbox" id="show-menu">
            <label for="show-menu fixed-top" class="menu-icon"><i class="fas fa-bars"></i></label>
            <div class="content">
                <div class="logo"><a href="index.html"><img src="assets/LOGO.png" alt=""></a></div>

                <ul class="links text-decoration-none">
                    <li>
                      <nuxt-link to="./"><a href="#" id="first">Beranda</a></nuxt-link>
                     </li>
                    <li>
                      <nuxt-link to="/profil"><a href="">Profil Sekolah</a></nuxt-link>
                      </li>
                    <li>
                      <nuxt-link to="/galeri"><a href="">Galeri</a></nuxt-link>
                    </li>
                    <li>
                      <nuxt-link to="/ekskul"><a href="">Ekstrakulikuler</a></nuxt-link>
                    </li>
                </ul>
            </div>
            <label for="show-search" class="search-icon"><i class="fas fa-search"></i></label>
            <form action="#" class="search-box">
                <input type="text" placeholder="Search" required>
                <button type="submit" class="go-icon"><i class="fas fa-long-arrow-alt-right"></i></button>
            </form>

        </nav>
    </div>
</template>
<style scoped>
  .header{
    background: white;
    width: 100%;
    box-shadow: 0px 1px 1px black;
}
.header nav{
    position: relative;
    display: flex;
    max-width: calc(100% - 200px);
    margin: 0 auto;
    height: 70px;
    align-items: center;
    justify-content: space-between;
}
nav .content{
    display: flex;
    align-items: center;
}
nav .content .links{
    margin-left: 80px;
    display: flex;
}
nav .content .logo a img{
    width: 50px;
}
nav .content .links li{
    list-style: none;
    line-height: 70px;
}

.content .links li a,
.content .links li label{
    color: black;
    font-size: 18px;
    padding: 9px 17px;
    font-weight: bold;
    border-radius: 5px;
    transition: all 0.3s ease;
}
.content .links li label{
    display: none;
}
.content .links li a:hover,
.content .links li label:hover{
    color: #388b6f;
}
.header .search-icon,
.header .menu-icon{
    color: #388b6f;
    font-size: 18px;
    line-height: 70px;
    width: 70px;
    text-align: center;
    cursor: pointer;
}
.header .menu-icon{
    display: none;
}
.header #show-search:checked ~ .search-icon i::before{
    content: "\f00d";
}
.header .search-box{
    position: absolute;
    height: 100%;
    max-width: calc(100% - 50px);
    width: 100%;
    opacity: 0;
    pointer-events: none;
    transition: all 0.3s ease;
}
.header #show-search:checked ~ .search-box{
    opacity: 1;
    pointer-events: auto;
}
.search-box input{
    width: 100%;
    height: 100%;
    border: none;
    outline: none;
    font-size: 17px;
    color: black;
    background: white;
    padding: 0 100px 0 15px;
}
.search-box input::placeholder{
    color: black;
}
.search-box .go-icon{
    position: absolute;
    right: 10px;
    top: 50%;
    transform: translateY(-50%);
    line-height: 60px;
    width: 70px;
    background: transparent;
    border: none;
    outline: none;
    color: #388b6f;
    font-size: 20px;
    cursor: pointer;
}
.header input[type="checkbox"]{
    display: none;
}

/* Responsive */
@media screen and (max-width:1250px){
    .header nav{
        max-width: 100%;
        padding: 0px 20px;
    }
    nav .content .links{
        margin-left: 30px;
    }
    .content .links a{
        padding: 8px 13px;
    }
    .header .search-box{
        max-width: calc(100% - 100px);
    }
    .header .search-box input{
        padding: 0px 100px 0px 15px;
    }
}
@media screen and (max-width: 900px){
    .header .menu-icon{
        display: block;
    }
    .header #show-menu:checked ~ .menu-icon i::before{
        content: "\f00d";
    }
    nav .content .links{
        display: block;
        position: fixed;
        background: white;
        height: 100%;
        width: 100%;
        top: 70px;
        left: -100%;
        margin-left: 0;
        max-width: 350px;
        overflow: auto;
        padding-bottom: 100px;
        transition: all 0.3s ease;
    }
    nav #show-menu:checked ~ .content .links{
        left: 0%;
    }
    .content .links li{
        margin: 15px 20px;
    }
    .content .links li a,
    .content .links li label{
        line-height: 40px;
        font-size: 20px;
        display: block;
        padding: 8px 18px;
        cursor: pointer;
    }
    .content .links li a.desktop-link{
        display: none;
    }
}
</style>