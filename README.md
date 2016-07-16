Quick SSVEP

Quick SSVEP is a web app that provides easy to setup SSVEP (Steady State Visually Evoked Potential) stimulation interfaces. When a stimulus in the visual field flickers at a certain frequency, there will be an increase in the brain activity over visual cortex at that frequency (and harmonics), which is called an SSVEP. This phenomenon provides a straightforward way to design a Brain-Computer Interface (BCI). In an SSVEP based BCI, different choices shown on the display flicker at different know frequencies. When the user looks at the intended choice, the EEG brain activity shows an increase in the flickering frequency of that choice. The BCI can process the EEG, detect the frequency that shows increased activity and thus detect the intended choice of the subject. It can the actuate the command associated with the choice, e.g. typing a letter, switching a light, etc. A fundamental property of such BCI design is that the stimulator which is showing the flickering choices, does not have to be communicating with the signal processor (in contrast to for example ERP based BCIs), thus allowing decoupling of the two software components. This application provides a stand-alone web-based SSVEP stimulator that can run on any modern web browser (although Google Chrome is used in development and is recommended for best performance). 

Note: The performance of this stimulator (the exact frequency of stimulations) highly depends on the machine and the web browser running it. It is not intended for academic use, rather it is a fast solution to test simple SSVEP setups.
