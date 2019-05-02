<!DOCTYPE html>
<html>
<head>
<meta http-equiv=Content-Type content="text/html;charset=utf8">
<title>2048</title>
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<meta name="HandheldFriendly" content="True">
<meta name="MobileOptimized" content="320">
<meta name="viewport" content="width=device-width, target-densitydpi=160dpi, initial-scale=1.0, maximum-scale=1, user-scalable=no, minimal-ui">
</head>
<body>
<style>
body,html{margin:0;padding:0;background:#faf8ef;color:#776e65;font-size:18px;font-family:Clear Sans,Helvetica Neue,Arial,sans-serif}
body{margin:5pc 0}
input{display:inline-block;box-sizing:border-box;margin:0;padding:0 20px;height:40px;outline:0;border:none;border-radius:3px;background:#8f7a66;color:#f9f6f2;text-decoration:none;font:inherit;font-weight:700;line-height:42px;cursor:pointer;-webkit-appearance:none;-moz-appearance:none;appearance:none}
input[type=email],input[type=text]{padding:0 15px;background:#fcfbf9;color:#776e65;font-weight:400;cursor:auto}
input[type=email]::-webkit-input-placeholder,input[type=text]::-webkit-input-placeholder{color:#9d948c}
input[type=email]::-moz-placeholder,input[type=text]::-moz-placeholder{color:#9d948c}
input[type=email]:-ms-input-placeholder,input[type=text]:-ms-input-placeholder{color:#9d948c}
.heading:after{clear:both;display:block;content:""}
h1.title{float:left;display:block;margin:0;font-weight:700;font-size:5pc}
@-webkit-keyframes move-up{0%{top:25px;opacity:1}
to{top:-50px;opacity:0}
}
@keyframes move-up{0%{top:25px;opacity:1}
to{top:-50px;opacity:0}
}
.scores-container{float:right;text-align:right}
.best-container,.score-container{position:relative;display:inline-block;margin-top:8px;padding:15px 25px;height:25px;border-radius:3px;background:#bbada0;color:#fff;text-align:center;font-weight:700;font-size:25px;line-height:47px}
.best-container:after,.score-container:after{position:absolute;top:10px;left:0;width:100%;color:#eee4da;text-align:center;text-transform:uppercase;font-size:13px;line-height:13px}
.best-container .score-addition,.score-container .score-addition{position:absolute;right:30px;z-index:100;color:red;color:hsla(30,8%,43%,.9);font-weight:700;font-size:25px;line-height:25px;-webkit-animation:move-up .6s ease-in;animation:move-up .6s ease-in;-webkit-animation-fill-mode:both;animation-fill-mode:both}
.score-container:after{content:"当前得分"}
.best-container:after{content:"历史最高"}
p{margin-top:0;margin-bottom:10px;line-height:1.65}
a{color:#776e65;text-decoration:underline;font-weight:700;cursor:pointer}
strong.important{text-transform:uppercase}
hr{margin-top:20px;margin-bottom:30px;border:none;border-bottom:1px solid #d8d4d0}
.container{margin:0 auto;width:500px}
@-webkit-keyframes fade-in{0%{opacity:0}
to{opacity:1}
}
@keyframes fade-in{0%{opacity:0}
to{opacity:1}
}
@-webkit-keyframes slide-up{0%{margin-top:32%}
to{margin-top:20%}
}
@keyframes slide-up{0%{margin-top:32%}
to{margin-top:20%}
}
.game-container{position:relative;box-sizing:border-box;margin-top:40px;padding:15px;width:500px;height:500px;border-radius:6px;background:#bbada0;cursor:default;-webkit-touch-callout:none;-ms-touch-callout:none;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;-ms-touch-action:none;touch-action:none}
.game-message{position:absolute;top:0;right:0;bottom:0;left:0;z-index:100;display:none;padding-top:40px;background:hsla(30,37%,89%,.73);text-align:center;-webkit-animation:fade-in .8s ease 1.2s;animation:fade-in .8s ease 1.2s;-webkit-animation-fill-mode:both;animation-fill-mode:both}
.game-message p{margin-top:222px;height:60px;font-weight:700;font-size:60px;line-height:60px}
.game-message .lower{display:block;margin-top:29px}
.game-message .mailing-list{margin-top:52px}
.game-message .mailing-list strong{display:block;margin-bottom:10px}
.game-message .mailing-list .mailing-list-email-field{margin-right:5px;width:230px}
.game-message a{display:inline-block;margin-left:9px;padding:0 20px;height:40px;border-radius:3px;background:#8f7a66;color:#f9f6f2;text-decoration:none;line-height:42px;cursor:pointer}
.game-message a.keep-playing-button{display:none}
.game-message .score-sharing{display:inline-block;margin-left:10px;vertical-align:middle}
.game-message.game-won{background:rgba(237,194,46,.5);color:#f9f6f2}
.game-message.game-won a.keep-playing-button{display:inline-block}
.game-message.game-over,.game-message.game-won{display:block}
.game-message.game-over p,.game-message.game-won p{-webkit-animation:slide-up 1.5s ease-in-out 2.5s;animation:slide-up 1.5s ease-in-out 2.5s;-webkit-animation-fill-mode:both;animation-fill-mode:both}
.game-message.game-over .mailing-list,.game-message.game-won .mailing-list{-webkit-animation:fade-in 1.5s ease-in-out 2.5s;animation:fade-in 1.5s ease-in-out 2.5s;-webkit-animation-fill-mode:both;animation-fill-mode:both}
.grid-container{position:absolute;z-index:1}
.grid-row{margin-bottom:15px}
.grid-row:last-child{margin-bottom:0}
.grid-row:after{clear:both;display:block;content:""}
.grid-cell{float:left;margin-right:15px;width:106.25px;height:106.25px;border-radius:3px;background:hsla(30,37%,89%,.35)}
.grid-cell:last-child{margin-right:0}
.tile-container{position:absolute;z-index:2}
.tile,.tile .tile-inner{width:107px;height:107px;line-height:107px}
.tile.tile-position-1-1{-webkit-transform:translate(0,0);transform:translate(0,0);-ms-transform:translate(0,0)}
.tile.tile-position-1-2{-webkit-transform:translate(0,121px);transform:translate(0,121px);-ms-transform:translate(0,121px)}
.tile.tile-position-1-3{-webkit-transform:translate(0,242px);transform:translate(0,242px);-ms-transform:translate(0,242px)}
.tile.tile-position-1-4{-webkit-transform:translate(0,363px);transform:translate(0,363px);-ms-transform:translate(0,363px)}
.tile.tile-position-2-1{-webkit-transform:translate(121px,0);transform:translate(121px,0);-ms-transform:translate(121px,0)}
.tile.tile-position-2-2{-webkit-transform:translate(121px,121px);transform:translate(121px,121px);-ms-transform:translate(121px,121px)}
.tile.tile-position-2-3{-webkit-transform:translate(121px,242px);transform:translate(121px,242px);-ms-transform:translate(121px,242px)}
.tile.tile-position-2-4{-webkit-transform:translate(121px,363px);transform:translate(121px,363px);-ms-transform:translate(121px,363px)}
.tile.tile-position-3-1{-webkit-transform:translate(242px,0);transform:translate(242px,0);-ms-transform:translate(242px,0)}
.tile.tile-position-3-2{-webkit-transform:translate(242px,121px);transform:translate(242px,121px);-ms-transform:translate(242px,121px)}
.tile.tile-position-3-3{-webkit-transform:translate(242px,242px);transform:translate(242px,242px);-ms-transform:translate(242px,242px)}
.tile.tile-position-3-4{-webkit-transform:translate(242px,363px);transform:translate(242px,363px);-ms-transform:translate(242px,363px)}
.tile.tile-position-4-1{-webkit-transform:translate(363px,0);transform:translate(363px,0);-ms-transform:translate(363px,0)}
.tile.tile-position-4-2{-webkit-transform:translate(363px,121px);transform:translate(363px,121px);-ms-transform:translate(363px,121px)}
.tile.tile-position-4-3{-webkit-transform:translate(363px,242px);transform:translate(363px,242px);-ms-transform:translate(363px,242px)}
.tile.tile-position-4-4{-webkit-transform:translate(363px,363px);transform:translate(363px,363px);-ms-transform:translate(363px,363px)}
.tile{position:absolute;-webkit-transition:.1s ease-in-out;transition:.1s ease-in-out;-webkit-transition-property:-webkit-transform;transition-property:transform}
.tile .tile-inner{z-index:10;border-radius:3px;text-align:center;font-weight:700;font-size:55px}
.tile .tile-inner,.tile.tile-2 .tile-inner{background:#eee4da}
.tile.tile-2 .tile-inner,.tile.tile-4 .tile-inner{box-shadow:0 0 30px 10px hsla(47,84%,70%,0),inset 0 0 0 1px hsla(0,0%,100%,0)}
.tile.tile-4 .tile-inner{background:#ede0c8}
.tile.tile-8 .tile-inner{background:#f2b179;color:#f9f6f2}
.tile.tile-16 .tile-inner{background:#f59563;color:#f9f6f2}
.tile.tile-32 .tile-inner{background:#f67c5f;color:#f9f6f2}
.tile.tile-64 .tile-inner{background:#f65e3b;color:#f9f6f2}
.tile.tile-128 .tile-inner{background:#edcf72;box-shadow:0 0 30px 10px hsla(47,84%,70%,.2381),inset 0 0 0 1px hsla(0,0%,100%,.14286);color:#f9f6f2;font-size:45px}
@media screen and (max-width:520px){.tile.tile-128 .tile-inner{font-size:25px}
}
.tile.tile-256 .tile-inner{background:#edcc61;box-shadow:0 0 30px 10px hsla(47,84%,70%,.31746),inset 0 0 0 1px hsla(0,0%,100%,.19048);color:#f9f6f2;font-size:45px}
@media screen and (max-width:520px){.tile.tile-256 .tile-inner{font-size:25px}
}
.tile.tile-512 .tile-inner{background:#edc850;box-shadow:0 0 30px 10px hsla(47,84%,70%,.39683),inset 0 0 0 1px hsla(0,0%,100%,.2381);color:#f9f6f2;font-size:45px}
@media screen and (max-width:520px){.tile.tile-512 .tile-inner{font-size:25px}
}
.tile.tile-1024 .tile-inner{background:#edc53f;box-shadow:0 0 30px 10px hsla(47,84%,70%,.47619),inset 0 0 0 1px hsla(0,0%,100%,.28571);color:#f9f6f2;font-size:35px}
@media screen and (max-width:520px){.tile.tile-1024 .tile-inner{font-size:15px}
}
.tile.tile-2048 .tile-inner{background:#edc22e;box-shadow:0 0 30px 10px hsla(47,84%,70%,.55556),inset 0 0 0 1px hsla(0,0%,100%,.33333);color:#f9f6f2;font-size:35px}
@media screen and (max-width:520px){.tile.tile-2048 .tile-inner{font-size:15px}
}
.tile.tile-super .tile-inner{background:#3c3a32;color:#f9f6f2;font-size:30px}
@media screen and (max-width:520px){.tile.tile-super .tile-inner{font-size:10px}
}
@-webkit-keyframes appear{0%{opacity:0;-webkit-transform:scale(0);transform:scale(0);-ms-transform:scale(0)}
to{opacity:1;-webkit-transform:scale(1);transform:scale(1);-ms-transform:scale(1)}
}
@keyframes appear{0%{opacity:0;-webkit-transform:scale(0);transform:scale(0);-ms-transform:scale(0)}
to{opacity:1;-webkit-transform:scale(1);transform:scale(1);-ms-transform:scale(1)}
}
.tile-new .tile-inner{-webkit-animation:appear .2s ease .1s;animation:appear .2s ease .1s;-webkit-animation-fill-mode:backwards;animation-fill-mode:backwards}
@-webkit-keyframes pop{0%{-webkit-transform:scale(0);transform:scale(0);-ms-transform:scale(0)}
50%{-webkit-transform:scale(1.2);transform:scale(1.2);-ms-transform:scale(1.2)}
to{-webkit-transform:scale(1);transform:scale(1);-ms-transform:scale(1)}
}
@keyframes pop{0%{-webkit-transform:scale(0);transform:scale(0);-ms-transform:scale(0)}
50%{-webkit-transform:scale(1.2);transform:scale(1.2);-ms-transform:scale(1.2)}
to{-webkit-transform:scale(1);transform:scale(1);-ms-transform:scale(1)}
}
.tile-merged .tile-inner{z-index:20;-webkit-animation:pop .2s ease .1s;animation:pop .2s ease .1s;-webkit-animation-fill-mode:backwards;animation-fill-mode:backwards}
.above-game:after{clear:both;display:block;content:""}
.game-intro{float:left;margin-bottom:0;line-height:42px}
.restart-button{float:right;padding:0 20px}
.copyright-button,.restart-button{display:inline-block;display:block;height:40px;border-radius:3px;background:#8f7a66;color:#f9f6f2;text-align:center;text-decoration:none;line-height:42px;cursor:pointer}
.copyright-button{margin-top:35px;width:100%}
.game-explanation{margin-top:50px}
.sharing{margin-top:20px;text-align:center}
.sharing>form,.sharing>iframe,.sharing>span{display:inline-block;vertical-align:middle}
@media screen and (max-width:520px){body,html{font-size:15px}
body{margin-top:0;padding:20px}
h1.title{margin-top:15px;font-size:27px}
.container{margin:0 auto;width:280px}
.best-container,.score-container{margin-top:0;padding:15px 10px;min-width:40px}
.heading{margin-bottom:10px}
.game-intro{width:55%;line-height:1.65}
.game-intro,.restart-button{display:block;box-sizing:border-box}
.restart-button{margin-top:2px;padding:0;width:42%}
.game-container{position:relative;box-sizing:border-box;margin-top:17px;padding:10px;width:280px;height:280px;border-radius:6px;background:#bbada0;cursor:default;-webkit-touch-callout:none;-ms-touch-callout:none;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;-ms-touch-action:none;touch-action:none}
.game-message{position:absolute;top:0;right:0;bottom:0;left:0;z-index:100;display:none;padding-top:40px;background:hsla(30,37%,89%,.73);text-align:center;-webkit-animation:fade-in .8s ease 1.2s;animation:fade-in .8s ease 1.2s;-webkit-animation-fill-mode:both;animation-fill-mode:both}
.game-message p{margin-top:222px;height:60px;font-weight:700;font-size:60px;line-height:60px}
.game-message .lower{display:block;margin-top:29px}
.game-message .mailing-list{margin-top:52px}
.game-message .mailing-list strong{display:block;margin-bottom:10px}
.game-message .mailing-list .mailing-list-email-field{margin-right:5px;width:230px}
.game-message a{display:inline-block;margin-left:9px;padding:0 20px;height:40px;border-radius:3px;background:#8f7a66;color:#f9f6f2;text-decoration:none;line-height:42px;cursor:pointer}
.game-message a.keep-playing-button{display:none}
.game-message .score-sharing{display:inline-block;margin-left:10px;vertical-align:middle}
.game-message.game-won{background:rgba(237,194,46,.5);color:#f9f6f2}
.game-message.game-won a.keep-playing-button{display:inline-block}
.game-message.game-over,.game-message.game-won{display:block}
.game-message.game-over p,.game-message.game-won p{-webkit-animation:slide-up 1.5s ease-in-out 2.5s;animation:slide-up 1.5s ease-in-out 2.5s;-webkit-animation-fill-mode:both;animation-fill-mode:both}
.game-message.game-over .mailing-list,.game-message.game-won .mailing-list{-webkit-animation:fade-in 1.5s ease-in-out 2.5s;animation:fade-in 1.5s ease-in-out 2.5s;-webkit-animation-fill-mode:both;animation-fill-mode:both}
.grid-container{position:absolute;z-index:1}
.grid-row{margin-bottom:10px}
.grid-row:last-child{margin-bottom:0}
.grid-row:after{clear:both;display:block;content:""}
.grid-cell{float:left;margin-right:10px;width:57.5px;height:57.5px;border-radius:3px;background:hsla(30,37%,89%,.35)}
.grid-cell:last-child{margin-right:0}
.tile-container{position:absolute;z-index:2}
.tile,.tile .tile-inner{width:58px;height:58px;line-height:58px}
.tile.tile-position-1-1{-webkit-transform:translate(0,0);transform:translate(0,0);-ms-transform:translate(0,0)}
.tile.tile-position-1-2{-webkit-transform:translate(0,67px);transform:translate(0,67px);-ms-transform:translate(0,67px)}
.tile.tile-position-1-3{-webkit-transform:translate(0,135px);transform:translate(0,135px);-ms-transform:translate(0,135px)}
.tile.tile-position-1-4{-webkit-transform:translate(0,202px);transform:translate(0,202px);-ms-transform:translate(0,202px)}
.tile.tile-position-2-1{-webkit-transform:translate(67px,0);transform:translate(67px,0);-ms-transform:translate(67px,0)}
.tile.tile-position-2-2{-webkit-transform:translate(67px,67px);transform:translate(67px,67px);-ms-transform:translate(67px,67px)}
.tile.tile-position-2-3{-webkit-transform:translate(67px,135px);transform:translate(67px,135px);-ms-transform:translate(67px,135px)}
.tile.tile-position-2-4{-webkit-transform:translate(67px,202px);transform:translate(67px,202px);-ms-transform:translate(67px,202px)}
.tile.tile-position-3-1{-webkit-transform:translate(135px,0);transform:translate(135px,0);-ms-transform:translate(135px,0)}
.tile.tile-position-3-2{-webkit-transform:translate(135px,67px);transform:translate(135px,67px);-ms-transform:translate(135px,67px)}
.tile.tile-position-3-3{-webkit-transform:translate(135px,135px);transform:translate(135px,135px);-ms-transform:translate(135px,135px)}
.tile.tile-position-3-4{-webkit-transform:translate(135px,202px);transform:translate(135px,202px);-ms-transform:translate(135px,202px)}
.tile.tile-position-4-1{-webkit-transform:translate(202px,0);transform:translate(202px,0);-ms-transform:translate(202px,0)}
.tile.tile-position-4-2{-webkit-transform:translate(202px,67px);transform:translate(202px,67px);-ms-transform:translate(202px,67px)}
.tile.tile-position-4-3{-webkit-transform:translate(202px,135px);transform:translate(202px,135px);-ms-transform:translate(202px,135px)}
.tile.tile-position-4-4{-webkit-transform:translate(202px,202px);transform:translate(202px,202px);-ms-transform:translate(202px,202px)}
.tile .tile-inner{font-size:35px}
.game-message{padding-top:0}
.game-message p{margin-top:32%!important;margin-bottom:0!important;height:30px!important;font-size:30px!important;line-height:30px!important}
.game-message .lower{margin-top:10px!important}
.game-message.game-won .score-sharing{margin-top:10px}
.game-message.game-over .mailing-list{margin-top:25px}
.game-message .mailing-list{margin-top:10px}
.game-message .mailing-list .mailing-list-email-field{width:180px}
.sharing>form,.sharing>iframe,.sharing>span{display:block;margin:0 auto;margin-bottom:20px}
}
.pp-donate button{display:inline-block;padding:0 20px;height:40px;border:none;border-radius:3px;background:#8f7a66;color:inherit;color:#f9f6f2;text-decoration:none;font:inherit;line-height:42px;cursor:pointer;-webkit-appearance:none;-moz-appearance:none;appearance:none}
.pp-donate button img{margin-right:8px;vertical-align:-4px}
.btc-donate{position:relative;display:inline-block;margin-left:10px;padding:0 20px;height:40px;border-radius:3px;background:#8f7a66;color:#f9f6f2;text-decoration:none;line-height:42px;cursor:pointer}
.btc-donate img{margin-right:8px;vertical-align:-4px}
.btc-donate a{color:#f9f6f2;text-decoration:none;font-weight:400}
.btc-donate .address{position:absolute;top:-30px;right:50%;margin-right:-170px;padding-bottom:7px;width:340px;opacity:0;cursor:auto;-webkit-transition:.4s ease;transition:.4s ease;-webkit-transition-property:top,opacity;transition-property:top,opacity;pointer-events:none}
.btc-donate .address:after{position:absolute;bottom:0;left:50%;margin-left:-7px;border-top:10px solid #bbada0;border-right:7px solid transparent;border-left:7px solid transparent;content:""}
.btc-donate .address code{padding:10px 15px;width:100%;border-radius:3px;background-color:#bbada0;text-align:center;font-weight:400;font-size:15px;font-family:Consolas,Liberation Mono,Courier,monospace;line-height:1}
.btc-donate .address:hover .address,.btc-donate:hover .address{top:-45px;opacity:1;pointer-events:auto}
@media screen and (max-width:520px){.btc-donate{width:90pt}
.btc-donate .address{margin-right:-150px;width:300px}
.btc-donate .address code{font-size:13px}
.btc-donate .address:after{bottom:2px;left:50%}
}
@-webkit-keyframes pop-in-big{0%{margin-top:-56px;opacity:0;-webkit-transform:scale(0) translateZ(0);transform:scale(0) translateZ(0)}
to{margin-top:30px;opacity:1;-webkit-transform:scale(1) translateZ(0);transform:scale(1) translateZ(0)}
}
@keyframes pop-in-big{0%{margin-top:-56px;opacity:0;-webkit-transform:scale(0) translateZ(0);transform:scale(0) translateZ(0)}
to{margin-top:30px;opacity:1;-webkit-transform:scale(1) translateZ(0);transform:scale(1) translateZ(0)}
}
@-webkit-keyframes pop-in-small{0%{margin-top:-76px;opacity:0;-webkit-transform:scale(0) translateZ(0);transform:scale(0) translateZ(0)}
to{margin-top:10px;opacity:1;-webkit-transform:scale(1) translateZ(0);transform:scale(1) translateZ(0)}
}
@keyframes pop-in-small{0%{margin-top:-76px;opacity:0;-webkit-transform:scale(0) translateZ(0);transform:scale(0) translateZ(0)}
to{margin-top:10px;opacity:1;-webkit-transform:scale(1) translateZ(0);transform:scale(1) translateZ(0)}
}
.app-notice{position:relative;box-sizing:border-box;margin-top:30px;padding:18px;height:56px;border-radius:3px;background:#edc53f;color:#fff;-webkit-animation:pop-in-big .7s ease 2s both;animation:pop-in-big .7s ease 2s both}
.app-notice:after{clear:both;display:block;content:""}
.app-notice .notice-close-button{float:right;margin-left:10px;font-weight:700;opacity:.7;cursor:pointer}
.app-notice p{margin-bottom:0}
.app-notice,.app-notice p{line-height:20px}
.app-notice a{color:#fff}
@media screen and (max-width:520px){.app-notice{margin-top:10px;height:76px;-webkit-animation:pop-in-small .7s ease 2s both;animation:pop-in-small .7s ease 2s both}
}
.links{margin-top:20px;text-align:center}
.privacy{word-wrap:break-word}
</style>
<div class="container">
	<div class="heading">
	<h1 class="title">2048</h1>
	<div class="scores-container">
		<div class="score-container">0</div>
		<div class="best-container">0</div>
	</div>
	</div>
	<div class="above-game">
	<p class="game-intro">WSAD 或 方向键进行移动方块，合成 <strong>2048</strong> 就成功了！</p>
	<a class="restart-button">重新开始(R)</a>
	</div>
	<div class="game-container">
	<div class="game-message">
		<p></p>
		<div class="lower">
		<a class="keep-playing-button">继续</a>
		<a class="retry-button">再来一次</a>
		</div>
	</div>

	<div class="grid-container">
		<div class="grid-row">
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		</div>
		<div class="grid-row">
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		</div>
		<div class="grid-row">
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		</div>
		<div class="grid-row">
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		<div class="grid-cell"></div>
		</div>
	</div>
	<div class="tile-container">
	</div>
	</div>
</div>
<script>
	(function () {
		var lastTime = 0;
		var vendors = ['webkit', 'moz'];
		for (var x = 0; x < vendors.length && !window.requestAnimationFrame; ++x) {
			window.requestAnimationFrame = window[vendors[x] + 'RequestAnimationFrame'];
			window.cancelAnimationFrame = window[vendors[x] + 'CancelAnimationFrame'] || window[vendors[x] + 'CancelRequestAnimationFrame'];
		}

		if (!window.requestAnimationFrame) {
			window.requestAnimationFrame = function (callback) {
			var currTime = new Date().getTime();
			var timeToCall = Math.max(0, 16 - (currTime - lastTime));
			var id = window.setTimeout(function () {
				callback(currTime + timeToCall);
				},
				timeToCall);
			lastTime = currTime + timeToCall;
			return id;
			};
		}

		if (!window.cancelAnimationFrame) {
			window.cancelAnimationFrame = function (id) {
			clearTimeout(id);
			};
		}
	}());

	// Wait till the browser is ready to render the game (avoids glitches)
	window.requestAnimationFrame(function () {
		new GameManager(4, KeyboardInputManager, HTMLActuator, LocalStorageManager);

		// TODO: This code is in need of a refactor (along with the rest)
		var storage = new LocalStorageManager;
		var noticeClose = document.querySelector(".notice-close-button");
		var notice = document.querySelector(".app-notice");
		if (storage.getNoticeClosed()) {
			notice.parentNode.removeChild(notice);
		} else {
			noticeClose.addEventListener("click", function () {
			notice.parentNode.removeChild(notice);
			storage.setNoticeClosed(true);
			ga("send", "event", "notice", "closed");
			});
		}
	});

	Function.prototype.bind = Function.prototype.bind || function (target) {
		var self = this;
		return function (args) {
		if (!(args instanceof Array)) {
			args = [args];
		}
		self.apply(target, args);
		};
	};

	(function () {
	if (typeof window.Element === "undefined" || "classList" in document.documentElement) {
		return;
	}

	var prototype = Array.prototype,
	push = prototype.push,
	splice = prototype.splice,
	join = prototype.join;

	function DOMTokenList(el) {
		this.el = el;
		// The className needs to be trimmed and split on whitespace to retrieve a list of classes.
		var classes = el.className.replace(/^s+|s+$/g, '').split(/s+/);
		for (var i = 0; i < classes.length; i++) {
			push.call(this, classes[i]);
		}
	}

	DOMTokenList.prototype = {
		add: function (token) {
		if (this.contains(token)) return;
		push.call(this, token);
		this.el.className = this.toString();
		},
		contains: function (token) {
		return this.el.className.indexOf(token) != -1;
		},
		item: function (index) {
		return this[index] || null;
		},
		remove: function (token) {
		if (!this.contains(token)) return;
		for (var i = 0; i < this.length; i++) {
			if (this[i] == token) break;
		}
		splice.call(this, i, 1);
		this.el.className = this.toString();
		},
		toString: function () {
		return join.call(this, ' ');
		},
		toggle: function (token) {
		if (!this.contains(token)) {
			this.add(token);
		} else {
			this.remove(token);
		}
		return this.contains(token);
		}
	};

	window.DOMTokenList = DOMTokenList;

	function defineElementGetter(obj, prop, getter) {
		if (Object.defineProperty) {
		Object.defineProperty(obj, prop, {
			get: getter
		});
		} else {
			obj.__defineGetter__(prop, getter);
		}
	}

defineElementGetter(HTMLElement.prototype, 'classList', function () {
		return new DOMTokenList(this);
	});
	})();

	function GameManager(size, InputManager, Actuator, StorageManager) {
		this.size = size; // Size of the grid
		this.inputManager = new InputManager;
		this.storageManager = new StorageManager;
		this.actuator = new Actuator;
		this.startTiles = 2;
		this.inputManager.on("move", this.move.bind(this));
		this.inputManager.on("restart", this.restart.bind(this));
		this.inputManager.on("keepPlaying", this.keepPlaying.bind(this));
		this.setup();
	}

	// Restart the game
	GameManager.prototype.restart = function () {
		this.storageManager.clearGameState();
		this.actuator.continueGame(); // Clear the game won/lost message
		this.setup();
	};

	// Keep playing after winning (allows going over 2048)
	GameManager.prototype.keepPlaying = function () {
		this.keepPlaying = true;
		this.actuator.continueGame(); // Clear the game win/lost message
	};

	// Return true if the game is lost, or has won and the user hasn't kept playing
	GameManager.prototype.isGameTerminated = function () {
		return this.over || (this.won && !this.keepPlaying);
	};

	// Set up the game
	GameManager.prototype.setup = function () {
		var previousState = this.storageManager.getGameState();

		// Reload the game from a previous game if present
		if (previousState) {
			this.grid = new Grid(previousState.grid.size,
			previousState.grid.cells);
			this.score = previousState.score;
			this.over = previousState.over;
			this.won = previousState.won;
			this.keepPlaying = previousState.keepPlaying;
		} else {
			this.grid = new Grid(this.size);
			this.score = 0;
			this.over = false;
			this.won = false;
			this.keepPlaying = false;
			this.addStartTiles();
		}
		this.actuate();
	};

	// Set up the initial tiles to start the game with
	GameManager.prototype.addStartTiles = function () {
		for (var i = 0; i < this.startTiles; i++) {
			this.addRandomTile();
		}
	};

	// Adds a tile in a random position
	GameManager.prototype.addRandomTile = function () {
		if (this.grid.cellsAvailable()) {
			var value = Math.random() < 0.9 ? 2 : 4;
			var tile = new Tile(this.grid.randomAvailableCell(), value);
			this.grid.insertTile(tile);
		}
	};

	// Sends the updated grid to the actuator
	GameManager.prototype.actuate = function () {
		if (this.storageManager.getBestScore() < this.score) {
			this.storageManager.setBestScore(this.score);
		}

		// Clear the state when the game is over (game over only, not win)
		if (this.over) {
			this.storageManager.clearGameState();
		} else {
			this.storageManager.setGameState(this.serialize());
		}

		this.actuator.actuate(this.grid, {
			score: this.score,
			over: this.over,
			won: this.won,
			bestScore: this.storageManager.getBestScore(),
			terminated: this.isGameTerminated()
		});
	};

	// Represent the current game as an object
	GameManager.prototype.serialize = function () {
		return {
			grid: this.grid.serialize(),
			score: this.score,
			over: this.over,
			won: this.won,
			keepPlaying: this.keepPlaying
		};
	};

	// Save all tile positions and remove merger info
	GameManager.prototype.prepareTiles = function () {
		this.grid.eachCell(function (x, y, tile) {
			if (tile) {
			tile.mergedFrom = null;
			tile.savePosition();
			}
		});
	};

	// Move a tile and its representation
	GameManager.prototype.moveTile = function (tile, cell) {
		this.grid.cells[tile.x][tile.y] = null;
		this.grid.cells[cell.x][cell.y] = tile;
		tile.updatePosition(cell);
	};

	// Move tiles on the grid in the specified direction
	GameManager.prototype.move = function (direction) {
		// 0: up, 1: right, 2: down, 3: left
		var self = this;

		if (this.isGameTerminated()) return; // Don't do anything if the game's over

		var cell, tile;
		var vector = this.getVector(direction);
		var traversals = this.buildTraversals(vector);
		var moved = false;

		// Save the current tile positions and remove merger information
		this.prepareTiles();

		// Traverse the grid in the right direction and move tiles
		traversals.x.forEach(function (x) {
			traversals.y.forEach(function (y) {
				cell = { x: x, y: y };
				tile = self.grid.cellContent(cell);

				if (tile) {
					var positions = self.findFarthestPosition(cell, vector);
					var next = self.grid.cellContent(positions.next);

					// Only one merger per row traversal?
					if (next && next.value === tile.value && !next.mergedFrom) {
					var merged = new Tile(positions.next, tile.value * 2);
					merged.mergedFrom = [tile, next];

					self.grid.insertTile(merged);
					self.grid.removeTile(tile);

					// Converge the two tiles' positions
					tile.updatePosition(positions.next);

					// Update the score
					self.score += merged.value;

					// The mighty 2048 tile
					if (merged.value === 2048) self.won = true;
						} else {
					self.moveTile(tile, positions.farthest);
					}

					if (!self.positionsEqual(cell, tile)) {
						moved = true; // The tile moved from its original cell!
					}
				}
			});
		});

		if (moved) {
			this.addRandomTile();
			if (!this.movesAvailable()) {
				this.over = true; // Game over!
			}
			this.actuate();
		}
	};

	// Get the vector representing the chosen direction
	GameManager.prototype.getVector = function (direction) {
		// Vectors representing tile movement
		var map = {
			0: { x: 0, y: -1 }, // Up
			1: { x: 1, y: 0 }, // Right
			2: { x: 0, y: 1 }, // Down
			3: { x: -1, y: 0 } // Left
		};

		return map[direction];
	};

	// Build a list of positions to traverse in the right order
	GameManager.prototype.buildTraversals = function (vector) {
	var traversals = { x: [], y: [] };

	for (var pos = 0; pos < this.size; pos++) {
		traversals.x.push(pos);
		traversals.y.push(pos);
	}

	// Always traverse from the farthest cell in the chosen direction
	if (vector.x === 1) traversals.x = traversals.x.reverse();
	if (vector.y === 1) traversals.y = traversals.y.reverse();
		return traversals;
	};

	GameManager.prototype.findFarthestPosition = function (cell, vector) {
		var previous;

		// Progress towards the vector direction until an obstacle is found
		do {
		previous = cell;
		cell = { x: previous.x + vector.x, y: previous.y + vector.y };
		} while (this.grid.withinBounds(cell) && this.grid.cellAvailable(cell));

		return {
			farthest: previous,
			next: cell // Used to check if a merge is required
		};
	};

	GameManager.prototype.movesAvailable = function () {
		return this.grid.cellsAvailable() || this.tileMatchesAvailable();
	};

	// Check for available matches between tiles (more expensive check)
	GameManager.prototype.tileMatchesAvailable = function () {
		var self = this;
		var tile;
		for (var x = 0; x < this.size; x++) {
			for (var y = 0; y < this.size; y++) {
			tile = this.grid.cellContent({ x: x, y: y });
			if (tile) {
				for (var direction = 0; direction < 4; direction++) {
				var vector = self.getVector(direction);
				var cell = { x: x + vector.x, y: y + vector.y };
				var other = self.grid.cellContent(cell);
				if (other && other.value === tile.value) {
					return true; // These two tiles can be merged
				}
				}
			}
			}
		}
		return false;
	};

	GameManager.prototype.positionsEqual = function (first, second) {
		return first.x === second.x && first.y === second.y;
	};

	function Grid(size, previousState) {
		this.size = size;
		this.cells = previousState ? this.fromState(previousState) : this.empty();
	}

	// Build a grid of the specified size
	Grid.prototype.empty = function () {
		var cells = [];
		for (var x = 0; x < this.size; x++) {
			var row = cells[x] = [];
			for (var y = 0; y < this.size; y++) {
			row.push(null);
			}
		}
		return cells;
	};

	Grid.prototype.fromState = function (state) {
		var cells = [];
		for (var x = 0; x < this.size; x++) {
			var row = cells[x] = [];
			for (var y = 0; y < this.size; y++) {
			var tile = state[x][y];
			row.push(tile ? new Tile(tile.position, tile.value) : null);
			}
		}
		return cells;
	};

	// Find the first available random position
	Grid.prototype.randomAvailableCell = function () {
		var cells = this.availableCells();
		if (cells.length) {
			return cells[Math.floor(Math.random() * cells.length)];
		}
	};

	Grid.prototype.availableCells = function () {
		var cells = [];
		this.eachCell(function (x, y, tile) {
			if (!tile) {
			cells.push({ x: x, y: y });
			}
		});
		return cells;
	};

	// Call callback for every cell
	Grid.prototype.eachCell = function (callback) {
		for (var x = 0; x < this.size; x++) {
			for (var y = 0; y < this.size; y++) {
			callback(x, y, this.cells[x][y]);
			}
		}
	};

	// Check if there are any cells available
	Grid.prototype.cellsAvailable = function () {
		return !!this.availableCells().length;
	};

	// Check if the specified cell is taken
	Grid.prototype.cellAvailable = function (cell) {
		return !this.cellOccupied(cell);
	};

	Grid.prototype.cellOccupied = function (cell) {
		return !!this.cellContent(cell);
	};

	Grid.prototype.cellContent = function (cell) {
		if (this.withinBounds(cell)) {
			return this.cells[cell.x][cell.y];
		} else {
			return null;
		}
	};

	// Inserts a tile at its position
	Grid.prototype.insertTile = function (tile) {
		this.cells[tile.x][tile.y] = tile;
	};

	Grid.prototype.removeTile = function (tile) {
		this.cells[tile.x][tile.y] = null;
	};

	Grid.prototype.withinBounds = function (position) {
		return position.x >= 0 && position.x < this.size &&	position.y >= 0 && position.y < this.size;
	};

	Grid.prototype.serialize = function () {
		var cellState = [];
		for (var x = 0; x < this.size; x++) {
			var row = cellState[x] = [];
			for (var y = 0; y < this.size; y++) {
			row.push(this.cells[x][y] ? this.cells[x][y].serialize() : null);
			}
		}
		return {
			size: this.size,
			cells: cellState
		};
	};

	function HTMLActuator() {
		this.tileContainer = document.querySelector(".tile-container");
		this.scoreContainer = document.querySelector(".score-container");
		this.bestContainer = document.querySelector(".best-container");
		this.messageContainer = document.querySelector(".game-message");
		this.sharingContainer = document.querySelector(".score-sharing");
		this.score = 0;
	}

	HTMLActuator.prototype.actuate = function (grid, metadata) {
		var self = this;

		window.requestAnimationFrame(function () {
			self.clearContainer(self.tileContainer);
			grid.cells.forEach(function (column) {
				column.forEach(function (cell) {
					if (cell) {
						self.addTile(cell);
					}
				});
			});

			self.updateScore(metadata.score);
			self.updateBestScore(metadata.bestScore);

			if (metadata.terminated) {
				if (metadata.over) {
					self.message(false); // You lose
				} else if (metadata.won) {
					self.message(true); // You win
				}
			}
		});
	};

	// Continues the game (both restart and keep playing)
	HTMLActuator.prototype.continueGame = function () {
	if (typeof ga !== "undefined") {
		ga("send", "event", "game", "restart");
	}

	this.clearMessage();
	};

	HTMLActuator.prototype.clearContainer = function (container) {
		while (container.firstChild) {
			container.removeChild(container.firstChild);
		}
	};

	HTMLActuator.prototype.addTile = function (tile) {
	var self = this;
	var wrapper = document.createElement("div");
	var inner = document.createElement("div");
	var position = tile.previousPosition || { x: tile.x, y: tile.y };
	var positionClass = this.positionClass(position);

	// We can't use classlist because it somehow glitches when replacing classes
	var classes = ["tile", "tile-" + tile.value, positionClass];
	if (tile.value > 2048) classes.push("tile-super");
	this.applyClasses(wrapper, classes);
	inner.classList.add("tile-inner");
	inner.textContent = tile.value;
	if (tile.previousPosition) {
		// Make sure that the tile gets rendered in the previous position first
		window.requestAnimationFrame(function () {
			classes[2] = self.positionClass({ x: tile.x, y: tile.y });
			self.applyClasses(wrapper, classes); // Update the position
		});
	} else if (tile.mergedFrom) {
		classes.push("tile-merged");
		this.applyClasses(wrapper, classes);

		// Render the tiles that merged
		tile.mergedFrom.forEach(function (merged) {
		self.addTile(merged);
		});
	} else {
		classes.push("tile-new");
		this.applyClasses(wrapper, classes);
	}

	// Add the inner part of the tile to the wrapper
	wrapper.appendChild(inner);

	// Put the tile on the board
	this.tileContainer.appendChild(wrapper);
	};

	HTMLActuator.prototype.applyClasses = function (element, classes) {
		element.setAttribute("class", classes.join(" "));
	};

	HTMLActuator.prototype.normalizePosition = function (position) {
		return { x: position.x + 1, y: position.y + 1 };
	};

	HTMLActuator.prototype.positionClass = function (position) {
		position = this.normalizePosition(position);
		return "tile-position-" + position.x + "-" + position.y;
	};

	HTMLActuator.prototype.updateScore = function (score) {
		this.clearContainer(this.scoreContainer);
		var difference = score - this.score;
		this.score = score;
		this.scoreContainer.textContent = this.score;
		if (difference > 0) {
			var addition = document.createElement("div");
			addition.classList.add("score-addition");
			addition.textContent = "+" + difference;
			this.scoreContainer.appendChild(addition);
		}
	};

	HTMLActuator.prototype.updateBestScore = function (bestScore) {
		this.bestContainer.textContent = bestScore;
	};

	HTMLActuator.prototype.message = function (won) {
		var type = won ? "game-won" : "game-over";
		var message = won ? "游戏胜利!" : "游戏结束!";
		if (typeof ga !== "undefined") {
			ga("send", "event", "game", "end", type, this.score);
		}

		this.messageContainer.classList.add(type);
		this.messageContainer.getElementsByTagName("p")[0].textContent = message;
		this.clearContainer(this.sharingContainer);
		this.sharingContainer.appendChild(this.scoreTweetButton());
		twttr.widgets.load();
	};

	HTMLActuator.prototype.clearMessage = function () {
		// IE only takes one value to remove at a time.
		this.messageContainer.classList.remove("game-won");
		this.messageContainer.classList.remove("game-over");
	};

	HTMLActuator.prototype.scoreTweetButton = function () {
		var tweet = document.createElement("a");
		tweet.classList.add("twitter-share-button");
		tweet.setAttribute("href", "https://twitter.com/share");
		tweet.setAttribute("data-via", "gabrielecirulli");
		tweet.setAttribute("data-url", "http://git.io/2048");
		tweet.setAttribute("data-counturl", "http://gabrielecirulli.github.io/2048/");
		tweet.textContent = "Tweet";

		var text = "I scored " + this.score + " points at 2048, a game where you join numbers to score high! #2048game";
		tweet.setAttribute("data-text", text);
		return tweet;
	};

	function KeyboardInputManager() {
		this.events = {};

		if (window.navigator.msPointerEnabled) {
				//Internet Explorer 10 style
				this.eventTouchstart = "MSPointerDown";
				this.eventTouchmove = "MSPointerMove";
				this.eventTouchend = "MSPointerUp";
			} else {
				this.eventTouchstart = "touchstart";
				this.eventTouchmove = "touchmove";
				this.eventTouchend = "touchend";
			}
		this.listen();
	}

	KeyboardInputManager.prototype.on = function (event, callback) {
		if (!this.events[event]) {
			this.events[event] = [];
		}
		this.events[event].push(callback);
	};

	KeyboardInputManager.prototype.emit = function (event, data) {
		var callbacks = this.events[event];
		if (callbacks) {
			callbacks.forEach(function (callback) {
				callback(data);
			});
		}
	};

	KeyboardInputManager.prototype.listen = function () {
			var self = this;
			var map = {
				38: 0, // Up
				39: 1, // Right
				40: 2, // Down
				37: 3, // Left
				87: 0, // W
				68: 1, // D
				83: 2, // S
				65: 3 // A
			};

			// Respond to direction keys
			document.addEventListener("keydown", function (event) {
				var modifiers = event.altKey || event.ctrlKey || event.metaKey || event.shiftKey;
				var mapped = map[event.which];

				// Ignore the event if it's happening in a text field
				if (self.targetIsInput(event)) return;
				if (!modifiers) {
				if (mapped !== undefined) {
					event.preventDefault();
					self.emit("move", mapped);
				}
				}

				// R key restarts the game
				if (!modifiers && event.which === 82) {
				self.restart.call(self, event);
				}
		});

		// Respond to button presses
		this.bindButtonPress(".retry-button", this.restart);
		this.bindButtonPress(".restart-button", this.restart);
		this.bindButtonPress(".keep-playing-button", this.keepPlaying);

		// Respond to swipe events
		var touchStartClientX, touchStartClientY;
		var gameContainer = document.getElementsByClassName("game-container")[0];

		gameContainer.addEventListener(this.eventTouchstart, function (event) {
			if ((!window.navigator.msPointerEnabled && event.touches.length > 1) || event.targetTouches.length > 1 || self.targetIsInput(event)) {
				return; // Ignore if touching with more than 1 finger or touching input
			}

			if (window.navigator.msPointerEnabled) {
				touchStartClientX = event.pageX;
				touchStartClientY = event.pageY;
			} else {
				touchStartClientX = event.touches[0].clientX;
				touchStartClientY = event.touches[0].clientY;
			}
			event.preventDefault();
		});
		gameContainer.addEventListener(this.eventTouchmove, function (event) {
			event.preventDefault();
		});

		gameContainer.addEventListener(this.eventTouchend, function (event) {
			if ((!window.navigator.msPointerEnabled && event.touches.length > 0) || event.targetTouches.length > 0 || self.targetIsInput(event)) {
				return; // Ignore if still touching with one or more fingers or input
			}

			var touchEndClientX, touchEndClientY;
			if (window.navigator.msPointerEnabled) {
				touchEndClientX = event.pageX;
				touchEndClientY = event.pageY;
			} else {
				touchEndClientX = event.changedTouches[0].clientX;
				touchEndClientY = event.changedTouches[0].clientY;
			}

			var dx = touchEndClientX - touchStartClientX;
			var absDx = Math.abs(dx);
			var dy = touchEndClientY - touchStartClientY;
			var absDy = Math.abs(dy);
			if (Math.max(absDx, absDy) > 10) {
				// (right : left) : (down : up)
				self.emit("move", absDx > absDy ? (dx > 0 ? 1 : 3) : (dy > 0 ? 2 : 0));
			}
		});
	};

	KeyboardInputManager.prototype.restart = function (event) {
		event.preventDefault();
		this.emit("restart");
	};

	KeyboardInputManager.prototype.keepPlaying = function (event) {
		event.preventDefault();
		this.emit("keepPlaying");
	};

	KeyboardInputManager.prototype.bindButtonPress = function (selector, fn) {
		var button = document.querySelector(selector);
		button.addEventListener("click", fn.bind(this));
		button.addEventListener(this.eventTouchend, fn.bind(this));
	};

	KeyboardInputManager.prototype.targetIsInput = function (event) {
		return event.target.tagName.toLowerCase() === "input";
	};


	window.fakeStorage = {
		_data: {},

		setItem: function (id, val) {
			return this._data[id] = String(val);
		},

		getItem: function (id) {
			return this._data.hasOwnProperty(id) ? this._data[id] : undefined;
		},

		removeItem: function (id) {
			return delete this._data[id];
		},

		clear: function () {
			return this._data = {};
		}
	};

	function LocalStorageManager() {
		this.bestScoreKey = "bestScore";
		this.gameStateKey = "gameState";
		this.noticeClosedKey = "noticeClosed";

		var supported = this.localStorageSupported();
		this.storage = supported ? window.localStorage : window.fakeStorage;
	}

	LocalStorageManager.prototype.localStorageSupported = function () {
		var testKey = "test";
		var storage = window.localStorage;

		try {
			storage.setItem(testKey, "1");
			storage.removeItem(testKey);
			return true;
		} catch (error) {
			return false;
		}
	};

	// Best score getters/setters
	LocalStorageManager.prototype.getBestScore = function () {
		return this.storage.getItem(this.bestScoreKey) || 0;
	};

	LocalStorageManager.prototype.setBestScore = function (score) {
		this.storage.setItem(this.bestScoreKey, score);
	};

	// Game state getters/setters and clearing
	LocalStorageManager.prototype.getGameState = function () {
		var stateJSON = this.storage.getItem(this.gameStateKey);
		return stateJSON ? JSON.parse(stateJSON) : null;
	};

	LocalStorageManager.prototype.setGameState = function (gameState) {
		this.storage.setItem(this.gameStateKey, JSON.stringify(gameState));
	};

	LocalStorageManager.prototype.clearGameState = function () {
		this.storage.removeItem(this.gameStateKey);
	};

	LocalStorageManager.prototype.setNoticeClosed = function (noticeClosed) {
		this.storage.setItem(this.noticeClosedKey, JSON.stringify(noticeClosed));
	};

	LocalStorageManager.prototype.getNoticeClosed = function () {
		return JSON.parse(this.storage.getItem(this.noticeClosedKey) || "false");
	};

	function Tile(position, value) {
		this.x  = position.x;
		this.y  = position.y;
		this.value = value || 2;
		this.previousPosition = null;
		this.mergedFrom = null; // Tracks tiles that merged together
	}

	Tile.prototype.savePosition = function () {
		this.previousPosition = { x: this.x, y: this.y };
	};

	Tile.prototype.updatePosition = function (position) {
		this.x = position.x;
		this.y = position.y;
	};

	Tile.prototype.serialize = function () {
		return {
			position: {
				x: this.x,
				y: this.y
			},
			value: this.value
		};
	};
</script>
</body>
</html>
