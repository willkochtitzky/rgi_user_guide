# 10: Asia, North

Covers all glaciers in Eastern Russia, Kazakhstan, Mongolia, Northern China, and Japan.

:::{figure-md} rgi10-new-fig
<img src="https://cluster.klima.uni-bremen.de/~fmaussion/misc/rgi7_data/l4_rgi7b0_plots/RGI10/isrgi6_map.jpeg" alt="region map" class="bg-primary mb-1">

Glacier locations and changes between RGI6 and RGI7.
:::

Glacier outlines in Kamchatka have been re-mapped. Glacier outlines in Eastern Russia were reviewed using the Glacier Inventory of Russia {cite:p}`Khromova2022`. In subregion 10-04 (Altay and Sayan), we use the GAMDAM inventory version 2 {cite:p}`Sakai2019`. We added 5 small glaciers in Japan that have been recently documented {cite:p}`Arie2022`. Outline dates range between 1996 and 2019, with most of the area (~80%) dating to 1998-2002.   

## Additional information 

```{admonition} Data sources and analysts
:class: important, dropdown

:::{figure-md} rgi10-source-fig
<img src="https://cluster.klima.uni-bremen.de/~fmaussion/misc/rgi7_data/l4_rgi7b0_plots/RGI10/inventory_map.jpeg" alt="region map" class="bg-primary mb-1">

Submission IDs used for this region.
:::

Submission 636
: **Submitter**: Cogley, Graham.<br/>**Number of outlines**: 1646. **Area**: 394.0km². **Release date**: 2015-07-16.<br/>**Analysts**: Cogley, Graham; Earl, Lucas; Gardner, Alex; Raup, Bruce H..

Submission 726
: **Submitter**: Kochtitzky, William.<br/>**Number of outlines**: 12. **Area**: 73.0km². **Release date**: 2021-09-01.<br/>**Analysts**: Kochtitzky, William.

Submission 752
: **Submitter**: Sakai, Akiko.<br/>**Number of outlines**: 3001. **Area**: 1245.2km². **Release date**: 2018-08-24.<br/>**Analysts**: Sakai, Akiko.

Submission 761
: **Submitter**: Paul, Frank.<br/>**Number of outlines**: 2491. **Area**: 929.9km². **Release date**: 2022-05-11.<br/>**Analysts**: Barr, Iestyn; Khromova, Tatiana; Muraviev, Anton; Paul, Frank; Rastner, Philipp.

Submission 763
: **Submitter**: Arie, Kenshiro.<br/>**Number of outlines**: 5. **Area**: 0.5km². **Release date**: 2022-07-20.<br/>**Analysts**: Arie, Kenshiro.

Reviewers
: Barr, Iestyn; Khromova, Tatiana;

```

```{admonition} Outlines date distribution
:class: seealso, dropdown

:::{figure-md} rgi10-hist-fig
<img src="https://cluster.klima.uni-bremen.de/~fmaussion/misc/rgi7_data/l4_rgi7b0_plots/RGI10/date_hist.png" alt="region map" class="bg-primary mb-1">

Relative glacier area distribution per outline date.
:::

```

```{admonition} Version history
:class: note, dropdown

Changes from Version 5.0 to 6.0
: For some glaciers the source for hypsometry was changed from the ASTER GDEM2 to the ViewfinderPanoramas DEM3 (http://www.viewfinderpanoramas.org/).<br/>An error in the minimum elevation of 11 glaciers was detected. It had been set wrongly to 0 and that value was reset to missing. The corresponding hypsometric lists were also set to missing.


Changes from Version 4.0 to 5.0
: The inventory of mainland North Asia was replaced in its entirety from {cite:t}`Earl2016`. Nominal glaciers remain on Wrangell Island (3 km2) and the De Long Islands (Jeanette, Henrietta, Bennet; 81 km2). Glaciers in Chukotka (regions 10-05 and 10-06; Sedov 1997) that formerly appeared only in the RGI global grid are represented explicitly in version 5.0.<br/>Glacier outlines retired from version 4.0 will be added to GLIMS if they are not in GLIMS already.<br/>Links were added to 12 glaciers in the WGMS mass-balance database.<br/>The four second-order regions of earlier RGI versions were replaced by six regions conforming to those of {cite:t}`Earl2016`. The outlines of the two sets of regions differ in detail, but all glaciers are in the same region in both the source and the RGI.

Changes from Version 3.2 to 4.0
: One exterior GLIMSId was replaced. Topographic and hypsometric attributes were added, although this could not be done for most glaciers in North Asia, of which 2,832 out of 4,403 are nominal glaciers.<br/>The addition of dates for glaciers in the Chinese Altay is described under Region 13: Central Asia.

Changes from Version 3.0 to 3.2
: None.

Changes from Version 2.0 to Version 3.0
: All of the glaciers represented as circles were regenerated from WGI-XF {cite:p}`Cogley2009a`. Some of them have not just nominal shapes but nominal positions, being derived from the Soviet Katalog Lednikov, which in each drainage basin gives full information only for glaciers larger than 0.1 km2. Only a total number and total area are given for glaciers smaller than 0.1 km2. In WGI-XF these small glaciers are all assigned a common position roughly in the centre of their basins, and an equal share of the listed small-glacier area. Obviously these and other nominal glaciers should not be used for purposes other than calculating total glacierized area.<br/>Some DCW outlines were found to overlie mountain ranges whose ice cover was already represented by nominal glaciers. These duplicate DCW outlines were removed.

Changes from Version 1.0 to Version 2.0
: The DCW outlines of glacier complexes in Mongolia were replaced by outlines of glaciers digitized by J.G. Cogley from Soviet military maps. Their dates range between 1968 and 1983.<br/>14 glaciers in the Tajgonos Peninsula, northwest of Kamchatka (10-02) were added as nominal circles from WGI-XF.

Version 1.0
: About one third of the glacier outlines in North Asia were manually delineated from Landsat TM/ETM+ or ASTER imagery. Missing areas were filled by a glacier layer compiled by B. Raup {cite:p}`Raup2000` from the Digital Chart of the World (DCW) and the World Glacier Inventory {cite:p}`WorldGlacierMonitoringServiceWGMS1998`.

```