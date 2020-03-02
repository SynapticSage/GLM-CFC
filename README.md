# GLM-CFC
A GLM based approach to measure CFC

Code to measure cross-frequency coupling between two signals as described in this manuscript: https://elifesciences.org/articles/44287v1

simfun: code to simulate signals V_low, V_high, with induced cross-frequency coupling and measure output statistics R_PAC, R_AAC, and R_CFC, along with confidence intervals and p-values

glmfun: code to evaluate coupling statistics R_PAC, R_AAC, and R_CFC, along with confidence intervals and p-values, between two signals

ExampleCode: run to get example voltage traces and surfaces in Phi_low, A_low, A_high space (as in Figure 4). Four simulations are present: one with no CFC, one with PAC, one with AAC, and one with both PAC and AAC

glmfun_with_indicator: an example of how to update glmfun to test for effect of condition (e.g. pre and post stimuli) on coupling

The human data from figures 9 and 10 can be found in Patient_Data, and the rat data from figure 11 can be found at https://github.com/tne-lab/cl-example-data

Any questions/comments please direct to Jessica Nadalin (jnadalin@bu.edu)
