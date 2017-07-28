/**
* 제이쿼리이용한 소스 시작
**/
/*퍼블리싱 링크 작업. todo 추후 제거 2016.09.12*/

$(function(){




});

$(document).mouseup(function (e) {
	// 팝업 아이디
	var container = $(".selectBtnWrap .slimScrollDiv");
	if (!container.is(e.target) && container.has(e.target).length === 0){
	container.css("display","none");
	}
});





function openPopup(id,w,h){
  var popup = document.getElementById(id);
  var realY = (document.documentElement.clientHeight-h)/2;
  var glayerPopup = popup.className;
  if( popup.style.display == "none" || popup.style.display == "" ){
   popup.style.display = "table";
   document.getElementById('dim').style.display = "block";
   document.body.style.overflow = "hidden";
	 
  } else {
   popup.style.display = "none";
   document.getElementById('dim').style.display = "none";
  }
 // popup.style.width = (w-10)+"px";

 }

/**
* 레이어 팝업 닫기
**/
 function closePopup(id){
  var popup = document.getElementById(id);
  popup.style.display = "none";
  document.getElementById('dim').style.display = "none";
  document.body.style.overflow = "visible";
}

function scroll_top(){
		if($(window).scrollTop()<=1) {
			$(".btnTopWrap").fadeOut("slow");
		}
		else {
			$(".btnTopWrap").fadeIn("slow");
		}
	}
