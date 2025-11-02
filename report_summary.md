Milestone 2: Clustering and Pattern Detection

Objective:

To group students based on their learning patterns (study hours, sleep hours, and exam scores) using K-Means clustering and identify insights about academic behavior.



 Steps Performed:

1. Data Preparation

Created a dataset containing students’ study hours, sleep hours, diet, and exam scores.

Selected numerical features for clustering.

Standardized data using StandardScaler for equal scaling.



2. Dimensionality Reduction

Used PCA (Principal Component Analysis) to reduce data to 2D for visualization.



3. Clustering

Applied K-Means with 3 clusters to detect student learning groups.



4. Visualization (4 Plots)

Scatter Plot (2D using PCA): Displayed clusters with distinct colors.

Cluster Characteristics (Bar Plot): Showed mean study hours, sleep hours, and exam scores per cluster.

Box Plot: Compared exam-score distribution among clusters.

Pie Chart: Displayed the proportion of students in each cluster.



Observations:

One cluster showed high study hours + high exam scores — consistent and focused learners.

Another cluster represented moderate study with balanced sleep — average performers.

The third cluster showed low study hours + low scores, possibly needing improvement.



Insights:

Regular study hours and sufficient sleep correlate with better exam performance.

Clustering helps institutions identify learning behavior and plan personalized guidance.
