<template>
<header class="header header--organic" data-sticky="true">
        <div class="header__top">
            <div class="container">
                <div class="header__left">
                    <div class="menu--product-categories">
                        <div class="menu__toggle"><i class="icon-menu"></i><span> Все программы</span></div>
                        <div class="menu__content">
                            <ul class="menu--dropdown">
                                <li><a href="/4x20"><i class="icon-star"></i> Лото 4x20</a></li>
                                <li><a href="/5x36"><i class="icon-star"></i> Лото 5x36</a></li>
                                <li><a href="/6x45"><i class="icon-star"></i> Лото 6x45</a></li>
                                <li><a href="/7x49"><i class="icon-star"></i> Лото 7x49</a></li>
                            </ul>
                        </div>
                    </div>
                    <a class="ps-logo" style='margin-right: 20px;' href="/"><img src="../assets/img/logo/logo.png" alt="eLotto Logo"></a>
                </div>
                <div class="header__center">
		</div>
                <div class="header__right">
                    <div class="header__actions">
                        <div class="ps-cart--mini"><a class="header__extra" href="#">
                            
                            <fa icon="bag-shopping" style='line-height: 38px; color: #ccc; font-size: 26pt;'/>
                            <span><i id='icon-bag-count'>0</i></span></a>
                            <div class='ps-cart__content' style='background-color: #fff;'>
                                <div class="ps-cart__items" style='padding: 20px 20px 0px 20px;'></div>
                                <div class="ps-cart__footer">
                                    <h3 style='font-size: 100%;'>Всего:<strong>$59.99</strong></h3>
                                <figure>
                                	<div style='text-align: right; width: 100%;'><a class='ps-btn' style='padding: 10px 15px 10px 15px;' href='/cabinet/cart'>Корзина</a></div>
                                </figure>
                                </div>
                            </div>
                        </div>
			<div class="ps-block--user-header" style="margin-left: 0px;">
				<div class="ps-block__left"><a href='/cabinet'><i class='icon-user'></i></a>
					<fa icon="user" style='color: #ccc; font-size: 22pt;'/>
				</div>
				<div class="ps-block__right"><b style='color: #56698F;'>Привет user_name!</b><a href='/logout'>Выйти</a>
					<a href='/login'>Войти</a><a href='/register'>Регистрация</a>
				</div>
			</div>
			</div>
                </div>
            </div>
        </div>
        <nav class="navigation" style="margin-top: 0px;">
            <div class="container">
                <div class="navigation__left">
                    <div class="menu--product-categories">
                        <div class="menu__toggle"><i class="icon-menu"></i><span> Все программы</span></div>
                        <div class="menu__content">
                            <ul class="menu--dropdown">
                                <li><a href="/4x20"><i class="icon-star"></i> Лото 4x20</a></li>
                                <li><a href="/5x36"><i class="icon-star"></i> Лото 5x36</a></li>
                                <li><a href="/6x45"><i class="icon-star"></i> Лото 6x45</a></li>
                                <li><a href="/7x49"><i class="icon-star"></i> Лото 7x49</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="navigation__right">
                    <ul class="menu menu--organic">
                        <li class="menu-item"><router-link to="/">Начало</router-link><span class="sub-toggle"></span></li>
                        <li class="menu-item"><router-link to="/about">О проекте</router-link><span class="sub-toggle"></span></li>
                        <li class="menu-item"><router-link to="/howto">Как играть?</router-link><span class="sub-toggle"></span></li>
			            <li class="menu-item"><router-link to="/crypto">Ввод и вывод средств</router-link><span class="sub-toggle"></span></li>
                    </ul>
                </div>
            </div>
        </nav>
</header>
<header class="header header--mobile organic" data-sticky="true">
        <div class="header__top">
            <div class="header__left" style="text-align: left;">
                <p><b>Добро пожаловать в ELOTTO.ME!</b><br>Ваши любимые лотереи Гослото в криптовалюте.</p>
            </div>
            <div class="header__right">
                <ul class="navigation__extra">
                    <li><router-link to="/about">О проекте</router-link></li>
                    <li><router-link to="/howto">Как играть?</router-link></li>
                    <li><router-link to="/crypto">Ввод и вывод средств</router-link></li>
                </ul>
            </div>
        </div>
        <div class="navigation--mobile">
            <div class="navigation__left"><a class="ps-logo" href="/"><img src="/dist/img/logo/logo-small.png" style="width: 50px;" alt=""></a></div>
            <div class="navigation__right">
                <div class="header__actions">
			<div class="ps-cart--mini"><a class="header__extra" href="#"><i style='line-height: 38px;' class="icon-bag2"></i><span><i id='icon-bag-count'>0</i></span></a>
                            <div class='ps-cart__content' style='background-color: #fff;'>
                                <div class="ps-cart__items" style='padding: 20px 20px 0px 20px;'></div>
                                <div class="ps-cart__footer">
                                    <h3 style='font-size: 100%;'>Всего:<strong>$59.99</strong></h3>
                                <figure>
                                	<div style='text-align: right; width: 100%;'><a class='ps-btn' style='padding: 10px 15px 10px 15px;' href='/cabinet/cart'>Корзина</a></div>
                                </figure>
                                </div>
                            </div>
			</div>
			<div class="ps-block--user-header">
				<div class="ps-block__left"><a href='/cabinet'><i class='icon-user'></i></a>
					<i class='icon-user'></i>
				</div>
				<div class="ps-block__right"><b style='color: #56698F;'>Привет user_name!</b><a href='/logout'>Выйти</a>";
					<a href='/login'>Войти</a><a href='/register'>Регистрация</a>
				</div>
			</div>
                </div>
            </div>
        </div>
</header>
<div class="ps-panel--sidebar" id="navigation-mobile">
	<div class="ps-panel__header">
		<h3>Все программы</h3>
	</div>
	<div class="ps-panel__content">
		<ul class="menu--dropdown">
                        <li><a href="/4x20"><i class="icon-star"></i> Лото 4x20</a></li>
                        <li><a href="/5x36"><i class="icon-star"></i> Лото 5x36</a></li>
                        <li><a href="/6x45"><i class="icon-star"></i> Лото 6x45</a></li>
                        <li><a href="/7x49"><i class="icon-star"></i> Лото 7x49</a></li>
		</ul>
	</div>
</div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .header {
        min-width: 100%;
        position: relative;
    }
</style>