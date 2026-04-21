# FAIR Evaluation Report – Week 1 In-Class Exercise

## Student Information
- **Name:** Pramodkumar Shivanna
- **Program:** M.Sc. Applied Data Science and Artificial Intelligence
- **University:** SRH University Heidelberg
- **Course:** Data Management
- **Date:** 21 April 2026

---

## Dataset Information

| Field | Details |
|-------|---------|
| **Dataset Title** | EDEN ISS 2020 Telemetry Dataset |
| **DOI** | 10.5281/zenodo.11485183 |
| **URL** | https://zenodo.org/records/11485183 |
| **Publisher** | Zenodo – German Aerospace Center (DLR) |
| **Creators** | Rewicki, Ferdinand; Norman, Tom; Vrakking, Vincent |
| **Publication Date** | June 13, 2024 |
| **Format** | CSV files (zipped) |
| **License** | Open Access |

### About the Dataset
The EDEN ISS 2020 Telemetry Dataset is a time series dataset consisting of sensor
readings from 97 sensors in the EDEN ISS research greenhouse. The greenhouse was
deployed in Antarctica to study Controlled Environment Agriculture (CEA) techniques
for future space missions. Data was collected throughout the year 2020, covering
sensors for temperature, humidity, CO2, light (PAR), nutrient delivery, and pressure
across five subsystems.

---

## FAIR Assessment

**Tool Used:** F-UJI – Automated FAIR Data Assessment Tool (https://www.f-uji.net)
**Assessment Date:** 21 April 2026
**F-UJI Software Version:** 3.5.1

---

## FAIR Results Summary

| Principle | Score Earned | Fair Level |
|-----------|-------------|------------|
| **Findable** | 7 of 7 | ✅ Advanced |
| **Accessible** | 6 of 7 | ✅ Moderate |
| **Interoperable** | 4 of 6 | ✅ Moderate |
| **Reusable** | 6 of 6 | ✅ Moderate |
| **Overall Score** | **88%** | ✅ **Moderate** |

*(See attached screenshots: Screenshot_2026-04-21_110620.png and Screenshot_2026-04-21_110739.png)*

---

## Analysis

### Findable (7/7 – Advanced)
The dataset achieved a perfect score for Findability. It is assigned a persistent
DOI (10.5281/zenodo.11485183) through Zenodo, which ensures it can be uniquely
identified and located. The metadata is rich, well-structured, and indexed by
DataCite, making it easily searchable in research repositories.

### Accessible (6/7 – Moderate)
The dataset is openly accessible without requiring authentication or login. It
can be freely downloaded from Zenodo. The slight deduction suggests that some
access protocol documentation could be improved.

### Interoperable (4/6 – Moderate)
Data is stored in standard CSV format, which is widely compatible across tools
and platforms. A description file (edeniss2020.csv) explains the units and
measurement types. The moderate score indicates that formal ontology or
vocabulary references could be added to improve machine readability.

### Reusable (6/6 – Moderate)
The dataset scored full marks for Reusability. It includes a README file,
a description of all 97 sensors, clear subsystem labels, and provenance
information about how and when the data was collected.

---

## 2 Strengths

1. **Perfect Findability Score (7/7):** The dataset has a persistent DOI,
   is indexed by DataCite, and is published on Zenodo with rich, structured
   metadata. This makes it easily discoverable by researchers worldwide and
   ensures long-term access even if the URL changes.

2. **Full Reusability Score (6/6):** The dataset is exceptionally well-documented
   with a README file, sensor description file, clear subsystem labels, and
   full provenance details including who collected the data, when, and where.
   This makes it easy for other researchers to understand and reuse confidently.

---

## 2 Areas for Improvement

1. **Interoperability could be improved (4/6):** While CSV is a standard format,
   the dataset does not reference formal ontologies or controlled vocabularies
   (e.g., using standardized sensor taxonomy or QUDT units ontology). Adding
   these would make the data more machine-readable and compatible with automated
   analysis pipelines across different systems.

2. **Accessible score not perfect (6/7):** The dataset lacks a formal,
   machine-readable description of its access conditions and protocols.
   Adding a structured access rights statement and explicit license identifier
   (such as a SPDX license code) in the metadata would improve this score
   and make access conditions clearer for automated systems.

---

## Conclusion

The EDEN ISS 2020 Telemetry Dataset scored **88% (Moderate)** overall on the
F-UJI FAIR assessment tool. It performed exceptionally well in Findability and
Reusability, reflecting Zenodo's strong metadata standards and the dataset
creators' thorough documentation. Minor improvements in formal ontology usage
and structured access rights descriptions would push this dataset toward an
Advanced FAIR level overall.
