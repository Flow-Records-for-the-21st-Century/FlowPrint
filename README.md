# FlowPrint Modified Datasets
Link Tor and Firefox data 
https://wpi0-my.sharepoint.com/:f:/g/personal/jhiggins_wpi_edu/EmWWygKnmnFMnp0ls2b4Em8BqXiVZabRwZCM2m4OA5DqMQ?e=iOZuYS

Link to Mobile data (the us.tgz set)
https://recon.meddle.mobi/cross-market.html


# FlowPrint
This repository contains the code for FlowPrint by the authors of the NDSS FlowPrint [1] paper [[PDF]](https://dx.doi.org/10.14722/ndss.2020.24412).
Please [cite](#References) FlowPrint when using it in academic publications.
This `master` branch provides FlowPrint as an out of the box tool.
For the original experiments from the paper, please checkout the `NDSS` branch.

## Introduction
FlowPrint introduces a semi-supervised approach for fingerprinting mobile apps from (encrypted) network traffic.
We automatically find temporal correlations among destination-related features of network traffic and use these correlations to generate app fingerprints.
These fingerprints can later be reused to recognize known apps or to detect previously unseen apps.
The main contribution of this work is to create network fingerprints without prior knowledge of the apps running in the network.

## Documentation
We provide an extensive documentation including installation instructions and reference at [flowprint.readthedocs.io](https://flowprint.readthedocs.io/en/latest/).

## References
[1] `van Ede, T., Bortolameotti, R., Continella, A., Ren, J., Dubois, D. J., Lindorfer, M., Choffnes, D., van Steen, M. & Peter, A. (2020, February). FlowPrint: Semi-Supervised Mobile-App Fingerprinting on Encrypted Network Traffic. In 2020 NDSS. The Internet Society.`

### Bibtex
```
@inproceedings{vanede2020flowprint,
  title={{FlowPrint: Semi-Supervised Mobile-App Fingerprinting on Encrypted Network Traffic}},
  author={van Ede, Thijs and Bortolameotti, Riccardo and Continella, Andrea and Ren, Jingjing and Dubois, Daniel J. and Lindorfer, Martina and Choffness, David and van Steen, Maarten, and Peter, Andreas},
  booktitle={NDSS},
  year={2020},
  organization={The Internet Society}
}
```
