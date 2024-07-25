<body>

<img src= "./Resource/page-image-1.png">
<img src= "./Resource/page-image-2.png">
<img src= "./Resource/page-image-3.png">
<a href="https://example.com" id="link">
<img src="./Resource/page-image-4.png">
</a>
<img src= "./Resource/page-image-5.png">

<script>

  (function(){var w=window;if(w.ChannelIO){return w.console.error("ChannelIO script included twice.");}var ch=function(){ch.c(arguments);};ch.q=[];ch.c=function(args){ch.q.push(args);};w.ChannelIO=ch;function l(){if(w.ChannelIOInitialized){return;}w.ChannelIOInitialized=true;var s=document.createElement("script");s.type="text/javascript";s.async=true;s.src="https://cdn.channel.io/plugin/ch-plugin-web.js";var x=document.getElementsByTagName("script")[0];if(x.parentNode){x.parentNode.insertBefore(s,x);}}if(document.readyState==="complete"){l();}else{w.addEventListener("DOMContentLoaded",l);w.addEventListener("load",l);}})();

  ChannelIO('boot', {
  pluginKey: 'a0e721d6-de54-49df-bb00-0a31ccda1eda'
}, function onBoot(error, user) {
  if (error) {
    console.error(error);
  } else {
    ChannelIO('openSupportBot', supportBotId: "108098", message?: null)
    ChannelIO('showMessenger');
  }
});

</script>

</body>