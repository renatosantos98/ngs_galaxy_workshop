# NGS Workshop

**Bioinformatics, Interpretation and Data Quality in Genome Analysis**

A hands-on workshop on analysing clinical next-generation sequencing data with [Galaxy Europe](https://usegalaxy.eu/). Using a simulated whole-exome case study of a patient with suspected metachromatic leukodystrophy, participants work through quality control, read alignment, variant calling, annotation and prioritisation.

**[Open the workshop](https://renatosantos98.github.io/ngs_galaxy_workshop/)**

No local installation is needed to follow the workshop, only a web browser and a Galaxy account.

## Repository contents

| Path              | Description                                      |
| ----------------- | ------------------------------------------------ |
| `workshop.qmd`    | Workshop source (Quarto)                         |
| `workshop.html`   | Rendered, self-contained copy of the workshop    |
| `data/`           | Workshop FASTQ and BED files                     |
| `images/`         | Figures and screenshots                          |
| `assets/mcq.html` | Script and styling for the interactive questions |

## Building locally

With [Quarto](https://quarto.org/docs/get-started/) installed, run:

```bash
quarto render workshop.qmd
```

## Authors

Alfredo Iacoangeli and Renato Santos, King's College London.

## License

Released under the [MIT License](LICENSE.md).
