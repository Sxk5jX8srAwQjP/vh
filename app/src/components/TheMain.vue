<template>
    <main class="page-main">
        <section class="page--body page--hero">
            <div class="page-main__inner">
                <header>
                    <h1 class="page-title page-title--hero">Створiть сво;t п*здате резюме</h1>
                    <p class="page-intro">Створіть своє власне професійне резюме та завантажте його протягом 15 хвилин.</p>
                </header>
                <p style="text-align:center"><a class="button button--purple button--hero" href="https://x.com" title="Професiйнi п*здуни">Створiть собi резюме</a></p>
            <br>
            <br>
            <span>У Вас буде на 65% більше шансів отримати роботу</span>
            </div>
            <div class="page--hero__background"></div>
        </section>
        <section class="page--body page--how-it-works">
            <ul class="how-it-works">
                <li class="how-it-works__item page--box" href="https://x.com">
                    <i class="how-it-works__icon">
                        <img src="/assets/images/icon/rating.svg" alt="rating">
                    </i>
                    <h2 class="how-it-works__title">Быстро и легко</h2>
                    <p>З нашим онлайн-конструктором резюме, будь-яка людина може швидко створити професійне резюме. Введіть свої особисті дані та почніть заповнювати резюме. Насамкінець, виберіть один з 36 доступних шаблонів і завантажте Ваше резюме.</p>
                </li>
                <li class="how-it-works__item page--box" href="https://x.com">
                    <i class="how-it-works__icon">
                        <img src="/assets/images/icon/recruitment.svg" alt="rating">
                    </i>
                    <h2 class="how-it-works__title">Быстро и легко</h2>
                    <p>З нашим онлайн-конструктором резюме, будь-яка людина може швидко створити професійне резюме. Введіть свої особисті дані та почніть заповнювати резюме. Насамкінець, виберіть один з 36 доступних шаблонів і завантажте Ваше резюме.</p>
                </li>
                <li class="how-it-works__item page--box" href="https://x.com">
                    <i class="how-it-works__icon">
                        <img src="/assets/images/icon/profiles.svg" alt="rating">
                    </i>
                    <h2 class="how-it-works__title">Быстро и легко</h2>
                    <p>З нашим онлайн-конструктором резюме, будь-яка людина може швидко створити професійне резюме. Введіть свої особисті дані та почніть заповнювати резюме. Насамкінець, виберіть один з 36 доступних шаблонів і завантажте Ваше резюме.</p>
                </li>
                
            </ul>
        </section>
        <section class="page--body page--reviews"><p>section page--body</p></section>
        <section class="page--section--companies"><p>section page--body</p></section>
        <section class="page--body page--cta-banner"><p>section page--body</p></section>
        <section class="page--body page--templates"><p>section page--body</p></section>
        <section class="page--body"><p>section page--body</p></section>
        <section class="page--body page--templates"><p>section page--body</p></section>
        <section class="page--body page--cta-banner"><p>section page--body</p></section>
    
    </main>
</template>

<style scoped>
p {
	font-weight: 400;
	padding: 0 0 20px;
	line-height: 28px;
}
.how-it-works__item p {
	text-align: left;
	padding: 0 0 44px;
}
h2, h3 {
	font-size: 18px;
}
h2, h3, h4, h5 {
	font-weight: 600;
	color: #444;
	/* padding: 0 0 10px; */
}
.how-it-works__title {
	display: block;
	text-align: left;
	padding: 40px 0 10px;
}
em, i {
	font-style: italic;
}
.how-it-works__icon img {
	display: inline-block;
	position: relative;
	height: 75px;
	width: 75px;
}

.page--box {
	background: #fff;
	box-shadow: 0 15px 35px rgba(50,50,93,.1),0 5px 15px rgba(0,0,0,.07);
}

.how-it-works__item {
	position: relative;
	display: inline-block;
	width: 100%;
	min-height: 100px;
	text-align: center;
	margin: 0 0 25px;
	padding: 0 30px 0 160px;
	border-radius: 4px;
}

.page--how-it-works {
	margin-top: -20px;
	z-index: 9999;
	padding-bottom: 40px;
	/* background-color: grey; */
}
.how-it-works__icon {
	position: absolute;
	top: 50%;
	height: 80px;
	width: 80px;
	background: #f0f1ff;
	border-radius: 50%;
	left: 40px;
	padding: 0;
	margin: -40px 20px 0 0;
	text-align: center;
	background-size: contain;
	background-repeat: no-repeat;
	background-position: 50% 50%;
}

ul{
    list-style-type: disc;
    list-style-position: outside;
    line-height:28px;
    /* list-style:none; */
    /* background-color: orange; */
} 

.page--box{
    background: #fff;
    box-shadow: 0 15px 35px rgba(50,50,93,.1),0 5px 15px rgba(0,0,0,.07);
}
.how-it-works{
    display:flex;
    flex-flow: row wrap;
    padding:0;
}

.page-main__inner .page-main{
    z-index: 99;
}
.page--how-it-works{
    margin-top:-20px;
    z-index:9999;
    padding-bottom: 40px;
}

.page-main__inner{
    z-index:999;
    width:100%;
    max-width:900px;
    padding:0 15px;
    margin-left:auto;
    margin-right:auto;
    position:relative;
    box-sizing: border-box;
}

.page--hero__background{
position: absolute;
background: #2dc46a;
/* background-color: red; */
z-index:99;
bottom: -100px;
left:0;
width:100%;
height: 200px;
transform:skewY(-6deg);
}

.button {
	outline: none;
	position: relative;
	font-size: 18px;
	padding: 15px 0 16px;
	display: inline-block;
	min-width: 200px;
	border-radius: 4px;
	border: none;
	cursor: pointer;
	font-weight: 700;
	text-decoration: none;
	box-shadow: 0 4px 6px rgba(50,50,93,.11),0 1px 3px rgba(0,0,0,.08);
}

.button--purple
{
    background:#626ccc;
    color:#fff;
    top: 0px;
    padding:18px 20px 19px;
}
.button--hero{
    margin:30px 0 0;
}

p{
    font-weight: 400;
    line-height: 28px;
}
.page-intro{
    display: block;
    text-align: center;
}
.page-title{
    display: block;
    text-align: center;
    padding: 60px 0 10px;
    font-size: 36px;
    font-weight: 700;
}
.page-title--hero{
    color:#fff;
    padding-top: 60px;
}

.page--hero.page--body{
    padding-bottom: 0;
}

.page--body {
    display: block;
    position:relative;
    padding: 30px 30px 100px;
    border-radius: 4px;
    /* background-color: grey; */
}

.page--hero{
    background-color: #2dc46a;
    color: #fff;
    min-height: 310px;
    padding-top: 0;
    border-radius:0;
    text-align:center;
}
.page-main{
    background-color: pink;
    position: relative;
    padding-top: 65px;
    top:0;
}
</style>