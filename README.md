# Awesome Mining Band Ratio


[![Awesome](https://raw.githubusercontent.com/softwareunderground/awesome-open-geoscience/master/media/icon/badge.svg)](https://github.com/sindresorhus/awesome) [![Commits](https://img.shields.io/github/last-commit/rodreras/awesome-mining-band-ratio.svg?label=last%20contribution)](https://github.com/rodreras/awesome-mining-band-ratio/commits/main) [![License](https://img.shields.io/github/license/rodreras/awesome-mining-band-ratio.svg)](https://github.com/rodreras/awesome-mining-band-ratio/blob/master/LICENSE)


_Under Construction_ (25.04.24)

A curated list of  materials, mineral spectral signature and published band ratios aiming the application of Remote Sensing to Mineral Exploration. 

![alt text](images/image-1.png)

**Please contribute. Let's make this guide better!**






**Table of Contents**

- [Band Ratios](#band-ratios)
- [RGB Compositions](#rgb-compositions)
- [Minerals Spectra Signature](#minerals-spectra-signature)
- [Awesome List](#awesome-list)
- [References](#references)

---

## Band Ratios

### Aster

**IMPORTANT**: <span style="color:red">the SWIR sensor (bands 4 to 9) are inoperable since 1st April 2008, and therefore only data acquired before this date will be suitable for mineral mapping</span>

| Feature               | Aster Band Ratio    | Ratio Description                                             | References                            |
|-----------------------|---------------------|---------------------------------------------------------------|---------------------------------------|
| Iron Minerals         | B2/B1               | Ferric Fe3                                                    | [Rowan and Mars, 2003](https://www.sciencedirect.com/science/article/pii/S003442570200127X); Hewson et al., 2001, 2004a |
| Iron Minerals         | (B5/B3)+(B1/B2)     | Ferrous Fe2                                                   | [Rowan and Mars, 2003](https://www.sciencedirect.com/science/article/pii/S003442570200127X)                |
| Iron Minerals         | B4/B2               | Gossan                                                        | Volesky et al., 2003                |
| Iron Minerals         | B5/B4               | Ferrous Silicates (biotite, chl, amphibolite) Cu-Au Alteration | Hewson et al., 2001, 2004a         |
| Iron Minerals         | B4/B3               | Ferric Oxides                                                 | Hewson et al., 2001, 2004a         |
| Carbonates/Mafic Minerals | (B7+B9)/B8     | Carbonate/Chlorite/Epidote                                    | [Rowan and Mars, 2003](https://www.sciencedirect.com/science/article/pii/S003442570200127X)                |
| Carbonates/Mafic Minerals | B13/B14        | Carbonate Index (Exoskarn (cal/dolom) 92% cfd                 | Bierwith, Nimoyima, CSIRO          |
| Carbonates/Mafic Minerals | (B6+B9)/(B7+B8) | Epidote/Chlorite/Amphibole (Endoskarn)                        | CSIRO                               |
| Carbonates/Mafic Minerals | (B6+B9)/B8     | Amphibole/MgOH (Can be other MgOH or carbonate*)             | Hewson et al., 2001, 2004a         |
| Carbonates/Mafic Minerals | B6/B8          | Amphibole                                                      | Bierwith                            |
| Carbonates/Mafic Minerals | (B6+B8)/B7     | Dolomite                                                       | [Rowan and Mars, 2003](https://www.sciencedirect.com/science/article/pii/S003442570200127X)                |
| Carbonates/Mafic Minerals | (B7/B6)*(B4/B6) | Hydroxyl Group (OHI) 92% cfd                                  | Ninomiya, 2003a                     |
| Carbonates/Mafic Minerals | (B4/B5)*(B8/B6) | Kaolinite (KLI) 92% cfd                                       | Ninomiya, 2003a                     |
| Carbonates/Mafic Minerals | (B7/B5)*(B7/B8) | Alunite (ALI) 92% cfd                                         | Ninomiya, 2003a                     |
| Carbonates/Mafic Minerals | (B6/B8)*(B9/B8) | Calcite (CLI)                                                  | Ninomiya, 2003a                     |
| Silicates             | (B5+B7)/B6          | Sericite / Muscovite / Illite / Smectite (Phyllic alteration) | [Rowan and Mars, 2003](https://www.sciencedirect.com/science/article/pii/S003442570200127X); Hewson et al., 2001, 2004a |
| Silicates             | (B4+B6)/B5          | Alunite / Kaolinite (Pyrophyllite) 92% cfd                   | [Rowan and Mars, 2003](https://www.sciencedirect.com/science/article/pii/S003442570200127X)               |
| Silicates             | B7/B6               | Muscovite 92% cfd                                             | Hewson et al., 2001, 2004a         |
| Silicates             | B7/B5               | Kaolinite 92% cfd                                             | Hewson et al., 2001, 2004a         |
| Silicates             | (B5*B7)/(B6*B6)     | Clay 92% cfd                                                  | Bierwith, 2002                      |
| Silica Sio2           | B14/B12             | Quartz Rich Rocks Qz Index                                    | [Rowan and Mars, 2003](https://www.sciencedirect.com/science/article/pii/S003442570200127X)               |
| Silica Sio2           | (B11/B10)*(B11/B12) | Quartz 92% cfd                                                | Ninomya, 2003a                      |
| Silica Sio2           | B12/B13             | Silica (Basic Degree Index (gnt                               | Ninomiya, 2002, Bierwith, CSIRO    |
| Silica Sio2           | B13/B10             | Silica                                                         | Hewson et al., 2001, 2004a         |
| Silica Sio2           | (B11xB11)(B10B12)  | Silica Index 92% cfd                                          | Ninoyima                            |




### Landsat

| Feature                   | Band Ratio         | Description                                  |
|---------------------------|--------------------|----------------------------------------------|
| Iron Minerals             | 4/2                | Ferric Iron 1 "Redness"                     |
| Iron Minerals             | (4/2)*((4+6)/5)   | Ferric Iron 2                               |
| Iron Minerals             | (3+6)/(4+5)       | Ferrous Iron, coarsed grained ferric iron   |
| Carbonates/Mafic Minerals| (6/7)/(5/4)       | Clay, sulphate, mica, marble                |
| Sulfates                  | (2/1)-(5/4)       | Iron sulphate                               |


### Sentinel-2

| Feature       | Sentinel Band Ratio  | Ratio Description                                        |
|---------------|-----------------------|----------------------------------------------------------|
| Iron Minerals | B4/B3                 | Ferric Fe3                                               |
| Iron Minerals | B12/B8 + B3/B4        | Ferrous Fe2                                              |
| Iron Minerals | B11/B4                | Gossan                                                   |
| Iron Minerals | B12/B11               | Ferrous Silicates (biotite, chl, amphibolite) Cu-Au Alteration |
| Iron Minerals | B11/B8                | Ferric Oxides                                            |
| Silicates     | B11/B12               | Alteration                                               |


**Aster Bands 5 to 7 fall within band 12 of Sentinel-2.**

| ▲ [Top](#awesome-mining-band-ratio) |
|---|

## RGB Compositions

| RGB Composition        | ASTER         | Sentinel-2    | Landsat       |
|------------------------|---------------|---------------|---------------|
| Iron Minerals          | B4/B3         | B8A/B4        | B7/B5         |
| Ferric Oxides         | (B7-B5)/(B7+B5) | B12/B8       | B7/B5         |
| Clay Minerals         | B7/B5         | B11/B8        | B7/B5         |
| Vegetation            | B3/B2         | B8/B4         | B4/B3         |
| Urban Areas           | B3/B1         | B12/B11       | B5/B4         |


## Minerals Spectra Signature

| ▲ [Top](#awesome-mining-band-ratio) |
|---|

## Awesome List

| ▲ [Top](#awesome-mining-band-ratio) |
|---|

## References

[Hyperspectral remote sensing in lithological mapping, mineral exploration, and environmental geology: an updated review](https://www.spiedigitallibrary.org/journals/journal-of-applied-remote-sensing/volume-15/issue-3/031501/Hyperspectral-remote-sensing-in-lithological-mapping-mineral-exploration-and-environmental/10.1117/1.JRS.15.031501.full?tab=ArticleLinkCited)

[Multi-Scale integrated application of Spectral Geology and Remote Sensing for
Mineral Exploration](https://www.researchgate.net/profile/Constanza-Jara/publication/320929822_Multi-scale_Integrated_Application_of_Spectral_Geology_and_Remote_Sensing_for_Mineral_Exploration/links/5a02f77c458515713b3f591a/Multi-scale-Integrated-Application-of-Spectral-Geology-and-Remote-Sensing-for-Mineral-Exploration.pdf)

[Multi- and hyperspectral geologic remote sensing: A review](https://pdf.sciencedirectassets.com/272637/1-s2.0-S0303243411X00065/1-s2.0-S0303243411001103/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLWVhc3QtMSJHMEUCIQCJyUff4Gz81QJF9JdezEEKRD%2BS1atEQYlRZHk%2Fmi0qRgIgETNRx0UVr%2FEnC4gpQ3biYZuhPQLGSAqF3b8IRFlb0T4qvAUIrP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDDYVk6eGnpHpedJhPiqQBXgjSIKURTr51rsKMdz0ZRMrbTW5LnIgAFBCcojJhHz3G6gL5v6CHHvmf9eJ1XNZf4DuWVuRvo0thZA8ZAYnIZAoQnfB8769v287qXxZ0Z%2FezUsNQZfF9cU8rXh2RkVTqtaDRD4%2Fiw1MuaV3ho7C77eSakSSyqcmThol8fN3KQXBfEgaA04LlBtqir45pLGp9LC%2FoZijU5Pz1F3qG0kPyiiXpWKg7otf4FlVXleyk9WDbwyOiuPwKoRVmm3wgmSgWzYbEnxJmw8DKwwH75tBjp%2Bhr53Tuv9yGnvfs%2B2vSjXkLyT51%2FjHe0fPYWF2f9uRmDBUaeYZHYh9EaM1W7fICQtBGw0Lg8dg5NXZ%2FLtphHef4Gtb2x4CiuX%2BAa5gziOjRVCRwBtgYjx7DWSw5yQ9tLsGY0siHVY6TptmoP71kfcuKlTnpFiBRemWeT97CubIPEPLvYNsjqjtzgbMTU7qPuaWb2NozzlFbPxqCRuhhb6LkDe5dcbgcXFZQTNNoyjM4m2O9X2hU%2FeQbVBE8yAX%2BHHV1148gvpLHZimg5SzOIB%2F%2BeQj43eTYCxa2CFMu%2BLrWIt9aciw8JTMvArEuhXe0IJ0p88dG%2FL8ZjKSPJAlqzHUiv9XNbzO3fXJ%2BN2vD1kur7d9zqREp%2BGHtLFUimLxYLmzoyh6YHGAa3nZEOGYk8SsLChWAj3Y71a154i0xPDDlLLKXCyK%2FxAwNrVe4r0NgQ5oSE%2BAFk0fJxpNjPDiUCnlSywBj2YXnkd95KgiGTwvgCghMlqGGAAjBmPquCm%2FjSMjwYmmqBxEraPBZ90jB%2FKuXUkRkhgPPS4fB4jeYSDDbjGl1S%2B7Dzr142vnd2KkiSY9c7n2DZrcd8f9j0bqqiUmMILIqrEGOrEBj4E80zOBvX%2F8JTKgnrkyuGZTasbkRWtQ2cFumYTurVL9Qxn3ikkRqn%2FBKEAMtW3147zZINdawVgBVI2S0Y5hT%2BmWkclnePa3aDnae38ZHgJbYx3uSJ2Qe7YoZnA%2FJ%2BRi1JNXR6ogHcHE107CTyqGSjhbUHWpTe%2Bqwe%2BKUUzfaSY3YUvV3LCfD6CzW6QEeULgHhkDPI4eOHiY1%2FNAV64bonv4xqH%2Fs%2BwZPdJ8hUXdcIhD&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240425T190706Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYUZJMK2ES%2F20240425%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=61194111661af2a2b54bb010aebf17aeb29756527712a8291d753b89900ed643&hash=103183f55df46fa10e14ad228c6bc030df697f7e7ab88e271033839fb8931d94&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0303243411001103&tid=spdf-abfaa764-d3c1-4b8f-9e3d-2d80631ef776&sid=f7ca20818f06a343a44ab634748009509968gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=1c135e510150570b5354&rr=87a09d34c89401cc&cc=fr)

| ▲ [Top](#awesome-mining-band-ratio) |
|---|