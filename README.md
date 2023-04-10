# MMGraphSLAM_Dataset
This dataset includes two data packets: IMU and mmWave Radar. Each data packet is divided into 5 scenarios, with the specific content as follows:
## IMU data:
	XX-XX_ACCELEROMETER_tag_walk_flat:
		timestamp, x, y, z, time.
	XX-XX_GYROSCOPE_tag_walk_flat:
		timestamp, x, y, z, time.
	XX-XX_MAGNETICFIELD_tag_walk_flat:
		timestamp, x, y, z, time.

## mmWave Radar data:

	time: Greenwich Mean Time (GMT), 19 bit timestamp.
	x: The x-coordinate of a point cloud in one frame (m).
	y: The y-coordinate of a point cloud in one frame (m).
	z: The z-coordinate of a point cloud in one frame (m).
	velocity: The velocity of point clouds relative to radar (m/s). 
	numObj: The number of detected points. 
	rangearray: Range in intensity-range information.
	Relative Power: Intensity in intensity-range information. 
