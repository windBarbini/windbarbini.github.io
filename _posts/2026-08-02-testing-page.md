---
layout: post
title:  "Hodograph Cross-Stitch Pattern Maker"
date:   2026-08-02-18T00:00:00-00:00
author: Emily Barbini
cover: "/assets/gis/hodo_emb/hodo_emb_header.jpg"
categories: art
tags: Cross-Stitch
---

This page is a work in progress!

<hr>

Select from the preferences below to generate an editable cross-stitch pattern from an observed weather balloon hodograph!
<i>(Please note that this generator uses soundings from the University of Wyoming's radiosonde archive, so some soundings might be missing.)</i>

<hr>

<h1>Step 1.</h1> <h3>Select your Preferences</h3>


<label for="locations">Select a Location:</label>
	<select id="locations" name="location">
                <option value ="70273">Anchorage, AK</option>
                <option value ="70398">Annette Island, AK</option>
                <option value ="70026">Barrow, AK</option>
                <option value ="70219">Bethel, AK</option>
                <option value ="70316">Cold Bay, AK</option>
                <option value ="70261">Fairbanks, AK</option>
                <option value ="70326">King Salmon, AK</option>
                <option value ="70350">Kodiak, AK</option>
                <option value ="70133">Kotzebue, AK</option>
                <option value ="70231">McGrath, AK</option>
                <option value ="70200">Nome, AK</option>
                <option value ="70414">Shemya Island, AK</option>
                <option value ="70308">St. Paul Islands, AK</option>
                <option value ="70361">Yakutat, AK</option>
                <option value ="72230">Birmingham, AL</option>
                <option value ="72340">Little Rock, AR</option>
                <option value ="72376">Flagstaff, AZ</option>
                <option value ="72273">Fort Huachuca, AZ</option>
                <option value ="74626">Phoenix, AZ</option>
                <option value ="72274">Tucson, AZ</option>
                <option value ="72280">Yuma, AZ</option>
                <option value ="74004">Yuma Proving Ground, AZ</option>
                <option value ="72481">Castle AFB, CA</option>
                <option value ="74612">China Lake NAF, CA</option>
                <option value ="72381">Edwards AFB, CA</option>
                <option value ="72493">Oakland, CA</option>
                <option value ="72293">San Diego, CA</option>
                <option value ="72393">Vandenberg AFB, CA</option>
                <option value ="72468">Colorado Springs, CO</option>
                <option value ="72469">Denver, CO</option>
                <option value ="72476">Grand Junction, CO</option>
                <option value ="74796">Avon Park Gunnery Range, FL</option>
                <option value ="74794">Cape Kennedy, FL</option>
                <option value ="72224">Cape San Blas, FL</option>
                <option value ="72206">Jacksonville, FL</option>
                <option value ="72201">Key West, FL</option>
                <option value ="72202">Miami, FL</option>
                <option value ="72214">Tallahassee, FL</option>
                <option value ="72210">Tampa Bay, FL</option>
                <option value ="72221">Valparaiso, FL</option>
                <option value ="72225">Fort Benning, GA</option>
                <option value ="72209">Fort Stewart, GA</option>
                <option value ="74780">Fort Stewart Reservation, GA</option>
                <option value ="72215">Peachtree City, GA</option>
                <option value ="74455">Quad City, IA</option>
                <option value ="72681">Boise, ID</option>
                <option value ="74560">Lincoln, IL</option>
                <option value ="72533">Fort Wayne, IN</option>
                <option value ="72451">Dodge City, KS</option>
                <option value ="72455">Fort Riley, KS</option>
                <option value ="72456">Topeka, KS</option>
                <option value ="72424">Fort Knox, KY</option>
                <option value ="74755">Claiborne Range AFS, LA</option>
                <option value ="72240">Lake Charles, LA</option>
                <option value ="72248">Shreveport, LA</option>
                <option value ="72233">Slidell, LA</option>
                <option value ="74494">Chatham, MA</option>
                <option value ="74002">Aberdeen Proving Grounds, MD</option>
                <option value ="72712">Caribou, ME</option>
                <option value ="74389">Gray, ME</option>
                <option value ="72634">Gaylord, MI</option>
                <option value ="72632">White Lake, MI</option>
                <option value ="72649">Chanhassen, MN</option>
                <option value ="72747">International Falls, MN</option>
                <option value ="72440">Springfield, MO</option>
                <option value ="72235">Jackson, MS</option>
                <option value ="72768">Glasgow, MT</option>
                <option value ="72776">Great Falls, MT</option>
                <option value ="72317">Greensboro, NC</option>
                <option value ="72305">Newport, NC</option>
                <option value ="72303">Pope AFB, NC</option>
                <option value ="72764">Bismarck, ND</option>
                <option value ="72562">North Platte, NE</option>
                <option value ="72558">Valley, NE</option>
                <option value ="72365">Albuquerque, NM</option>
                <option value ="72268">Roswell, NM</option>
                <option value ="72364">Santa Teresa, NM</option>
                <option value ="72269">White Sands, NM</option>
                <option value ="72582">Elko, NV</option>
                <option value ="72388">Las Vegas, NV</option>
                <option value ="72387">Mercury, NV</option>
                <option value ="72489">Reno, NV</option>
                <option value ="72518">Albany County Airport, NY</option>
                <option value ="72528">Buffalo, NY</option>
                <option value ="72501">Upton, NY</option>
                <option value ="72426">Wilmington, OH</option>
                <option value ="72355">Fort Sill, OK</option>
                <option value ="74646">Lamont, OK</option>
                <option value ="72357">Norman, OK</option>
                <option value ="72597">Medford, OR</option>
                <option value ="72694">Salem, OR</option>
                <option value ="72520">Pittsburgh, PA</option>
                <option value ="72514">Williamsport, PA</option>
                <option value ="72208">Charleston, SC</option>
                <option value ="72659">Aberdeen, SD</option>
                <option value ="72662">Rapid City, SD</option>
                <option value ="72327">Nashville, TN</option>
                <option value ="72363">Amarillo, TX</option>
                <option value ="72250">Brownsville, TX</option>
                <option value ="72251">Corpus Christi, TX</option>
                <option value ="72261">Del Rio, TX</option>
                <option value ="72257">Fort Hood, TX</option>
                <option value ="72249">Fort Worth, TX</option>
                <option value ="72265">Midland, TX</option>
                <option value ="74003">Dugway Proving Grounds, UT</option>
                <option value ="72572">Salt Lake City, UT</option>
                <option value ="72318">Blacksburg, VA</option>
                <option value ="72403">Sterling, VA</option>
                <option value ="72402">Wallops Island, VA</option>
                <option value ="72797">Quillayute, WA</option>
                <option value ="72786">Spokane, WA</option>
                <option value ="72645">Green Bay, WI</option>
                <option value ="72672">Riverton, WY</option>
	</select>
		

<label for="dates">Select a Date:</label>
	<input type="date" id="date">


<label for="times">Select an Hour (in UTC/Zulu):</label>
	<select id="times" name="time">
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

<label for="borders">Would you like an Outline?:</label>
	<select id="borders" name="border">
		<option value="yes">Yes</option>
		<option value="no">No</option>
	</select>


<hr>

<h1>Step 2.</h1> <h3>Generate the Pattern</h3>
"Generate Pattern" button goes here...
Pattern and reference(s) should appear below:


<hr>

<h1>Step 3.</h1> <h3>Download the pattern, edit as needed, and sew!</h3>

<hr>

<h1>Pixel Art-Pattern Translations</h1>

<hr>

<h1>Tutorial</h1>

<hr>

<h1>Pattern Gallery</h1>

<hr>

<h1>Credits</h1>