// JavaScript Document

jQuery(window).on('load resize', function(){
 
  var w = jQuery(window).width();
  var x = 769; //下記を適用させるウィンドウの最小値
 
  if (x <= w) {

	jQuery(function() {

	  // #headerの高さを取得
	  var getHeight = jQuery('#header').outerHeight();

	  // #main_visualの高さと縦中央
	  jQuery('#main_visual').css({'height': 'calc(100vh - ' + getHeight + 'px)'});

	});

  }
 
})
