# Neural-network-estimation-of-vocal-function

Phyton code used in [1] for implementing a neural network architecture providing a mapping from aerodynamic glottal features into a set of clinically-relevant measures of vocal function. Seven input features describing the glottal airflow waveform were considered: amplitude of the unsteady glottal airflow (ACFL), maximum flow declination rate (MFDR), open quotient (OQ), speed quotient (SQ), spectral tilt measured as the log-magnitude difference between the first and second harmonics (H1-H2), fundamental frequency (fo), and the sound pressure level (SPL). The output layer, in turn, involved four target vocal function measures: subglottal pressure (P_s), vocal fold collision pressure (P_c), and cricothyroid (a_CT) and thyroarytenoid (a_TA) muscle activation. The devised nonlinear mapping was trained solely with 13,000 simulated samples (DataSetModel.cvs) obtained from Monte Carlo simulations with a physiological low-order voice production model that utilizes a symmetric triangular body-cover model of the vocal folds. For more details, see [1].

[1] Emiro J. Ibarra, Jesus Parra, Gabriel A. Alzamendi, Juan P. Cortés,Víctor M. Espinoza, Daryush D. Mehta, Robert E. Hillman, and Matías Zañartu, (2021) "Estimation of subglottal pressure, vocal fold collision pressure, and intrinsic laryngeal muscle activation from neck-surface vibration using a neural network model", submitted for publication to 'Frontiers in Physiology', 2021.

code: https://github.com/Emiroji/Neural-network-estimation-of-vocal-function/blob/main/code.ipynb

DataSet: https://github.com/Emiroji/Neural-network-estimation-of-vocal-function/blob/3562744816772634d3125398328fd1f7351c11e5/DataSetModel.csv
