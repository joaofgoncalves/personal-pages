+++
title = "SegOptim - A new R package for optimizing object-based image analyses of high-spatial resolution remotely-sensed data"
date = "2019-01-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Gonçalves J", "Pôças I", "Marcos B", "Mücher CA", "Honrado JP"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *International Journal of Applied Earth Observation and Geoinformation*"
publication_short = "In *JAG*"

# Abstract and optional shortened version.
abstract = "Geographic Object-based Image Analysis (GEOBIA) is increasingly used to process high-spatial resolution imagery, with applications ranging from single species detection to habitat and land cover mapping. Image segmentation plays a key role in GEOBIA workflows, allowing to partition images into homogenous and mutually exclusive regions. Nonetheless, segmentation techniques require a robust parameterization to achieve the best results. Frequently, inappropriate parameterization leads to sub-optimal results and difficulties in comparing distinct methods. Here, we present an approach based on Genetic Algorithms (GA) to optimize image segmentation parameters by using the performance scores from object-based classification, thus allowing to assess the adequacy of a segmented image in relation to the classification problem. This approach was implemented in a new R package called SegOptim, in which several segmentation algorithms are interfaced, mostly from open-source software (GRASS GIS, Orfeo Toolbox, RSGISLib, SAGA GIS, TerraLib), but also from proprietary software (ESRI ArcGIS). SegOptim also provides access to several machine-learning classification algorithms currently available in R, including Gradient Boosted Modelling, Support Vector Machines, and Random Forest. [open to see the full abstract]"

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_pdf = "http://joaogoncalves.cc/files/2019_Goncalves_et_al_SegOptim-A_new_R_package_for_optimizing_object-based_image_analyses.pdf"
#url_preprint = "#"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "https://www.sciencedirect.com/science/article/pii/S0303243418303556"

# Custom links (optional).
# Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
  #image = "headers/bubbles-wide.jpg"
  #caption = "My caption :smile:"

+++

### Full abstract

Geographic Object-based Image Analysis (GEOBIA) is increasingly used to process high-spatial resolution imagery, with applications ranging from single species detection to habitat and land cover mapping. Image segmentation plays a key role in GEOBIA workflows, allowing to partition images into homogenous and mutually exclusive regions. Nonetheless, segmentation techniques require a robust parameterization to achieve the best results. Frequently, inappropriate parameterization leads to sub-optimal results and difficulties in comparing distinct methods. Here, we present an approach based on Genetic Algorithms (GA) to optimize image segmentation parameters by using the performance scores from object-based classification, thus allowing to assess the adequacy of a segmented image in relation to the classification problem. This approach was implemented in a new R package called SegOptim, in which several segmentation algorithms are interfaced, mostly from open-source software (GRASS GIS, Orfeo Toolbox, RSGISLib, SAGA GIS, TerraLib), but also from proprietary software (ESRI ArcGIS). SegOptim also provides access to several machine-learning classification algorithms currently available in R, including Gradient Boosted Modelling, Support Vector Machines, and Random Forest. We tested our approach using very-high to high spatial resolution images collected from an Unmanned Aerial Vehicle (0.03-0.10 m), WorldView-2 (2 m), RapidEye (5 m) and Sentinel-2 (10-20 m) in six different test sites located in northern Portugal with varying environmental conditions and for different purposes, including invasive species detection and land cover mapping. The results highlight the added value of our novel comparison of image segmentation and classification algorithms. Overall classification performances (assessed through cross-validation with the Kappa index) ranged from 0.85 to 1.00. Pilot-tests show that our GA-based approach is capable of providing sound results for optimizing the parameters of different segmentation algorithms, with benefits for classification accuracy and for comparison across techniques. We also verified that no particular combination of an image segmentation and a classification algorithm is suited for all the tasks/objectives. Consequently, it is crucial to compare and optimize available methods to understand which one is more suited for a certain objective. Our approach allows a closer integration between the segmentation and classification stages, which is of high importance for GEOBIA workflows. The results from our tests confirm that this integration has benefits for comparing and optimizing both processes. We discuss some limitations of the SegOptim approach (and potential solutions) as well as a future roadmap to expand its current functionalities.