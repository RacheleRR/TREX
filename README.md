
<div align="center">
  <h1>🧬 TREX</h1>
  <img src="https://github.com/user-attachments/assets/80f75e28-da91-4f2b-b90e-6c2cedf85274" width="600" />
  <br/><br/>
  <p align="center" style="max-width: 720px; font-size: 16px;">
    TREX is a <strong>Tandem Repeat Expansion Analysis Pipeline</strong>. This pipeline provides an end-to-end, reproducible framework for the genome-wide analysis of tandem repeat (TR) expansions from whole-genome sequencing data. It enables systematic detection, characterization, and biological interpretation of repeat expansions across multiple cohorts and phenotypic groups, with an emphasis on statistical rigor and downstream functional relevance.
  </p>
</div>

<img width="502" height="227" alt="Pipeline overview" src="https://github.com/user-attachments/assets/027ad199-35c7-4519-8be6-dbc6e99c1ea6" />







## ✨ Key Capabilities
- **Genome-wide TR expansion analysis** across single or multiple cohorts
- **Cohort-aware modeling**, supporting case–control and multi-group study designs
- **Robust statistical framework** integrating burden tests, non-parametric comparisons, and regression modeling
- **Biological contextualization** of expansions via genomic annotation, regulatory proximity, and gene set enrichment
- **Flexible filtering strategies**, including private vs shared expansions and pure vs mixed group assignments
- **Integrated functional enrichment and network analysis**, with optional Cytoscape visualization
- **Fully reproducible execution**, implemented as a modular Snakemake workflow with YAML-based configuration

## 📘 Documentation
Full documentation is available in the [Documents](docs) directory, including:
- [Installation](docs/02_Installation.md)
- [Configuration options](docs/03_Configuration.md)
- [Usage guide](docs/04_Usage_guide.md)
- [Pipeline_stages](docs/01_Pipeline_structure.md)
- [Troubleshooting](docs/05_Troubleshooting.md)

Start here:
➡️ [here](docs/00_Introduction.md)


# Basic Usage
**Clone repository**
```
git lfs install
git clone https://github.com/RacheleRR/TREX.git
cd TREX
```
**Run setup**
```
bash setup/setup.sh
```
**Dry run**
```
snakemake -n
```

**Run pipeline**
```
snakemake --cores 12
```


## Citation

If you use this pipeline, please cite:

- **ExpansionHunterDenovo**: Dolzhenko et al. (2020) Genome Biology
- **g:Profiler**: Raudvere et al. (2019) Nucleic Acids Research
- **DBSCAN**: Ester et al. (1996) KDD-96
- Fazal et al. (2020) - EHDN helper scripts
- Trost et al. (2020) - BTlib utilities
- Sarah Fazal et al. Genome Biol. 2024.- Rexprt

## License

MIT License - see LICENSE file

## Contact

For questions or issues, please open a GitHub issue or contact [rachelerebeccarubiu98@gmail.com].



  





