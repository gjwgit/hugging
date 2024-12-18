# [MLHub](https://mlhub.ai) Hugging

This package provides easy to use capabilities from the extensive
[Hugging Face](https://huggingface.co/) repository through the command
line. The implementation began as a student project by Shashank
Gummuluru under the supervision of Graham Williams, available from
https://github.com/shashank-gv/hugging. This official mlhub version
has built on that project to add further features from Hugging
Face. The features are document in
https://survivor.togaware.com/mlhub/hugging.html

## Installation

To install, configure, and demonstrate the package:


```bash
ml install   gjwgit/hugging
ml configure hugging
ml readme    hugging
ml commands  hugging
ml demo      hugging
```

## Commands

```bash
ml summarize hugging (link_to_article | text_file.txt)
ml sentiment hugging (input_text | text_file.txt)
```

## Quickstart

```bash
ml summarize hugging microsoft.txt
ml sentiment hugging microsoft.txt
```
