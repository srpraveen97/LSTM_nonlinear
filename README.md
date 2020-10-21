# LSTM_CSTR

A nonlinear chemical reactor is modeled using a LSTM network. This CSTR model has two states: concentration of reactant Ca, temperature of the reactor Tr and two 
inputs: inlet concentration of the reactant Ca0 and the heat input into the reactor Q. The objective of this project is to be able to use a nonlinear reactor model 
in the context of a model predictive control framework. To that end, a time series model of the reactor is modeled as an LSTM network. This model takes in the current
state of the reactor system and the new input signal to predict the future state of the reactor.
