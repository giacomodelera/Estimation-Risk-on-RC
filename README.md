# Estimation Risk on Regulatory Capital

## Abstract
The set of international banking regulations mandates that banks maintain a minimum capital reserve as a safeguard against potential future losses, which are primarily influenced by two factors: stochastic variables risk and the uncertainty inherent in the chosen model itself.

In this project, the Vasicek model was applied to a homogeneous portfolio to focus on the measurement of portfolio credit risk. Additionally, the risks associated with errors in model parameters were examined, and the impact of each parameter’s uncertainty on capital requirements was assessed.

In particular, the difference between a simplified "naive" model, which is widely used, and several stressed models was evaluated. In the stressed models, fixed parameters were not considered; instead, different simulation approaches were employed using the Monte Carlo method to assess their impact on regulatory capital.

A confidence level of α = 99.9% was used, as established by the Basel Committee, though results were also stressed with α = 99% throughout the project.

In the first section, statistical tests were conducted to verify the assumptions necessary for subsequent analyses, particularly those related to Gaussianity. However, in the final part of the report, alternative distributional assumptions for the parameters were also considered to analyze potential differences.

Both an asymptotic homogeneous portfolio (LHP) and a homogeneous portfolio (HP) with a finite number of obligors were analyzed. Differences were examined in cases where the number of obligors was small (N = 50) and possible relationships were explored for larger numbers (e.g., N = 1000).

Additionally, the regulatory capital derived from the Standard model was compared to that obtained through the IRB model, which is the primary focus of this discussion.

## Repository Structure
For a better understanding of the work, please refer to the attached [Report](Report.pdf). 
It contains:
* A deeper description of the problem
* Detailed methodologies
* Bibliography of referenced papers

The code, available in both Python and MATLAB, can be provided upon request.
