# michaelf500.github.io 
<!DOCTYPE html>
<html>
<head>
	
	<title>Random views of Newcastle upon Tyne</title>

	<meta charset="utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	
	<link rel="shortcut icon" type="image/x-icon" href="docs/images/favicon.ico" />

    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.6.0/dist/leaflet.css" integrity="sha512-xwE/Az9zrjBIphAcBb3F6JVqxf46+CDLwfLMHloNu6KEQCAWi6HcDUbeOfBIptF7tcCzusKFjFw2yuvEpDL9wQ==" crossorigin=""/>
    <script src="https://unpkg.com/leaflet@1.6.0/dist/leaflet.js" integrity="sha512-gZwIG9x3wUXg2hdXF6+rVkLF/0Vi9U8D2Ntg4Ga5I5BZpVkVxlJWbSQtXPSiUTtC0TjtGOmxa1AJPuV0CPthew==" crossorigin=""></script>


	
</head>
<body>



<div id="mapid" style="width: 600px; height: 400px;"></div>

<script>

	var mymap = L.map('mapid').setView([55, -1.6], 12);

	L.tileLayer('https://api.mapbox.com/styles/v1/{id}/tiles/{z}/{x}/{y}?access_token=pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4NXVycTA2emYycXBndHRqcmZ3N3gifQ.rJcFIG214AriISLbB6B5aw', {
		maxZoom: 18,
		attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors, ' +
			'<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, ' +
			'Imagery Â© <a href="https://www.mapbox.com/">Mapbox</a>',
		id: 'mapbox/streets-v11',
		tileSize: 512,
		zoomOffset: -1
	}).addTo(mymap);

var marker1= L.marker([55.01992,-1.6148124]).addTo(mymap);
var marker2= L.marker([54.97488,-1.5792821]).addTo(mymap);
var marker3= L.marker([55.012144,-1.6619448]).addTo(mymap);
var marker4= L.marker([54.998096,-1.6310662]).addTo(mymap);
var marker5= L.marker([55.028328,-1.6226135]).addTo(mymap);
var marker6= L.marker([54.991519832896,-1.6449024290645]).addTo(mymap);
var marker7= L.marker([54.988738797328,-1.6059979410377]).addTo(mymap);
var marker8= L.marker([55.03412193672,-1.613957424418]).addTo(mymap);
var marker9= L.marker([54.986794671832,-1.5486149504083]).addTo(mymap);
var marker10= L.marker([54.976200360928,-1.5897149147324]).addTo(mymap);
var marker11= L.marker([54.98963807476,-1.5396365601985]).addTo(mymap);
var marker12= L.marker([54.983582770096,-1.6746997482413]).addTo(mymap);
var marker13= L.marker([55.03180984484,-1.5952919066062]).addTo(mymap);
var marker14= L.marker([54.964847744224,-1.543005969047]).addTo(mymap);
var marker15= L.marker([54.975355244976,-1.6250246446572]).addTo(mymap);

//		.bindPopup("<b>picture 1</b><br />I am a popup.").closePopup();
//var popup = L.popup();
//~ function onMapClick(e) {
//~     popup
//~         .setLatLng(e.latlng)
//~         .setContent("You clicked the map at " )
//~         .openOn(mymap); 
//~     document.getElementById("demox").innerHTML="test";
//~ }

//~ function onMapClick11(e) {document.getElementById('photo').src='./images/'}
//~ function onMapClick12(e) {document.getElementById('photo').src='./images/'}
//~ function onMapClick13(e) {document.getElementById('photo').src='./images/DSC02566.JPG'}
//~ function onMapClick14(e) {document.getElementById('photo').src='./images/sDSC02602.JPG'}
//~ function onMapClick15(e) {
//~ document.getElementById('photo').src='./images/sDSC02631.JPG'
//~ }


//function onMapClick001(e) {document.getElementById('photo').src='./images/location_001.JPG'}

//function onMapClick15(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02631.JPG'; tmp.alt="St James' Park";document.getElementById('phototext').textContent="St James' Park 2020-12-13 Latitude=54.9754; Longitude=-1.6250"}
function onMapClick1(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02451.JPG'; tmp.alt="Junction Whitebridge Park, Swainby Close";document.getElementById('phototext').textContent="Junction Whitebridge Park, Swainby Close 2020-07-18 Latitude=55.0199; Longitude=-1.6148"}
function onMapClick2(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02455.JPG'; tmp.alt="North End Raby Street (Byker)";document.getElementById('phototext').textContent="North End Raby Street (Byker) 2020-07-20 Latitude=54.9749; Longitude=-1.5793"}
function onMapClick3(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02462.JPG'; tmp.alt="Airport industrial estate";document.getElementById('phototext').textContent="Airport industrial estate 2020-08-02 Latitude=55.0121; Longitude=-1.6619"}
function onMapClick4(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02472.JPG'; tmp.alt="Kenton Road";document.getElementById('phototext').textContent="Kenton Road 2020-08-09 Latitude=54.9981; Longitude=-1.6311"}
function onMapClick5(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02473.JPG'; tmp.alt="Great North Road";document.getElementById('phototext').textContent="Great North Road 2020-08-15 Latitude=55.0283; Longitude=-1.6226"}
function onMapClick6(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02476.JPG'; tmp.alt="Newcastle United Golf Course";document.getElementById('phototext').textContent="Newcastle United Golf Course 2020-08-16 Latitude=54.9915; Longitude=-1.6449"}
function onMapClick7(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02490.JPG'; tmp.alt="Alley behind Osborne Road";document.getElementById('phototext').textContent="Alley behind Osborne Road 2020-09-06 Latitude=54.9887; Longitude=-1.6060"}
function onMapClick8(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02494.JPG'; tmp.alt="Gosforth Park Racecourse";document.getElementById('phototext').textContent="Gosforth Park Racecourse 2020-09-13 Latitude=55.0341; Longitude=-1.6140"}
function onMapClick9(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02499.JPG'; tmp.alt="Stockwell Green";document.getElementById('phototext').textContent="Stockwell Green 2020-09-21 Latitude=54.9868; Longitude=-1.5486"}
function onMapClick10(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02512.JPG'; tmp.alt="Byker Bridge";document.getElementById('phototext').textContent="Byker Bridge 2020-09-27 Latitude=54.9762; Longitude=-1.5897"}
function onMapClick11(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02540.JPG'; tmp.alt="Portugal Place";document.getElementById('phototext').textContent="Portugal Place 2020-10-29 Latitude=54.9896; Longitude=-1.5396"}
function onMapClick12(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02543.JPG'; tmp.alt="West Road Crem";document.getElementById('phototext').textContent="West Road Crem 2020-11-02 Latitude=54.9836; Longitude=-1.6747"}
function onMapClick13(e) {var tmp=document.getElementById('photo'); tmp.src='./images/DSC02566.JPG'; tmp.alt="Gosforth Wood";document.getElementById('phototext').textContent="Gosforth Wood 2020-11-08 Latitude=55.0318; Longitude=-1.5953"}
function onMapClick14(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02602.JPG'; tmp.alt="Hadrian's Wall Path, Walker";document.getElementById('phototext').textContent="Hadrian's Wall Path, Walker 2020-11-29 Latitude=54.9648; Longitude=-1.5430"}
function onMapClick15(e) {var tmp=document.getElementById('photo'); tmp.src='./images/sDSC02631.JPG'; tmp.alt="St James' Park";document.getElementById('phototext').textContent="St James' Park 2020-12-13 Latitude=54.9754; Longitude=-1.6250"}

marker1.on('click', onMapClick1);
marker2.on('click', onMapClick2);
marker3.on('click', onMapClick3);
marker4.on('click', onMapClick4);
marker5.on('click', onMapClick5);
marker6.on('click', onMapClick6);
marker7.on('click', onMapClick7);
marker8.on('click', onMapClick8);
marker9.on('click', onMapClick9);
marker10.on('click', onMapClick10);
marker11.on('click', onMapClick11);
marker12.on('click', onMapClick12);
marker13.on('click', onMapClick13);
marker14.on('click', onMapClick14);
marker15.on('click', onMapClick15);
//marker001.on('click', 'document.getElementById("demo").innerHTML="test";')';
//https://leafletjs.com/examples/video-overlay/

</script>

<!--
see
https://www.w3schools.com/Js/tryit.asp?filename=tryjs_intro_lightbulb
-->


<figure>
<!--Note the figure tag, which gives more info-->
   <img id="photo" src="./images/location_001.JPG" alt="Some Trees">
<figcaption id="phototext">Junction of Whitebridge Park and Swainby Close. 18/07/2020. </figcaption>
</figure>
</main>
<footer>
Michael Firbank 2020
</footer>
</body>
</html>


