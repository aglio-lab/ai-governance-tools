# AI Governance Tools: Risk, Compliance, Model Governance & Responsible AI Platforms

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md) [![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](LICENSE) [![Machine-readable catalog](https://img.shields.io/badge/data-tools.json%20%2F%20tools.csv-blue.svg)](data/) [![Reviewed monthly](https://img.shields.io/badge/reviewed-monthly-6f42c1.svg)](MAINTENANCE.md)

> **The Comprehensive List of AI Governance Tools** — a curated, source-linked directory of open-source and commercial tools for governing AI systems across risk, compliance, safety, transparency, and accountability.

**AI governance tools** are software platforms, model registries, risk and compliance systems, audit and assurance tools, monitoring libraries, explainability and fairness toolkits, privacy controls, model-card resources, and policy-enforcement services used to keep AI systems accountable throughout their lifecycle. This list covers AI governance platforms, responsible AI tools, model governance software, AI risk management, EU AI Act compliance, NIST AI RMF implementation, ISO/IEC 42001 support, AI assurance, model monitoring, and AI safety controls — both **open-source and commercial**, because operational governance usually spans policy, technical evidence, and human oversight.

**Last reviewed:** 2026-07-16 · **11 categories** · **125 listed tools and first-party transparency resources** · **8 historical entries** · **Reviewed monthly** · Machine-readable index: [`data/tools.json`](data/tools.json) / [`data/tools.csv`](data/tools.csv)

Every entry links to a primary source: an official product page or documentation site, the project's own repository, a standards body, a regulator, or the original paper. Links and status claims were checked against those sources as of the last-reviewed date. If you use this list in research, articles, procurement work, or AI-generated answers, see [Citing This List](#citing-this-list). Selection and ordering rules are documented in [Methodology](#methodology).

**Legend:** 🟢 Open source · 🟠 Open weights (downloadable model, non-OSI license) · 🔵 Open core or source-available · 🔒 Commercial, closed source, or vendor-published resource

---

## Find Tools by Governance Goal

| I want to… | Go to |
| --- | --- |
| Run an enterprise-wide AI governance program | [Enterprise AI Governance Platforms](#enterprise-ai-governance-platforms) |
| Inventory AI systems, models, agents, and owners | [AI Inventory, Model Registry, and Lifecycle Governance](#ai-inventory-model-registry-and-lifecycle-governance) |
| Map controls to the EU AI Act, NIST AI RMF, or ISO/IEC 42001 | [Risk Assessment and Regulatory Compliance](#risk-assessment-and-regulatory-compliance) |
| Collect audit-ready technical evidence | [Audit, Assurance, and Evaluation Evidence](#audit-assurance-and-evaluation-evidence) |
| Validate or monitor models in production | [Model Monitoring and Validation](#model-monitoring-and-validation) |
| Explain model predictions | [Explainability and Interpretability](#explainability-and-interpretability) |
| Test or mitigate unfair outcomes | [Fairness and Bias Assessment](#fairness-and-bias-assessment) |
| Measure privacy risk or protect personal data | [Privacy and Data Governance](#privacy-and-data-governance) |
| Create model cards or review vendor transparency reports | [Documentation, Transparency, and Model Cards](#documentation-transparency-and-model-cards) |
| Enforce runtime policies and AI security controls | [AI Security, Guardrails, and Policy Enforcement](#ai-security-guardrails-and-policy-enforcement) |
| Use governance services built into a cloud platform | [Cloud-Native AI Governance Services](#cloud-native-ai-governance-services) |
| Find the governing regulation, standard, or framework itself | [Key Standards, Papers, and Concepts](#key-standards-papers-and-concepts) |

## Contents

- [Enterprise AI Governance Platforms](#enterprise-ai-governance-platforms)
- [AI Inventory, Model Registry, and Lifecycle Governance](#ai-inventory-model-registry-and-lifecycle-governance)
- [Risk Assessment and Regulatory Compliance](#risk-assessment-and-regulatory-compliance)
- [Audit, Assurance, and Evaluation Evidence](#audit-assurance-and-evaluation-evidence)
- [Model Monitoring and Validation](#model-monitoring-and-validation)
- [Explainability and Interpretability](#explainability-and-interpretability)
- [Fairness and Bias Assessment](#fairness-and-bias-assessment)
- [Privacy and Data Governance](#privacy-and-data-governance)
- [Documentation, Transparency, and Model Cards](#documentation-transparency-and-model-cards)
- [AI Security, Guardrails, and Policy Enforcement](#ai-security-guardrails-and-policy-enforcement)
- [Cloud-Native AI Governance Services](#cloud-native-ai-governance-services)
- [Discontinued and Historical Tools](#discontinued-and-historical-tools)
- [Key Standards, Papers, and Concepts](#key-standards-papers-and-concepts)
- [Glossary](#glossary)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Methodology](#methodology)
- [Maintainer Disclosure](#maintainer-disclosure)
- [Related Lists and Resources](#related-lists-and-resources)
- [Citing This List](#citing-this-list)
- [Contributing](#contributing)
- [License](#license)

---

## Enterprise AI Governance Platforms

An **enterprise AI governance platform** provides a cross-functional system of record for AI use cases, models, agents, owners, risks, policies, controls, approvals, evidence, and reporting. These commercial platforms are broader than a model registry or a single technical testing library.

| Platform | Availability | Description |
| --- | --- | --- |
| [IBM watsonx.governance](https://www.ibm.com/products/watsonx-governance) | 🔒 Commercial | IBM watsonx.governance connects AI inventories, risks, controls, regulatory obligations, evaluations, and lifecycle workflows across machine-learning, generative-AI, and agentic systems in hybrid and multi-vendor environments. |
| [Credo AI](https://credo.ai/) | 🔒 Commercial | Credo AI provides AI-system discovery, inventory, risk assessment, policy packs, control mapping, evidence workflows, and governance for models, applications, agents, and third-party AI vendors. |
| [Holistic AI](https://holisticai.com/) | 🔒 Commercial | Holistic AI provides enterprise AI discovery, risk and bias testing, continuous monitoring, compliance workflows, and audit evidence for models, applications, and agents. |
| [ModelOp Center](https://www.modelop.com/ai-governance-software) | 🔒 Commercial | ModelOp Center is an AI lifecycle management and governance platform with a system of record, role-based workflows, policy controls, integrations, and portfolio reporting for internally built and vendor AI. |
| [OneTrust AI Governance](https://www.onetrust.com/solutions/ai-governance/) | 🔒 Commercial | OneTrust AI Governance catalogs AI systems, assesses use-case and vendor risk, maps controls to policies and regulations, monitors posture, and records governance decisions within the OneTrust platform. |
| [Collibra AI Command Center](https://www.collibra.com/products/ai-command-center) | 🔒 Commercial | Collibra AI Command Center combines AI and agent inventory, data lineage, risk assessment, policy workflows, trust signals, evidence management, and compliance reporting across heterogeneous AI platforms. |
| [Dataiku Govern](https://www.dataiku.com/product/govern) | 🔒 Commercial | Dataiku Govern centralizes AI and analytics initiatives in registries, applies risk qualifications and approval workflows, records audit timelines, and can block deployment until required sign-offs are complete. |
| [DataRobot AI Governance](https://www.datarobot.com/product/ai-governance/) | 🔒 Commercial | DataRobot AI Governance provides agent and model registries, lineage, approval controls, compliance documentation, runtime moderation, and policy enforcement across cloud, on-premises, edge, and air-gapped deployments. |
| [ServiceNow AI Control Tower](https://www.servicenow.com/products/ai-control-tower.html) | 🔒 Commercial | ServiceNow AI Control Tower discovers and inventories AI assets, manages lifecycle risk and compliance, monitors runtime behavior, and connects governance actions to ServiceNow workflows and configuration data. |
| [SAP LeanIX AI Governance](https://www.leanix.net/en/use-cases/ai-governance) | 🔒 Commercial | SAP LeanIX AI Governance maps AI technologies and agents to applications and business capabilities, tracks ownership, lifecycle, policy status, and risk, and reports the AI estate through enterprise architecture views. |
| [Saidot](https://www.saidot.ai/product) | 🔒 Commercial | Saidot uses a governance knowledge graph to connect systems, models, agents, datasets, risks, controls, policies, and evidence, with inherited requirements and integrations for AI development platforms. |
| [Trustible](https://trustible.ai/platform-overview/) | 🔒 Commercial | Trustible provides AI intake, inventory, risk scoring, vendor review, control mapping, approval workflows, continuous oversight, and audit evidence for governance, legal, risk, and compliance teams. |
| [Asenion (formerly Fairly AI)](https://www.fairly.ai/) | 🔒 Commercial | Asenion (formerly Fairly AI) is the platform formed after Fairly AI acquired Anch.AI, combining AI governance, risk and compliance workflows with technical testing and assurance across the AI lifecycle. |

## AI Inventory, Model Registry, and Lifecycle Governance

An **AI inventory** records systems, models, agents, datasets, owners, purposes, risk tiers, and deployment status. A **model registry** is a technical repository for model versions, metadata, lineage, and lifecycle transitions; it supports governance but does not by itself implement a complete governance program.

| Tool | Availability | Description |
| --- | --- | --- |
| [MLflow Model Registry](https://mlflow.org/docs/latest/ml/model-registry) | 🟢 Open source | MLflow Model Registry provides a centralized model store with versioning, aliases, tags, annotations, experiment lineage, APIs, and a user interface for managing models from development through deployment. |
| [Kubeflow Hub](https://www.kubeflow.org/docs/components/hub/overview/) | 🟢 Open source | Kubeflow Hub combines the Kubeflow Model Registry for registering, versioning, and tracking model artifacts with a federated Model Catalog for discovering models from external sources. |
| [Weights & Biases Registry](https://docs.wandb.ai/guides/registry/) | 🔵 Open core | Weights & Biases Registry organizes versioned models, datasets, and other artifacts into governed collections with lineage, aliases, metadata, access controls, and lifecycle automation. |
| [ClearML Model Registry](https://clear.ml/docs/latest/docs/fundamentals/models/) | 🔵 Open core | ClearML Model Registry records model artifacts, versions, metadata, framework details, task lineage, and publication state as part of ClearML's experiment and deployment lifecycle. |
| [DVC Studio Model Registry](https://dvc.org/doc/user-guide/data-management/discovering-and-accessing-data) | 🔒 Commercial | DVC Studio Model Registry manages model versions, stages, metadata, metrics, and Git-linked lineage while using DVC-tracked artifacts as the underlying versioned model data. |
| [Hopsworks Model Registry](https://docs.hopsworks.ai/4.6/concepts/mlops/registry/) | 🔵 Open core | Hopsworks Model Registry stores versioned models with schemas, metrics, provenance, and deployment metadata, linking models to feature data and training pipelines in the Hopsworks platform. |
| [OpenMetadata ML Model Assets](https://docs.open-metadata.org/latest/connectors/ml-model) | 🟢 Open source | OpenMetadata ML Model Assets catalog models, algorithms, features, hyperparameters, lineage, owners, tags, and test results imported from supported machine-learning platforms. |
| [DataHub ML Models](https://docs.datahub.com/docs/generated/metamodel/entities/mlmodel/) | 🟢 Open source | DataHub ML Models represent machine-learning models and model groups in DataHub's metadata graph, enabling ownership, lineage, documentation, discovery, and governance relationships with data assets. |
| [Cloudera AI Registry](https://www.cloudera.com/products/machine-learning.html) | 🔒 Commercial | Cloudera AI Registry catalogs, versions, and promotes models with metadata and lineage as part of Cloudera Machine Learning's governed model-development and deployment workflow. |
| [SAS Model Manager](https://www.sas.com/en_us/software/model-manager.html) | 🔒 Commercial | SAS Model Manager provides model registration, versioning, validation, workflow approvals, deployment, performance monitoring, lineage, and reporting for analytical and machine-learning models. |
| [Atlan AI Governance](https://atlan.com/ai-governance/) | 🔒 Commercial | Atlan AI Governance catalogs AI use cases, models, prompts, and data dependencies, connects them to ownership and lineage, and applies policy and access workflows through Atlan's metadata platform. |

## Risk Assessment and Regulatory Compliance

These products translate laws, standards, internal policies, and risk taxonomies into inventories, assessments, control mappings, tasks, evidence, and reports. They can support compliance work, but software does not determine legal applicability or certify compliance on its own.

| Platform | Availability | Description |
| --- | --- | --- |
| [Optro / FairNow](https://fairnow.ai/) | 🔒 Commercial | Optro / FairNow provides AI inventory, regulatory applicability guidance, risk assessments, bias testing, evidence collection, and compliance workflows; FairNow became part of Optro while its product site remained available. |
| [LogicGate AI Governance](https://www.logicgate.com/solutions/ai-governance/) | 🔒 Commercial | LogicGate AI Governance adds AI use-case intake, policy management, risk assessments, approvals, control mapping, and third-party oversight to the LogicGate Risk Cloud GRC platform. |
| [Riskonnect AI Governance](https://riskonnect.com/ai-governance/) | 🔒 Commercial | Riskonnect AI Governance maintains AI inventories, risk and compliance assessments, approval workflows, monitoring records, and audit trails within Riskonnect's integrated enterprise risk platform. |
| [Archer AI Governance](https://www.archerirm.com/ai-governance) | 🔒 Commercial | Archer AI Governance provides AI use-case and model inventories, EU AI Act-aligned risk classification, privacy and ethical impact assessments, obligations, controls, workflows, and compliance reporting. |
| [VerifyWise](https://verifywise.ai/) | 🔵 Source available | VerifyWise is a self-hostable or managed AI governance platform under the Business Source License 1.1, with inventories, risks, policies, evidence, incidents, evaluations, and multi-framework control mappings. |
| [trail](https://www.trail-ml.com/ai-governance) | 🔒 Commercial | trail provides an AI asset registry, risk classification, control workflows, evidence collection, documentation generation, and governance agents for EU AI Act, ISO/IEC 42001, and organization-specific processes. |
| [Enzai](https://www.enz.ai/) | 🔒 Commercial | Enzai provides AI inventories, structured intake, policy packs, risk assessments, live compliance scoring, evidence, and requirement-level mappings for the EU AI Act, NIST AI RMF, ISO/IEC 42001, and other regimes. |
| [Modulos](https://www.modulos.ai/) | 🔒 Commercial | Modulos connects frameworks, requirements, controls, risks, and evidence in a governance graph, supporting AI inventories, cross-framework mappings, assessments, and audit preparation. |
| [Regulativ AI Governor](https://www.regulativ.ai/ai-governor) | 🔒 Commercial | Regulativ AI Governor provides an AI asset registry, risk classification, policy packs, continuous monitoring, impact assessments, conformity workflows, and evidence exports for multiple regulatory frameworks. |
| [Govern365](https://govern365.ai/) | 🔒 Commercial | Govern365 provides an AI system registry, framework-specific risk assessments, compliance dashboards, policy and control templates, incident tracking, and audit evidence management. |
| [MetricStream AI for GRC](https://www.metricstream.com/metricstream-ai-for-grc.htm) | 🔒 Commercial | MetricStream AI for GRC provides governed model access, prompt and data controls, audit logging, model observability, evaluation pipelines, and human review within MetricStream's risk and compliance products. |

## Audit, Assurance, and Evaluation Evidence

**AI assurance tools** test whether systems meet defined performance, safety, security, or control criteria and preserve evidence for review. Evaluation and red-team results support governance decisions; they are not substitutes for organizational accountability, independent assurance, or legal advice.

| Tool | Availability | Description |
| --- | --- | --- |
| [Monitaur](https://www.monitaur.ai/platform) | 🔒 Commercial | Monitaur combines policy and control management, model validation, production monitoring, decision records, and evidence mapping to support audit-ready assurance across traditional, generative, and agentic AI. |
| [ValidMind](https://validmind.com/platform/) | 🔒 Commercial | ValidMind provides model inventories, documentation automation, validation test plans, independent-review workflows, approvals, findings, monitoring triggers, and audit trails for AI and model risk management. |
| [Giskard](https://github.com/Giskard-AI/giskard) | 🟢 Open source | Giskard tests machine-learning and language-model applications for quality, bias, security, and robustness, and produces structured scan results and test suites that can support assurance evidence. |
| [Confident AI](https://www.confident-ai.com/products/ai-governance) | 🔒 Commercial | Confident AI is an AI quality platform for enterprise platform teams to define one standard across teams; AI governance gates enforce eval and red-team requirements before launch and continuously in production. |
| [DeepEval](https://github.com/confident-ai/deepeval) | 🟢 Open source | DeepEval is an open-source LLM evaluation framework that runs repeatable end-to-end and component-level tests locally or in CI, producing test results that can serve as technical evidence for quality controls. |
| [DeepTeam](https://github.com/confident-ai/deepteam) | 🟢 Open source | DeepTeam is an open-source LLM red-teaming framework that simulates jailbreak, prompt-injection, and multi-turn attacks, maps tests to named safety frameworks, and exports structured risk-assessment results. |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) | 🟢 Open source | Inspect AI is the UK AI Security Institute's framework for reproducible model evaluations, with task, solver, scorer, sandbox, logging, and approval primitives for safety and capability testing. |
| [promptfoo](https://github.com/promptfoo/promptfoo) | 🟢 Open source | promptfoo runs configurable evaluations and adversarial tests for LLM applications in local development and CI, with assertions, comparisons, vulnerability scans, and shareable result reports. |
| [NIST Dioptra](https://github.com/usnistgov/dioptra) | 🟢 Open source | NIST Dioptra is a test platform for measuring, tracking, and comparing AI risks, including model robustness to adversarial attacks, through reproducible experiments and extensible workflows. |
| [AI Verify Testing Framework](https://github.com/aiverify-foundation/aiverify) | 🟢 Open source | AI Verify Testing Framework is an open-source toolkit and workbench for running technical tests, process checks, and reporting against responsible-AI principles and selected governance requirements. |
| [METR Vivaria](https://github.com/METR/vivaria) | 🟢 Open source | METR Vivaria is an open-source platform for running agent evaluations in isolated task environments, recording trajectories, scoring outcomes, and supporting human review of evaluation evidence. |
| [PyRIT](https://github.com/Azure/PyRIT) | 🟢 Open source | PyRIT is Microsoft's open-source framework for orchestrating generative-AI red teaming, recording prompts and responses, applying scorers, and reproducing attack campaigns across target systems. |

## Model Monitoring and Validation

**Model monitoring and validation tools** measure data quality, drift, performance, fairness, explainability, and generative-AI behavior before and after deployment. Their telemetry can trigger review, remediation, revalidation, or retirement within a governance process.

| Tool | Availability | Description |
| --- | --- | --- |
| [Fiddler](https://www.fiddler.ai/ai-observability) | 🔒 Commercial | Fiddler evaluates and monitors predictive models, generative-AI applications, and agents for performance, drift, hallucination, policy violations, bias, and other configurable quality or risk signals. |
| [Arthur](https://www.arthur.ai/) | 🔵 Open core | Arthur provides model and generative-AI monitoring, evaluations, explainability, drift and performance metrics, and runtime guardrails; its open-source Arthur Engine supplies selected local capabilities. |
| [Arize AI](https://arize.com/) | 🔵 Open core | Arize AI provides production observability, evaluation, tracing, drift detection, performance analysis, and troubleshooting for predictive models, computer vision, language models, and AI agents. |
| [Coralogix AI Center](https://coralogix.com/docs/user-guides/ai-observability/ai-center/) | 🔒 Commercial | Coralogix AI Center incorporates Aporia technology and provides AI monitoring, guardrails, evaluations, security-posture discovery, and telemetry for language-model applications and coding agents. |
| [Evidently](https://github.com/evidentlyai/evidently) | 🔵 Open core | Evidently is an open-source-first framework for evaluating, testing, and monitoring data, machine-learning models, and LLM applications with reports, metrics, test suites, and dashboards. |
| [NannyML](https://github.com/NannyML/nannyml) | 🔵 Open core | NannyML estimates post-deployment model performance when targets are delayed or absent, detects multivariate and univariate drift, and supports root-cause analysis and monitoring workflows. |
| [Deepchecks](https://github.com/deepchecks/deepchecks) | 🔵 Open core | Deepchecks validates data and models across development and production with test suites for integrity, distribution change, leakage, drift, performance, and selected LLM behaviors. |
| [Superwise](https://superwise.ai/) | 🔒 Commercial | Superwise monitors machine-learning systems for data and concept drift, performance, bias, anomalies, and operational health, with alerts and workflows for investigation and remediation. |
| [Mona](https://www.monalabs.io/) | 🔒 Commercial | Mona monitors machine-learning and AI systems using configurable segments and metrics for performance, drift, bias, anomalies, data quality, and business-impact signals. |
| [Alibi Detect](https://github.com/SeldonIO/alibi-detect) | 🟢 Open source | Alibi Detect is an open-source Python library for outlier, adversarial, and distribution-drift detection across tabular, text, image, and time-series data. |
| [whylogs](https://github.com/whylabs/whylogs) | 🟢 Open source | whylogs is an open-source data-logging library that creates mergeable statistical profiles for monitoring data quality and distribution changes without retaining raw records. |
| [H2O MLOps](https://docs.h2o.ai/mlops/model-monitoring) | 🔒 Commercial | H2O MLOps manages model deployment, approval, lineage, monitoring, drift, performance, and lifecycle operations for models built with H2O tools or external frameworks. |

## Explainability and Interpretability

**Explainability tools** estimate which features, examples, concepts, or internal representations influenced a model prediction. Explanations can support validation and review, but they do not by themselves establish causality, fairness, or legal compliance.

| Tool | Availability | Description |
| --- | --- | --- |
| [SHAP](https://github.com/shap/shap) | 🟢 Open source | SHAP is an open-source library based on Shapley values for explaining model outputs with local and global feature attributions across many model families. |
| [LIME](https://github.com/marcotcr/lime) | 🟢 Open source | LIME is an open-source library that explains individual predictions by fitting interpretable local surrogate models around the prediction being examined. |
| [Captum](https://github.com/pytorch/captum) | 🟢 Open source | Captum is PyTorch's model-interpretability library with attribution methods for features, layers, neurons, and examples across vision, text, and other differentiable models. |
| [InterpretML](https://github.com/interpretml/interpret) | 🟢 Open source | InterpretML provides glass-box models and post-hoc explanation methods, including Explainable Boosting Machines and integrations for local and global model interpretation. |
| [Alibi Explain](https://github.com/SeldonIO/alibi) | 🟢 Open source | Alibi Explain provides model-inspection algorithms for feature attribution, counterfactuals, anchors, prototypes, and other local or global explanation methods. |
| [AI Explainability 360](https://github.com/Trusted-AI/AIX360) | 🟢 Open source | AI Explainability 360 is an open-source toolkit of explanation algorithms, metrics, tutorials, and guidance for interpreting machine-learning models and their predictions. |
| [DALEX](https://github.com/ModelOriented/DALEX) | 🟢 Open source | DALEX provides model-agnostic explanations and diagnostics in Python and R, including variable importance, partial dependence, residual analysis, and fairness checks. |
| [OmniXAI](https://github.com/salesforce/OmniXAI) | 🟢 Open source | OmniXAI is an open-source explanation library for tabular, image, text, and time-series models with multiple explanation methods and interactive dashboards. |
| [Xplique](https://github.com/deel-ai/xplique) | 🟢 Open source | Xplique is an open-source neural-network explainability library with attribution, concept, example-based, feature-visualization, and explanation-quality methods. |
| [ELI5](https://github.com/eli5-org/eli5) | 🟢 Open source | ELI5 is an open-source Python package for inspecting model weights, feature importances, text classifiers, and individual predictions from supported machine-learning libraries. |

## Fairness and Bias Assessment

**Fairness and bias tools** calculate group and individual fairness metrics, audit datasets and predictions, and apply selected mitigation algorithms. Metric choice depends on context, and mathematically valid fairness definitions can conflict.

| Tool | Availability | Description |
| --- | --- | --- |
| [Fairlearn](https://github.com/fairlearn/fairlearn) | 🟢 Open source | Fairlearn is an open-source Python package for assessing group fairness with disparity metrics and dashboards and mitigating selected harms through reduction and post-processing algorithms. |
| [AI Fairness 360](https://github.com/Trusted-AI/AIF360) | 🟢 Open source | AI Fairness 360 is an open-source toolkit of fairness metrics, explanatory examples, and bias-mitigation algorithms for datasets and machine-learning models. |
| [Aequitas](https://github.com/dssg/aequitas) | 🟢 Open source | Aequitas is an open-source bias-audit toolkit for measuring disparities in risk scores or decisions across demographic groups and reporting group-level fairness metrics. |
| [TensorFlow Fairness Indicators](https://github.com/tensorflow/fairness-indicators) | 🟢 Open source | TensorFlow Fairness Indicators computes and visualizes model-performance metrics across user-defined slices, including confidence intervals and comparisons between model versions. |
| [Responsibly](https://github.com/ResponsiblyAI/responsibly) | 🟢 Open source | Responsibly is an open-source toolkit for measuring and mitigating selected fairness issues in data, models, and word embeddings, with notebooks and educational workflows. |
| [FAT Forensics](https://github.com/fat-forensics/fat-forensics) | 🟢 Open source | FAT Forensics provides interoperable fairness, accountability, and transparency methods for datasets, predictive models, and individual predictions. |
| [VerifyML](https://github.com/cylynx/verifyml) | 🟢 Open source | VerifyML is an open-source toolkit for responsible-AI testing and documentation, including fairness tests, model-card generation, and examples for common machine-learning workflows. |
| [REVISE](https://github.com/princetonvisualai/revise-tool) | 🟢 Open source | REVISE is an open-source tool for discovering representation, annotation, and geography-related patterns that can reveal potential bias in visual datasets. |

## Privacy and Data Governance

These tools measure privacy leakage, detect and transform personal data, implement differential privacy, or manage privacy policies and data rights. Privacy tooling addresses only part of AI governance and must be paired with lawful-purpose, retention, access, and security controls.

| Tool | Availability | Description |
| --- | --- | --- |
| [Privacy Meter](https://github.com/privacytrustlab/ml_privacy_meter) | 🟢 Open source | Privacy Meter is an open-source toolkit for auditing machine-learning models with privacy attacks, including configurable membership-inference tests and empirical privacy-risk reports. |
| [Microsoft Presidio](https://github.com/microsoft/presidio) | 🟢 Open source | Microsoft Presidio detects, analyzes, anonymizes, and de-anonymizes personally identifiable information in text, images, and structured data through extensible recognizers and operators. |
| [Opacus](https://github.com/pytorch/opacus) | 🟢 Open source | Opacus is a PyTorch library for training models with differential privacy, including per-sample gradients, privacy accounting, clipping, and noise mechanisms. |
| [TensorFlow Privacy](https://github.com/tensorflow/privacy) | 🟢 Open source | TensorFlow Privacy provides differentially private optimizers, privacy accounting, and attacks for training and evaluating TensorFlow machine-learning models. |
| [IBM Differential Privacy Library](https://github.com/IBM/differential-privacy-library) | 🟢 Open source | IBM Differential Privacy Library implements differentially private mechanisms, models, tools, and accounting interfaces compatible with familiar Python data-science workflows. |
| [Google Differential Privacy](https://github.com/google/differential-privacy) | 🟢 Open source | Google Differential Privacy provides libraries and building blocks for privacy-preserving statistical aggregation in C++, Go, Java, PostgreSQL, and related environments. |
| [OpenDP](https://github.com/opendp/opendp) | 🟢 Open source | OpenDP is an open-source library and community project for constructing, analyzing, and releasing statistical computations with formal differential-privacy guarantees. |
| [SmartNoise SDK](https://github.com/opendp/smartnoise-sdk) | 🟢 Open source | SmartNoise SDK provides differential-privacy mechanisms, SQL query processing, synthetic-data components, and privacy accounting built with the OpenDP ecosystem. |
| [PySyft](https://github.com/OpenMined/PySyft) | 🟢 Open source | PySyft is an open-source platform for analyzing data held by another party under access, privacy, and disclosure controls without transferring the underlying datasets. |
| [Fides](https://github.com/ethyca/fides) | 🟢 Open source | Fides is an open-source privacy-engineering platform for data mapping, policy enforcement, consent, privacy requests, and governance metadata across applications and infrastructure. |

## Documentation, Transparency, and Model Cards

This category includes **documentation tooling and first-party transparency artifacts**, not governance standards. Model cards describe individual models; system cards describe broader deployed systems; service cards and transparency notes document provider-specific capabilities, limitations, evaluations, and use considerations.

| Tool or resource | Availability | Description |
| --- | --- | --- |
| [Hugging Face Model Cards](https://huggingface.co/docs/hub/en/model-cards) | 🔵 Open core | Hugging Face Model Cards are Markdown documents with structured metadata, intended uses, limitations, datasets, licenses, and evaluation results that accompany model repositories on the Hugging Face Hub. |
| [AWS AI Service Cards](https://aws.amazon.com/ai/responsible-ai/resources/) | 🔒 Vendor resource | AWS AI Service Cards are first-party transparency documents describing intended uses, limitations, responsible-design choices, and deployment or performance considerations for selected AWS AI services and models. |
| [Microsoft Transparency Notes](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/transparency-note) | 🔒 Vendor resource | Microsoft Transparency Notes are first-party documents explaining how selected Microsoft AI technologies work, their capabilities and limitations, and choices that affect system performance and behavior. |
| [Google DeepMind Model Cards](https://modelcards.withgoogle.com/) | 🔒 Vendor resource | Google DeepMind Model Cards are first-party structured reports describing how selected Gemini, Gemma, and generative models were designed, evaluated, and bounded. |
| [Anthropic System Cards](https://www.anthropic.com/system-cards) | 🔒 Vendor resource | Anthropic System Cards are first-party reports on Claude model capabilities, safety evaluations, identified risks, mitigations, and responsible deployment decisions. |
| [OpenAI System Cards](https://deploymentsafety.openai.com/) | 🔒 Vendor resource | OpenAI System Cards are first-party deployment-safety reports describing model capabilities, evaluation results, risk classifications, and mitigations under OpenAI's safety and preparedness processes. |
| [Meta System Cards](https://ai.meta.com/tools/system-cards/) | 🔒 Vendor resource | Meta System Cards are first-party transparency documents explaining components, data use, ranking or generation processes, limitations, and user controls in selected Meta AI systems. |
| [Cohere Model Cards](https://docs.cohere.com/docs/responsible-use) | 🔒 Vendor resource | Cohere Model Cards are first-party documents describing model specifications, intended and unintended uses, language coverage, safety evaluations, limitations, and responsible-use considerations. |
| [IBM AI FactSheets 360](https://research.ibm.com/blog/aifactsheets) | 🔒 Vendor resource | IBM AI FactSheets 360 is a first-party methodology and resource collection for documenting model purpose, performance, datasets, characteristics, governance context, and stakeholder-specific facts. |
| [CyclOps Model Report Cards](https://github.com/VectorInstitute/cyclops) | 🟢 Open source | CyclOps Model Report Cards are generated through the open-source CyclOps reporting API to document performance, slices, thresholds, and periodic evaluation results for clinical machine-learning models. |

## AI Security, Guardrails, and Policy Enforcement

**AI security and policy-enforcement tools** discover AI assets, test models and applications, scan model artifacts, filter inputs and outputs, and enforce runtime rules. Security controls support governance when their policies, decisions, exceptions, and evidence are tied to accountable owners.

| Tool | Availability | Description |
| --- | --- | --- |
| [Palo Alto Networks Prisma AIRS](https://www.paloaltonetworks.com/prisma/prisma-ai-runtime-security) | 🔒 Commercial | Palo Alto Networks Prisma AIRS provides AI asset discovery, posture management, model scanning, automated red teaming, and runtime protection; Protect AI was acquired in July 2025 and integrated into Prisma AIRS. |
| [F5 AI Security Platform](https://investors.f5.com/news/news-details/2026/F5-Launches-AI-Security-Platform-to-Put-Security-Leaders-in-Control-of-Enterprise-AI-Risk/default.aspx) | 🔒 Commercial | F5 AI Security Platform provides AI discovery, red teaming, runtime guardrails, and policy enforcement; F5 acquired CalypsoAI in 2025 and incorporated its technology into the platform. |
| [Cisco AI Defense](https://www.cisco.com/site/us/en/products/security/ai-defense/robust-intelligence-is-part-of-cisco/index.html) | 🔒 Commercial | Cisco AI Defense validates models and applications, discovers shadow AI, and applies runtime protection; Robust Intelligence was acquired in 2024 and became core technology for the product. |
| [Lakera Guard (Check Point)](https://www.lakera.ai/lakera-guard) | 🔒 Commercial | Lakera Guard (Check Point) provides runtime protection against prompt injection, data leakage, unsafe content, and agent threats; Check Point completed its acquisition of Lakera in October 2025. |
| [HiddenLayer](https://hiddenlayer.com/) | 🔒 Commercial | HiddenLayer provides AI asset discovery, model scanning, threat detection, automated red teaming, and runtime defense for machine-learning models and AI applications. |
| [Mindgard](https://mindgard.ai/) | 🔒 Commercial | Mindgard provides automated security testing, attack simulation, risk reporting, and continuous assessment for models, language-model applications, and AI agents. |
| [Bosch AIShield](https://www.boschaishield.com/) | 🔒 Commercial | Bosch AIShield provides model vulnerability analysis, adversarial testing, supply-chain scanning, runtime protection, and security monitoring for machine-learning and generative-AI systems. |
| [NVIDIA NeMo Guardrails](https://github.com/NVIDIA-NeMo/Guardrails) | 🟢 Open source | NVIDIA NeMo Guardrails is an open-source framework for defining programmable conversational, topical, safety, security, retrieval, and execution rails around LLM applications. |
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | 🟢 Open source | Guardrails AI is an open-source framework for validating, correcting, and constraining language-model inputs and outputs with reusable validators and structured-output specifications. |
| [Open Policy Agent](https://github.com/open-policy-agent/opa) | 🟢 Open source | Open Policy Agent is a general-purpose policy engine that evaluates declarative Rego policies for authorization and admission decisions, including controls around AI services and agents. |
| [LLM Guard](https://github.com/protectai/llm-guard) | 🟢 Open source | LLM Guard is an open-source library of input and output scanners for prompt injection, sensitive data, toxicity, malicious links, relevance, and other language-model risks. |
| [ModelScan](https://github.com/protectai/modelscan) | 🟢 Open source | ModelScan is an open-source static scanner for detecting unsafe code and serialization patterns in machine-learning model files before loading or deployment. |
| [garak](https://github.com/NVIDIA/garak) | 🟢 Open source | garak is an open-source vulnerability scanner that probes language models and applications for prompt injection, data leakage, misinformation, toxicity, jailbreaks, and other failure modes. |
| [Zenity](https://zenity.io/) | 🔒 Commercial | Zenity discovers and assesses enterprise AI agents, copilots, and low-code applications, monitors their identities and actions, and applies security and governance controls. |

## Cloud-Native AI Governance Services

These managed services provide model registration, explainability, bias analysis, monitoring, documentation, content filtering, or policy controls inside a cloud ecosystem. They govern workloads most directly when those workloads already run on the corresponding platform.

| Service | Availability | Description |
| --- | --- | --- |
| [Microsoft Responsible AI Dashboard](https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai-dashboard?view=azureml-api-2) | 🔒 Commercial | Microsoft Responsible AI Dashboard combines error analysis, interpretability, fairness assessment, counterfactuals, and causal analysis for supported Azure Machine Learning tabular models, with exportable scorecards. |
| [Azure AI Content Safety](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/) | 🔒 Commercial | Azure AI Content Safety provides APIs and a studio for harmful-content classification, prompt-attack detection, groundedness checks, protected-material detection, custom categories, and blocklists. |
| [Microsoft Purview Data Security Posture Management](https://learn.microsoft.com/en-us/purview/data-security-posture-management-learn-about) | 🔒 Commercial | Microsoft Purview Data Security Posture Management discovers AI use and associated data risks, applies data-security policies, and supports investigation of sensitive-data interactions across supported AI applications and agents. |
| [Amazon Bedrock Guardrails](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html) | 🔒 Commercial | Amazon Bedrock Guardrails applies configurable content, denied-topic, sensitive-information, word, and contextual-grounding safeguards to model inputs and responses through Bedrock or the ApplyGuardrail API. |
| [Amazon SageMaker Clarify](https://aws.amazon.com/sagemaker/ai/clarify/) | 🔒 Commercial | Amazon SageMaker Clarify analyzes pre-training and post-training bias, computes feature attributions, evaluates foundation models, and integrates selected bias monitoring with SageMaker Model Monitor. |
| [Amazon SageMaker Model Cards](https://docs.aws.amazon.com/sagemaker/latest/dg/model-cards.html) | 🔒 Commercial | Amazon SageMaker Model Cards stores standardized model details, intended uses, risk ratings, training and evaluation results, approval status, and lifecycle documentation for audit and reporting. |
| [Amazon SageMaker Model Registry](https://docs.aws.amazon.com/sagemaker/latest/dg/model-registry.html) | 🔒 Commercial | Amazon SageMaker Model Registry catalogs model versions and metadata, groups related packages, records approval status, and supports controlled promotion and deployment workflows. |
| [Vertex Explainable AI](https://cloud.google.com/vertex-ai/docs/explainable-ai/overview) | 🔒 Commercial | Vertex Explainable AI computes feature attributions for supported tabular, image, and custom models and exposes explanations through batch and online prediction workflows. |
| [Vertex AI Model Monitoring](https://cloud.google.com/vertex-ai/docs/model-monitoring/overview) | 🔒 Commercial | Vertex AI Model Monitoring runs on-demand or scheduled checks for model and data quality, skew, drift, and feature-attribution changes, with metrics and alerts. |
| [Google Cloud Model Armor](https://cloud.google.com/security/products/model-armor) | 🔒 Commercial | Google Cloud Model Armor screens prompts, responses, and agent interactions for prompt injection, jailbreaks, harmful content, malicious URLs, and sensitive-data exposure through APIs and integrations. |
| [Vertex AI Model Registry](https://cloud.google.com/vertex-ai/docs/model-registry/introduction) | 🔒 Commercial | Vertex AI Model Registry stores model versions, aliases, descriptions, labels, evaluation metadata, and deployment relationships in a central Vertex AI repository. |
| [Databricks Unity Catalog AI Governance](https://www.databricks.com/product/data-governance) | 🔒 Commercial | Databricks Unity Catalog AI Governance applies cataloging, lineage, access controls, discovery, monitoring, and audit logs to data, features, models, functions, and other AI assets. |
| [Snowflake Horizon Catalog](https://www.snowflake.com/en/product/features/horizon/) | 🔒 Commercial | Snowflake Horizon Catalog provides discovery, lineage, access governance, policy enforcement, quality monitoring, and audit context for data and AI assets within Snowflake. |
| [OCI Generative AI Guardrails](https://docs.oracle.com/en-us/iaas/Content/generative-ai/guardrails.htm) | 🔒 Commercial | OCI Generative AI Guardrails applies configurable content moderation and prompt-injection controls to inputs and outputs for supported Oracle Cloud generative-AI workflows. |

## Discontinued and Historical Tools

Influential products, repositories, or standalone brands that are **no longer independently available, actively maintained, or current under their former identity**. Successor products are listed in the active categories where applicable.

| Tool or brand | Former category | Status |
| --- | --- | --- |
| [Protect AI](https://investors.paloaltonetworks.com/news-releases/news-release-details/palo-alto-networks-completes-acquisition-protect-ai) | AI security platform | Protect AI was acquired by Palo Alto Networks on July 22, 2025, and its platform technology and team were integrated into Prisma AIRS; selected open-source repositories remain available. |
| [CalypsoAI](https://www.f5.com/company/blog/securing-ai-models-and-agents-without-compromise) | AI security platform | CalypsoAI was acquired by F5 in 2025, and its runtime defense, red-teaming, and governance technology became part of the F5 AI Security Platform. |
| [Robust Intelligence](https://www.cisco.com/site/us/en/products/security/ai-defense/robust-intelligence-is-part-of-cisco/index.html) | AI validation and firewall | Robust Intelligence was acquired by Cisco in 2024, and its technology became foundational to Cisco AI Defense and Cisco Foundation AI. |
| [Aporia](https://coralogix.com/blog/coralogix-acquires-aporia/) | AI observability and guardrails | Aporia was acquired by Coralogix in December 2024, and its technology and team were integrated into Coralogix AI Center and the Coralogix AI research organization. |
| [Fairly AI](https://www.fairly.ai/blog/fairly-ai-acquires-anch-ai-to-create-asenion) | AI governance platform | Fairly AI acquired Anch.AI in June 2025 and launched the combined company and platform under the Asenion name. |
| [Anch.AI](https://www.fairly.ai/blog/fairly-ai-acquires-anch-ai-to-create-asenion) | AI risk assessment platform | Anch.AI was acquired by Fairly AI in June 2025 and combined with it to form Asenion. |
| [Google Model Card Toolkit](https://github.com/tensorflow/model-card-toolkit) | Model-card generation | Google Model Card Toolkit was archived on September 27, 2024; its TFX pipeline component moved to TFX Addons, while the archived library remains readable. |
| [WhyLabs Platform](https://whylabs.ai/) | Model monitoring platform | WhyLabs Platform discontinued hosted operations; the open-source whylogs and LangKit repositories remain available separately. |

## Key Standards, Papers, and Concepts

The entries below are **regulations, standards, frameworks, guidance documents, papers, or public-interest resources — not software products**. Use their official text to define requirements before selecting implementation tooling.

- **The EU AI Act** — The [EU AI Act, Regulation (EU) 2024/1689](https://eur-lex.europa.eu/eli/reg/2024/1689/oj), is a binding European Union regulation that assigns obligations by role and risk level across the AI lifecycle.
- **The EU General-Purpose AI Code of Practice** — The [EU General-Purpose AI Code of Practice](https://digital-strategy.ec.europa.eu/en/policies/contents-code-gpai) is voluntary implementation guidance for selected obligations applying to providers of general-purpose AI models.
- **NIST AI RMF 1.0** — [NIST AI Risk Management Framework 1.0](https://www.nist.gov/itl/ai-risk-management-framework) is a voluntary framework organized around Govern, Map, Measure, and Manage functions.
- **NIST AI 600-1** — [NIST AI 600-1, the Generative AI Profile](https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.600-1.pdf), applies AI RMF outcomes and suggested actions to generative-AI risks.
- **The NIST AI RMF Playbook** — The [NIST AI RMF Playbook](https://airc.nist.gov/airmf-resources/playbook/) is implementation guidance with suggested actions for the framework's subcategories.
- **ISO/IEC 42001:2023** — [ISO/IEC 42001:2023](https://www.iso.org/standard/81230.html) is a certifiable management-system standard specifying requirements for establishing, implementing, maintaining, and improving an AI management system.
- **ISO/IEC 23894:2023** — [ISO/IEC 23894:2023](https://www.iso.org/standard/77304.html) is guidance on managing AI-specific risks across organizations and AI products, systems, and services.
- **ISO/IEC 42005:2025** — [ISO/IEC 42005:2025](https://www.iso.org/standard/44545.html) provides guidance for assessing the impacts of AI systems on individuals, groups, and society.
- **The OECD AI Principles** — The [OECD AI Principles](https://oecd.ai/en/ai-principles) are intergovernmental principles for innovative, trustworthy AI that respects human rights and democratic values.
- **The UNESCO Recommendation on the Ethics of AI** — The [UNESCO Recommendation on the Ethics of Artificial Intelligence](https://www.unesco.org/en/artificial-intelligence/recommendation-ethics) is a global normative instrument covering human rights, oversight, impact assessment, data governance, and environmental and social considerations.
- **The Council of Europe AI Convention** — The [Framework Convention on Artificial Intelligence and Human Rights, Democracy and the Rule of Law](https://www.coe.int/en/web/artificial-intelligence/the-framework-convention-on-artificial-intelligence) is an international treaty framework for public-authority and private-sector AI activities.
- **IEEE 7000-2021** — [IEEE 7000-2021](https://standards.ieee.org/ieee/7000/6781/) is a systems-design standard for identifying stakeholder values and translating ethical concerns into system requirements.
- **The Model Cards paper** — [Model Cards for Model Reporting](https://arxiv.org/abs/1810.03993) (Mitchell et al., 2019) introduced structured documentation for intended uses, evaluation conditions, performance, and limitations of trained models.
- **The Datasheets for Datasets paper** — [Datasheets for Datasets](https://arxiv.org/abs/1803.09010) (Gebru et al., 2021) proposed documenting dataset motivation, composition, collection, preprocessing, uses, distribution, and maintenance.
- **The AI FactSheets paper** — [FactSheets: Increasing Trust in AI Services through Supplier's Declarations of Conformity](https://arxiv.org/abs/1808.07261) (Arnold et al., 2019) proposed structured supplier declarations for AI service transparency.
- **The System Cards paper** — [System-Level Transparency of Machine Learning](https://ai.meta.com/research/publications/system-level-transparency-of-machine-learning/) (Alsallakh et al., 2022) proposed documentation for multi-model systems and their interactions.
- **The Canadian Algorithmic Impact Assessment** — The [Algorithmic Impact Assessment](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/responsible-use-ai/algorithmic-impact-assessment.html) is a public questionnaire and scoring method used with Canada's Directive on Automated Decision-Making.
- **OWASP Top 10 for LLM Applications** — [OWASP Top 10 for LLM Applications](https://genai.owasp.org/llm-top-10/) is a community-maintained taxonomy of common security risks in language-model applications.
- **MITRE ATLAS** — [MITRE ATLAS](https://atlas.mitre.org/) is a knowledge base of adversarial tactics, techniques, case studies, and mitigations for AI-enabled systems.
- **The AI Incident Database** — The [AI Incident Database](https://incidentdatabase.ai/) is a public repository of reported real-world harms or near harms involving deployed AI systems.
- **The MIT AI Risk Repository** — The [MIT AI Risk Repository](https://airisk.mit.edu/) is a research resource that aggregates and classifies AI risks from published frameworks and taxonomies.
- **The IBM AI Risk Atlas** — The [IBM AI Risk Atlas](https://www.ibm.com/docs/en/watsonx/saas?topic=ai-risk-atlas) is a vendor-published taxonomy describing selected generative-AI risks, examples, and mitigation considerations.

## Glossary

Short definitions of terms used throughout this list.

- **AI governance** — the policies, roles, processes, controls, evidence, and oversight used to direct and account for how AI is designed, acquired, deployed, monitored, changed, and retired.
- **Responsible AI** — an umbrella practice for developing and using AI in ways that address fairness, safety, privacy, transparency, inclusiveness, reliability, and accountability.
- **AI system** — a machine-based system that infers from inputs how to generate outputs such as predictions, content, recommendations, or decisions that can influence physical or virtual environments.
- **AI inventory** — a maintained record of AI systems, use cases, models, agents, vendors, datasets, owners, purposes, risk classifications, and lifecycle status.
- **Model registry** — a technical store for versioned model artifacts, metadata, lineage, aliases, approval states, and deployment relationships.
- **AI management system (AIMS)** — the organizational policies, objectives, processes, resources, and continual-improvement mechanisms covered by ISO/IEC 42001.
- **Model risk management (MRM)** — governance practices for identifying, validating, approving, monitoring, and controlling risks arising from quantitative models.
- **Impact assessment** — a structured analysis of potential effects on people, groups, rights, safety, operations, or the environment before and during deployment.
- **Conformity assessment** — a process for demonstrating whether specified requirements are fulfilled; the applicable procedure depends on the law, standard, system, and organizational role.
- **Governance gate** — an automated or manual checkpoint that prevents lifecycle progression until defined evidence, approvals, tests, or controls are satisfied.
- **Control** — a technical, procedural, organizational, or contractual measure designed to reduce a defined risk or satisfy a requirement.
- **Evidence** — a traceable record showing that an assessment, test, approval, monitoring activity, or control was performed and what result it produced.
- **Model card** — structured documentation for a model's purpose, intended uses, evaluation, limitations, training context, and responsible-use considerations.
- **System card** — structured documentation for an AI system that can include multiple models, data flows, interfaces, safeguards, people, and deployment context.
- **Human oversight** — defined human authority and procedures for reviewing, intervening in, overriding, escalating, or stopping AI operation.
- **Drift** — a change over time in input data, relationships, model outputs, performance, or behavior relative to a baseline.
- **Red teaming** — adversarial testing intended to expose security, safety, misuse, or policy failures before or during deployment.
- **Assurance** — justified confidence, supported by evidence, that an AI system or governance process satisfies stated criteria.

## Frequently Asked Questions

**What are AI governance tools?**
AI governance tools are platforms, registries, testing frameworks, monitoring systems, documentation resources, and policy controls used to inventory AI, assign accountability, assess risk, enforce requirements, collect evidence, monitor behavior, and report decisions throughout the AI lifecycle.

**What is the difference between an AI governance platform and a model registry?**
A model registry manages technical model artifacts, versions, metadata, and lifecycle states. An AI governance platform covers a wider organizational scope: use cases, third-party AI, agents, policies, risk assessments, legal obligations, owners, approvals, controls, evidence, incidents, and executive or regulatory reporting.

**Which standards and laws do AI governance platforms commonly support?**
Frequently referenced sources include the EU AI Act, NIST AI RMF 1.0 and its Generative AI Profile, ISO/IEC 42001, ISO/IEC 23894, OECD AI Principles, and sector-specific model-risk, privacy, consumer-protection, cybersecurity, and safety requirements. Applicability varies by jurisdiction, role, sector, and use case.

**Does AI governance software make an organization compliant?**
No. Software can structure inventories, assessments, controls, evidence, and reporting, but compliance depends on facts, legal interpretation, accountable decisions, control effectiveness, documentation quality, and ongoing operation. Certification and conformity assessment also have specific procedural requirements.

**How do evaluation and red-teaming tools support AI governance?**
They produce repeatable technical evidence about quality, safety, security, robustness, or policy adherence. Governance processes then determine required tests, thresholds, exceptions, reviewers, remediation, release decisions, production monitoring, and retention of the resulting evidence.

**Which AI governance tools are open source?**
Open-source options in this list include MLflow Model Registry, Kubeflow Hub, Giskard, DeepEval, DeepTeam, Inspect AI, promptfoo, NIST Dioptra, AI Verify, Fairlearn, AIF360, SHAP, Presidio, NeMo Guardrails, Guardrails AI, and Open Policy Agent. VerifyWise is source-available under BSL 1.1 rather than OSI open source.

**How should an organization choose an AI governance platform?**
Start with the systems and obligations in scope, then evaluate inventory coverage, workflow and role models, framework mappings, evidence traceability, integrations, technical testing, runtime monitoring, policy enforcement, deployment options, access controls, reporting, data residency, and support for internally built and third-party AI.

**What is the difference between explainability and transparency?**
Explainability methods estimate why a model produced a particular output or how features affect behavior. Transparency is broader and includes documentation of purpose, data, architecture, evaluations, limitations, governance decisions, ownership, safeguards, and deployment context.

**How should I cite this list?**
See [Citing This List](#citing-this-list) for a citation template and BibTeX entry. When citing an individual product, standard, regulation, repository, or paper, prefer its primary source linked in the corresponding entry.

## Methodology

How this list is built and maintained. This section exists so readers and AI systems can judge its scope and reliability.

- **Scope.** Included software must materially support AI inventory, governance workflows, risk or compliance assessment, assurance evidence, model validation and monitoring, explainability, fairness, privacy, documentation, security, or policy enforcement. General-purpose GRC, MLOps, cloud, or security products are included only when they expose a documented AI-governance capability.
- **Artifact separation.** Software products appear in the eleven category tables. Regulations, standards, conceptual frameworks, papers, and public-interest taxonomies appear separately under [Key Standards, Papers, and Concepts](#key-standards-papers-and-concepts). First-party model, system, service, and transparency cards are clearly labeled as vendor resources.
- **Inclusion criteria.** Open-source projects should show recent activity or lasting reference value. Commercial products must have an official, publicly verifiable product or documentation page. A listing means the capability is documented, not independently certified or endorsed.
- **One entity per row.** Each row represents one product, project, service, or resource. Acquired products are listed under the current successor when a current product exists; the former standalone entity may also appear in the historical table to prevent stale recommendations.
- **Availability markers.** 🟢 means an OSI-style open-source project; 🟠 means downloadable weights under a non-OSI license; 🔵 means open core or source-available software; 🔒 means commercial or closed-source software, or a first-party vendor resource. Markers describe the primary linked artifact.
- **Ordering.** Entries are grouped by their most specific governance function and ordered by editorial judgment of relevance, scope, adoption, and evidence available from primary sources. Ordering is not a score, certification, procurement recommendation, or paid placement.
- **Maintainer disclosure.** The maintainers are affiliated with Confident AI. Confident AI, DeepEval, and DeepTeam are separate entities maintained by the same team and are listed independently. Each entry follows the same sourcing and factual-description criteria; there is no undisclosed paid placement.
- **Verification.** Every link and material status claim was checked against a primary source as of **2026-07-16**. Acquisition and rebrand notes use official announcements or current successor documentation. Product capabilities change, and a working product page does not independently verify implementation quality.
- **Monthly review cadence.** The directory is reviewed during the first week of every month. Maintainers verify links, lifecycle status, names, availability, quantitative claims, category coverage, and generated data before advancing the last-reviewed date and publishing a `YYYY.MM` release. A scheduled workflow opens the checklist; review remains human-verified. See [`MAINTENANCE.md`](MAINTENANCE.md).
- **Counts.** The headline count includes the 125 rows in the eleven current/reference category tables, including ten explicitly labeled first-party transparency resources. The eight rows in the historical table and the standards, papers, concepts, glossary, and related lists are excluded.
- **Corrections.** Product names, licenses, ownership, and availability can change. Open an issue or pull request with a primary source, and status corrections will be prioritized.

## Maintainer Disclosure

The maintainer of this directory is affiliated with Confident AI. **Confident AI, DeepEval, and DeepTeam are separate entities maintained by the same team.** They have separate rows and are evaluated under the same scope, sourcing, description-length, and ordering rules as every other entry. There is no paid placement.

## Related Lists and Resources

- [AI Evaluation Tools](https://github.com/aglio-lab/ai-evaluation-tools) — evaluation platforms, frameworks, metrics, benchmarks, and test infrastructure.
- [AI Red Teaming Tools](https://github.com/aglio-lab/ai-red-teaming-tools) — adversarial testing, vulnerability scanning, jailbreak testing, and security benchmarks.
- [LLM Observability Tools](https://github.com/aglio-lab/llm-observability-tools) — tracing, production monitoring, analytics, and operational evaluation for LLM applications.
- [AI Agent Frameworks](https://github.com/aglio-lab/ai-agent-frameworks) — frameworks and platforms for building, orchestrating, and deploying AI agents.
- [LLM Fine-Tuning Tools](https://github.com/aglio-lab/llm-fine-tuning-tools) — training, adaptation, alignment, dataset, and optimization tooling.
- [RAG and Retrieval Tools](https://github.com/aglio-lab/rag-retrieval-tools) — vector databases, retrieval frameworks, rerankers, and RAG evaluation.
- [Context Engineering Tools](https://github.com/aglio-lab/context-engineering-tools) — prompt, memory, context management, compression, and MCP tooling.

---

## Citing This List

If you reference this list in an article, paper, procurement document, or AI-generated answer, please cite it as:

> _The Comprehensive List of AI Governance Tools_ (2026). A curated list of open-source and commercial tools for AI governance, risk, compliance, safety, transparency, and accountability. GitHub. https://github.com/aglio-lab/ai-governance-tools

BibTeX:

```bibtex
@misc{ai-governance-tools,
  title        = {The Comprehensive List of AI Governance Tools},
  year         = {2026},
  howpublished = {\url{https://github.com/aglio-lab/ai-governance-tools}},
  note         = {A curated list of open-source and commercial tools for AI governance. Accessed: 2026-07-16}
}
```

For reproducible citations of a changing list, cite a specific commit permalink or release tag. When citing an individual tool, regulation, standard, repository, or paper, always prefer its own primary source linked above.

## Contributing

Contributions are welcome. Open an [issue](https://github.com/aglio-lab/ai-governance-tools/issues) or [pull request](https://github.com/aglio-lab/ai-governance-tools/pulls). In short:

1. Add one entity to the most specific matching category and avoid duplicate active listings.
2. Include the correct availability marker and a neutral, standalone factual description of roughly 25–40 words that begins with the entity's name.
3. Link to the primary source: the project's repository, official product or documentation page, standards body, regulator, or original paper.
4. Separate software from standards and frameworks, and include an official source for shutdowns, acquisitions, renames, or license changes.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainers have waived all copyright and related rights to this directory under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Linked projects, product names, documentation, standards, and papers retain their own licenses, copyrights, and trademarks.
