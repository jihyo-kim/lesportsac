<%@ page language="java" contentType="text/html; charset=UTF-8"
    pageEncoding="UTF-8"%>
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<base href="http://localhost:8080/lesportsac_korea/" target="_self" />
<script type="text/javascript" src="http://openapi.map.naver.com/openapi/naverMap.naver?ver=2.0&key=9ccaaa967495d4d22de8e83f4260ba9d"></script>



<title>lesportsackorea</title>
</head>
<body>
 <div id="map" style="border:1px solid #000;"></div>
<script>
var oPoint = new nhn.api.map.LatLng(37.5130363,127.0259533);
nhn.api.map.setDefaultPoint('LatLng');
oMap = new nhn.api.map.Map('map' ,{
                        point : oPoint,
                        zoom : 12,
                        enableWheelZoom : true,
                        enableDragPan : true,
                        enableDblClickZoom : false,
                        mapMode : 0,
                        activateTrafficMap : false,
                        activateBicycleMap : false,
                        minMaxLevel : [ 1, 14 ],
                        size : new nhn.api.map.Size("500","500")
                });
var mapZoom = new nhn.api.map.ZoomControl(); // - 줌 컨트롤 선언
mapZoom.setPosition({right:10, bottom:10}); // - 줌 컨트롤 위치 지정
oMap.addControl(mapZoom); // - 줌 컨트롤 추가.

var oSize = new nhn.api.map.Size(28, 37);
var oOffset = new nhn.api.map.Size(14, 37);
var oIcon = new nhn.api.map.Icon('http://static.naver.com/maps2/icons/pin_spot2.png', oSize, oOffset);

var oMarker1 = new nhn.api.map.Marker(oIcon, { title : 'METEORA ' });  //마커 생성 
oMarker1.setPoint(oPoint); //마커 표시할 좌표 선택
oMap.addOverlay(oMarker1); //마커를 지도위에 표현 
var oLabel1 = new nhn.api.map.MarkerLabel(); // - 마커 라벨 선언. 
oMap.addOverlay(oLabel1); // - 마커 라벨 지도에 추가. 기본은 라벨이 보이지 않는 상태로 추가됨. 
oLabel1.setVisible(true, oMarker1); // 마커 라벨 보이기


</script>
 
 

</body>
</html>