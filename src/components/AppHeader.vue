<template>
<header class="header header--organic" data-sticky="true">
        <div class="header__top">
            <div class="container">
                <div class="header__left">
                    <div class="menu--product-categories">
                        <div class="menu__toggle"><i class="icon-menu"></i><span> Все программы</span></div>
                        <div class="menu__content">
                            <ul class="menu--dropdown">
                                <li><RouterLink to="/4x20"><i class="icon-star"></i> Лото 4x20</RouterLink></li>
                                <li><RouterLink to="/5x36"><i class="icon-star"></i> Лото 5x36</RouterLink></li>
                                <li><RouterLink to="/6x45"><i class="icon-star"></i> Лото 6x45</RouterLink></li>
                                <li><RouterLink to="/7x49"><i class="icon-star"></i> Лото 7x49</RouterLink></li>
                            </ul>
                        </div>
                    </div><a class="ps-logo" style='margin-right: 20px;' href="/"><img src="../assets/img/logo/logo.png" alt=""></a>
                </div>
                <div class="header__center">

                </div>
                <div class="header__right">
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
                        <div class="ps-block--user-header" style="margin-left: 0px;">
                            <div class="ps-block__left">Left
                            </div>
                            <div class="ps-block__right">Right
                            </div>
                        </div>
			        </div>
                </div>
            </div>
        </div>
        <nav class="navigation">
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
                        <li class="menu-item"><a href="/">Начало</a><span class="sub-toggle"></span></li>
                        <li class="menu-item"><a href="/about">О проекте</a><span class="sub-toggle"></span></li>
                        <li class="menu-item"><a href="/howto">Как играть?</a><span class="sub-toggle"></span></li>
			            <li class="menu-item"><a href="/crypto">Ввод и вывод средств</a><span class="sub-toggle"></span></li>
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
                    <li><a href="/about">О проекте</a></li>
                    <li><a href="/howto">Как играть?</a></li>
                    <li><a href="/crypto">Ввод и вывод средств</a></li>
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
				<div class="ps-block__left">Left
				</div>
				<div class="ps-block__right">Right
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
        background-color: yellow;
    }
</style>