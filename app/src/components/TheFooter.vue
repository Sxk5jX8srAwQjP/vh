<template>
<footer class="page-footer-container">
    <div class="page-footer__top"></div>
    <div class="page-footer -primary">
        <div class="page-footer__inner">
            <div class="footer__block" style="min-width: 260px !important;">
                <h3 class="footer__title">Послуги</h3>
                <ul class="footer__list">
                    <li class="footer__item">
                        <a href="https://x.com" title="link">Створити резюме</a>
                    </li>
                    <li class="footer__item">
                        <a href="https://x.com" title="link">Послуги зi складання резюме</a>
                    </li>
                    <li class="footer__item">
                        <a href="https://x.com" title="link">Послуги з ":5*\%#'' резюме</a>
                    </li>
                </ul></div>
            <div class="footer__block" style="min-width: 170px !important;">
                <h3 class="footer__title">Пiдтримка</h3>
                <ul class="footer__list">
                    <li class="footer__item">
                        <a href="https://x.com" title="link">Про нас</a>
                    </li>
                    <li class="footer__item">
                        <a href="https://x.com" title="link">Зв`язатися з нами</a>
                    </li>
                    <li class="footer__item">
                        <a href="https://x.com" title="link">FAQ</a>
                    </li>
                </ul></div>
            <div class="footer__block" style="min-width: 258px !important;">
                <h3 class="footer__title">CVmaket</h3>
                <ul class="footer__list">
                    <li class="footer__item">
                        <a href="https://x.com" title="link">Заява про конфiдецiйнiсть</a>
                    </li>
                    <li class="footer__item">
                        <a href="https://x.com" title="link">Умови та положення</a>
                    </li>
                    <li class="footer__item">
                        <a href="https://x.com" title="link">Цiни</a>
                    </li>
                </ul></div>
            <div class="footer__block" style="min-width: 161px !important;">
                <h3 class="footer__title">Курсы</h3>
                <ul class="footer__list">
                    <li class="footer__item">
                        <a href="https://x.com" title="link">Вкажiть сво...</a>
                    </li>
                    <li class="footer__item">
                        <a href="https://x.com" title="link">Як написати...</a>
                    </li>
                    <li class="footer__item">
                        <a href="https://x.com" title="link">Як написати...</a>
                    </li>
                </ul></div>
        </div>
    </div>
    <div class="page-footer -secondary">
        <div class="page-footer__inner">
            <div style="float:left;">2021 @CVMaket.link |
            <a href="https://x.com" title="trash">Умови та положення</a> | 
            <a href="https://x.com" title="trash">Заява та конфiдецiйнiсть</a>
            </div>
        </div>
        <div style="float:right;margin-top:-40px; margin-right:30px;"></div>
    </div>
    </footer>    
</template>

<style scoped>
.page-footer__top{
    top: -120px;
    /* padding: 20px 0 0 0; */
    transform: skewY(-6deg);
    width:100%;
    height: 250px;
    background-color:#11121b;
    display: block;
    z-index: 1;
    position: absolute;
}
.page-footer.-secondary a {
	color: #858799;
}
.page-footer__inner a {
	text-decoration: none;
    color:#858799;
}
.page-footer.-secondary {
	padding: 60px 0 100px;
	background: #11121b;
	color: #858799;
}
.footer-item a{
    color:#858799;
}
.footer-item__inner a{
    text-decoration: none;
}
.footer__item{
    display: block;
    line-height: 32px;
    margin-bottom:6px;
}
ul{
    padding-left: 0;
    list-style-position: outside;
    color:white;
    line-height: 28px;
    list-style:none;
}
h3{
    font-weight: 600;
    padding: 0 0 10px;
    /* color:crimson; */
    font-size: 18px;
}
.footer__title{
    color:#f4f5fc;
    margin-bottom: 10px;
}
.footer__block{
    display: inline-block;
    /* background-color: royalblue; */
}
.page-footer__inner {
    width: 100%;
    max-width: 900px;
    padding: 0 15px;
    margin-left: auto;
    margin-right: auto;
    position: relative;
    z-index: 1;
    box-sizing: border-box;
}
.page-footer {
    display: block;
}
.page-footer.-primary {
	padding: 240px 0 0;
	background: #11121b;
}

.page-footer-container{
    position: relative;
    /* background-color:white; */
    /* color:chartreuse; */
    display: block;
}

</style>