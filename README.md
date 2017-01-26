# getClassBookmarklet

Copy and paste the following link into your bookmarks*:

###Simple Version:

javascript:void%20function(e){var%20t=function(e){(function(){var%20t=[];e(%22*%22).each(function(){if(e(this).hasClass(%22%22)===!1){var%20a=e(this).attr(%22class%22),o=(e(this).prop(%22nodeName%22),e(this).position()),i=o.top,n=o.left,s=e(this).width(),h=e(this).height();t.push({className:a,elements:[{top:i,left:n,width:s,height:h}]})}}),console.log(t)})()},a=e%26%26e.fn%26%26parseFloat(e.fn.jquery)%3E=1.7;if(a)t(e);else{var%20o=document.createElement(%22script%22);o.src=%22//ajax.googleapis.com/ajax/libs/jquery/1/jquery.js%22,o.onload=o.onreadystatechange=function(){var%20e=this.readyState;e%26%26%22loaded%22!==e%26%26%22complete%22!==e||t(jQuery.noConflict())}}document.getElementsByTagName(%22head%22)[0].appendChild(o)}(window.jQuery);

*Github doesn't allow JQuery to be loaded on to its page, so the script won't work on this page.*

###Unfinished Version:

javascript:void%20function(e){var%20a=function(e){(function(a){var%20n=[],t=[];e(%22*%22).each(function(){e(this).hasClass(%22%22)===!1%26%26(a=e(this).attr(%22class%22),n.push(a),n.sort())}),n=n.filter(function(e,a,n){return%20n.indexOf(e)==a});for(var%20s=0;s%3Cn.length;s++){var%20o=n[s];e(o).hasClass(%22.%22+o)===!1%26%26(class_name_width=e(%22.%22+o).width(),t.push({class___name:o,elem:[e(%22.%22+o).each(function(){class_name_width})]}))}console.log(t)})()},n=e%26%26e.fn%26%26parseFloat(e.fn.jquery)%3E=1.7;if(n)a(e);else{var%20t=document.createElement(%22script%22);t.src=%22//ajax.googleapis.com/ajax/libs/jquery/1/jquery.js%22,t.onload=t.onreadystatechange=function(){var%20e=this.readyState;e%26%26%22loaded%22!==e%26%26%22complete%22!==e||a(jQuery.noConflict())}}document.getElementsByTagName(%22head%22)[0].appendChild(t)}(window.jQuery);
