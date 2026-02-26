# KG_project

## Scenario

1. T3. Healthcare Diagnosis Team
Strong paper-to-scenario links:
Social AI for chronic disease lifestyle management → healthcare teamwork, stakeholder support networks, reflective interactions, actionable explanations. 
FAIA-408-FAIA250649
Organ donation policy simulation (ABSS + serious game) → healthcare policy stakeholders + simulation agents; also good for “AI decision support in a high-stakes medical domain.” 
FAIA-408-FAIA250667
Hybrid moral decision-making (humans + LLMs) → clinical ethics, triage-like dilemmas, “should we follow AI advice?”, mismatch in human vs LLM moral defaults. 
FAIA-408-FAIA25

Clean instances for Stakeholder roles (patient, primary caregiver, specialist, AI system).
Data/object properties you’ll likely add: hasTrustLevel, hasExplanationType, hasValue, followsNorm, recommendsTreatment, requestsSecondOpinion, usesPolicyModel.

2. T1. Research HI Team
Why it fits your papers
Several of your papers are fundamentally about HI in research / knowledge work, data-to-insight workflows, and tool-assisted expert processes.
Strong paper-to-scenario links:
AI-assisted reconstruction of past environments (archaeology, human-in-the-loop) → classic expert+AI pipeline; multiple expert roles (archaeologist, botanist, computer scientist). 
FAIA-408-FAIA250638
Real-time gaze-aware conversational agent in VR + knowledge graph → knowledge engineering + interaction + KG-backed conversational agent; also very “research team builds a system” vibes. 
FAIA-408-FAIA250634
(Optionally) Trust-factor game (trust-aware RL + LLM human simulation) can also be framed as a “research team” building/evaluating a HI system. 
FAIA-408-FAIA250625
What it gives you in the KG
Great for modeling: datasets, tools, methods, experiments, evaluation metrics, iterative development, plus linking to external scholarly KGs later.
Likely ontology additions: usesDataset, usesTool, appliesMethod, evaluatedByMetric, producesArtifact (model / KG / simulation / visualization), hasHumanInLoopStep.

3) T2. Child Education Team
Why it fits your papers
You have interaction-heavy, human-centered papers that align naturally with education/learning support teams.
Strong paper-to-scenario links:
Gaze-aware conversational agent in VR → can be reframed as adaptive guidance / personalized explanations in immersive learning contexts (education-tech). 
FAIA-408-FAIA250634
Trust calibration via biosignals (EEG) in human-AI decision support → if you interpret “learning” as learning to collaborate / learning to use AI appropriately, EEG-based trust state can be an “adaptive teaching” signal (e.g., when to explain more, when to reduce autonomy). 
FAIA-408-FAIA250631
What it gives you in the KG
Strong coverage for: human factors, adaptation/personalization, collaboration quality attributes (norm awareness, autonomy calibration, communication mechanisms).
Likely ontology additions: hasLearningGoal, hasPersonalizationSignal (e.g., gaze/EEG), adaptsInteractionStrategy, providesFeedback, monitorsProgress.