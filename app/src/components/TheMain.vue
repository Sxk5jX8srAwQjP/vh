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
        <section class="page--body page--how-it-works"><p>section page--body</p></section>
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

.page-main__inner .page--hero{
    z-index: 999;
    transition: all .5s ease;
}

.page--hero__background{
position: absolute;
background-color: red;
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