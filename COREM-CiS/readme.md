COREM-CiS Ontology
📘 Description

The COREM-CiS Ontology (Competence Ontology for Resource Management in the Civil Service) is a modular ontology designed to support competence and career management in the Burkinabe civil service.
It provides a semantic reference model that enables:

Formal structuring of knowledge about jobs, job families, positions, competences, diplomas, and career paths.

Enhancing fairness, transparency, and relevance in recruitment, appointment, and assignment processes.

Facilitating interoperability across information systems (e.g., SIGASPE, RIME).

Supporting knowledge inference to uncover implicit competences and career development trajectories.

🎯 Objectives

Provide a controlled and shared vocabulary for the civil service domain.

Improve semantic matching between employee profiles and job requirements.

Encode regulatory rules to ensure compliance with legal frameworks.

Serve as a foundation for recommendation systems and knowledge graph integration.

📍 Scope

The ontology covers, but is not limited to, the following concepts:

Public servants (civil servants, contractors) and their attributes (grade, level).

Job positions and responsibilities, including title, hierarchy level, and access conditions.

Jobs and job families defined in the RIME (Interministerial Directory of State Jobs).

Competences (technical, behavioral, transversal) with associated proficiency levels.

⚠️ Excluded from the ontology scope: payroll processes, absence/time management, and purely financial or budgetary aspects.

🛠️ Implementation

Language: OWL 2 (OWL 2 DL profile)

Syntax: RDF/XML

Editor: Protégé

Reasoning: Business rules encoded via SWRL to reflect civil service regulations.

👥 Intended End-Users

Human Resources managers in public administrations.

Institutional decision-makers (ministers, general directors).

Developers and engineers in charge of maintaining and integrating the ontology into existing IS.

Civil servants consulting recommendations or updating their profiles.

📌 Intended Uses

Powering a semantic recommendation system for post–employee matching.

Serving as a semantic schema for integration and enrichment of data into a knowledge graph.

Supporting reasoning and inference (e.g., deducing competences from diplomas or work experience).

Facilitating the search and analysis of critical competences and career paths within the administration.

📂 Modular Architecture

The ontology is organized into five complementary modules:

Core – fundamental concepts (Agent, Position, Organization).

Competences – technical, behavioral, transversal competences and mastery levels.

Jobs – representation of jobs and job families from the RIME.

Career – career paths, mobility, and promotion rules.

Recruitment – appointment criteria, recruitment processes, and regulatory rules.

📖 Documentation

The Ontology Requirements Specification Document (ORSD), included in this repository, details objectives, scope, competency questions, and glossary.

✍️ Authors

Dr Wend-Panga Cédric BÉRÉ

Dr Yaya TRAORÉ

Dr Justin P. KOURAOGO