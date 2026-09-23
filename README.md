# Day 13 – RAG and Source Verification

## Overview

This project is part of the **Generative AI for Business** course and demonstrates how Retrieval-Augmented Generation (RAG) can improve the reliability of AI-generated answers in aviation management. The activity uses **ChatGPT** and an official Air India source about delayed, lost and damaged baggage.

The main objective was to compare an **ungrounded answer** with a **grounded answer** based only on the supplied source. The initial ungrounded response contained general information about baggage reporting, reimbursement, delivery timelines and compensation, but these claims were not supported by the specific Air India document. This showed the risk of presenting plausible information as airline policy.

After the source was provided, grounding instructions required every factual claim to be supported by the document and missing information to be clearly identified. The grounded response confirmed that passengers should contact Air India personnel in the arrival hall and receive assistance with filing a **Property Irregularity Report (PIR)**. It also explained that essential expenses may be considered for reimbursement and that delivery timelines can vary because of local customs regulations.

The project also included **claim-source matching, citation checking, missing-information testing, conditional-information testing, and a RAG risk audit**. A second scenario examined Air India's Flight Disruption Statement and its use as documentary evidence for eligible insurance claims.

## Key Learning

RAG helps AI use specific source information, but **human verification remains essential** because sources can be incomplete, outdated, or incorrectly interpreted. This approach can support aviation customer service, policy research, report preparation, and document-based decision support.
