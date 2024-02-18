<html>
	<head></head>
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
		This dataset includes information about accidents that occurred in 2022, with a range of casualty types, ages, and severities. The data may be used for analysis of traffic accidents and development of strategies to prevent them.

        <br />
        <p>Each row in the dataset contains a record for a single casualty, with the values in the columns providing information about the casualty and the accident. For example, the first row indicates that the casualty was a 46-year-old male pedestrian who was slightly injured in an accident that occurred in 2022. The casualty was not a road maintenance worker, and the accident occurred in the E01033378 LSOA.</p>    
    </body>
</html>