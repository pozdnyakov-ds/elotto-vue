<template>
<footer class="ps-footer ps-footer--2" style='margin-top: 20px; background-color: #eee; border-top: 1px solid #ccc;'>
	<div class="container">
		<div class="ps-footer__content" style="width: 100%; margin-bottom: 20px; display: flex; justify-content: space-between;">
		<div style="display: inline-block; text-align: center; border: 1px solid #ccc; border-radius: 5px; background-color: #fff; padding: 10px 0px 10px 20px; margin-left: 50px;">
			<ul class="ps-list--social">
				<li>
                    <router-link target=_blank class="telegram" to="https://t.me/+c-r74HlcM08zZThi">
                        <fa icon="telegram-plane" style='color: #576A90; margin-right: 10px;'/>
                    </router-link>
                    <router-link style='font-size: 100%;' target=_blank to="https://t.me/+c-r74HlcM08zZThi">Группа в Телеграм</router-link>
                </li>
			</ul>
		</div>
		<div style="display: inline-block; margin-right: 50px; text-align: center;">
			<form class="ps-form--newletter" action="#" method="get">
				<div class="form-group--nest">
					<button class='ps-btn unsubscribe' style='background-color: #ccc; color: #333; padding: 10px 15px 10px 15px;'>Отписаться от новостей</button>
					<button class='ps-btn subscribe' style='padding: 10px 15px 10px 15px;'>Подписаться на новости</button>
				</div>
			</form>
		</div>
		</div>
	</div>
	<div class="ps-footer__copyright" style="margin: 0 20px 0 20px;">
		<p style="text-align: center; width: 100%; margin-top: 0;">© 2017-2022 eLotto.me</p>
	</div>
</footer>
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