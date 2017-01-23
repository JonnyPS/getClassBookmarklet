# getClassBookmarklet

Copy and paste the following link into your bookmarks*:

javascript:void%20function(e){var%20t=function(e){(function(){var%20t=[];e(%22*%22).each(function(){if(e(this).hasClass(%22%22)===!1){var%20a=e(this).attr(%22class%22),o=(e(this).prop(%22nodeName%22),e(this).position()),i=o.top,n=o.left,s=e(this).width(),h=e(this).height();t.push({className:a,elements:[{top:i,left:n,width:s,height:h}]})}}),console.log(t)})()},a=e%26%26e.fn%26%26parseFloat(e.fn.jquery)%3E=1.7;if(a)t(e);else{var%20o=document.createElement(%22script%22);o.src=%22//ajax.googleapis.com/ajax/libs/jquery/1/jquery.js%22,o.onload=o.onreadystatechange=function(){var%20e=this.readyState;e%26%26%22loaded%22!==e%26%26%22complete%22!==e||t(jQuery.noConflict())}}document.getElementsByTagName(%22head%22)[0].appendChild(o)}(window.jQuery);

*On a couple of the pages i've tested it on, it generates an error relating to the page, but still works.
Github is the only page it doesn't work on as i've used JQuery and it will not allow the cdn to be loaded.