# The Secretary Problem With Competing Hypothesis

## Problem in a nutshell
In optimal stopping theory, the secretary problem is a classical problem in which a decision-maker has to find the optimal time to take an action. In this scenario, the decision-maker can be thought of as a manager interviewing a series of candidates for a position. Each candidate has a score that can only be shown to the manager after the interview. The interviews take place sequentially and the order of the candidates is random. If the manager does not hire a candidate after the interview, then she cannot reuturn to the rejected candidate in the future. The process stops either when the managers hires a candidate or the last candidate is interviewed. The goal is to maximise the score of the selected candidate.

## ML predictions
Suppose that the manager has access to some predictions coming from pre-trained ML algorithms which tell her the scores of the candidates before being interviewed. These preictions need not all be perfectly accurate, as it is often the case with machine learning models. We seek to understand how to use these hypothsesis as part of the algotirithms used to solved the secretary problem.

## Context
This research project was conducted during my internship in the Bocconi Institute for Data Science and Analytics and the Bocconi Computing Sciences Department under the guidance of prof. Andrea Celli and prof. Marek Elias. Although the results do not bring a significant contribution to the literature, this work has consituted a very instructive exercise. I am grateful to have had the opportunity to work this project.
