# parsing result sample:


Key Inclusion Criteria: 
* Participant has histologically or cytologically confirmed metastatic NSCLC (stage IV with known subtype). 
* Participant has progressed radiographically on or after receiving: * One prior line of therapy (PD-1/PD-L1 inhibitor and platinum-based chemotherapy concomitantly) in the metastatic disease setting; OR * No more than 2 prior lines of therapy (PD-1/PD-L1 inhibitor and platinum-based chemotherapy sequentially, irrespective of the order) in the metastatic disease setting. 
* Participant must have positive tumor PD-L1 expression (tumor cells ≥1%) determined prospectively on a tumor sample from the metastatic setting at a sponsor-designated central laboratory. 
* Participant has measurable disease according to RECIST v1.1 as assessed by the investigator at baseline. 
* Participant has an Eastern Cooperative Oncology Group (ECOG) performance status 0 or 1 within 7 days of Cycle 1 Day 
1. * Participant has a life expectancy of ≥3 months. 
* Participant must have adequate organ and bone marrow function, per laboratory test results within 7 days of trial treatment. 

Key Exclusion Criteria: 
* Documentation of known targetable epidermal growth factor receptor (EGFR) sensitizing mutations, anaplastic lymphoma kinase (ALK), RET proto-oncogene (RET), ROS proto-oncogene 1; receptor tyrosine kinase (ROS1) rearrangement, Kirsten rat sarcoma virus (KRAS), B-Raf proto-oncogene (BRAF) mutations, and MET proto-oncogene; receptor tyrosine kinase (MET) exon 14 skipping mutations/MET amplification. NOTE: MET amplification testing is optional based on local availability of the test. 
* Participants with known KRAS/BRAF mutations are eligible for the trial if they do not have access to approved targeted therapies. 
* Participants with newly identified or known unstable or symptomatic central nervous system (CNS) metastases or history of carcinomatous meningitis. * Prior treatment with docetaxel for NSCLC. 
* Prior treatment with a 4-1BB (CD137) targeted agent, any type of antitumor vaccine, autologous cell immunotherapy, or any unapproved immunotherapy. * Treatment with an anticancer agent within 28 days prior to the first dose of trial treatment. Note: Other protocol-defined inclusion and exclusion criteria may apply.


```json
{
  "trial_id": null,
  "trial_category": "therapeutic_interventional",
  "age": {
    "min": 18,
    "max": null
  },
  "region_specific_age": {
    "japan_min": null
  },
  "inclusion": {
    "disease": {
      "confirmed_by": "histology or cytology",
      "cancer_type": "non-small cell lung cancer",
      "histology_subtype": "",
      "stage": "IV",
      "stage_list": ["IV"],
      "metastatic": true,
      "measurable_disease_recist": true,
      "biomarker_required": ["PD-L1 expression ≥1%"]
    },
    "performance_status": {
      "scale": "ECOG",
      "min": 0,
      "max": 1
    },
    "life_expectancy_weeks": 12,
    "prior_therapy": {
      "required": ["PD-1/PD-L1 inhibitor and platinum-based chemotherapy"],
      "allowed": [],
      "disallowed": ["docetaxel for NSCLC", "4-1BB targeted agent", "antitumor vaccine", "autologous cell immunotherapy", "unapproved immunotherapy"],
      "max_lines_systemic": 2,
      "washout_weeks": {
        "chemotherapy": 4,
        "targeted_therapy": 4,
        "immunotherapy": 4,
        "investigational": 4,
        "radiation": null,
        "major_surgery": null
      }
    },
    "brain_metastases": "excluded",
    "brain_mets_stable_duration_weeks": null,
    "organ_function": {
      "anc": null,
      "platelets": null,
      "hemoglobin_g_per_dl": null,
      "creatinine_clearance_ml_min": null,
      "bilirubin_x_uln": null,
      "ast_alt_x_uln": null,
      "albumin_g_per_dl": null
    },
    "cardiac": {
      "qtcf_ms_max": null,
      "recent_mi_months_exclusion": null,
      "nyha_class_max": null,
      "lvef_percent_min": null
    },
    "contraception_required": null,
    "other_inclusions": [
      "Tumor sample from metastatic setting required for PD-L1 testing",
      "Adequate organ and bone marrow function"
    ]
  },
  "exclusion": {
    "pregnant_or_breastfeeding": null,
    "active_cns_metastases": true,
    "uncontrolled_intercurrent_illness": null,
    "grade_2_or_higher_neuropathy": null,
    "history_of": ["carcinomatous meningitis"],
    "concurrent_medications_disallowed": [],
    "other_exclusions": [
      "Known targetable EGFR mutations",
      "Known ALK rearrangement",
      "Known RET rearrangement",
      "Known ROS1 rearrangement",
      "Known MET exon 14 skipping mutations/MET amplification",
      "Known KRAS/BRAF mutations with access to approved targeted therapies"
    ]
  }
}
```