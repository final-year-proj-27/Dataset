# Lecture Video Dataset: Transcript-Dominant Summary-Assisted Semantic Indexing and Moment Retrieval

## Overview

This repository documents the **Lecture Video Dataset: Transcript-Dominant Summary-Assisted Semantic Indexing and Moment Retrieval**, published on IEEE DataPort.

The dataset is designed to support research on query-driven lecture video retrieval, transcript-dominant semantic indexing, and summary-assisted identification of relevant video moments.

It provides a collection of 40 lecture video files along with associated query metadata, enabling researchers to investigate how natural-language queries can be used to discover relevant content within lecture videos.

## Dataset Publication

| Attribute | Details |
|---|---|
| Publication Platform | IEEE DataPort |
| Dataset Name | Lecture Video Dataset: Transcript-Dominant Summary-Assisted Semantic Indexing and Moment Retrieval |
| Number of Videos | 40 |
| Video Format | MP4 |
| Query Metadata | `queries.json` |
| DOI | `10.21227/72f6-hd17` |

**Official Dataset Links:**
- [IEEE DataPort – Dataset](https://ieee-dataport.org/documents/lecture-video-dataset-transcript-dominant-summary-assisted-semantic-indexing-and-moment)
- [DOI: 10.21227/72f6-hd17](https://doi.org/10.21227/72f6-hd17)

## Dataset Contents

The dataset consists of the following:

### 1. Lecture Videos
- 40 lecture video files in MP4 format.
- Files are named sequentially from `video_01.mp4` to `video_40.mp4`.
- These videos serve as the primary multimedia content for retrieval experiments.

### 2. Query Metadata
- `queries.json` contains query information associated with the video collection.
- Provides the textual query information required for investigating query-based retrieval.
- Researchers should inspect its structure to understand the available fields, video references, and annotations.

## Retrieval Workflow

The dataset supports research involving a retrieval pipeline that combines multiple stages of text processing and semantic search.

1. **Automatic Speech Transcription:** Extracting textual representations from lecture videos.
2. **Transcript Summarization:** Generating concise summaries from lecture transcripts.
3. **Semantic Text Representation:** Converting transcript-derived textual information into semantic embeddings.
4. **Similarity-Based Search:** Comparing natural-language queries with indexed representations to identify relevant lecture content.
5. **Moment Retrieval:** Investigating the identification of relevant segments within lecture videos.

These stages provide a foundation for exploring transcript-based semantic indexing and query-driven lecture video retrieval.

## Getting Started

### Step 1: Download the Dataset

Download the dataset files from the official [IEEE DataPort publication](https://ieee-dataport.org/documents/lecture-video-dataset-transcript-dominant-summary-assisted-semantic-indexing-and-moment).

### Step 2: Extract the Files

If the dataset is provided as a ZIP archive, extract it into a directory on your local machine.

### Step 3: Verify the Dataset

Ensure that:
- All 40 MP4 video files are present.
- `queries.json` is available.
- The downloaded files are readable and complete.

### Step 4: Inspect Query Metadata

Examine `queries.json` to understand its structure, query fields, video references, and available annotations.

Preserve the original video filenames to ensure correct mapping between the videos and their corresponding metadata.

## Research Applications

The dataset can support research and experimentation in:

- Video Information Retrieval
- Semantic Search and Indexing
- Natural Language Processing
- Transcript-Based Video Understanding
- Query-Driven Moment Retrieval
- Educational Multimedia Information Retrieval
- Lecture Content Discovery

## Reproducibility and Validation

For reproducible experimentation, researchers are encouraged to:

- Verify the integrity and readability of downloaded files.
- Validate video references against the original filenames.
- Inspect the JSON metadata before interpreting queries or annotations.
- Document preprocessing and transcript segmentation strategies.
- Specify the models and embedding techniques used.
- Report retrieval configurations, evaluation protocols, and metrics.
- Document any modifications or exclusions applied to the original dataset.

## Scope and Limitations

The dataset is intended for academic experimentation, benchmarking, and further development of query-driven lecture retrieval methods.

The availability of reference timestamps, relevance labels, and other ground-truth annotations should be verified directly from `queries.json` before applying evaluation metrics that depend on such annotations.

Researchers should refer to the official IEEE DataPort publication for the latest dataset information, documentation, and access conditions.

## Citation

If you use this dataset in your research or publications, please cite the original IEEE DataPort record.

**DOI:** [10.21227/72f6-hd17](https://doi.org/10.21227/72f6-hd17)

**Publication:** [Lecture Video Dataset: Transcript-Dominant Summary-Assisted Semantic Indexing and Moment Retrieval](https://ieee-dataport.org/documents/lecture-video-dataset-transcript-dominant-summary-assisted-semantic-indexing-and-moment)

## Repository Information

This repository serves as the documentation and reference point for the published Lecture Video Dataset.

The complete dataset is hosted on IEEE DataPort and can be accessed through the official publication link provided above.

---

**Maintained as part of the LectureRetrieval Final-Year Project.**
