# Star-DataSet-1 Analysis

## Project Overview:
The project revolves around the classification of celestial objects—stars, galaxies, and quasars—based on their spectral properties. Leveraging data from the Sloan Digital Sky Survey (SDSS), the aim is to employ machine learning techniques to categorize these objects. Understanding the unique characteristics of each object, such as right ascension, declination, photometric filters, and redshift, enables insightful exploration of their physical attributes and evolutionary stages.

## Data Columns:
1. obj_ID: Object Identifier, unique to the SDSS image catalog.
2. alpha: Right Ascension angle (J2000 epoch) - celestial object's position.
3. delta: Declination angle (J2000 epoch) - another coordinate for object position.
4. u, g, r, i, z: Photometric filters representing light intensity in different wavelength bands.
5. run_ID: Run Number identifying the specific sky scan by SDSS.
6. rereun_ID: Rerun Number specifying image processing details.
7. cam_col: Camera column identifying scanline within the run.
8. field_ID: Field Number identifying each field within the camera column.
9. spec_obj_ID: Unique ID for optical spectroscopic objects.
10. class: Object class - classification based on spectral properties (galaxy, star, quasar).
11. redshift: Redshift value - measure of universe expansion since light emission.
12. plate: Plate ID identifying plates used in SDSS spectroscopic survey.
13. MJD: Modified Julian Date indicating when SDSS data was taken.
14. fiber_ID: Fiber ID identifying the fiber pointing light at the focal plane.

## Project Scope:
The scope involves implementing machine learning models to classify celestial objects based on spectral data. The project aims to leverage features such as photometric filters, redshift, and spatial coordinates to develop accurate classifiers for stars, galaxies, and quasars. Exploration of the SDSS dataset will facilitate understanding the distribution and characteristics of various celestial entities.

## Key Achievements:
1. Developed a robust classification model for stars, galaxies, and quasars.
2. Explored the impact of different features on classification accuracy.
3. Investigated the distribution of celestial objects based on redshift values.
4. Implemented data preprocessing techniques for enhancing model performance.
5. Contributed insights into the physical properties and evolutionary stages of classified objects.
6. Successfully navigated the challenges of working with astronomical data, leading to a deeper understanding of spectral classification in astronomy.

## Technologies Used
The Star Dataset Analysis project utilized the following technologies and tools:
1. Python: For data preprocessing, analysis, and visualization (Pandas, Matplotlib, Seaborn)


### File Information:
For better organization of the code file, I have divided the file into 3 different parts:

Part 1 :
  This includes the Data Analysis, Data Cleaning, Finding Data Types, Understanding Data Values.
Part 2:
  Part 2 is then divided into 3 sub parts
  This includes all the Analysis files, Finding Relations, Relation between different columns, Heatmaps, Confussion Matrix
Part 3:
  This includes Traning, Splitting, Prediction of values, and Confusion Matrix after traning


### PDF
Along with all the I have also provided a ZIP file of the Parts all together for proper understandings.
