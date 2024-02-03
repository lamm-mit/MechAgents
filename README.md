# MechAgents

## Large language model multi-agent collaborations for solving mechanics problems, generating new data, and integrating knowledge

B. Ni, M.J. Buehler*

MIT

*mbuehler@MIT.EDU

## Summary
Solving mechanics problems using numerical methods requires comprehensive intelligent capability of retrieving relevant knowledge and theory, constructing and executing codes, analyzing the results, a task that has thus far mainly been reserved for humans. While emerging AI methods can provide effective approaches to solve end-to-end problems, for instance via the use of deep surrogate models or various data analytics strategies, they often lack physical intuition since knowledge is baked into the parametric complement through training, offering less flexibility when it comes to incorporating mathematical or physical insights. By leveraging diverse capabilities of multiple dynamically interacting large language models (LLMs), we can overcome the limitations of conventional approaches and develop a new class of physics-inspired generative machine learning platform, here referred to as MechAgents. A set of AI agents can solve mechanics tasks, here demonstrated for elasticity problems, via autonomous collaborations. A two-agent team can effectively write, execute and self-correct code, in order to apply finite element methods to solve classical elasticity problems in various flavors (different boundary conditions, domain geometries, meshes, small/finite deformation and linear/hyper-elastic constitutive laws, and others). For more complex tasks, we construct a larger group of agents with enhanced division of labor among planning, formulating, coding, executing and criticizing the process and results. The agents mutually correct each other to improve the overall team-work performance in understanding, formulating and validating the solution. Our framework shows the potential of synergizing the intelligence of language models, the reliability of physics-based modeling, and the dynamic collaborations among diverse agents, opening novel avenues for automation of solving engineering problems.

![image](https://github.com/lamm-mit/MechAgents/assets/101393859/9ab19d88-8762-4138-b040-c5f4a391b62e)

Figure 1: Framework of multi-agent AI modeling for solving mechanics problems

### Codes
This repository contains google colab notebooks that organize collaborative teams of LLM powered agents to solve elasticity problems using finite element method. 

### Requirements
To run the colab notebooks, just click the "open in Colab" badge and include your API key to the language model in the relvent cells.


### Original paper

Please cite this work as:
```
@article{NiBuehler_2024,
    title   = {MechAgents: Large language model multi-agent collaborations can solve mechanics
               problems, generate new data, and integrate knowledge},
    author  = {B. Ni, M.J. Buehler},
    journal = {Extreme Mechanics Letters},
    year    = {2024},
    volume  = {},
    pages   = {},
    url     = {}
}
```
