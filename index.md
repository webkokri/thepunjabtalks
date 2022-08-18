<!DOCTYPE html>
<html>
<head>

    <meta charset=utf-8 />
	<title>Live TV and Radio</title>


	<!-- Global site tag (gtag.js) - Google Analytics -->
	<!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
	new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
	j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
	'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
	})(window,document,'script','dataLayer','GTM-PDPN6F');</script>
	<!-- End Google Tag Manager -->

	<link href='https://fonts.googleapis.com/css?family=Berkshire+Swash|Dosis|Jockey+One' rel='stylesheet'>
	<link href='https://fonts.googleapis.com/css?family=Dosis' rel='stylesheet'>








	<link rel="icon" href="https://kunsh13.github.io/iptv/img/favicon_round.png">
    <link href="style.css" rel="stylesheet">

	<link href="https://unpkg.com/video.js@7/dist/video-js.min.css" rel="stylesheet">
	<link href="https://unpkg.com/@videojs/themes@1/dist/fantasy/index.css" rel="stylesheet">
	<link hrref="https://unpkg.com/@videojs/themes@1/dist/city/index.css" rel="stylesheet">

	<script src="https://unpkg.com/video.js/dist/video.js"></script>
	
	

	
</head>
<body>
	

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PDPN6F"
	height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
	<!-- End Google Tag Manager (noscript) -->
	
	<section>
	<div id="currentInfo"></div>
        <main>
            <div id="myvideo"></div>
        </main>
		<div class="aside">
			
			<ul class="searchUl">
				<li class="searchbutt"></li>
				<!--li class="fav">Faviourites</li-->
			</ul>
			<div class="searchbox hidden">
				<span>
					<input type="text" id="inptbx" placeholder="Search...">
					<!--button type="submit">Search</button-->
				</span>
				<ul id="filterList">
					<li>Welcome</li>
					<li>News</li>
					<li>Regional</li>
					<li>Lifestyle</li>
					<li>Music</li>
					<li>Movies</li>
					<li>International</li>	
					<li>Community Radio</li>
					<li>Internet Radio</li>
				</ul>
			</div>
		</div>
        <nav>
            <div id="pane"><ul id="menu"></ul></div>
        </nav>
    </section>
</body>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
<script src="script.js"></script>


	
<script type="module">
	// Import the functions you need from the SDKs you need
	import { initializeApp } from "https://www.gstatic.com/firebasejs/9.9.1/firebase-app.js";
	import { getAnalytics } from "https://www.gstatic.com/firebasejs/9.9.1/firebase-analytics.js";
	// TODO: Add SDKs for Firebase products that you want to use
	// https://firebase.google.com/docs/web/setup#available-libraries
  
	// Your web app's Firebase configuration
	// For Firebase JS SDK v7.20.0 and later, measurementId is optional
	const firebaseConfig = {
	  apiKey: "AIzaSyCMmyHTh3QvJRYnLhYGwSvezT_l1xG5ZeQ",
	  authDomain: "iptv-web.firebaseapp.com",
	  projectId: "iptv-web",
	  storageBucket: "iptv-web.appspot.com",
	  messagingSenderId: "1085908988091",
	  appId: "1:1085908988091:web:a34657cdfba7eca88e799e",
	  measurementId: "G-6V6SRF6GFF"
	};
  
	// Initialize Firebase
	const app = initializeApp(firebaseConfig);
	const analytics = getAnalytics(app);
  </script>

</html>


