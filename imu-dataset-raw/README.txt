**** Inertial Measurement Unit Fall Detection Dataset (IMU Dataset)****
IMU Dataset is a dataset devised to benchmark fall detection and prediction algorithms based on acceleration, angular velocity and magnetic fields of body-worn APDM Opal IMU sensors at 7 body locations (right ankle, left ankle, right thigh, left thigh, head, sternum, and waist).

DATA DESCRIPTION:
The dataset contains data of 10 subjects, healthy young adults with age ranging from 22 to 32 years (Mean = 26.6 years, SD = 2.8 years). All subjects were students at Simon Fraser University and recruited through advertisements and flyers on university notice boards. The experiment protocol was approved by the Research Ethics Committee at Simon Fraser University, and all subjects provided written consent.

Each subject underwent 60 trials (15 Activity of Daily Livings - ADLs, 24 Falls, and 15 Near Falls). The experiment environment and scenario were designed to generate many activity primitives in a realistic manner. During all fall and near-fall trials, the floor was covered with a 30-cm-thick gymnasium mattress of the type used to cushion falls in athletic activities. We also inserted a 13-cm top layer of high-density ethylene vinyl acetate foam, so the composite structure was stiff enough to allow for stable standing and walking, but soft enough to reduce the forces during impact to a safe level. For Fall events, we conducted training sessions with each subject, where we displayed one representative video for each real-life fall and instructed subjects to fall in a fashion similar to that observed in the older adult in the video. For near-fall and ADL events, we did not present subjects with videos, but instructed them to execute non-fall scenarios as if there were frailer older adults.

Folder structure of the dataset:
- Each folder (sub1, sub2, ..., sub10) corresponds to one subject.
- Each subfolder (ADLs, Falls, Near_Falls) corresponds to ADL, Fall or Near Fall trials
- Each file (.xlsx) contains sensor data of one trial. The columns are described below.

DATA COLUMNS:
- Time: timestamp (the number of microseconds that has elapsed since 1 January 1970), unit = uS
- r.ankle Acceleration X (m/s^2): Right ankle's acceleration along X axis, unit = m/s^2
- r.ankle Acceleration Y (m/s^2): Right ankle's acceleration along Y axis, unit = m/s^2
- r.ankle Acceleration Z (m/s^2): Right ankle's acceleration along Z axis, unit = m/s^2
- r.ankle Angular Velocity X (rad/s): Right ankle's angular velocity along X axis, unit = rad/s
- r.ankle Angular Velocity Y (rad/s): Right ankle's angular velocity along Y axis, unit = rad/s
- r.ankle Angular Velocity Z (rad/s): Right ankle's angular velocity along Z axis, unit = rad/s
- r.ankle Magnetic Field X (uT): Right ankle's magnetic field along X axis, unit = uT
- r.ankle Magnetic Field Y (uT): Right ankle's magnetic field along Y axis, unit = uT
- r.ankle Magnetic Field Z (uT): Right ankle's magnetic field along Z axis, unit = uT
- l.ankle Acceleration X (m/s^2): Left ankle's acceleration along X axis, unit = m/s^2
- l.ankle Acceleration Y (m/s^2): Left ankle's acceleration along Y axis, unit = m/s^2
- l.ankle Acceleration Z (m/s^2): Left ankle's acceleration along Z axis, unit = m/s^2
- l.ankle Angular Velocity X (rad/s): Left ankle's angular velocity along X axis, unit = rad/s
- l.ankle Angular Velocity Y (rad/s): Left ankle's angular velocity along Y axis, unit = rad/s
- l.ankle Angular Velocity Z (rad/s): Left ankle's angular velocity along Z axis, unit = rad/s
- l.ankle Magnetic Field X (uT): Left ankle's magnetic field along X axis, unit = uT
- l.ankle Magnetic Field Y (uT): Left ankle's magnetic field along Y axis, unit = uT
- l.ankle Magnetic Field Z (uT): Left ankle's magnetic field along Z axis, unit = uT
- r.thigh Acceleration X (m/s^2): Right thigh's acceleration along X axis, unit = m/s^2
- r.thigh Acceleration Y (m/s^2): Right thigh's acceleration along Y axis, unit = m/s^2
- r.thigh Acceleration Z (m/s^2): Right thigh's acceleration along Z axis, unit = m/s^2
- r.thigh Angular Velocity X (rad/s): Right thigh's angular velocity along X axis, unit = rad/s
- r.thigh Angular Velocity Y (rad/s): Right thigh's angular velocity along Y axis, unit = rad/s
- r.thigh Angular Velocity Z (rad/s): Right thigh's angular velocity along Z axis, unit = rad/s
- r.thigh Magnetic Field X (uT): Right thigh's magnetic field along X axis, unit = uT
- r.thigh Magnetic Field Y (uT): Right thigh's magnetic field along Y axis, unit = uT
- r.thigh Magnetic Field Z (uT): Right thigh's magnetic field along Z axis, unit = uT
- l.thigh Acceleration X (m/s^2): Left thigh's acceleration along X axis, unit = m/s^2
- l.thigh Acceleration Y (m/s^2): Left thigh's acceleration along Y axis, unit = m/s^2
- l.thigh Acceleration Z (m/s^2): Left thigh's acceleration along Z axis, unit = m/s^2
- l.thigh Angular Velocity X (rad/s): Left thigh's angular velocity along X axis, unit = rad/s
- l.thigh Angular Velocity Y (rad/s): Left thigh's angular velocity along Y axis, unit = rad/s
- l.thigh Angular Velocity Z (rad/s): Left thigh's angular velocity along Z axis, unit = rad/s
- l.thigh Magnetic Field X (uT): Left thigh's magnetic field along X axis, unit = uT
- l.thigh Magnetic Field Y (uT): Left thigh's magnetic field along Y axis, unit = uT
- l.thigh Magnetic Field Z (uT): Left thigh's magnetic field along Z axis, unit = uT
- head Acceleration X (m/s^2): Head's acceleration along X axis, unit = m/s^2
- head Acceleration Y (m/s^2): Head's acceleration along Y axis, unit = m/s^2
- head Acceleration Z (m/s^2): Head's acceleration along Z axis, unit = m/s^2
- head Angular Velocity X (rad/s): Head's angular velocity along X axis, unit = rad/s
- head Angular Velocity Y (rad/s): Head's angular velocity along Y axis, unit = rad/s
- head Angular Velocity Z (rad/s): Head's angular velocity along Z axis, unit = rad/s
- head Magnetic Field X (uT): Head's magnetic field along X axis, unit = uT
- head Magnetic Field Y (uT): Head's magnetic field along Y axis, unit = uT
- head Magnetic Field Z (uT): Head's magnetic field along Z axis, unit = uT
- sternum Acceleration X (m/s^2): Sternum's acceleration along X axis, unit = m/s^2
- sternum Acceleration Y (m/s^2): Sternum's acceleration along Y axis, unit = m/s^2
- sternum Acceleration Z (m/s^2): Sternum's acceleration along Z axis, unit = m/s^2
- sternum Angular Velocity X (rad/s): Sternum's angular velocity along X axis, unit = rad/s
- sternum Angular Velocity Y (rad/s): Sternum's angular velocity along Y axis, unit = rad/s
- sternum Angular Velocity Z (rad/s): Sternum's angular velocity along Z axis, unit = rad/s
- sternum Magnetic Field X (uT): Sternum's magnetic field along X axis, unit = uT
- sternum Magnetic Field Y (uT): Sternum's magnetic field along Y axis, unit = uT
- sternum Magnetic Field Z (uT): Sternum's magnetic field along Z axis, unit = uT
- waist Acceleration X (m/s^2): Waist's acceleration along X axis, unit = m/s^2
- waist Acceleration Y (m/s^2): Waist's acceleration along Y axis, unit = m/s^2
- waist Acceleration Z (m/s^2): Waist's acceleration along Z axis, unit = m/s^2
- waist Angular Velocity X (rad/s): Waist's angular velocity along X axis, unit = rad/s
- waist Angular Velocity Y (rad/s): Waist's angular velocity along Y axis, unit = rad/s
- waist Angular Velocity Z (rad/s): Waist's angular velocity along Z axis, unit = rad/s
- waist Magnetic Field X (uT): Waist's magnetic field along X axis, unit = uT
- waist Magnetic Field Y (uT): Waist's magnetic field along Y axis, unit = uT
- waist Magnetic Field Z (uT): Waist's magnetic field along Z axis, unit = uT

NOTES:
- Magnetic field data from two sensors (at sternum and waist) seems to be more noisy compared to other sensors.

CITATION REQUEST:
Use of this dataset in publications must be acknowledged by referencing the following publication:
- Omar Aziz, Magnus Musngi, Edward J. Park, Greg Mori, Stephen N. Robinovitch. "A comparison of accuracy of fall detection algorithms (threshold-based vs. machine learning) using waist-mounted tri-axial accelerometer signals from a comprehensive set of falls and non-fall trials". SpringerLink Med Biol Eng Comput (2017) 55: 45.

We also appreciate if you drop us an email (stever@sfu.ca and oaziz@sfu.ca) to inform us of any publication using this dataset, so we can point to your publication on our webpage.