+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = 2016-04-20T00:00:00

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Microscopy"
subtitle = "Click on an image to view caption and open gallery"

# Order that this section will appear in.
weight = 15

+++
{{< load-photoswipe >}}
{{< gallery hover-effect="none" caption-position="none" >}}
{{< figure link="/img/Microscopy_Img/A-gossypii-Cdc12-RNA-smFISH.jpg" caption="A. gossypii Cdc12 RNA smFISH" >}}
{{< figure link="/img/Microscopy_Img/Ashbya-phalloidin.jpg" caption="A. gossypii labeled actin and nuclei" >}}
{{< figure link="/img/Microscopy_Img/C2C12-AchRa-smFISH.jpg" caption="C2C12 myotube with labeled AchRα mRNA" >}}
{{< figure link="/img/Microscopy_Img/C2C12-Fxr1GFP.jpg" caption="C2C12 myoblast overexpressing labeled FXR1" >}}
{{< figure link="/img/Microscopy_Img/S-pombe-fixed-and-phalloidin-stained.jpg" caption="S. pombe stained for actin" >}}
{{< figure link="/img/Microscopy_Img/S-pombe-fluorescent-cytokinetic-ring-and-SPBs.jpg" caption="S. pombe tagged actomyosin ring and SPBs" >}}
{{< /gallery >}}
