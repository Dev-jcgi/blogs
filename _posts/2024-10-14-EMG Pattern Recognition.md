## Abstract
In this document, we present a methodology for movement pattern recognition from arm-forearm myoelectric signals, starting off from the design and implementation of an electromyography (EMG) instrumentation system, considering the Surface EMG for the Non-Invasive Assessment of Muscles (SENIAM) rules. Signal processing and characterization techniques were applied using the pass-band Butterworth digital filter and fast Fourier transform (FFT). Artificial neural networks (ANN) such as back propagation and radial basis function (RBF) were used for the pattern recognition or classification of the EMG signals. The best results were obtained using the RBF ANN, achieving an average accuracy of 98%.

**Published in:** 2012 11th Mexican International Conference on Artificial Intelligence  
**Date of Conference:** 27 October 2012 - 04 November 2012  
**Date Added to IEEE Xplore:** 24 December 2012  
**Print ISBN:** 978-1-4673-4731-0  
**DOI:** [10.1109/MICAI.2012.23](https://doi.org/10.1109/MICAI.2012.23)  
**Publisher:** IEEE  
**Conference Location:** San Luis Potos, Mexico  

## I. Introduction
One of the modern challenges in Biomedical Engineering is to design and build a system that may be used as a man-machine interface for people who have suffered amputations of their upper or lower extremities or that present motor disabilities. This system must be able to recognize and appropriately respond to the person's desired movements using superficial electrodes as a means of communication or sensing, which are placed in the remaining muscles of the person's amputated extremity or in strategic positions in the case of people with motor disabilities. The signals that the system must acquire, process, and analyze are the electric potentials from the neuromuscular activity, better known as electromyographic (EMG) signals; these signals present amplitudes that vary from micro to mili volts and a bandwidth from 10 to 1000 Hz [1]. 

There have been great advances in the study of EMG signals, especially in the electric device control applications focused on the rehabilitation of people with amputations through the implementation of myoelectric prostheses in arms [2],[3]. These systems use a simple codification scheme of the EMG signal amplitude in order to activate one or more of the prosthesis devices such as the elbow, wrist, or hand. Although these systems have been successful, they do not provide enough information to reliably and intuitively control more than one function or multiple functions of the myoelectric prosthesis, which is a problem yet to be solved. One of the techniques that may help solve this problem is applying pattern recognition to the EMG signal processing and analysis [4]. Some of the methods that have been more successful in recognizing or classifying EMG signals include: Bayesian systems [5], artificial neural networks (ANN) [6], [7], Markov maps [8], and fuzzy logic [9].

## Authors
**Juan Carlos Gonzalez-Ibarra**  
Centro de Investigación y Estudios de Posgrado (CIEP), Facultad de Ingeniería, Universidad Autónoma de San Luis Potosí, San Luis Potosi, San Luis Potosi, Mexico

## References
1. A. Ashok, "Procesamiento de Señales Analógicas y Digitales" 3rd ed., Thomson 1999.
2. P. A. Parker and R. N. Scott, "Myoelectric control of prostheses," *CRC Crit. Rev. Biomed. Eng.*, vol. 13, no. 4, pp. 283-310, 1986.
3. K. Englehart and B. Hudgins, "A robust, real-time control scheme for multifunction myoelectric control," *IEEE Trans. Biomed. Eng.*, vol. 50, no. 7, pp. 848-854, 2003.
4. K. Englehart, B. Hudgins, and A. D. C. Chan, "Continuous Multifunction Myoelectric Control using Pattern Recognition," *Technology and Disability*, vol. 15, no. 2, pp. 95-103, 2003.
5. K. Englehart, B. Hudgins, P. A. Parker, and M. Stevenson, "Classification of the myoelectric signal using time-frequency based representations," *Med. Eng. Phys.* (Special Issue: Intelligent Data Analysis in Electromyography and Electroneurography), vol. 21, pp. 431-438, 1999.
6. B. S. Hudgins, P. A. Parker, and R. N. Scott, "A new strategy for multifunction myoelectric control," *IEEE Trans. Biomed. Eng.*, vol. 40, no. 1, pp. 82-94, 1993.
7. C. Christodoulou and C. S. Pattichis, "A new technique for the classification and decomposition of EMG signals," in *Proc. 1995 IEEE Int. Conf. Neural Networks*, New York, vol. 5, pp. 2303-2308, 1995.
8. A. D. C. Chan and K. Englehart, "Continuous myoelectric control for powered prostheses using hidden Markov models," *IEEE Trans. Biomed. Eng.*, vol. 52, no. 1, pp. 121-124, 2005.
9. R. F. Weir and A. B. Ajiboye, "A multifunction prosthesis controller based on fuzzy-logic techniques," in *Proc. 25th Silver Anniversary Int. Conf. IEEE Engineering in Medicine and Biology Society (EMBS)*, Cancun, Mexico, 2003.
10. Surface Electromyography Non-Invasive Assessment Muscular [http://www.seniam.org](http://www.seniam.org)
11. D. Dumitru, A. Gitter "A. Nerve and muscle anatomy and Physiology" *Electrodiagnosis Medicine*. Philadelphia: Hanley and Belfus; pp. 3-26, 2002.
12. G. Yang, "Study of Emotion Recognition Based on Surface Electromyography and Improved Least Squares Support Vector Machine," *J. of computers*, vol. 6, 2011.

## Keywords
- **IEEE Keywords:** Electromyography, Electrodes, Artificial neural networks, Pattern recognition, Muscles, Accuracy, Neurons
- **Index Terms:** Pattern Recognition, Electromyography Patterns, Electromyography Pattern Recognition, Signal Processing, Artificial Neural Network, Fast Fourier Transform, Average Accuracy, Radial Basis Function, Electromyography Signals, Digital Filter, Electrostatic Potential, Resting-state, Peripheral Nervous System, Amputation, Electrodeposition, Coefficient Vector, Recognition Time, Movement Of Persons, Radial Nerve, Triceps Muscle, Electromyography System
- **Author Keywords:** Artificial Neural Networks, EMG, FFT, Pattern Recognition

## Metrics
**Total usage since Jan 2013:** 879  
**Year Total:** 12  
Data is updated monthly. Usage includes PDF downloads and HTML views.

**Citations:**  
- **13 Crossref®**  
- **16 Scopus®**

### Cites in Papers - IEEE
1. Yusen Guo et al., "sEMG-Based Wearable HMI System For Real-Time Robotic Arm Control With Edge AI", 2023 IEEE Biomedical Circuits and Systems Conference (BioCAS), pp.1-5, 2023.
2. Netra Trivedi et al., "Universal Remote using EMG based Gesture Recognition", 2021 IEEE Bombay Section Signature Conference (IBSSC), pp.1-5, 2021.
3. Feng Duan et al., "A Gesture Recognition System Based on Time Domain Features and Linear Discriminant Analysis", *IEEE Transactions on Cognitive and Developmental Systems*, vol.13, no.1, pp.200-208, 2021.
4. Hee Young Chae et al., "A Wearable sEMG Pattern-Recognition Integrated Interface Embedding Analog Pseudo-Wavelet Preprocessing", *IEEE Access*, vol.7, pp.151320-151328, 2019.
5. Yang Zhao et al., "A sEMG-Based Hand Motions Recognition System With Dimension-Reduced FFT", 2019 Chinese Control And Decision Conference (CCDC), pp.1415-1420, 2019.
6. Xina Ren et al., "A stable recognition system for human gestures based on sEMG signals", 2017 IEEE International Conference on Robotics and Biomimetics (ROBIO), pp.1038-1043, 2017.
7. Xina Ren et al., "sEMG-based hand motion recognition system using RMSR and AR model", 2017 36th Chinese Control Conference (CCC), pp.5410-5415, 2017.
8. Reena Patil et al., "Spectral model based intent detection for multichannel SEMG signals", 2017 IEEE EMBS International Conference on Biomedical & Health Informatics (BHI), pp.469-472, 2017.
9. Stephen Hickman et al., "A case study on tuning artificial neural networks to recognize signal patterns of hand motions", SoutheastCon 2015, pp.1-4, 2015.

### Cites in Papers - Other Publishers
1. Anna Igrevskaya et al., "The Research of Characteristic Frequencies for Gesture-based EMG Control Channels", *Biologically Inspired Cognitive Architectures 2021*, vol.1032, pp.158, 2022
