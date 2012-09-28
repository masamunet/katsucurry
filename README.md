katsucurry
==========

みんな〜Twitterにカツカレーを大量に表示するブックマークレット作ったよ〜

[カツカレー](javascript:(function(){var src_url='http://jqueryjs.googlecode.com/files/jquery-1.2.3.pack.js';var s=document.createElement('script');s.setAttribute('src',src_url);document.getElementsByTagName('body')[0].appendChild(s);var id=window.setInterval(function(){if(window['jQuery']&&window['jQuery']['fn']&&window['jQuery']['fn']['offset']){window.clearInterval(id);var avatar=$('img.avatar');avatar.each(function(){var t=$(this);t.attr('src','http://yahoo.jp/w-yPhJ');});var fullNames=$('.fullname');fullNames.each(function(){var t=$(this);t.html('カツカレー');});}},100);})();)