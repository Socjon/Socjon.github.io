---
layout: post
title: Defining a Time Series 
---
 
Time series are everywhere, if you notice them or not. They provide a great wealth of knowledge but only if you grasp what they are. For a long time, I was confounded with the concept and that was my motivation in writing this piece. Hopefully this clears up your confusion too.  

Through rigorous study, a time series has been formulated as a mathematical object. That is to say, it has a definition, obeys certain properties, and can be the target of certain operations (Wikipedia contributors. Mathematical). The majority of time series analysis comes from the Signal Processing field. “Signal processing is not the transmission of signals, as through telephone wires or by radio waves, but the changes made to the signals as to improve transmission or use of the signals.” (Fifty 1) This field has helped society in many ways; in the 1950s with the breakthroughs of radio technologies, the quality of audio in telephones in the 1960s, and the imaging schemes of MRI machines in the 1970s to name just a few.  

Signals are represented mathematically as functions of one or more independent variables.The variables that produce these signals are inexhaustible. They can include the visible light spectrum (electromagnetic radiation), the reported quarterly GPD of South Africa, or the heartbeat in your chest. Signal processing deals in analog, time, nonlinear, statistical, and digital domains. A time series is the recorded value of a variable in a ordered index of time. Methods for time series analysis may be divided into two classes: frequency-domain methods and time-domain methods. (Shumway 167)  

The time domain can be broken into two frameworks, discrete time and continuous time. Each framework has a distinct subset of rules/conditions that they follow. Taking a step back for a moment to remember we are talking about a signal, something that conveys information. We have to consider how we are going to study this information. For a continuous-time signal, also stated as a continuous signal, there is a defined value at any given moment. Also between any two points in time, there are an infinite number of other points in time. (Continuous-Time) The framework of continuous signals lends itself to theory application and engineering. Examples of continuous signals include the voltage in a powerline or radiation from uranium. It is not a far leap from continuous signals to discrete time signals.  

The discrete time framework views that we are getting signal information as set points in time. These intervals are evenly spaced and there exists a finite number of them. When we take a subset of a continuous-time signal, the subset is a discrete time signal. There need not exist a continuous signal to obtain a discrete signal. Measuring a variable at distinct, equidistant intervals also yields a discrete time series. These intervals can be infrequent as years or as quick as nanoseconds. The changing of these intervals is known as sampling. Assuming the data exists, going from a monthly indexed time series to a daily time series would be called upsampling. Conversely, changing indexing from seconds to minutes would be called downsampling. For example, an audio signal is measured in Hz (hertz is defined as one cycle per second). A sampling rate for walkie-talkies is around 8,000 Hz while the audio sampling rate for Blu-ray audio track is 96,000 Hz. The more frequent the sampling rate, the more data there is to deal with.  

It is from the time framework that we can start to work with time series. Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data (Wikipedia contributors. Time) There are a great many articles out there explaining seasonality, trends, etc out there. Hopefully this has given you a greater understanding of a time series as a concept and with it, the confidence to tackle your projects.  
 


References:


"Continuous-Time vs Discrete-Time Signals." Wireless Pi, wirelesspi.com/
    continuous-time-vs-discrete-time-signals/.

Fifty Years of Signal Processing: The IEEE Signal Processing Society and its Technologies 1984-1998.
    PDF ed., 1998.

Shumway, Robert H., and David S. Stoffer. Time Series Analysis and Its Applications. 4th ed.,
    Springer International Publishing, 2017.

Van Veen, Barry. "Discrete-Time Frequency: Avoid Confusion." All Signal Processing,
    allsignalprocessing.com/discrete-time-frequency-avoid-confusion/.

Wikipedia contributors. "Time series." Wikipedia, The Free Encyclopedia. Wikipedia, The Free Encyclopedia, 26 Feb. 2019. Web. 28 Feb. 2019. 

Wikipedia contributors. "Mathematical object." Wikipedia, The Free Encyclopedia. Wikipedia, The Free Encyclopedia, 30 Aug. 2018. Web. 28 Feb. 2019. 












