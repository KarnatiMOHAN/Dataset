# Dataset
•	Please see “Subject_details.xlsx” for details of below mentioned field.

     Data Id: ID of the subject

     Age: Age of the subject

     Gender: Gender of the subject

     Date: Data of experiment

     Time: Starting time of the experiment

     Score: PHQ-9 score of the subject

•	EEG data of each experiment is stored in separate files.

•	Each dataset file has its name according to the “ID of the subject”.

•	The dataset can be converted into Matlab variable using “Matlab” or “Octave” software.

•	Each dataset file has a structure.

•	This structure has three fields

     o	data:  continuous data of the experiment (both eye opened and eye closed states)

     o	dataClose:  data of eye closed state

     o	dataOpen: 	data of eye opened state

•	These three fields have double type values (in micro volts) with size 20 x N, where N is the total number of time points of the eye state.

     o	I row of the matrix is for A1-A2.

     o	II row of the matrix is for Fp1

     o	III row of the matrix is for Fp2

     o	IV row of the matrix is for F7

     o	V row of the matrix is for F3

     o	VI row of the matrix is for Fz

     o	VII row of the matrix is for F4

     o	VIII row of the matrix is for F8

     o	IX row of the matrix is for T3

     o	X row of the matrix is for C3

     o	XI row of the matrix is for Cz

     o	XII row of the matrix is for C4

     o	XIII row of the matrix is for T4

     o	XIV row of the matrix is for T5

     o	XV row of the matrix is for P3

     o	XVI row of the matrix is for Pz

     o	XVII row of the matrix is for P4

     o	XVIII row of the matrix is for T6

     o	XIX row of the matrix is for O1

     o	XX row of the matrix is for O2

•	The sampling rate of EEG acquisition system is 256Hz.

•	Use “load("data_1001")” to load the structure to the runtime.
