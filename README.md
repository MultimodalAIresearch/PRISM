# PRISM Preprocessing Skeleton
PRISM (Progressive Representation Integration & Dynamic Fusion Strategies) preprocessing targets paired text+video data (~16GB) so downstream teams can experiment with adaptive fusion, representation sharing, and deployment-friendly multimodal models.

## Research Questions
- **RQ1:** How do we learn a shared space without losing modality-specific signals?
- **RQ2:** Can fusion be adaptive per sample (memory/meta-learning) so noisy or missing modalities do not break performance?
- **RQ3:** How can we align distributions across modalities without destroying semantics?
- **RQ4:** How to make multimodal models interpretable and compact for deployment?

## Phases
- **Phase 1 – Foundations & Baselines:** datasets, preprocessing, unimodal baselines, early/late/hybrid fusion prototypes, meta-controller concept, metrics and ablations.
- **Phase 2 – Robustness & Interpretability:** missing-modality strategies, alignment and calibration, probes/explainability, compression and quantization, automated evaluation.
- **Phase 3 – Results & Deployment:** report accuracy and robustness, percentage performance under missing modalities, latency and size thresholds.

## Success Metrics
- Accuracy and robustness gains over baselines.
- Percentage performance retained under X% missing modalities.
- Latency and model size thresholds met for deployment targets.

## Scope of This Repo
- Preprocessing design and assets for text+video pairs.
- Repository skeleton, manifests, metadata schema, and benchmark planning.
- Modeling, training code, and evaluation dashboards live elsewhere.

## Data Assumptions
- Approximately 16GB of curated paired text+video stored externally.
- Access-controlled storage with eventual Hugging Face Hub benchmark.
- Inputs expected to be clean enough for light normalization only.

## Team Status

**Arun**
| Working | Completed | Pending / Blockers |
|---|---|---|
|  |  |  |

**Kartik**
| Working | Completed | Pending / Blockers |
|---|---|---|
|  |  |  |

**Sam**
| Working | Completed | Pending / Blockers |
|---|---|---|
|  |  |  |

## Communication & Cadence
- Daily concise updates with changes, next actions, and blockers.
- Ping Pradeep for safety or approval needs; aim to wrap Phase 1 setup before Christmas.

## Next Steps Checklist
- [ ] Confirm data access paths and license notes with Arun.
- [ ] Draft preprocessing pipeline architecture for Pradeep review.
- [ ] Outline Hugging Face benchmark scope and acceptance criteria.

## Ethics & Safety
- Follow redaction and compliance guidelines in `docs/SAFETY.md`; obtain Pradeep’s approval before any public dataset release.
