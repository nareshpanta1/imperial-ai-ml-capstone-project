# Overview
- Name: Imperial AI/ML Capstone Black Box optimisation project
- Type: Surrogate based optimisation using acqusition functions
- Version: V1.0 (12 round cycle)

# Intended Use
- Suitable Tasks:
   - optimising unknown functions
   - benchmarking acquision functions (Expected improvement, Upper Confidence Bound)
   - learning exploration/exploitation
- Avoided use cases:
   - High dimensional functions
   - Real world deployment

# Details
   - Please refer to the [Observations](observations/Observations.xlsx)

# Performace
- Manual observation of the output for each functions for each week and deciding on the next week approach

# Assumptions and Limitations
- Assumptions
    - Objective functions are smooth and can be approximated using GP
    - Search space is bounded and finite
- Limitations
    - Non smooth functions are misinterpresented

# Ethical Considerations
- Transperancy: All process is documented and available in this repository 
- Real world adaptation: assumption and limitation described so that it is not used in sensitive domains 