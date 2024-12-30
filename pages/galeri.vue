<template>
  <div class="gallary">
        <h3>Our Gallary</h3>
        <div class="gallary-img">
            <div class="img1">
                <img src="assets/slide2.jpg" alt="">
                <img src="assets/3.png" alt="">
            </div>
            <div class="img1">
                <img src="assets/1.png" alt="">
                <img src="assets/slide3.jpg" alt="">
            </div>
        </div>
    </div>
</template>
<style scoped>
  .gallary{
    padding: 0px 8% 120px;
}
.gallary h3{
    text-align: center;
    font-size: 36px;
    text-transform: uppercase;
    font-weight: 600;
    color: #388b6f;
    text-shadow: 0px 1px 1px black;
}
.gallary-img{
    margin-top: 30px;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    align-items: center;
}
.gallary-img img{
    max-width: 530px;
    height: auto;
    width: 100%;
    border-radius: 10px;
    box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
    transition: 0.3s;
    cursor: pointer;
}
.gallary-img img:hover{
    transform: translateY(-10px);
}
@media (max-width:920px){
    .gallary-img{
        grid-template-columns: 1fr;
    }
    .gallary-img img{
        width: 100%;
        height: auto;
        max-width: 100%;
    }
}
</style> 