<template>
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
    </div>
</template>
<script>
export default {

}
</script>
<style>
.container {
    max-width: 1220px;
    margin: 0 auto;
    padding: 0 10px;
}

.header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 26px;
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
</style>