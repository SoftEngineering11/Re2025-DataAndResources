# Data And Resources for "Demystifying Feature Requests: Leveraging LLMs to Refine Feature Requests in Open Source Software"

This readme contains details for the respository navigation. There are 3 directories:
- Dataset: This contains the reconciled corpus of 100 Feature requests.
  - 100-FeatureRequests-GroundTruth-RequestLevel.csv -> This file has all the feature requests and their annotations.
  - 100-FeatureRequests-GroundTruth-InstanceBased.csv -> This file has all the instances of each annotation for ambiguities.
  - Incompleteness-InstanceBased.csv -> This file has all the instances of each annotation for incompleteness.
- Documents and Readme:
  - ExtendedResultsForAllExperiment.md -> This file has all the results for experiments that we explain in the paper.
  - AnnotationHeuristicDocument.pdf -> This pdf is our heuristics document that was used for annotation.
- Prompts and Generations: This directory contains 2 sub directories:
  - Prompts: This directory contains prompts used for each experiment.
  - Manual Analysis: This directory contains genearations that were manually evaluated.
- Interview data:
  - InterviewQuestions.docx -> This file has the interview questions and the feature requets that we use for the interviews.
  - IQ1-2-3-Analysis.csv -> This file consists of the analysis for IQ 1 - 3.
  - IQ4-Analysis.csv -> This file consists of the analysis for IQ 4.
