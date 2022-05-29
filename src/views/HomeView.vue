<template>
  <div class="ps-top-categories" style="margin: 20px 50px 0 50px;">
		<div class="container">

		<div class="container" style="display: grid; grid-gap: 5px; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));">

			<div style='padding: 20px; background-color: #CFFFCD; border-radius: 5px; margin: 10px;'>
			<h4>График розыгрыша тиражей</h4>
			</div>

			<div style='padding: 20px; background-color: #CFFFCD; border-radius: 5px; margin: 10px;'>
			<h4>Последние победители</h4></div>

			<div style='border-radius: 5px; margin: 10px; background-color: #221e1d; text-align: center;'>
				<router-link to='https://accounts.binance.com/ru/register?ref=HDSV144D' target=_blank><img style='border-radius: 5px;' src='../assets/img/binance/binance_exchange.gif'></router-link>
			</div>
		</div>

		<div class="container" style="display: grid; grid-gap: 5px; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); grid-template-rows: repeat(1, 250px);">

		<router-link to="/4x20"><div style="margin: 10px;">
			<div style="vertical-align: top; background-clip: padding-box; background-size: auto 150px; background-repeat: no-repeat; background-position: left top; border: 0px solid #eee; border-bottom: 0; padding: 0px; border-radius: 5px 5px 0 0; overflow: hidden; margin: 0px;" 
        		:style="{backgroundImage: 'url(../src/assets/img/lotto/4x20/logo_4x20.png)'}">
				<div class="ps-block__thumbnail" style="position: relative; top: 0; left: 0;"><img src="../assets/img/trans_1x1.png" style="width: auto; height: 130px;" alt="Спортлото 4 из 20"></div>
			</div>
			<div style="vertical-align: top; background-color: #FF8A26; border-color: transparent; padding: 10px; border-radius: 0 0 5px 5px; overflow: hidden; margin: 0px;">
				<div class="ps-block__content" style="display: flex; justify-content: space-between;">
					<div style="border-radius: 5px; padding: 5px 10px 5px 10px; text-align: left; color: #fff; font-size: 120%;"> <b>Джекпот _$ </b></div>
					<div style="border-radius: 25px; padding: 5px 10px 5px 10px; text-align: right; color: #fff; font-size: 120%; background-color: rgba(255, 255, 255, 0.3);"><b>betPrice _$</b></div>
				</div>
			</div>
		</div></router-link>

		<router-link to="/7x49"><div style="margin: 10px;">
			<div style="vertical-align: top; background-image: url(../src/assets/img/lotto/7x49/logo_7x49.png); background-clip: padding-box; background-size: auto 150px; background-repeat: no-repeat; background-position: left top; border: 0px solid #eee; border-bottom: 0; padding: 0px; border-radius: 5px 5px 0 0; overflow: hidden; margin: 0px;">
				<div class="ps-block__thumbnail" style="position: relative; top: 0; left: 0;"><img src="../assets/img/trans_1x1.png" style="width: auto; height: 130px;" alt="Спортлото 7 из 49"></div>
			</div>
			<div style="vertical-align: top; background-color: #B663FF; border-color: transparent; padding: 10px; border-radius: 0 0 5px 5px; overflow: hidden; margin: 0px;">
				<div class="ps-block__content" style="display: flex; justify-content: space-between;">
					<div style="border-radius: 5px; padding: 5px 10px 5px 10px; text-align: left; color: #fff; font-size: 120%;"> <b>Джекпот _$ </b></div>
					<div style="border-radius: 25px; padding: 5px 10px 5px 10px; text-align: right; color: #fff; font-size: 120%; background-color: rgba(255, 255, 255, 0.3);"><b>betPrice _$</b></div>
				</div>
			</div>
		</div></router-link>

		<router-link to="/6x45"><div style="margin: 10px;">
			<div style="vertical-align: top; background-image: url(../src/assets/img/lotto/6x45/logo_6x45.png); background-clip: padding-box; background-size: auto 150px; background-repeat: no-repeat; background-position: left top; border: 0px solid #eee; border-bottom: 0; padding: 0px; border-radius: 5px 5px 0 0; overflow: hidden; margin: 0px;">
				<div class="ps-block__thumbnail" style="position: relative; top: 0; left: 0;"><img src="../assets/img/trans_1x1.png" style="width: auto; height: 130px;" alt="Спортлото 6 из 45"></div>
			</div>
			<div style="vertical-align: top; background-color: #FFDA00; border-color: transparent; padding: 10px; border-radius: 0 0 5px 5px; overflow: hidden; margin: 0px;">
				<div class="ps-block__content" style="display: flex; justify-content: space-between;">
					<div style="border-radius: 5px; padding: 5px 10px 5px 10px; text-align: left; color: #fff; font-size: 120%;"> <b>Джекпот _$ </b></div>
					<div style="border-radius: 25px; padding: 5px 10px 5px 10px; text-align: right; color: #fff; font-size: 120%; background-color: rgba(0, 0, 0, 0.1);"><b>betPrice _$</b></div>
				</div>
			</div>
		</div></router-link>

		<router-link to="/5x36"><div style="margin: 10px;">
			<div style="vertical-align: top; background-image: url(../src/assets/img/lotto/5x36/logo_5x36.png); background-clip: padding-box; background-size: auto 150px; background-repeat: no-repeat; background-position: left top; border: 0px solid #eee; border-bottom: 0; padding: 0px; border-radius: 5px 5px 0 0; overflow: hidden; margin: 0px;">
				<div class="ps-block__thumbnail" style="position: relative; top: 0; left: 0;"><img src="../assets/img/trans_1x1.png" style="width: auto; height: 130px;" alt="Спортлото 5 из 36"></div>
			</div>
			<div style="vertical-align: top; background-color: #00B93B; border-color: transparent; padding: 10px; border-radius: 0 0 5px 5px; overflow: hidden; margin: 0px;">
				<div class="ps-block__content" style="display: flex; justify-content: space-between;">
					<div style="border-radius: 5px; padding: 5px 10px 5px 10px; text-align: left; color: #fff; font-size: 120%;"> <b>Джекпот _$ </b></div>
					<div style="border-radius: 25px; padding: 5px 10px 5px 10px; text-align: right; color: #fff; font-size: 120%; background-color: rgba(255, 255, 255, 0.3);"><b>betPrice _$</b></div>
				</div>
			</div>
		</div></router-link>

		</div>
		</div>
	</div>
</template>

<script setup>
</script>