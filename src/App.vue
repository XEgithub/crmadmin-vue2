<template>
    <div id="app">
        <router-view></router-view>
    </div>
</template>

<style lang='scss'>
	@import './css/common';
    #app{
    	width: 100%;
    	height: 100%;
    }
	.content{
		  background:none repeat scroll 0 0 #fff;
		  position:absolute;
		  left:200px;
		  right:0;
		  top:55px;
		  bottom:0;
	}
</style>