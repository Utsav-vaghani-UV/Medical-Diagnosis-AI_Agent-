# Medical-Diagnosis (AI_agent)

A Python project designed to create specialized LLM-based AI agents that analyze complex medical cases. The system integrates insights from various medical professionals to provide comprehensive assessments and personalized treatment recommendations, demonstrating the potential of AI in multidisciplinary medicine.

## Current Version Overview

In the current version, i have implemented three AI agents using GPT-4o, each specializing in a different aspect of medical analysis. A medical report is passed to each of these agents, who then analyze the report simultaneously using threading, based on their specific area of expertise. Each agent provides recommendations and diagnoses from their perspective. After all AI agents complete their analyses, the results are combined and passed to a large language model, which summarizes the findings and identifies three potential health issues for the patient.

### AI Agents

**1. Cardiologist Agent**

- **Focus**: Identify any potential cardiac issues that could explain the patient's symptoms, including ruling out conditions such as arrhythmias or structural abnormalities that might not be apparent in initial evaluations.
  
- **Recommendation**: Suggest additional cardiovascular testing or continuous monitoring if necessary to uncover hidden heart-related problems. Provide management strategies if a cardiovascular issue is identified.

**2. Psychologist Agent**

- **Focus**: Determine if the symptoms align with a psychological condition, such as panic disorder or another anxiety-related issue. Assess the impact of stress, anxiety, and lifestyle factors on the patient’s overall condition.
  
- **Recommendation**: Recommend appropriate psychological interventions (e.g., therapy, stress management techniques) or medications to address the psychological aspects of the symptoms. Evaluate whether adjustments to the current psychological management are needed.

**3. Pulmonologist Agent**

- **Focus**: Assess whether symptoms like shortness of breath and dizziness are due to a respiratory condition, such as asthma or a breathing disorder, that could mimic cardiac symptoms.
  
- **Recommendation**: Suggest additional respiratory evaluations, such as lung function tests or exercise-induced bronchoconstriction tests, to rule out any underlying lung conditions. Recommend breathing exercises or other treatments if a respiratory issue is suspected.

## Repository Structure

- **Medical Reports Folder**: Contains a synthetic medical report of a patient with Panic Attack disorder.
- **Results Folder**: Stores the outputs of the agentic system.
  
**To be able to run the code, please insert your OpenAI API key within the `apikey.env` file.**

