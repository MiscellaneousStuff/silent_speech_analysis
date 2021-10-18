# sEMG Silent Speech Analysis

## About

Analysis of open-source sEMG silent speech datasets.

## Usage

The recommended way to run the notebook, across WSL2
and Debian-based Linux distributions, is to use this
command:

```bash
jupyter lab --allow-root --no-browser
```

## Datasets

Below are a list of the currently analysed datasets:

### David Gaddy and Dan Klein

[Digital Voicing of Silent Speech](https://arxiv.org/pdf/2010.02960.pdf)

[An Improved Model for Voicing Silent Speech](https://arxiv.org/pdf/2106.01933.pdf)

This dataset is analysed within the `dgaddy_analysis.ipynb`
notebook as there are two related papers for the dataset.

Both papers are also analysed in further depth within `docs/dgaddy.md`
as it is important to read the authors published papers to fully
understand how they use their dataset to train their system.

- Open vocabulary
    - Parallel Silent / Vocalised Speech (Es, Ev, Av)
        - 3.6 hours silent / 3.9 hours vocalised
        - Avverage sesison has 30 minutes of each mode
        - 1,588 utterances
    - Non-parallel Vocalised Speech (Ev, AV)
        - 11.2 hours
        - Average session length 67 minutes
        - 5,477 utterances
- Closed vocabulary
    - Parallel silent / vocalised speech (Es, Ev, Av)
        - 26 minutes silent / 30 minutes vocalised
        - Single session
        - 500 utterances
        - Average of 4 words per utterance
        - 67 words in vocabulary