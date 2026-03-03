# Final Project for ECS189G

## DemoLeakExpGPT4
- Contains the final scored spreadsheets for the Demographic Leaking Experiment in the original paper.
- In the original paper, the authors created a set of 11 neutral Reddit posts, where race, gender, and age cannot be inferred. They then transformed each post so that they had keywords either explicity (Ex. [32yo, male]) or implicitly (through dialect or personal life mentions) stating their gender and race. For each of the 11 original posts, they created versions : BlackFemaleExplicit, BlackFemaleImplicit, BlackMaleExplicit, BlackMaleImplicit, WhiteFemaleExplicit, WhiteFemaleImplicit, WhiteMaleExplicit, WhiteMaleImplicit. These datasets are featured in the original github
- Our group used these datasets and a GPT-4 model (gpt-4.1-2025-04-14) to generate responses for all 99 posts (88 transformations posts + the 11 original posts)
- Then we used a GPT-5 (gpt-5.2-2025-12-11) model to rate the empathy scores for each demographic, 1-10.

## DemoAuditingGPT4
- Contains the final scored spreadsheets for demographics: asian, black, white, unknown race.
- In the original paper, the authors also evaluated empathy scores for Reddit posts GPT-4 inferred demographic attributes for (253 inferred Black posts, 58 Asian posts, 47 White posts and 520 Unknown Race posts). These datasets can be found in the original github. 
- Similar to the Demographic Leaking Experiment, we used a GPT-4 model(gpt-4.1-2025-04-14) to generate responses for all posts in each demographic.
- Then we used a GPT-5 (gpt-5.2-2025-12-11) model to rate the empathy scores for each demographic, 1-10.

## Notebooks
- This contains the notebooks we used to generate LLM responses, and evaluate empathy scores.

## Analysis
- Analysis of results from experiments

# Source
@article{Gabriel2024CanAR,
  title={Can AI Relate: Testing Large Language Model Response for Mental Health Support},
  author={Saadia Gabriel and Isha Puri and Xuhai Xu and Matteo Malgaroli and Marzyeh Ghassemi},
  journal={Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing (Findings)},
  year={2024}
}


