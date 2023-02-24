# Problem of Interest

Given a data set with 500 samples and the following eight variables:

**GRE** (GRE scores), **TF** (TOEFL scores), **UR** (university rating), **SOP** (Statement of Purpose strength), LOR (Letter of Recommendation strength), **GPA** (undergraduate GPA), **Research** (have research experience or not), Admit (chance of admittance),

we are interested in the **causal relationships** between them, especially the causal influence on the variable Admit (the chance of admittance).


# Causal Graphical Model

The main methodology in this project is the use of causal graphical model which is a **Bayesian network** where the directed edges indicate the causal relationships between nodes. 

I established the model by making reasonable causal assumptions based on our prior knowledge and intuition about the variables.



# Structure

*/graduate_admissions* contains two datasets of graduate school admission dicisions. 

*/CausalAdmit_Joy.ipynb* presents my work on how I constructed a Bayesian network, then explored causal relationships between different variables.
