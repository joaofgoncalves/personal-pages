+++
title = "Evaluating an Unmanned Aerial Vehicle-Based Approach for Assessing Habitat Extent and Condition in Fine-Scale Early Successional Mountain Mosaics"
date = "2015-11-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Gonçalves, J", "Henriques R", "Alves P", "Sousa-Silva R", "Monteiro AT", "Lomba A", "Marcos B", "Honrado J"]

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
publication = "In *Applied Vegetation Science*"
publication_short = "In *AVS*"

# Abstract and optional shortened version.
abstract = "In this work we evaluated how very high-resolution colour imagery and digital surface models from an unmanned aerial vehicle can be effectively used for assessing of habitat extent and condition in fine-scale disturbance-dependent mountain mosaics. [open to see the full abstract]"

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["example-external-project"]

# Links (optional).
url_pdf = "http://onlinelibrary.wiley.com/doi/10.1111/avsc.12204/abstract"
#url_preprint = "#"
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

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

**Question**:
Can very high-resolution colour orthophotography and digital surface models (DSMs) from an unmanned aerial vehicle (UAV) be effectively used for assessment of habitat extent and condition in fine-scale disturbance-dependent mosaics? 

**Location**:
Serra de Arga mountain range, a Natura 2000 protected site in the NW region of Portugal where drastic changes in pastoral activities have occurred over recent decades. 

**Methods**:
An UAV platform was used to collect very high-resolution (6 cm) images and to produce a DSM (10 cm). From these data, several features were extracted related to colour, band ratios, as well as texture features calculated from colour imagery and surface elevation. Based on a systematic sampling design, field data were collected for both training and validation of a supervised classifier. Extracted features and ground truth training data were combined to calibrate a pixel-based Random forest classifier, with the purpose of devising a habitat map for the entire study area. Map validation was performed to assess classification accuracy, and feature importance metrics were calculated. 

**Results**:
Validation results revealed good mean overall accuracy (0.89), with some performance decrease in situations of high interspersion of habitat types. The priority habitat type 6230* (_Nardus_ grasslands), defining the vegetation matrix of the test site, obtained 0.96 and 0.91, considering, respectively, producer and user accuracy. In turn, priority habitat type 4020* (Atlantic wet heathlands) recorded 0.68 and 0.77. The obtained habitat map allowed measurement of the extent, description of the spatial arrangement and provided an indication of the conservation condition of target habitat types. Test results regarding the discrimination ability of different features highlighted the importance of surface elevation textures derived from the DSM, followed by band ratios textures and other more complex texture features calculated from colour imagery. 

**Conclusions**:
Overall, the developed methodology showed promising results for assessing the extent and condition of habitats of high conservation priority in fine-scale, dynamic vegetation mosaics. Future advances in the use of UAV platforms may play an important role in monitoring protected sites and fulfil legal reporting obligations of EU member states, while reducing the costs associated with intensive in-field assessments.
