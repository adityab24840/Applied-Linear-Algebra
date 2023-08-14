    ###Assiggnment 2

    # Patient Data Analysis

    This Python script performs analysis on a dataset containing health attributes of patients. It calculates distances between patients based on their heart rate (HR), blood pressure (BP), and body temperature (TEMP). It identifies the patient farthest from the rest based on cumulative distances and finds the two patients closest to each other.

    ## Usage

    1. Install the required dependencies:

    pip install pandas numpy

    ## Functionality

    1. **Calculating Distances**: The script uses the Euclidean distance formula to compute the distances between each pair of patients based on their health attributes. It constructs a distance matrix that captures the dissimilarity between patients.

    2. **Identifying Farthest Patient**: The patient with the highest cumulative distance from the rest is identified and displayed. This helps in identifying outliers or patients with distinct health attributes.

    3. **Finding Nearest Patients**: The two patients that are closest to each other are determined by comparing all possible patient pairs based on the calculated distances. This provides insights into patients with the most similar health profiles.

    4. **Adding New Patient**: The script appends a new dummy patient ('patient-5') with specified health attributes to the dataset. It then recalculates distances and identifies the patient in the existing dataset that is closest to the new patient.

    ## Output

    The script generates output that highlights the farthest patient from the rest, the two patients nearest to each other, and the patient in the dataset closest to the newly added dummy patient.
