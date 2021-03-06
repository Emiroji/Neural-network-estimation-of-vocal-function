# Neural-network-estimation-of-vocal-function

Phyton code used in [1] for implementing a neural network architecture providing a mapping from aerodynamic glottal features into a set of clinically-relevant measures of vocal function. Seven input features describing the glottal airflow waveform were considered: amplitude of the unsteady glottal airflow (ACFL), maximum flow declination rate (MFDR), open quotient (OQ), speed quotient (SQ), spectral tilt measured as the log-magnitude difference between the first and second harmonics (H1-H2), fundamental frequency (fo), and the sound pressure level (SPL). The output layer, in turn, involved four target vocal function measures: subglottal pressure (P_s), vocal fold collision pressure (P_c), and cricothyroid (a_CT) and thyroarytenoid (a_TA) muscle activation. The devised nonlinear mapping was trained solely with 13,000 simulated samples (DataSetModel.cvs) obtained from Monte Carlo simulations with a physiological low-order voice production model that utilizes a symmetric triangular body-cover model of the vocal folds. For more details, see [1].

[1] **E. J. Ibarra, J. Parra, G. A. Alzamendi, J. P. Cortés, V. M. Espinoza, D. D. Mehta, R. E. Hillman and M. Zañartu (2021), “Estimation of subglottal pressure, vocal fold collision pressure, and intrinsic laryngeal muscle activation from neck-surface vibration using a neural network framework and a voice production model”, Frontiers in Physiology, section Computational Physiology and Medicine, Vol 12, pp. 1419. DOI: 10.3389/fphys.2021.732244, Available online at: https://www.frontiersin.org/articles/10.3389/fphys.2021.732244/full


code: https://github.com/Emiroji/Neural-network-estimation-of-vocal-function/blob/2ba26326b1e67ad7d206109808898438340dda58/Code.ipynb

DataSet: https://github.com/Emiroji/Neural-network-estimation-of-vocal-function/blob/2ba26326b1e67ad7d206109808898438340dda58/DataSetModel.csv
