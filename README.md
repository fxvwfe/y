!function(){function e(){var e=document.createElement("link");e.setAttribute("type","text/css"),e.setAttribute("rel","stylesheet"),e.setAttribute("href",_),e.setAttribute("class",k),document.body.appendChild(e)}function t(){for(var e=document.getElementsByClassName(k),t=0;t<e.length;t++)document.body.removeChild(e[t])}function n(){var e=document.createElement("div");e.setAttribute("class",E),document.body.appendChild(e),setTimeout(function(){document.body.removeChild(e)},100)}function o(e){return{height:e.offsetHeight,width:e.offsetWidth}}function r(e){var t=o(e);return t.height>f&&t.height<g&&t.width>h&&t.width<p}function a(e){for(var t=e,n=0;t;)n+=t.offsetTop,t=t.offsetParent;return n}function i(){var e=document.documentElement;return window.innerWidth?window.innerHeight:e&&!isNaN(e.clientHeight)?e.clientHeight:0}function s(){return window.pageYOffset?window.pageYOffset:Math.max(document.documentElement.scrollTop,document.body.scrollTop)}function u(e){var t=a(e);return t>=C&&N+C>=t}function d(){var e=document.createElement("audio");e.setAttribute("class",k),e.src=w,e.loop=!1,e.addEventListener("canplay",function(){setTimeout(function(){m(A)},500),setTimeout(function(){l(),n();for(var e=0;e<x.length;e++)c(x[e])},15500)},!0),e.addEventListener("ended",function(){l(),t()},!0),e.innerHTML=" <p>If you are reading this, it is because your browser does not support the audio element. We recommend that you get a new browser.</p> <p>",document.body.appendChild(e),e.play()}function m(e){e.className+=" "+b+" "+v}function c(e){e.className+=" "+b+" "+y[Math.floor(Math.random()*y.length)]}function l(){for(var e=document.getElementsByClassName(b),t=new RegExp("\\b"+b+"\\b"),n=0;n<e.length;)e[n].className=e[n].className.replace(t,"")}for(var f=30,h=30,g=350,p=350,w="//s3.amazonaws.com/moovweb-marketing/playground/harlem-shake.mp3",b="mw-harlem_shake_me",v="im_first",y=["im_drunk","im_baked","im_trippin","im_blown"],E="mw-strobe_light",_="//s3.amazonaws.com/moovweb-marketing/playground/harlem-shake-style.css",k="mw_added_css",N=i(),C=s(),T=document.getElementsByTagName("*"),A=null,H=0;H<T.length;H++){var M=T[H];if(r(M)&&u(M)){A=M;break}}if(null===M)return void console.warn("Could not find a node of the right size. Please try a different page.");e(),d();for(var x=[],H=0;H<T.length;H++){var M=T[H];r(M)&&x.push(M)}}();
