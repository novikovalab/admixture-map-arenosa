_Arabidopsis arenosa_ Admixture Map
==
The population map is constructed using the implementation from the [1001 genomes project](http://1001genomes.org/).

The population data represented on the piecharts was generated using software [Entropy](https://doi.org/10.1111/1755-0998.13330).

The following help message is cited from [1001 Genomes project admixture map](https://github.com/1001genomes/admixture-map) with changes according to the present dataset.

![Admixture-map](https://raw.githubusercontent.com/1001genomes/admixture-map/master/preview.gif "1001 Genomes Admixture Map")

For each population a piechart is displayed. The slices correspond to the various fractions of the Entropy cluster. Users can change the number of clusters K by clicking on the gear icon in the top left corner (by default data for K=6 is shown).

For K=6, clusters were named post-hoc according to geography. These clusters were also used to attribute individuals to groups. An individual for which more than 60% of its genome derives from a given cluster is attributed to the group of the same name as the cluster. Individuals which do not draw more than 60% from a single cluster were labelled "admixed".

Because of the number of populations nearby locations are clustered together and an averaged piechart is displayed. The number inside the piechart shows the number of samples that are clustered together. Clicking on a cluster will zoom into the region and display piecharts for individual populations or smaller clusters.

The list on the left side shows all samples that are visible in the current view. Zooming into specific regions either by clicking on a cluster or using the Google Maps zoom control will update the list. Hovering the mouse over a cluster will filter the list to display only the samples that are part of the corresponding cluster and in addition to show a popup with a more detailed version of the piechart.

Hovering the mouse over a sample in the list will display a pin on the map at its location and clicking on the list item will zoom into that position. A searchbox above the list allows the user to search for a specific sample using either the ID or the name.
