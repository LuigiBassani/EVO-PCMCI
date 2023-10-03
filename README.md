# EVO-PCMCI

Causal discovery, the task of identifying the causal relationships between
variables, has been a long-standing challenge for many domains such as climate science,
econometrics, and healthcare. One of the most advanced causal discovery methods is the
PCMCI+, which uses conditional independence tests to reconstruct the causal
relationships between time series and predict future values. Despite the changing nature
of real-world relationships, PCMCI+ assumes constant causal relationships through time.
This assumption is shared among most causal discovery methods and makes them
inapplicable to predict financial markets, which are known to be a highly evolving
dynamical system. To model the time-varying causal relationships of financial data we
propose EVO-PCMCI+, a novel multivariate forecasting framework which iterates a
variation of the PCMCI+ combined with various predictive functions. We evaluated
EVO-PCMCI+ using synthetic and real-world datasets. The empirical results demonstrate
the effectiveness of the proposed method in both capturing time-varying causal
relationships as well as forecasting with discrete accuracy short-term financial data.
