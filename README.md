# Multilingual Story Illustration Dataset (English & Hindi)

This repository hosts a multilingual dataset for story visualization and text-to-image generation, including English and Hindi narratives accompanied by high-quality illustrations. The dataset is designed to promote research in culturally diverse storytelling, character consistency, and narrative coherence.

## Dataset Description

Existing story visualization datasets are predominantly English and aligned with Western cultural contexts. This dataset addresses these limitations by providing:

- **Languages:** English and Hindi
- **Narratives:** Diverse stories spanning multiple genres and cultural contexts
- **Illustrations:** Aligned images for each story, maintaining character and scene consistency
- **Applications:** Text-to-image generation, story visualization, cross-lingual narrative modeling, and benchmarking

## Dataset Structure

The dataset is organized hierarchically by language:

dataset/
├── English/
│   ├── Stories/
│   │   ├── eng_story_0001.txt
│   │   ├── eng_story_0002.txt
│   │   └── ...
│   └── Images/
│       ├── eng_story_0001_01.jpg
│       ├── eng_story_0001_02.jpg
│       └── ...
├── Hindi/
│   ├── Stories/
│   │   ├── hin_story_0001.txt
│   │   ├── hin_story_0002.txt
│   │   └── ...
│   └── Images/
│       ├── hin_story_0001_01.jpg
│       ├── hin_story_0001_02.jpg
│       └── ...



- **Stories:** Narrative text files (`.txt`) with zero-padded identifiers.
- **Images:** Illustrations in `.jpg`, `.jpeg`, or `.png` formats aligned to the story IDs.
- **Hierarchy:** First divided by language, then by story and associated images, ensuring clear narrative–visual alignment.

## Benchmarking Baseline

We provide a baseline experiment in `baseline.py` to evaluate story visualization performance using this dataset. This script demonstrates:

- Loading the dataset
- Preprocessing narratives and images
- Running a simple text-to-image model
- Computing baseline metrics for character consistency and narrative coherence

## License

This dataset is released under the CC BY-NC 4.0 License, for research and non-commercial use.

## Contributions

We welcome contributions, feedback, and suggestions to expand the dataset or improve benchmarking experiments.
