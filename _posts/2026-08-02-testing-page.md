---
layout: post
title:  "Hodograph Cross-Stitch Pattern Maker"
date:   2026-08-02-18T00:00:00-00:00
author: Emily Barbini
cover: "/assets/gis/hodo_emb/hodo_emb_header.jpg"
categories: art
tags: Cross-Stitch
---

<center><h1>This page is a work in progress!</h1></center>

<hr>

<center>Select from the preferences below to generate an editable cross-stitch pattern from an observed US weather balloon hodograph!</center>
<br>
<center><i>(Please note that this generator uses soundings from the University of Wyoming's radiosonde archive, so some soundings might be missing.)</i></center>

<hr>

<h1>Step 1. Select your Preferences</h1>

<style>
	optgroup {
		font-weight: bold;
		color: black;
	}
	option {
		font-weight: normal;
		color: black;
	}
</style>
		
<label for="locations">Select a Location:</label>
	<select id="locations" name="location">
	
            <optgroup label="Alabama">
                <option value ="72230">Birmingham</option>
            </optgroup>
            <optgroup label="Alaska">
                <option value ="70273">Anchorage</option>
                <option value ="70398">Annette Island</option>
                <option value ="70026">Barrow</option>
                <option value ="70219">Bethel</option>
                <option value ="70316">Cold Bay</option>
                <option value ="70261">Fairbanks</option>
                <option value ="70326">King Salmon</option>
                <option value ="70350">Kodiak</option>
                <option value ="70133">Kotzebue</option>
                <option value ="70231">Mcgrath</option>
                <option value ="70200">Nome</option>
                <option value ="70414">Shemya Island</option>
                <option value ="70308">St. Paul Islands</option>
                <option value ="70361">Yakutat</option>
            </optgroup>
            <optgroup label="Arizona">
                <option value ="72376">Flagstaff</option>
                <option value ="72273">Fort Huachuca</option>
                <option value ="74626">Phoenix</option>
                <option value ="72274">Tucson</option>
                <option value ="72280">Yuma</option>
                <option value ="74004">Yuma Proving Ground</option>
            </optgroup>
            <optgroup label="Arkansas">
                <option value ="72340">Little Rock</option>
            </optgroup>
            <optgroup label="California">
                <option value ="72481">Castle Afb</option>
                <option value ="74612">China Lake Naf</option>
                <option value ="72381">Edwards Afb</option>
                <option value ="72493">Oakland</option>
                <option value ="72293">San Diego</option>
                <option value ="72393">Vandenberg Afb</option>
            </optgroup>
            <optgroup label="Colorado">
                <option value ="72468">Colorado Springs</option>
                <option value ="72469">Denver</option>
                <option value ="72476">Grand Junction</option>
            </optgroup>
            <optgroup label="Florida">
                <option value ="74796">Avon Park Gunnery Range</option>
                <option value ="74794">Cape Kennedy</option>
                <option value ="72224">Cape San Blas</option>
                <option value ="72206">Jacksonville</option>
                <option value ="72201">Key West</option>
                <option value ="72202">Miami</option>
                <option value ="72214">Tallahassee</option>
                <option value ="72210">Tampa Bay</option>
                <option value ="72221">Valparaiso</option>
            </optgroup>
            <optgroup label="Georgia">
                <option value ="72225">Fort Benning</option>
                <option value ="72209">Fort Stewart</option>
                <option value ="74780">Fort Stewart Reservation</option>
                <option value ="72215">Peachtree City</option>
            </optgroup>
            <optgroup label="Idaho">
                <option value ="72681">Boise</option>
            </optgroup>
            <optgroup label="Illinois">
                <option value ="74560">Lincoln</option>
            </optgroup>
            <optgroup label="Indiana">
                <option value ="72533">Fort Wayne</option>
            </optgroup>
            <optgroup label="Iowa">
                <option value ="74455">Quad City</option>
            </optgroup>
            <optgroup label="Kansas">
                <option value ="72451">Dodge City</option>
                <option value ="72455">Fort Riley</option>
                <option value ="72456">Topeka</option>
            </optgroup>
            <optgroup label="Kentucky">
                <option value ="72424">Fort Knox</option>
            </optgroup>
            <optgroup label="Louisiana">
                <option value ="74755">Claiborne Range Afs</option>
                <option value ="72240">Lake Charles</option>
                <option value ="72248">Shreveport</option>
                <option value ="72233">Slidell</option>
            </optgroup>
            <optgroup label="Maine">
                <option value ="72712">Caribou</option>
                <option value ="74389">Gray</option>
            </optgroup>
            <optgroup label="Maryland">
                <option value ="74002">Aberdeen Proving Grounds</option>
            </optgroup>
            <optgroup label="Massachusetts">
                <option value ="74494">Chatham</option>
            </optgroup>
            <optgroup label="Michigan">
                <option value ="72634">Gaylord</option>
                <option value ="72632">White Lake</option>
            </optgroup>
            <optgroup label="Minnesota">
                <option value ="72649">Chanhassen</option>
                <option value ="72747">International Falls</option>
            </optgroup>
            <optgroup label="Mississippi">
                <option value ="72235">Jackson</option>
            </optgroup>
            <optgroup label="Missouri">
                <option value ="72440">Springfield</option>
            </optgroup>
            <optgroup label="Montana">
                <option value ="72768">Glasgow</option>
                <option value ="72776">Great Falls</option>
            </optgroup>
            <optgroup label="North Carolina">
                <option value ="72317">Greensboro</option>
                <option value ="72305">Newport</option>
                <option value ="72303">Pope Afb</option>
            </optgroup>
            <optgroup label="North Dakota">
                <option value ="72764">Bismarck</option>
            </optgroup>
            <optgroup label="Nebraska">
                <option value ="72562">North Platte</option>
                <option value ="72558">Valley</option>
            </optgroup>
            <optgroup label="New Mexico">
                <option value ="72365">Albuquerque</option>
                <option value ="72268">Roswell</option>
                <option value ="72364">Santa Teresa</option>
                <option value ="72269">White Sands</option>
            </optgroup>
            <optgroup label="New York">
                <option value ="72518">Albany County Airport</option>
                <option value ="72528">Buffalo</option>
                <option value ="72501">Upton</option>
            </optgroup>
            <optgroup label="Nevada">
                <option value ="72582">Elko</option>
                <option value ="72388">Las Vegas</option>
                <option value ="72387">Mercury</option>
                <option value ="72489">Reno</option>
            </optgroup>
            <optgroup label="Ohio">
                <option value ="72426">Wilmington</option>
            </optgroup>
            <optgroup label="Oklahoma">
                <option value ="72355">Fort Sill</option>
                <option value ="74646">Lamont</option>
                <option value ="72357">Norman</option>
            </optgroup>
            <optgroup label="Oregon">
                <option value ="72597">Medford</option>
                <option value ="72694">Salem</option>
            </optgroup>
            <optgroup label="Pennsylvania">
                <option value ="72520">Pittsburgh</option>
                <option value ="72514">Williamsport</option>
            </optgroup>
            <optgroup label="South Carolina">
                <option value ="72208">Charleston</option>
            </optgroup>
            <optgroup label="South Dakota">
                <option value ="72659">Aberdeen</option>
                <option value ="72662">Rapid City</option>
            </optgroup>
            <optgroup label="Tennessee">
                <option value ="72327">Nashville</option>
            </optgroup>
            <optgroup label="Texas">
                <option value ="72363">Amarillo</option>
                <option value ="72250">Brownsville</option>
                <option value ="72251">Corpus Christi</option>
                <option value ="72261">Del Rio</option>
                <option value ="72257">Fort Hood</option>
                <option value ="72249">Fort Worth</option>
                <option value ="72265">Midland</option>
            </optgroup>
            <optgroup label="Utah">
                <option value ="74003">Dugway Proving Grounds</option>
                <option value ="72572">Salt Lake City</option>
            </optgroup>
            <optgroup label="Virginia">
                <option value ="72318">Blacksburg</option>
                <option value ="72403">Sterling</option>
                <option value ="72402">Wallops Island</option>
            </optgroup>
            <optgroup label="Washington">
                <option value ="72797">Quillayute</option>
                <option value ="72786">Spokane</option>
            </optgroup>
            <optgroup label="Wisconsin">
                <option value ="72645">Green Bay</option>
            </optgroup>
            <optgroup label="Wyoming">
                <option value ="72672">Riverton</option>
	    </optgroup>
	</select>
		

<label for="dates">Select a Date:</label>
	<input type="date" id="date">


<label for="times">Select an Hour (in UTC/Zulu):</label>
	<select id="times" name="time" size="15" style="width:250px;">
		<option value="00">00</option>
		<option value="01">01</option>
		<option value="02">02</option>
		<option value="03">03</option>
		<option value="04">04</option>
		<option value="05">05</option>
		<option value="06">06</option>
		<option value="07">07</option>
		<option value="08">08</option>
		<option value="09">09</option>
		<option value="10">10</option>
		<option value="11">11</option>
		<option value="12">12</option>
		<option value="13">13</option>
		<option value="14">14</option>
		<option value="15">15</option>
		<option value="16">16</option>
		<option value="17">17</option>
		<option value="18">18</option>
		<option value="19">19</option>
		<option value="20">20</option>
		<option value="21">21</option>
		<option value="22">22</option>
		<option value="23">23</option>
	</select>

<label for="themes">Select a Theme:</label>
	<select id="themes" name="theme">
		<option value="light">Light</option>
		<option value="dark">Dark</option>
	</select>

<label for="styles">Select a Style:</label>
	<select id="styles" name="style">
		<option value="spc">SPC</option>
		<option value="spy">SounderPy</option>
		<option value="sharppy">SHARPpy</option>
	</select>

<label for="backgrounds">Select a Background:</label>
	<select id="backgrounds" name="background">
		<option value="coordinateplane">Coordinate Plane</option>
		<option value="blank">Blank</option>
	</select>

<label for="frames">Select the Framing Type:</label>
	<select id="frames" name="framing">
		<option value="embroideryhoop">Embroidery Hoop</option>
		<option value="pictureframe">Picture Frame</option>
	</select>

<label for="titles">Would You like to Display the Date and Station?</label>
	<select id="titles" name="title">
		<option value="">Select a Framing type first</option>
	</select>

<script>
	function updateCustomization() {
		const frame = document.getElementById("frames").value;
		const title = document.getElementById("titles");
		title.innerHTML = "";
	
		const titleoptions = frame === "pictureframe"
			? [
				{value: "yes", text: "Yes"},
				{value: "no", text: "No"}
			  ]
			: [
				{value: "no", text: "No"}
			  ];

		titleoptions.forEach(option => {
			const choice = document.createElement("option");
			choice.value = option.value;
			choice.textContent = option.text;
			title.appendChild(choice);
		});
	}

	document.getElementById("frames").addEventListener("change", updateCustomization);
	updateCustomization(); 			
</script>

<label for="borders">Would you like to add an Outline?</label>
	<select id="borders" name="border">
		<option value="yes">Yes</option>
		<option value="no">No</option>
	</select>

<hr>

<h1>Step 2. Generate the Pattern</h1>
<style>
	button {
		background-color: #87DDFF;
		border: none;
		color: white;
		padding: 15px 32px;
		text-align: center;
		text-decoration: none;
		display: inline-block;
		font-size: 16px;
		margin: 0 auto;
		cursor: pointer;
	}
</style>
<center><button>Generate Pattern!</button></center>
<br>
<center><i>("Generate Pattern" button does not work yet.)</i></center>

<hr>

<h1>Step 3. Edit the Pattern as Needed, and Sew!</h1>
<center><i>Pattern and reference(s) should appear here once the code is connected with the webpage!</i></center>
<br>
<hr>

<h1>Pixel Art-Pattern Translations</h1>

<hr>

<h1>Tutorial</h1>

<hr>

<h1>Pattern Gallery</h1>

<hr>

<h1>Credits</h1>