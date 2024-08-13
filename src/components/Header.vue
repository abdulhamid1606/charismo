<template>
    <div class="header_parent">
        <div class="container">
            <div class="header">
                <div class="header_left">
                    <img src="../assets/images/Charismo-logo-3-e1591187795482 1 (3).png" alt="">
                </div>
                <div class="header_right">
                    <ul>
                        <li><a href="#">Главная</a></li>
                        <li><a href="#">Магазин</a></li>
                        <li><a href="#">Вопросы и ответы</a></li>
                        <li><a href="#">Отзывы</a></li>
                        <li><a href="#">Контакты</a></li>
                    </ul>
                    <div class="btn">
                        <div class="btn_left">
                            <img src="../assets/images/cart (1).png" alt="">
                        </div>
                        <div class="btn_right">
                            <button>Перезвоните мне</button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="header_bottom">
                <div class="header_bottom_left">
                    <h1>Инновации на службе
                        ваших волос</h1>
                    <p>Эффективные решения против выпадения и для роста волос, рекомендуемые профессионалами</p>
                    <button>В магазин <img src="../assets/images/Vector (15).png" alt=""></button>
                </div>
                <div class="header_bottom_right">
                    <img src="../assets/images/Group 1 (1).png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.container {
    max-width: 1220px;
    margin: 0 auto;
    padding: 0 10px;
}

.header_parent {
    background: linear-gradient(180deg, #F4F7FE 0%, rgba(244, 247, 254, 0.5) 100%);
    width: 100%;
    height: 730px;
}

.header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 20px;
}

.header_right {
    display: flex;
    align-items: center;
}

.header_right ul li {
    display: inline-block;
    margin-left: 33px;
}

.header_right ul li a {
    font-family: "IBM Plex Sans";
    font-size: 16px;
    font-weight: 400;
    line-height: 20.8px;
    text-align: left;
    color: rgba(48, 69, 96, 1);
    text-decoration: none;
}

.header_right ul li a:hover {
    font-family: IBM Plex Sans;
    font-size: 16px;
    font-weight: 500;
    text-align: left;
    color: rgba(35, 137, 255, 1);
}

.btn {
    display: flex;
    align-items: center;
    margin-left: 200px;
}

.btn_right button {
    font-family: IBM Plex Sans;
    font-size: 16px;
    font-weight: 400;
    line-height: 20.8px;
    text-align: left;
    color: rgba(48, 69, 96, 1);
    padding: 16px 35px;
    margin-left: 20px;
    border-radius: 8px;
    border: 1px solid rgba(35, 137, 255, 1);
    background: transparent;
}

.header_bottom {
    display: flex;
    margin-top: 100px;
    justify-content: space-between;
    /* align-items:center ; */
}

.header_bottom_left h1 {
    font-family: MTS Sans;
    font-size: 42px;
    font-weight: 700;
    line-height: 50.4px;
    text-align: left;
    color: rgba(48, 69, 96, 1);
}

.header_bottom_left p {
    color: rgba(114, 131, 153, 1);
    font-family: IBM Plex Sans;
    font-size: 20px;
    font-weight: 400;
    line-height: 26px;
    text-align: left;
    margin-top: 35px;
    width: 502px;
}

.header_bottom_left button {
    color: rgba(35, 137, 255, 1);
    box-shadow: 0px 5px 15px 0px rgba(35, 137, 255, 0.15);
    font-family: MTS Sans;
    font-size: 20px;
    font-weight: 700;
    line-height: 24px;
    text-align: left;
    color: rgba(255, 255, 255, 1);
    padding: 16px 50px;
    margin-top: 50px;
    background: rgba(35, 137, 255, 1);
    border: none;
    border-radius: 5px;
    display: flex;
    align-items: center;
}
.header_bottom_left button img{
    margin-left: 10px;
}
</style>