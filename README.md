<a href="https://amitsubhash.github.io/">
  <img src="https://raw.githubusercontent.com/AmitSubhash/amitsubhash.github.io/main/banner.webp" alt="Amit Subhash: neuroengineering, optics, ML" width="100%" />
</a>

PhD student in Intelligent Systems Engineering (Neuroengineering) at Indiana University, advised by Silvina Ferradal. I make optical brain imaging of infants and animals anatomically accurate and fast: MRI segmentation, FEM head mesh, GPU photon transport, reconstruction.

- Built the MRI-to-mesh-to-Jacobian pipeline for a first-in-large-animal high-density diffuse optical tomography study with the University of Pennsylvania and Children's Hospital of Philadelphia, and cut a forward-solve step from about 1400 s to 8 s on the GPU.
- First-author oral at the Optica Biophotonics Congress 2026: "Developing Diffuse Optical Tomography for Peri-Arrest Monitoring in Piglets" ([OT2D.3](https://doi.org/10.1364/OTS.2026.OT2D.3)). Companion poster with Brian White's group at fNIRS 2026, Macau.
- Looking for a summer 2027 research visit, mid-May to late August.

### Contributions to open-source tools

- [pyRiemann #476](https://github.com/pyRiemann/pyRiemann/pull/476) (merged): `transport_wasserstein`, parallel transport under the Bures-Wasserstein metric.
- [pyRiemann #478](https://github.com/pyRiemann/pyRiemann/pull/478) (merged): namespace-native `expand_dims` in place of an array-api-extra helper.
- [NeuroDOT #8](https://github.com/WUSTL-ORL/NeuroDOT/pull/8): reported that `TtestWelch` returned a one-tailed p-value; the maintainers made the two-tailed test the default.
- [CEBRA #309](https://github.com/AdaptiveMotorControlLab/CEBRA/pull/309) (in review): chunked `top_k` search in `OrthogonalProcrustesAlignment`; peak memory on a 15000 x 15000 alignment from 5372 MB to 621 MB, bit-identical results.
- [NeuroDOT_py #5](https://github.com/WUSTL-ORL/NeuroDOT_py/pull/5), [NIRFAST #22](https://github.com/nirfast-admin/NIRFAST/pull/22) and [#23](https://github.com/nirfast-admin/NIRFAST/pull/23), [openlifu-python #476](https://github.com/OpenwaterHealth/openlifu-python/pull/476) (in review): a cached dense reconstruction path, Apple Silicon support and a large-mesh save fix, and ported coordinate transforms.

### Public code

- [dot-qc-simulator](https://github.com/AmitSubhash/dot-qc-simulator): a marimo app that teaches DOT/fNIRS quality-control plots on physics-based synthetic HD-DOT data.
- [3brown1blue](https://github.com/AmitSubhash/3brown1blue): 3Blue1Brown-style Manim explainer videos from topics or slide decks.
- [iu-hpc-agent](https://github.com/AmitSubhash/iu-hpc-agent): a checked reference for Indiana University's Big Red 200 and Quartz clusters.

Lab code built on unpublished data stays private until the work is published.

[amitsubhash.github.io](https://amitsubhash.github.io/) · [atsubhas@iu.edu](mailto:atsubhas@iu.edu) · [LinkedIn](https://www.linkedin.com/in/amitsubhash/)
