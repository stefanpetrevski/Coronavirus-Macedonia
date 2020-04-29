# Coronavirus-Macedonia
Fitting an SIR model to the Macedonian COVID-19 epidemic. Work in progress.
Thanks to Dr. Aaron King and his pomp library for making the execution of the model very simple for a user. 
This R Markdown attempts to fit the classic SIR model to the Macedonian epidemic. One parameter (gamma) is taken from a previous study in Wuhan, whereas the other parameters are estimated by numerical optimisation. However, due to the small population and inconsistent testing/reporting, the stochasticity in the data is enormous, and the SIR model cannot accurately predict/model this outbreak.  
