# Awesome Mining Band Ratio


[![Awesome](https://raw.githubusercontent.com/softwareunderground/awesome-open-geoscience/master/media/icon/badge.svg)](https://github.com/sindresorhus/awesome) [![Commits](https://img.shields.io/github/last-commit/rodreras/awesome-mining-band-ratio.svg?label=last%20contribution)](https://github.com/rodreras/awesome-mining-band-ratio/commits/main) [![License](https://img.shields.io/github/license/rodreras/awesome-mining-band-ratio.svg)](https://github.com/rodreras/awesome-mining-band-ratio/blob/master/LICENSE)



A curated list of  materials, mineral spectral signature and published band ratios aiming the application of Remote Sensing to Mineral Exploration. 

![alt text](images/logo.png)

**Please contribute. Let's make this guide better!**






**Table of Contents**

- [Aster Band Ratios](#aster-band-ratios)
- [Landsat and Sentinel](#landsat-and-sentinel)
- [Minerals Spectra Signature](#minerals-spectra-signature)
- [Awesome List](#awesome-list)
- [References](#references)

---

## Aster Band Ratios


**IMPORTANT**: <span style="color:red">the SWIR sensor (bands 4 to 9) are inoperable since 1st April 2008, and therefore only data acquired before this date will be suitable for mineral mapping</span>

| Feature               | Aster Band Ratio    | Ratio Description                                             | References                            |
|-----------------------|---------------------|---------------------------------------------------------------|---------------------------------------|
| Iron Minerals         | B2/B1               | Ferric Fe3                                                    | Rowan and Mars, 2003; Hewson et al., 2001, 2004a |
| Iron Minerals         | (B5/B3)+(B1/B2)     | Ferrous Fe2                                                   | Rowan and Mars, 2003                |
| Iron Minerals         | B4/B2               | Gossan                                                        | Volesky et al., 2003                |
| Iron Minerals         | B5/B4               | Ferrous Silicates (biotite, chl, amphibolite) Cu-Au Alteration | Hewson et al., 2001, 2004a         |
| Iron Minerals         | B4/B3               | Ferric Oxides                                                 | Hewson et al., 2001, 2004a         |
| Carbonates/Mafic Minerals | (B7+B9)/B8     | Carbonate/Chlorite/Epidote                                    | Rowan and Mars, 2003                |
| Carbonates/Mafic Minerals | B13/B14        | Carbonate Index (Exoskarn (cal/dolom) 92% cfd)                 | Bierwirth 2002, Nimoyima         |
| Carbonates/Mafic Minerals | (B6+B9)/(B7+B8) | Epidote/Chlorite/Amphibole (Endoskarn)                        | Hewson et al., 2001, 2004a                                |
| Carbonates/Mafic Minerals | (B6+B9)/B8     | Amphibole/MgOH (Can be other MgOH or carbonate*)             | Hewson et al., 2001, 2004a         |
| Carbonates/Mafic Minerals | B6/B8          | Amphibole                                                      | Bierwirth, 2002                          |
| Carbonates/Mafic Minerals | (B6+B8)/B7     | Dolomite                                                       | Rowan and Mars, 2003                |
| Carbonates/Mafic Minerals | (B7/B6)*(B4/B6) | Hydroxyl Group (OHI) 92% cfd                                  | Ninomiya, 2002                     |
| Carbonates/Mafic Minerals | (B4/B5)*(B8/B6) | Kaolinite (KLI) 92% cfd                                       | Ninomiya, 2002                     |
| Carbonates/Mafic Minerals | (B7/B5)*(B7/B8) | Alunite (ALI) 92% cfd                                         | Ninomiya, 2002                     |
| Carbonates/Mafic Minerals | (B6/B8)*(B9/B8) | Calcite (CLI)                                                  | Ninomiya, 2002                     |
| Silicates             | (B5+B7)/B6          | Sericite / Muscovite / Illite / Smectite (Phyllic alteration) | Rowan and Mars, 2003; Hewson et al., 2001, 2004a |
| Silicates             | (B4+B6)/B5          | Alunite / Kaolinite (Pyrophyllite) 92% cfd                   | Rowan and Mars, 2003               |
| Silicates             | B7/B6               | Muscovite 92% cfd                                             | Hewson et al., 2001, 2004a         |
| Silicates             | B7/B5               | Kaolinite 92% cfd                                             | Hewson et al., 2001, 2004a         |
| Silicates             | (B5*B7)/(B6*B6)     | Clay 92% cfd                                                  | Bierwith, 2002                      |
| Silica Sio2           | B14/B12             | Quartz Rich Rocks Qz Index                                    | Rowan and Mars, 2003               |
| Silica Sio2           | (B11/B10)*(B11/B12) | Quartz 92% cfd                                                | Ninomya, 2003a                      |
| Silica Sio2           | B12/B13             | Silica (Basic Degree Index (gnt))                               | Ninomiya,  2002; Bierwirth, 2002;  Hewson et al., 2001, 2004a    |
| Silica Sio2           | B13/B10             | Silica                                                         | Hewson et al., 2001, 2004a         |
| Silica Sio2           | (B11xB11)(B10B12)  | Silica Index 92% cfd                                          | Ninoyima, 2002                            |


| ▲ [Top](#awesome-mining-band-ratio) |
|---|

## Landsat and Sentinel

Landsat and Sentinel don't have the same range as Aster. The ratios and RBG compositions below can be done with data from them and other plataforms. In order to make it comparable, let's use [Awesome Spectral Indeces](https://awesome-ee-spectral-indices.readthedocs.io/en/latest/index.html) table of generic variables for spectral indices expressions and satellite equivalents.

#### Bands Comparison Among Plataforms

<table>
<tr>
<th> Description </th>
<th> Standard </th>
<th> Spectral Range (nm) </th>
<th> Sentinel-2 </th>
<th> Landsat-89 </th>
<th> Landsat-457 </th>
</tr>
<tr>
<td>Aerosols</td>
<td>A</td>
<td>400 - 455</td>
<td>B1</td>
<td>B1</td>
<td></td>
</tr>
<tr>
<td>Blue</td>
<td>B</td>
<td>450 - 530</td>
<td>B2</td>
<td>B2</td>
<td>B1</td>
</tr>
<tr>
<td>Green</td>
<td>G</td>
<td>510 - 600</td>
<td>B3</td>
<td>B3</td>
<td>B2</td>
</tr>
<tr>

<tr>
<td>Red</td>
<td>R</td>
<td>620 - 690</td>
<td>B4</td>
<td>B4</td>
<td>B3</td>
</tr>
<tr>
<td>Red Edge 1</td>
<td>RE1</td>
<td>695 - 715</td>
<td>B5</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Red Edge 2</td>
<td>RE2</td>
<td>730 - 750</td>
<td>B6</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Red Edge 3</td>
<td>RE3</td>
<td>765 - 795</td>
<td>B7</td>
<td></td>
<td></td>
</tr>
<tr>
<td>NIR</td>
<td>N</td>
<td>760 - 900</td>
<td>B8</td>
<td>B5</td>
<td>B4</td>
</tr>
<tr>
<td>NIR 2</td>
<td>N2</td>
<td>850 - 880</td>
<td>B8A</td>
<td></td>
<td></td>
</tr>
<tr>
<td>Water Vapour</td>
<td>WV</td>
<td>930 - 960</td>
<td>B9</td>
<td></td>
<td></td>
</tr>
<tr>
<td>SWIR 1</td>
<td>S1</td>
<td>1550 - 1750</td>
<td>B11</td>
<td>B6</td>
<td>B5</td>
</tr>
<tr>
<td>SWIR 2</td>
<td>S2</td>
<td>2080 - 2350</td>
<td>B12</td>
<td>B7</td>
<td>B7</td>
</tr>
<tr>
<td>Thermal</td>
<td>T</td>
<td>10400 - 12500</td>
<td></td>
<td></td>
<td>B6</td>
</tr>
<tr>
<td>Thermal 1</td>
<td>T1</td>
<td>10600 - 11190</td>
<td></td>
<td>B10</td>
<td></td>
</tr>
<tr>
<td>Thermal 2</td>
<td>T2</td>
<td>11500 - 12510</td>
<td></td>
<td>B11</td>
<td></td>
</tr>
</table>

____

#### RGB Composition and Band Ratio for Landsat 8-9 and Sentinel-2 

**Aster Bands 5 to 7 fall within band 12 of Sentinel-2.**

| Description                       | Ratio / Channel R | Channel G | Channel B | Comment                            |
|-----------------------------------|-------------------|-----------|-----------|------------------------------------|
| Natural Colour                    | R                 | G         | B         |                                    |
| Colour Infrared (vegetation)      | N                 | R         | G         |                                    |
| False Colour (Urban)              | S2                | S1        | R         |                                    |
| Agriculture                       | S1                | N         | B         |                                    |
| Vegetation Index                  | (N – R)/(N + R)   |           |           |                                    |
| Moisture Index                    | (N2 – S1)/(N2 + S1)|          |           |                                    |
| Geology                           | S2                | R         | B         |                                    |
| Bathymetric                       | R                 | G         | A         |                                    |
| Atmospheric Penetration           | S2                | S1        | N2        |                                    |
| SWIR                              | S2                | N2        | R         |                                    |
| NDWI                              | (G – N)/(G + N)   |           |           |                                    |
| SWIR-2                            | B                 | S1        | S2        |                                    |
| Ferric Iron "Redness"             | R/B               |           |           |                                    |
| Ferric Iron 2                     | (R/B)*((R+S1)/N)  |           |           |                                    |
| Ferrous Iron                      | (G+S1)/(R+N)      |           |           | coarse grained ferric iron          |
| Clay, sulphate, mica, marble      | (S1/S2)/(N/R)     |           |           |                                    |
| Iron sulphate                     | (B/A)-(N/R)       |           |           |                                    |
| Ross Smail/Getech                 | S1/R              | R/B       | S2/S1     |                                    |
| Gad and Kusky 1                   | S1/R              | S2/S1     | S1/B      |                                    |
| Gad and Kusky 2                   | S2/S1             | S1/N      | R/B       | Serpentinites in dark brown-green   |
| Zohair et al 2019                 | S1/S2             | S1/N      | R/B       | Serpentinites in dark brown         |
| Pour                              | R/B               | R/S1      | S1/S2     | Serpentinites in yellow             |
| Sultan 1986/Gomez 2005            | S1/S2             | S1/B      | S1/N * R/N|                                    |
| Abrams 1983                       | S1/S2             | N/S1      | R/B       | Ultramafic/Basic-Mafic/Felsic       |
| Mineral map                       | S2/N              | N/S2      | S1/R      |                                    |


## Minerals Spectra Signature

- [USGS Mineral Spectral Library](https://crustal.usgs.gov/speclab/QueryAll07a.php)

| ▲ [Top](#awesome-mining-band-ratio) |
|---|

## Awesome List

[Awesome Spectral Indexes](https://awesome-ee-spectral-indices.readthedocs.io/en/latest/index.html)

| ▲ [Top](#awesome-mining-band-ratio) |
|---|

## References

[Loughlin, 1991. Principal Component Analysis for alteration mapping](https://www.asprs.org/wp-content/uploads/pers/1991journal/sep/1991_sep_1163-1169.pdf)

[Sabin, 1997. Remote Sensing for Mineral Exploration](https://pdf.sciencedirectassets.com/271770/1-s2.0-S0169136800X00194/1-s2.0-S0169136899000074/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPz%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJGMEQCIE7V6MKq3URKltuba4cfNOVrSOGDvzLjaAncv8lE9qP%2BAiANPBdCURQwE2cGZMr77cng7yPzQj8%2BFu1xAY2NTpPfsyqyBQh1EAUaDDA1OTAwMzU0Njg2NSIMP%2Fa3IAcSaIKZD6kWKo8FtUtpXngTzLtWIl3S1ndToZc1zAwLRS9lV%2F41L%2B9UN%2FYB000Sg72W%2B8Nz3vpb76tVX1R3%2FEo8THTCmLyqR4rWatDsG5vy%2FUBLYsf8jMQxwLnAmgNy3CKfDbPIchXx362zIK%2BIr1YSawaLmwZ5WliGkqZD8p20DG%2Bmu8HVbuDaF0OV8Wj0bMO%2F%2BCov9X3VeQEwxHwvT%2Ffk%2BmARr5YUJcfZx7v889LyqUpv7BszkQhHNFWMgNktE4JHjaEvNr8XH0QgweFD%2FvqB%2F1EYG0lymbM01hnOXeGFUmZ4Z7k7OFPd%2FohYhAx36R5RtkL1P%2BQqgzl3RD7Q1ZvJ5Ns%2FTJWtHWAnuKOLk1ga9weFraJX4aivzkilwjb7iICnbc%2Fuss0jzA72WVHxJmP3pkzRxY4CzXg28xp9Coze4BWljwmBguyuH3ilURBZ6ZrruSDhIeD29gGNIDX%2FdcHQdvb%2Bfa0kKWt5BJ%2BOr1kbYWRaeaKk5SiFmJpVxLPhq1%2FHtP%2FCBGHTr5d3Zz7hn2lHJUKn1ip53Q1gIyQlmIBXpGPf%2FyT7g4IkuR0JLyjVcGGo6XMJ2TXU5zKDl%2F5vXB%2BJny5uLmBibezYyN251G5Z19j6ByPf2mAj0x9hvtoghqGz3%2BifGsdw%2BJUcQjyYyTOc6%2B2hVkvO2Ki8hnPoh8OpHQmxyzzt19VwLTCefvaJDNe5ki9ah4ShAwqkMhh6sBPx85BfnKqIfJK%2BjcV%2B6IYxdFpCbYhy0lE%2Bfy%2FKRVwATxN8I9bOYWCJuLeIBpgxzHlTkk4zQe0fdLZUgnWAbg0LZuTAFYsBa6sSoJvEbzppMzUeoSZN%2F4jd70qXxOxmVm3CDLNGakpnI3q65wQuQwRmarlbWqFUnDMnXDCy4LyyBjqyAUwC2yF%2FsaobUlS1557J7p2gbVXnQHrArWCZhzAalqhWrtHcZtUUOX0ABnSUohwVrQ73GtCXxj4LNf5LXdAZxXt8d%2FOKRm4xuGXzUGP2EVZm%2BzbE%2FeRs41MGpbV8hxAEBe4eOgo9Ro%2BWWeNlm%2FxAkcwTuKgyFuCRUMYlQTrVmwrRcBStL3aCVoeYf2KvsEbpsJ4LkgYj2OhopJmMFf%2BG89z2qiyBIJRgs5ubu8ERSkdGyoI%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240523T132406Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY7LPIKMMH%2F20240523%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=1204e8782ed6fa74193192def1d6f758e00641ae596cad826d96cdd19b435d97&hash=1a91b05a53633d1eb756931e29a5f46fdce1afaa6e8a9b6a3e116d02acf96148&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0169136899000074&tid=spdf-b20a0a9a-48e1-421e-bf28-00c8c6c74962&sid=2d32cc1b1d558945c53a779348f8cdccfba4gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=001156565a5353075651&rr=88855d458b5e7762&cc=fr)

[Hewson & Huntington, 2001A. Geologic and alteration mapping at Mt Fitton, South Australia, using ASTER satellite-borne data](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=976615)

[Hewson et al., 2001B. Seamless geological map generation using ASTER in the Broken Hill-Curnamona province of Australia](https://pdf.sciencedirectassets.com/271745/1-s2.0-S0034425705X0284X/1-s2.0-S0034425705001744/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEP3%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJIMEYCIQCWlNjLarYGIRrg98m6NboO8QU3a2w12fsaZDn3iR%2B3yQIhAPb0bg8TIXQTUgWed2J7HbdSSHn2uNC2KhZL8qNnKAEwKrMFCHUQBRoMMDU5MDAzNTQ2ODY1IgyXPuxgJi2PnTqPDAMqkAU7Hk8ZNzKLyolTf7yAX3ClEOXEsN2fJ4WnDnCLju%2BkcVZ1oS8Xp6nm0uESoZns1hcb5ucDzkXJbAXpxFukywOfqYuBdiSz4pRuqaFQ7KXI5xQQRrHAiASLg3HYREO6AxEro8A8kgnO4RVEtmrT4OjMZ0lbNcBs4BgSCLg3d7vMqsHHlQnN%2F01IU5JDD6dbw3h3Przh7hPEi%2B6PGjgKQguDgiXawghKJOkxUODjKsLpBh8nwjbCFGbIbCVHBA%2BnmR%2FaJxoEdqWbL341XhREH1F9SlyHKOSAet3EgfDR%2BbalwrBJnA%2BytcFAmHQxwoyqdKVWdWJG6CwvIq%2F5bUcfORF7mMFl%2B3GjZ%2BcOQY%2BhdS4gp3riNk%2B0PqNtmWKVFYPym6h%2FserLopyMarVV63DsMREYSpqDUbaTKbMJHaCrRfrZSNY8QLuxmwRy9BDbY0HJ98%2FSbnLnRmAzDxiYRDWBPiAVFjFyx5SAVL1ayYQQEkj02SYpA%2Bvxk8X5x9aVaKs2jRowJIUQ3RISpVNMVJ1EU8yv%2FBh850mQIRUSxyPfZfj12ondCRlEkRTxOTZks7MytyHk1937dGDAkVoNoIEDLJvGZzG8IoIhB9pUBNrhlVGF1NpO90bY1w%2FMOOtCSu0VRSZaMKvwNUjIuAK9K7Loun13TyrcnymJQZpGtllUHZ40VW%2F5INt%2BsHxbrk%2FE856mM0lWeos%2B0VaOpzpOH1dFKF1bIyDCnFVBCZ2%2FDBfBE7XOLtDzj7OiqJx4yD236iLecUyy5PHVyYwCRfTNTJwb%2BMEqHalnP%2BSuvE2iJN8C%2BvU5dBfJixc0fyVFHala9t%2F8nmvviiVXZk4W68%2FFVB%2Blv7n8YUuUscni596YYOKRSekUzjCB47yyBjqwAVrNSAl1jQyWQU6GnSPv%2FvhMVnpHBQlYkqD%2BVzF0GF91yLpzFYd2dSTlW%2BVg9QzFW7fvHwfRnPpQV0Kkzvgy7a%2BKzddcwtQZyXwuLzzDEhhF9HZ8%2BIKG1AeX80hOw5UZvtoJvYlqW5MJ%2Bi16%2BnfrpqutMFeYVzIP8iFcIoTkouOmLGAze8T2L%2F4nTzrdt3kmoBhF5tD8Nu8bVNQVPh5oEn0ziIXQN8z2iX5RfzZAd6WV&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240523T130637Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYRIB5NT6H%2F20240523%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=bb9b31efec7c798785b93979597f8916b6cf828b96ee49f0634785d3089118a6&hash=0724a8656f8a7f269255aaad7cf8bc7a34f927f963a00803a2afb492625fcbc5&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0034425705001744&tid=spdf-b9df9244-428c-426a-ac18-44d80830e709&sid=2d32cc1b1d558945c53a779348f8cdccfba4gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=001156565a5352500352&rr=888543a658ad76cb&cc=fr)

[Bierwirth et al., 2002. Hyperspectral Mapping of Mineral Assemblages Associated with Gold Mineralization in the Central Pilbara, Western Australia](https://pubs.geoscienceworld.org/segweb/economicgeology/article-abstract/97/4/819/22214/Hyperspectral-Mapping-of-Mineral-Assemblages)

[Ninomiya, 2002. Mapping quartz, carbonate minerals, and mafic-ultramafic rocks using remotely sensed multispectral thermal infrared ASTER data](https://www.researchgate.net/publication/234942606_Mapping_quartz_carbonate_minerals_and_mafic-ultramafic_rocks_using_remotely_sensed_multispectral_thermal_infrared_ASTER_data)

[Volesky et al., 2003. Geological control of massive sulfide mineralization in the Neoproterozoic Wadi Bidah shear zone, southwestern Saudi Arabia, inferences from orbital remote sensing and field studies](https://www.sciencedirect.com/science/article/pii/S0301926803000706)

[Rowan & Mars, 2004. Lithologic mapping in the Mountain Pass, California area using Advanced Spaceborne Thermal Emission and Reflection Radiometer (ASTER) data](https://www.sciencedirect.com/science/article/pii/S003442570200127X)

[van der Meer et al., 2012. Multi- and hyperspectral geologic remote sensing: A review](https://pdf.sciencedirectassets.com/272637/1-s2.0-S0303243411X00065/1-s2.0-S0303243411001103/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEGMaCXVzLWVhc3QtMSJHMEUCIQCJyUff4Gz81QJF9JdezEEKRD%2BS1atEQYlRZHk%2Fmi0qRgIgETNRx0UVr%2FEnC4gpQ3biYZuhPQLGSAqF3b8IRFlb0T4qvAUIrP%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDDYVk6eGnpHpedJhPiqQBXgjSIKURTr51rsKMdz0ZRMrbTW5LnIgAFBCcojJhHz3G6gL5v6CHHvmf9eJ1XNZf4DuWVuRvo0thZA8ZAYnIZAoQnfB8769v287qXxZ0Z%2FezUsNQZfF9cU8rXh2RkVTqtaDRD4%2Fiw1MuaV3ho7C77eSakSSyqcmThol8fN3KQXBfEgaA04LlBtqir45pLGp9LC%2FoZijU5Pz1F3qG0kPyiiXpWKg7otf4FlVXleyk9WDbwyOiuPwKoRVmm3wgmSgWzYbEnxJmw8DKwwH75tBjp%2Bhr53Tuv9yGnvfs%2B2vSjXkLyT51%2FjHe0fPYWF2f9uRmDBUaeYZHYh9EaM1W7fICQtBGw0Lg8dg5NXZ%2FLtphHef4Gtb2x4CiuX%2BAa5gziOjRVCRwBtgYjx7DWSw5yQ9tLsGY0siHVY6TptmoP71kfcuKlTnpFiBRemWeT97CubIPEPLvYNsjqjtzgbMTU7qPuaWb2NozzlFbPxqCRuhhb6LkDe5dcbgcXFZQTNNoyjM4m2O9X2hU%2FeQbVBE8yAX%2BHHV1148gvpLHZimg5SzOIB%2F%2BeQj43eTYCxa2CFMu%2BLrWIt9aciw8JTMvArEuhXe0IJ0p88dG%2FL8ZjKSPJAlqzHUiv9XNbzO3fXJ%2BN2vD1kur7d9zqREp%2BGHtLFUimLxYLmzoyh6YHGAa3nZEOGYk8SsLChWAj3Y71a154i0xPDDlLLKXCyK%2FxAwNrVe4r0NgQ5oSE%2BAFk0fJxpNjPDiUCnlSywBj2YXnkd95KgiGTwvgCghMlqGGAAjBmPquCm%2FjSMjwYmmqBxEraPBZ90jB%2FKuXUkRkhgPPS4fB4jeYSDDbjGl1S%2B7Dzr142vnd2KkiSY9c7n2DZrcd8f9j0bqqiUmMILIqrEGOrEBj4E80zOBvX%2F8JTKgnrkyuGZTasbkRWtQ2cFumYTurVL9Qxn3ikkRqn%2FBKEAMtW3147zZINdawVgBVI2S0Y5hT%2BmWkclnePa3aDnae38ZHgJbYx3uSJ2Qe7YoZnA%2FJ%2BRi1JNXR6ogHcHE107CTyqGSjhbUHWpTe%2Bqwe%2BKUUzfaSY3YUvV3LCfD6CzW6QEeULgHhkDPI4eOHiY1%2FNAV64bonv4xqH%2Fs%2BwZPdJ8hUXdcIhD&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240425T190706Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYUZJMK2ES%2F20240425%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=61194111661af2a2b54bb010aebf17aeb29756527712a8291d753b89900ed643&hash=103183f55df46fa10e14ad228c6bc030df697f7e7ab88e271033839fb8931d94&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0303243411001103&tid=spdf-abfaa764-d3c1-4b8f-9e3d-2d80631ef776&sid=f7ca20818f06a343a44ab634748009509968gxrqb&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=1c135e510150570b5354&rr=87a09d34c89401cc&cc=fr)

[Jara, 2017. Multi-Scale integrated application of Spectral Geology and Remote Sensing for Mineral Exploration](https://www.researchgate.net/profile/Constanza-Jara/publication/320929822_Multi-scale_Integrated_Application_of_Spectral_Geology_and_Remote_Sensing_for_Mineral_Exploration/links/5a02f77c458515713b3f591a/Multi-scale-Integrated-Application-of-Spectral-Geology-and-Remote-Sensing-for-Mineral-Exploration.pdf)

[Frutuoso et al., 2020. Application of remote sensing data in gold exploration: targeting hydrothermal alteration using Landsat 8 imagery in northern Portugal](https://www.fc.up.pt/RS-GISLab/papers/Frutuoso2021_Article_ApplicationOfRemoteSensingData.pdf)

[Peyghambari & Zhang, 2021. Hyperspectral remote sensing in lithological mapping, mineral exploration, and environmental geology: an updated review](https://www.spiedigitallibrary.org/journals/journal-of-applied-remote-sensing/volume-15/issue-3/031501/Hyperspectral-remote-sensing-in-lithological-mapping-mineral-exploration-and-environmental/10.1117/1.JRS.15.031501.full?tab=ArticleLinkCited)


| ▲ [Top](#awesome-mining-band-ratio) |
|---|