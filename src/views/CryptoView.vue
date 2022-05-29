<template>
<div class="ps-top-categories" style="margin: 20px 50px 0 50px;">
		<div class="container">
		<h3>Работа с криптовалютой</h3>

		<b>Пополнение валанса </b><br><br>
		<router-link to='https://metamask.io/' target=_blank><img src='../assets/img/crypto/metamask_logo_200.png' style='float: right;'></router-link>
		 
		Платформа работает с валютой Binance BNB. Это обусловлено низкими транзакционными издержками при проведении небольших сумм.<br>
		Самым простым механизмом для пополнения личного кошелька пользователя в системе является использование <router-link to='https://metamask.io/' target=_blank><b>плагина Метамаск</b></router-link>.<br><br>
		На сайте <router-link to='https://academy.binance.com/ru/articles/connecting-metamask-to-binance-smart-chain' target=_blank><b>Binance</b></router-link> описан способ подключения сети BEP20 к кошельку Метамаск.<br><br>
		Сейчас же мы предположим, что вы провели все подготовительные действия по установке и настройке плагина.<br><br>

		<router-link to='https://accounts.binance.com/ru/register?ref=HDSV144D' target=_blank><img src='../assets/img/binance/binance.jpg' style='float: right; max-width: 200px;'></router-link>
		<b>На данный момент существует единственный кошелек для расчетов с платформой Elotto.me:</b><br>
		<div id='address' style='border: 1px solid #ccc; border-radius: 5px; display: inline-block; margin: 10px 5px 10px 0; background-color: #eee; padding: 5px'>BNB_ADDRESS</div>
		<router-link to='#' id='address' data-id='BNB_ADDRESS'>
            <div style='border: 0px solid #ccc; border-radius: 5px; display: inline-block; margin: 10px 0 10px 0; background-color: #5FA30F; padding: 5px 10px 5px 10px; color: #fff;'>
                <fa icon="copy" style="color: #fff;"/>
            </div>
        </router-link><br>

		<b>Важно!</b> Так как адрес в сети Binance выглядит одинаково с адресом в сети Etherium, то есть вероятность ошибки при указании адресатов.<br>
		Поэтому, всегда проверяйте, что указываете правильный токен <b>BEP20</b> вместо обычного для сети Etherium ERC-20!<br><br>

		<img src='../assets/img/crypto/rules_08_01.png' style='width: 600px;  border: 3px solid #eee; border-radius: 5px; margin: 10px 0 10px 20px;'><br><br>
		<img src='../assets/img/crypto/rules_08_02.png' style='width: 600px;  border: 3px solid #eee; border-radius: 5px; margin: 10px 0 10px 20px;'><br><br>

		После выбора пункта <b>"Пополнить"</b> вы получите приглашение плагина Метамаск о подтверждении платежа. <br>
		Информацию о зачислении средств на кошелек платформы Elotto вы получите в <b>email-уведомлении</b>.<br><br>

		<b>Вывод средств </b><br><br>
		Вывод средств можно произвести в кабинете пользователя по <router-link to='/cabinet/personal' target=_blank><b>ссылке</b></router-link>.<br>
		<img src='../assets/img/crypto/rules_07.png' style='width: 600px;  border: 3px solid #eee; border-radius: 5px; margin: 10px 0 10px 20px;'><br><br>

		Для сети существуют минимальные суммы переводов. Для сети Binance BEP20 в настоящий момент они меняются в диапазоне 0.001 BNB, то есть около 0.5 $. <br><br>
		<b>Важно!</b> Если платеж осуществляется на сумму, находящуюся на нижнем пределе разрешенной суммы, то платеж может быть отвергнут платежной системой.
		В этом случае средства не спишутся, и у вас будет возможность повторить платеж на немного бОльшую сумму.

		</div>
	</div>  
</template>

<script setup>
</script>
