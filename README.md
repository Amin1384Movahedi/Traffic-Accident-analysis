<html>
	<body>
		<h2>Traffic Accident Dataset Description</h2>
		<p>This dataset contains information about traffic accidents, including details about the accidents, vehicles, and casualties involved. Each row in the dataset represents a single casualty, and there may be multiple casualties associated with a single accident.</p>
		<table border="1">
			<tbody>
				<tr>
					<th>Column Name</th>
					<th>Description</th>
				</tr>
				<tr>
					<td>status</td>
					<td>The validation status of the record (all records in this dataset are currently labeled as "Unvalidated").</td>
				</tr>
				<tr>
					<td>accident_index</td>
					<td>A unique identifier for each accident.</td>
				</tr>
				<tr>
					<td>accident_year</td>
					<td>The year in which the accident occurred.</td>
				</tr>
				<tr>
					<td>accident_reference</td>
					<td>Another identifier for each accident.</td>
				</tr>
				<tr>
					<td>vehicle_reference</td>
					<td>A unique reference number for each vehicle involved in the accident.</td>
				</tr>
				<tr>
					<td>casualty_reference</td>
					<td>The number of the casualty within the accident.</td>
				</tr>
				<tr>
					<td>casualty_class</td>
					<td>The type of casualty (e.g. driver, passenger, pedestrian).</td>
				</tr>
				<tr>
					<td>sex_of_casualty</td>
					<td>The gender of the casualty.</td>
				</tr>
				<tr>
					<td>age_of_casualty</td>
					<td>The age of the casualty at the time of the accident.</td>
				</tr>
				<tr>
					<td>age_band_of_casualty</td>
					<td>The age band of the casualty (e.g. 0-15, 16-24, etc.).</td>
				</tr>
				<tr>
					<td>casualty_severity</td>
					<td>The severity of the casualty's injuries (e.g. fatal, serious, slight).</td>
				</tr>
				<tr>
					<td>pedestrian_location</td>
					<td>The location of the casualty if they were a pedestrian (e.g. carriageway, footpath, etc.).</td>
				</tr>
				<tr>
					<td>pedestrian_movement</td>
					<td>The movement of the casualty if they were a pedestrian (e.g. crossing, standing, etc.).</td>
				</tr>
				<tr>
					<td>car_passenger</td>
					<td>Whether the casualty was a car passenger at the time of the accident.</td>
				</tr>
				<tr>
					<td>bus_or_coach_passenger</td>
					<td>Whether the casualty was a bus or coach passenger at the time of the accident.</td>
				</tr>
				<tr>
					<td>pedestrian_road_maintenance_worker</td>
					<td>Whether the casualty was a road maintenance worker at the time of the accident.</td>
				</tr>
				<tr>
					<td>casualty_type</td>
					<td>The type of casualty (e.g. driver, passenger, pedestrian).</td>
				</tr>
				<tr>
					<td>casualty_home_area_type</td>
					<td>The type of area where the casualty resides.</td>
				</tr>
				<tr>
					<td>casualty_imd_decile</td>
					<td>The Index of Multiple Deprivation (IMD) decile for the casualty's area of residence.</td>
				</tr>
				<tr>
					<td>lsoa\_of\_casualty</td>
					<td>The Lower Layer Super Output Area (LSOA) code for the casualty's area of residence.</td>
				</tr>
			</tbody>
		</table>
		<p>This dataset includes information about accidents that occurred in 2022, with a range of casualty types, ages, and severities. The data may be used for analysis of traffic accidents and development of strategies to prevent them.</p><br />
        <p>Each row in the dataset contains a record for a single casualty, with the values in the columns providing information about the casualty and the accident. For example, the first row indicates that the casualty was a 46-year-old male pedestrian who was slightly injured in an accident that occurred in 2022. The casualty was not a road maintenance worker, and the accident occurred in the E01033378 LSOA.</p>
		<br />
		<p>Let's check out the frequency of unique values of some of dataset columns.</p> 
		<table>
			<thead>
				<tr>
					<th>Variable</th>
					<th>Unique Value</th>
					<th>Frequency</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<td>status</td>
					<td>'Unvalidated'</td>
					<td>61352</td>
				</tr>
				<tr>
					<td>accident year</td>
					<td>'2022'</td>
					<td>61352</td>
				</tr>
				<tr>
					<td>vehicle reference</td>
					<td>'2'</td>
					<td>23337</td>
				</tr>
				<tr>
					<td></td>
					<td>'1'</td>
					<td>36255</td>
				</tr>
				<tr>
					<td></td>
					<td>'3'</td>
					<td>1427</td>
				</tr>
				<tr>
					<td></td>
					<td>'4'</td>
					<td>227</td>
				</tr>
				<tr>
					<td></td>
					<td>'5'</td>
					<td>71</td>
				</tr>
				<tr>
					<td></td>
					<td>'8'</td>
					<td>4</td>
				</tr>
				<tr>
					<td></td>
					<td>'6'</td>
					<td>19</td>
				</tr>
				<tr>
					<td></td>
					<td>'9'</td>
					<td>3</td>
				</tr>
				<tr>
					<td></td>
					<td>'227'</td>
					<td>1</td>
				</tr>
				<tr>
					<td></td>
					<td>'7'</td>
					<td>7</td>
				</tr>
				<tr>
					<td></td>
					<td>'61'</td>
					<td>1</td>
				</tr>
				<tr>
					<td>casualty reference</td>
					<td>'1'</td>
					<td>47792</td>
				</tr>
				<tr>
					<td></td>
					<td>'3'</td>
					<td>2795</td>
				</tr>
				<tr>
					<td></td>
					<td>'2'</td>
					<td>9305</td>
				</tr>
				<tr>
					<td></td>
					<td>'4'</td>
					<td>934</td>
				</tr>
				<tr>
					<td></td>
					<td>'5'</td>
					<td>325</td>
				</tr>
				<tr>
					<td></td>
					<td>'6'</td>
					<td>100</td>
				</tr>
				<tr>
					<td></td>
					<td>'7'</td>
					<td>37</td>
				</tr>
				<tr>
					<td></td>
					<td>'8'</td>
					<td>15</td>
				</tr>
				<tr>
					<td></td>
					<td>'9'</td>
					<td>11</td>
				</tr>
				<tr>
					<td></td>
					<td>'10'</td>
					<td>10</td>
				</tr>
				<tr>
					<td></td>
					<td>'11'</td>
					<td>7</td>
				</tr>
				<tr>
					<td></td>
					<td>'12'</td>
					<td>6</td>
				</tr>
				<tr>
					<td></td>
					<td>'14'</td>
					<td>4</td>
				</tr>
				<tr>
					<td></td>
					<td>'15'</td>
					<td>3</td>
				</tr>
				<tr>
					<td></td>
					<td>'13'</td>
					<td>4</td>
				</tr>
				<tr>
					<td></td>
					<td>'16'</td>
					<td>2</td>
				</tr>
				<tr>
					<td></td>
					<td>'22'</td>
					<td>1</td>
				</tr>
				<tr>
					<td></td>
					<td>'148'</td>
					<td>1</td>
				</tr>
				<tr>
					<td>casualty class</td>
					<td>'1'</td>
					<td>40702</td>
				</tr>
				<tr>
					<td></td>
					<td>'2'</td>
					<td>11710</td>
				</tr>
				<tr>
					<td></td>
					<td>'3'</td>
					<td>8940</td>
				</tr>
				<tr>
					<td>sex of casualty</td>
					<td>'2'</td>
					<td>23442</td>
				</tr>
				<tr>
					<td></td>
					<td>'1'</td>
					<td>37452</td>
				</tr>
				<tr>
					<td></td>
					<td>'-1'</td>
					<td>448</td>
				</tr>
				<tr>
					<td></td>
					<td>'9'</td>
					<td>10</td>
				</tr>
				<tr>
					<td>age band of casualty</td>
					<td>'8'</td>
					<td>7842</td>
				</tr>
				<tr>
					<td></td>
					<td>'6'</td>
					<td>12872</td>
				</tr>
				<tr>
					<td></td>
					<td>'9'</td>
					<td>5842</td>
				</tr>
				<tr>
					<td></td>
					<td>'11'</td>
					<td>2442</td>
				</tr>
				<tr>
					<td></td>
					<td>'4'</td>
					<td>6328</td>
				</tr>
				<tr>
					<td></td>
					<td>'10'</td>
					<td>2982</td>
				</tr>
				<tr>
					<td></td>
					<td>'3'</td>
					<td>2985</td>
				</tr>
				<tr>
					<td></td>
					<td>'7'</td>
					<td>9407</td>
				</tr>
				<tr>
					<td></td>
					<td>'2'</td>
					<td>1575</td>
				</tr>
				<tr>
					<td></td>
					<td>'5'</td>
					<td>6730</td>
				</tr>
				<tr>
					<td></td>
					<td>'1'</td>
					<td>997</td>
				</tr>
				<tr>
					<td></td>
					<td>'-1'</td>
					<td>1350</td>
				</tr>
				<tr>
					<td>casualty severity</td>
					<td>'3'</td>
					<td>48831</td>
				</tr>
				<tr>
					<td></td>
					<td>'2'</td>
					<td>11731</td>
				</tr>
				<tr>
					<td></td>
					<td>'1'</td>
					<td>790</td>
				</tr>
				<tr>
					<td>pedestrian location</td>
					<td>'0'</td>
					<td>52412</td>
				</tr>
				<tr>
					<td></td>
					<td>'5'</td>
					<td>3351</td>
				</tr>
				<tr>
					<td></td>
					<td>'10'</td>
					<td>869</td>
				</tr>
				<tr>
					<td></td>
					<td>'9'</td>
					<td>953</td>
				</tr>
				<tr>
					<td></td>
					<td>'6'</td>
					<td>1047</td>
				</tr>
				<tr>
					<td></td>
					<td>'8'</td>
					<td>565</td>
				</tr>
				<tr>
					<td></td>
					<td>'1'</td>
					<td>1472</td>
				</tr>
				<tr>
					<td></td>
					<td>'4'</td>
					<td>546</td>
				</tr>
				<tr>
					<td></td>
					<td>'7'</td>
					<td>63</td>
				</tr>
				<tr>
					<td></td>
					<td>'3'</td>
					<td>32</td>
				</tr>
				<tr>
					<td></td>
					<td>'2'</td>
					<td>42</td>
				</tr>
				<tr>
					<td>pedestrian movement</td>
					<td>'0'</td>
					<td>52411</td>
				</tr>
				<tr>
					<td></td>
					<td>'2'</td>
					<td>429</td>
				</tr>
				<tr>
					<td></td>
					<td>'9'</td>
					<td>2567</td>
				</tr>
				<tr>
					<td></td>
					<td>'8'</td>
					<td>224</td>
				</tr>
				<tr>
					<td></td>
					<td>'3'</td>
					<td>1784</td>
				</tr>
				<tr>
					<td></td>
					<td>'1'</td>
					<td>2847</td>
				</tr>
				<tr>
					<td></td>
					<td>'7'</td>
					<td>226</td>
				</tr>
				<tr>
					<td></td>
					<td>'5'</td>
					<td>482</td>
				</tr>
				<tr>
					<td></td>
					<td>'4'</td>
					<td>322</td>
				</tr>
				<tr>
					<td></td>
					<td>'6'</td>
					<td>60</td>
				</tr>
				<tr>
					<td>car passenger</td>
					<td>'0'</td>
					<td>51219</td>
				</tr>
				<tr>
					<td></td>
					<td>'2'</td>
					<td>3582</td>
				</tr>
				<tr>
					<td></td>
					<td>'1'</td>
					<td>6170</td>
				</tr>
				<tr>
					<td></td>
					<td>'-1'</td>
					<td>314</td>
				</tr>
				<tr>
					<td></td>
					<td>'9'</td>
					<td>67</td>
				</tr>
				<tr>
					<td>bus or coach passenger</td>
					<td>'0'</td>
					<td>60471</td>
				</tr>
				<tr>
					<td></td>
					<td>'2'</td>
					<td>59</td>
				</tr>
				<tr>
					<td></td>
					<td>'4'</td>
					<td>494</td>
				</tr>
				<tr>
					<td></td>
					<td>'1'</td>
					<td>32</td>
				</tr>
				<tr>
					<td></td>
					<td>'3'</td>
					<td>264</td>
				</tr>
				<tr>
					<td></td>
					<td>'-1'</td>
					<td>23</td>
				</tr>
				<tr>
					<td></td>
					<td>'9'</td>
					<td>9</td>
				</tr>
				<tr>
					<td>pedestrian road maintenance worker</td>
					<td>'0'</td>
					<td>60117</td>
				</tr>
			</tbody>
		</table><br />
		<p>Because the "status" and "accident year" columns has just one value we can just remove them from our dataset.</p><br />
		<p>Now let's check out the correlation between the variables of the dataset.</p>
		<img src="https://github.com/Amin1384Movahedi/Traffic-Accident-analysis/blob/main/assets/correlation.png"></img>
		<br />
		<h2> Let's do some analysis on the dataset.</h2>
		<p>as we can see here, the severity of the casualty's injuries for Male is so higher than Female.
		<img src="https://github.com/Amin1384Movahedi/Traffic-Accident-analysis/blob/main/assets/casualty_severity_by_gender.png"></img>
		<br />
		<p>Now, based of the relationship between casualty severity and casualty class, it's abviuse the Driver has the most injuries, after that passenger and then pedestrian.
		<img src="https://github.com/Amin1384Movahedi/Traffic-Accident-analysis/blob/main/assets/casualty_severity_by_casualty_class.png"></img>
		<br />
		<p>The Urban Home Area Type has the most casualty severity injuries and the Semi-Urban Area Type has lower casualty severity.
		<img src="https://github.com/Amin1384Movahedi/Traffic-Accident-analysis/blob/main/assets/casualty_severity_by_home_area_type.png"></img>
		<br />
		<p>From Age of Casualty Distribution with is a left-skewed distribution, we can find out the most casualty is for 19 years old and by increasing the age, the casualty is decreasing.
		<img src="https://github.com/Amin1384Movahedi/Traffic-Accident-analysis/blob/main/assets/age_of_casualty_distribution.png"></img>
    </body>
</html>