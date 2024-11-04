# Agricultural Computer Vision Datasets Survey

<p align="center">
  <img src="plants.png" alt="Agricultural plants">
  <br>
  <em>Example images from included datasets. From left to right: LucasVision [Yo23], GlobalWheatHeadDetection [Da21], PaddyDoctor [Pe23], and CottonWeedID15 [Ch23].</em>
</p>

This repository contains a curated list of high-quality RGB image datasets for computer vision in agriculture, specifically focused on natural field scenes. The datasets were collected as part of our research paper "A Survey of Datasets for Computer Vision in Agriculture: A catalogue of high-quality RGB image datasets of natural field scenes" (Heider et al., 2025).

## Overview

We provide access information to 45 carefully selected datasets that meet the following criteria:
- Domain coherence: Natural field scenes (plants on fields or pastures taken under natural light)
- High-quality ground truth data with substantial annotations 
- Consistent image quality (resolution, minimal motion blur, adequate lighting)
- Original datasets (no web-scraped or reused images)

The datasets cover various agricultural computer vision tasks:
- Weed detection and classification (29 datasets)
- Disease and pest detection (9 datasets)
- Seedling and crop detection (6 datasets)
- Plant growth stage detection
- Phenotyping
- Various detection and counting tasks

## Contributing

We welcome contributions to this dataset collection! If you have a dataset that meets our criteria, please submit a pull request with the following information:
- Dataset name and brief description
- Task category
- Image count and resolution
- Annotation type and count
- Access information
- Citation details

## Citation

If you use this collection in your research, please cite our paper:

```bibtex
@article{heider2025survey,
  title={A Survey of Datasets for Computer Vision in Agriculture: A catalogue of high-quality RGB image datasets of natural field scenes},
  author={Heider, Nico and Gunreben, Lorenz and Z{\"u}rner, Sebastian and Schieck, Martin},
  journal={Lecture Notes in Informatics (LNI)},
  publisher={Gesellschaft f{\"u}r Informatik},
  address={Bonn},
  year={2025}
}
```

Full citations for individual datasets can be found in the bibliography section of our paper.

## Dataset Collection

| Label | Year | Author | Plant (English) | Plant (Latin) | Plant / Leaf / Fruit | Task | Annotation | Public Comment | Number of Images | Paper-URL | Dataset-URL |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| AmsinckiaInChickpeas [We24b] | 2023 | Plant, Brad | Crops: Chickpeas; Weeds: Ansinckia | Crops: Cicer arietinum; Weeds: Ansinckia | Whole plant | Weed Detection | Bounding Boxes |  | 124 | https://weed-ai.sydney.edu.au/datasets/21675efe-9d25-4096-be76-3a541475efd4 | https://weed-ai.sydney.edu.au/datasets/21675efe-9d25-4096-be76-3a541475efd4 |
| AnnualRyegrassAndTurnipweedInWheat [We24c] | 2021 | Coleman, Guy | Crops: Wheat; Weeds: Annual Ryegrass, Turnipweed; | Crops: Triticum aestivum; Weeds: Lolium rigidum, Rapistrum rugosum; | Whole plant | Weed Detection | Bounding Boxes |  | 27 | https://weed-ai.sydney.edu.au/datasets/5158bbe5-6030-48ad-8214-b68ff8118c22 | https://weed-ai.sydney.edu.au/datasets/5158bbe5-6030-48ad-8214-b68ff8118c22 |
| ASDID [BSH22] | 2022 | Bevers, Noah; Sikora, Edward J.; Hardy, Nate B. | Crops: Soybean; | Crops: Glycine max; | Leaf | Disease Detection | Image Classes | Disease types and deficiencies like bacterial blight, Cercospora leaf blight, frogeye leaf spot, downy mildew, soybean rust, target spot, potassium deficiency, and healthy plants | 9981 | https://www.sciencedirect.com/science/article/pii/S0168169922007578 | https://datadryad.org/stash/dataset/doi:10.5061/dryad.41ns1rnj3 |
| BeanLeafDataset [Ma20] | 2020 | Makerere AI Lab | Crops: Bean; | Crops: Phaseolus; | Leaf | Disease Identification | Image Classes | Angular Leaf Spot and Bean Rust | 1200+ | https://github.com/AI-Lab-Makerere/ibean | https://huggingface.co/datasets/AI-Lab-Makerere/beans |
| BroadleafWeedsInCommonCouch [We24d] | 2022 | Coleman, Guy | Crops: Common Couch; Weeds: Broadleaf Weeds; | Crops: Elymus repens.; Weeds: Conyza spp.; | Whole plant | Weed Detection | Bounding Boxes |  | 78 | https://weed-ai.sydney.edu.au/datasets/8b14a44b-bc7f-4b92-9bc0-224a2a2c4e22 | https://weed-ai.sydney.edu.au/datasets/8b14a44b-bc7f-4b92-9bc0-224a2a2c4e22 |
| BrownlowHillFireweed [We24k] | 2022 | Coleman, Guy | Crops: Pasture; Weeds: Fireweed; | Crops: Various Poaceae; Weeds: Senecio madagascariensis; | Whole plant | Weed Detection | Bounding Boxes |  | 20 | https://weed-ai.sydney.edu.au/datasets/24b34712-c31b-4efc-9790-406d1f14d840 | https://weed-ai.sydney.edu.au/datasets/24b34712-c31b-4efc-9790-406d1f14d840 |
| CobbityWheat [We24e] | 2021 | Coleman, Guy | Crops: Wheat; Weeds: Wild radish, Turnipweed; | Crops: Triticum aestivum; Weeds: Raphanus Raphanistrum, Rapistrum rugosum; | Whole plant | Weed Detection | Bounding Boxes |  | 39 | https://weed-ai.sydney.edu.au/datasets/3c363da3-6274-45e4-a0ce-b307cb0f89cc | https://weed-ai.sydney.edu.au/datasets/3c363da3-6274-45e4-a0ce-b307cb0f89cc |
| CornLeafInfection [Ac20] | 2020 | Acharya, Ramkrishna. | Crops: Maize; | Crops: Zea mays; | Leaf | Disease Detection | Bounding Boxes |  | 2225 | https://www.kaggle.com/datasets/qramkrishna/corn-leaf-infection-dataset | https://www.kaggle.com/datasets/qramkrishna/corn-leaf-infection-dataset |
| CottonWeedDet3 [RLW23] | 2023 | Rahman, Abdur; Lu, Yuzhen; Wang, Haifeng | Crops: Cotton; Weeds: Various; | Crops: Gossypium; Weeds: Various; | Leaf | Weed Detection | Bounding Boxes |  | 848 | https://www.sciencedirect.com/science/article/pii/S2772375522000910 | https://www.kaggle.com/datasets/yuzhenlu/cottonweeddet3 |
| CottonWeedID15 [Ch23] | 2023 | Chen et al. | Crops: Cotton; Weeds: Morningglory, Carpetweed, Palmer amaranth, Waterhemp, Purslane, Nutsedge, Eclipta, Spotted spurge, Sicklepod, Goosegrass, Prickly sida, Ragweed, Crabgrass, Swinecress, Spurred anoda; | Crops: Gossypium; Weeds: Mollugo verticillata, Amaranthus palmeri, Amaranthus tuberculatus, Portulaca oleracea, Cyperus spp., Eclipta prostrata, Euphorbia maculata, Senna obtusifolia, Eleusine indica, Sida spinosa, Ambrosia artemisiifolia, Digitaria spp., Coronopus didymus, Anoda cristata; | Leaf | Weed Identification | Image Classes |  | 5187 | https://www.sciencedirect.com/science/article/abs/pii/S0168169922004082?via%3Dihub | https://www.kaggle.com/datasets/yuzhenlu/cottonweedid15 |
| DeepSeedling [Ji19] | 2019 | Jian et al. | Crops: Cotton; Weeds:  Dicotyledonous, Monocotyledonous, Various; | Crops: Gossypium hirsutum; Weeds:  Dicotyledonous, Monocotyledonous, Various; | Seedlings  | Seedling Detection, Seedling Counting | Bounding Boxes |  | 5610 | https://doi.org/10.1186/s13007-019-0528-3 | https://figshare.com/s/616956f8633c17ceae9b |
| DeepWeeds [Ol19] | 2019 | Olsen et al. | Weeds: Chinee apple, Snake weed, Lantana, Prickly acacia, Siam weed, Parthenium, Rubber vine, Parkinsonia; | Weeds: Ziziphus mauritiana, Stachytarpheta spp., Lantana camara, Vachellia nilotica, Chromolaena odorata, Parthenium hysterophorus, Cryptostegia grandiflora, Parkinsonia aculeata; | Leaf | Weed Detection | Image Classes |  | 17509 | https://www.nature.com/articles/s41598-018-38343-3 | https://github.com/AlexOlsen/DeepWeeds |
| DPA [RRG20] | 2020 | Riehle, Daniel; Reiser, David; Griepentrog, Hans W. | Crops: Maize, Sugar beet; | Crops: Zea mays, Beta vulgaris; | Leaf, Fruit, Whole plant | Plant Classification | Segmentation Masks |  | 200 | https://www.sciencedirect.com/science/article/pii/S0168169919314346 | https://github.com/hohenheimdr/DPA |
| EarlyCropWeed [Es20] | 2020 | Espejo-Garcia et al. | Crops: Tomato, Cotton; Weeds: Black nightshade, Velvetleaf; | Crops: Solanum lycopersicum, Gossypium hirsutum; Weeds: Solanum nigrum, Abutilon theophrasti; | Leaf | Weed Detection | Image Classes |  | 504 | https://www.sciencedirect.com/science/article/pii/S0168169919319854 | https://github.com/AUAgroup/early-crop-weed |
| GlobalWheatHeadDetection [Da21] | 2021 | David et al. | Crops: Wheat; | Crops: Triticum aestivum; | Fruit, Wheat Head | Plant Detection | Bounding Boxes |  | 6422 | https://openreview.net/forum?id=fEoYkscKoS | https://zenodo.org/records/5092309 |
| ImageWeeds [Ra23c] | 2023 | Rai et al. | Weeds: Kochia, Common ragweed, Horseweed, Redroot pigweed, Waterhemp; | Weeds: Bassia scoparia, Ambrosia artemisiifolia, Erigeron canadensis, Amaranthus retroflexus, Amaranthus tuberculatus; | Whole plant | Weed Identification | Bounding Boxes |  | 3975 | https://www.sciencedirect.com/science/article/pii/S2352340923007709 | https://data.mendeley.com/datasets/8kjcztbjz2/2 |
| LucasVision [Yo23] | 2023 | Yordanov et al. | Crops: Common wheat, Durum wheat, Barley, Rye, Oats, Maize, Potatoes, Sugar beet, Sunflower, Rape/Turnip rape, Soybeans, Temporary grassland; | Crops: Triticum aestivum, Triticum durum, Hordeum vulgare, Secale cereale, Avena sativa, Zea mays, Solanum tuberosum, Beta vulgaris, Helianthus annuus, Brassica napus, Glycine max; | Ground cover crops | Plant Identification | Image Classes | 15,876 high-quality labeled images | 16946 | https://arxiv.org/abs/2305.04994v1 | https://jeodpp.jrc.ec.europa.eu/ftp/jrc-opendata/DRLL/LUCASvision/ |
| MaizeDiseaseSymptoms [Wi18] | 2018 | Wiesner-Hanks et al. | Crops: Maize; | Crops: Zea mays; | Leaf | Disease Detection | Other (Polyline) | Lesion annotations (number of lesions marked with lines) | 18222 | https://doi.org/10.1186/s13104-018-3548-6 | https://osf.io/p67rz/?view_only= |
| MaizeWeedDataset [Ol22] | 2022 | Olaniyi et al. | Crops: Maize; Weeds: Various; | Crops: Zea mays; Weeds: various; | Whole plant | Weed Detection, Plant Identification, Weed Identification | Bounding Boxes | 500 labeled images, 36,874 total images (18,187 from the dry season, 18,187 from the wet season, and 500 annotated images) | 500 | https://data.mendeley.com/datasets/jjbfcckrsp/1 | https://data.mendeley.com/datasets/jjbfcckrsp/1 |
| MFWD [Ge24] | 2024 | Genze et al. | Crops: Maize, Sorghum; Weeds: Various; | Crops: Sorghum bicolor, Zea mays; | Whole plant | Weed Detection | Image Classes, Bounding Boxes, Segmentation Masks |  | 94321 | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10805845/ | https://github.com/grimmlab/MFWD |
| NarrabriChickpea [We24f] | 2021 | Coleman, Guy | Crops: Chickpeas; Weeds: Asteraceae, Brassicaceae, Rigid Ryegrass, Non-grass species, Grasses; | Crops: Cicer arietinum; Weeds: Asteraceae, Brassicaceae, Lolium Rigidum, Non-Poaceae, Poaceae; | Whole plant | Weed Detection | Bounding Boxes |  | 31 | https://weed-ai.sydney.edu.au/datasets/839a5f35-9c7b-4df3-92f4-d0fc15120920 | https://weed-ai.sydney.edu.au/datasets/839a5f35-9c7b-4df3-92f4-d0fc15120920 |
| NarrabriWheat [We24a] | 2021 | Coleman, Guy | Crops: Wheat; Weeds: Annual Ryegrass, Turnipweed, Common Sowthistle; | Crops: Triticum aestivum; Weeds: Lolium rigidum, Rapistrum rugosum, Sonchus oleraceu; | Whole plant | Weed Detection | Bounding Boxes |  | 184 | https://weed-ai.sydney.edu.au/datasets/dc322d80-be00-49cf-822c-9e9b40e37425 | https://weed-ai.sydney.edu.au/datasets/dc322d80-be00-49cf-822c-9e9b40e37425 |
| NorthernWAWheatbeltBlueLupins [We24g] | 2021 | Quinlan et al. | Crops: Lupins; Weeds: Sandplain lupin; | Crops: Lupinus spp.; Weeds: Lupinus cosentinii; | Whole plant | Weed Detection | Bounding Boxes |  | 217 | https://weed-ai.sydney.edu.au/datasets/9df290f4-a29b-44b2-9de6-24bca1cee846 | https://weed-ai.sydney.edu.au/datasets/9df290f4-a29b-44b2-9de6-24bca1cee846 |
| OpenWeedPhenotype [Ma20] | 2020 | Leminen Madsen et al. | Weeds: Blackgrass, Scarlet pimpernel, Fat-hen, Common chickweed, Various; | Weeds: Alopecurus myosuroides, Anagallis arvensis, Chenopodium album, Stellaria media; | Leaf | Weed Detection, Weed Identification | Bounding Boxes, Image Classes |  | 7590 | https://www.mdpi.com/2072-4292/12/8/1246 | https://vision.eng.au.dk/open-plant-phenotyping-database/ |
| PaddyDoctor [Pe23] | 2023 | Petchiammal et al. | Crops: Rice; | Crops: Oryza sativa; | Leaf | Disease Classification | Image Classes | 12 Different Diseases, More Images at,: https://paddydoc.github.io/ | 10407 | http://arxiv.org/abs/2205.11108 | https://www.kaggle.com/competitions/paddy-disease-classification/data |
| PalmerAmaranthGrowth [We24m] | 2023 | Coleman et al. | Crops: Cotton; Weeds: Palmer amaranth; | Crops: Gossypium spp.; Weeds: Amaranthus palmeri; | Whole plant | Weed Detection | Bounding Boxes |  | 614 | https://weed-ai.sydney.edu.au/datasets/5c78d067-8750-4803-9cbe-57df8fae55e4 | https://weed-ai.sydney.edu.au/datasets/5c78d067-8750-4803-9cbe-57df8fae55e4 |
| PhenoBench [We24] | 2024 | Weyler et al. | Crops: Sugar beet; Weeds: Various; | Crops: Beta vulgaris; Weeds: Chenopodium album, Polygonum aviculare; | Leaf, Whole plant | Plant Identification, Weed Detection | Segmentation Masks | 71,264 leaf instances labeled | 2179 | https://ieeexplore.ieee.org/abstract/document/10572312 | https://www.phenobench.org/dataset.html |
| PlantSeedlingClassification [Gi17] | 2017 | Giselsson et al. | Crops: Maize, Common wheat, Sugar beet; Weeds: Various; | Crops: Zea mays, Triticum aestivum, Beta vulgaris; Weeds: Various; | Seedlings | Seedling Classification | Image Classes | 960 different plants | n.a. | https://arxiv.org/abs/1711.05458v1 | https://vision.eng.au.dk/plant-seedlings-dataset/ |
| PumkinDiseases [RBH24] | 2024 | Rashid, Mohammad Rifat Ahmmad; Biswas, Joy; Hossain, Md Miskat | Crops: Pumpkin; | Crops: Cucurbita; | Leaf | Disease Identification | Image Classes |  | 2000 | https://data.mendeley.com/datasets/wtxcw8wpxb/1 | https://data.mendeley.com/datasets/wtxcw8wpxb/1 |
| RadishWheatDataset [We24j] | 2022 | Rayner, Gilbert | Crops: Wheat; Weeds: Wild radish; | Crops: Triticum aestivum; Weeds: Raphanus raphanistrum; | Whole plant | Weed Detection | Bounding Boxes |  | 552 | https://weed-ai.sydney.edu.au/datasets/8b8f134f-ede4-4792-b1f7-d38fc05d8127 | https://weed-ai.sydney.edu.au/datasets/8b8f134f-ede4-4792-b1f7-d38fc05d8127 |
| RiceLeafDiseases [An23] | 2023 | Antony, Lourdu; Prasanth, Leo | Crops: Rice; | Crops: Oryza sativa; | Leaf | Disease Detection | Image Classes | Diseases: Bacterialblight, Brownspot, Leafsmut | 4684 | https://data.mendeley.com/datasets/dwtn3c6w6p/1 | https://data.mendeley.com/datasets/dwtn3c6w6p/1 |
| RicePanicles [Ra23b] | 2023 | Rashid et al. | Crops: Rice; | Crops: Oryza sativa; | Panicle, Fruit | Panicle Detection | Bounding Boxes | 5701 images after data augmentation. | 2193 | https://www.sciencedirect.com/science/article/pii/S2352340923008399#fig0001 | https://data.mendeley.com/datasets/ndb6t28xbk/4 |
| RoboWeedMap [TJG22] | 2022 | Teimouri, Nima; Jørgensen, Rasmus Nyholm; Green, Ole; | Crops: Barley; Weeds: Grasses, Mustard family; | Crops: Hordeum vulgare; Weeds: Poaceae, Brassicaceae; | Whole plant | Weed Detection | Bounding Boxes |  | 1147 | https://www.mdpi.com/2073-4395/12/5/1167 | https://weed-ai.sydney.edu.au/datasets/aa0cb351-9b5a-400f-bb2e-ed02b2da3699 |
| RumexLeaves [GAN23] | 2023 | Güldenring, Ronja; Andersen, Rasmus Eckholdt; Nalpantidis, Lazaros | Weeds: Broad-leaved dock; | Weeds: Rumex obtusifolius; | Leaf | Plant Detection, Leaf Strcture Analysis | Segmentation Mask, Bounding Boxes, Other (Polyline) |  | 809 | https://arxiv.org/abs/2312.08805v1 | https://dtu-pas.github.io/RumexLeaves/ |
| RyegrassSeedlings [We24l] | 2022 | Leon, Lorenzo | Crops: None (Fallow); Weeds: Ryegrass; | Crops: None (Fallow); Weeds: Lolium Perenne; | Whole plant | Weed Detection | Bounding Boxes |  | 14 | https://weed-ai.sydney.edu.au/datasets/c828f20d-9b3b-451a-b1a3-eb35398760da | https://weed-ai.sydney.edu.au/datasets/c828f20d-9b3b-451a-b1a3-eb35398760da |
| SorghumAphids [Ra24] | 2024 | Rahman et al. | Crops: Sorghum; Insects: Aphids; | Crops: Sorghum bicolor; | Leaf | Pest Detection | Segmentation Masks | Insects: Aphidoidea; | 54742 | https://arxiv.org/abs/2405.04305v1 | https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/N3YJXG |
| SoybeanNet [Li24] | 2024 | Li et al. | Crops: Soybean; | Crops: Glycine max; | Panicle, Fruit | Bean Counting | Segmentation Masks, Other (Points) | 262,611 (!) manually annotated soybean pods | 196 | https://www.sciencedirect.com/science/article/pii/S0168169924002527 | https://www.kaggle.com/datasets/jiajiali/uav-based-soybean-pod-images/data |
| SoyNet [Ra23a] | 2023 | Rajput et al. | Crops: Soybean; | Crops: Glycine max; | Leaf | Disease Detection | Image Classes |  | 4500+ | https://www.sciencedirect.com/science/article/pii/S2352340923005474 | https://data.mendeley.com/datasets/w2r855hpx8/1 |
| SugarcanePlantCounting [UJ24] | 2024 | Ubaid, Muhammad Talha; Javaid, Sameena | Crops: Sugarcane; | Crops: Saccharum officinarum; | Cane, Fruit | Plant Counting | Bounding Boxes |  | 3730 | https://www.mdpi.com/2313-433X/10/5/102 | https://data.mendeley.com/datasets/m5zxyznvgz/1 , https://data.mendeley.com/datasets/ydr8vgg64w/1  |
| TobaccoAerialDataset [Mo23] | 2023 | Moazzam, Imran | Crops: Tobacco; Weeds: Various; | Crops: Nicotiana tabacum; Weeds: Various; | Whole plant | Weed Detection | Semantic Masks |  | 1870 | https://data.mendeley.com/datasets/5dpc5gbgpz/2 | https://data.mendeley.com/datasets/5dpc5gbgpz/1 |
| WE3DS [Ki23] | 2023 | Kitzler et al. | Crops: Broad bean, Pea, Corn, Soybean, Sunflower, Sugar beet; Weeds: Corn spurry, Red-root amaranth, Common buckwheat, Red fingergrass, Common wild oat, Cornflower, Milk thistle, Rye brome, Narrow-leaved plantain, Small-flower geranium; | Crops: Vicia faba, Pisum sativum, Zea mays, Glycine max, Helianthus annuus, Beta vulgaris; Weeds: Spergula arvensis, Amaranthus retroflexus, Fagopyrum esculentum, Digitaria sanguinalis, Avena fatua, Centaurea cyanus, Silybum marianum, Bromus secalinus, Plantago lanceolata, Geranium pusillum; | Leaf, Whole plant | Weed Detection, Weed Identification, Crop Identification | Semantic Masks | RGB-D Images | 2568 | https://www.mendeley.com/catalogue/6873cb53-b2e2-34e7-8b49-5d36b1c51fbe/ | https://zenodo.org/records/7457983 |
| WeedGrowthState [Te18] | 2018 | Teimouri et al. | Weeds: Knotgrass, Blackgrass, Fat-hen, Various; | Weeds: Alopecurus myosuroides, Chenopodium album, Polygonum spp., Various; | Leaf | Weed Growth Estimation, Leaf Counting | Image Classes | Classification into 9 growth stages (1-8 leaves and >8 leaves) | 12165 | https://www.mdpi.com/1424-8220/18/5/1580 | https://vision.eng.au.dk/leaf-counting-dataset/ |
| WildCarrotFlowersInCanola [We24h] | 2021 | Leon, Lorenzo | Crops: Canola; Weeds: Wild carrot; | Crops: Brassica napus; Weeds: Daucus carota; | Whole plant | Weed Detection | Bounding Boxes |  | 52 | https://weed-ai.sydney.edu.au/datasets/c4a80379-afda-4972-b274-82a544addd0d | https://weed-ai.sydney.edu.au/datasets/c4a80379-afda-4972-b274-82a544addd0d |
| WildRadishInWheat [We24i] | 2021 | Coleman, Guy | Crops: Wheat; Weeds: Wild radish; | Crops: Triticum aestivum; Weeds: Raphanus raphanistrum; | Whole plant | Weed Detection | Bounding Boxes |  | 41 | https://weed-ai.sydney.edu.au/datasets/09af32ad-2e9e-4f7c-ae08-55374824ee15 | https://weed-ai.sydney.edu.au/datasets/09af32ad-2e9e-4f7c-ae08-55374824ee15 |
| YOLOWeeds [Da23] | 2023 | Dang et al. | Weeds: Waterhemp, Morningglory, Purslane, Spotted Spurge, Carpetweed, Ragweed, Eclipta, Prickly Sida, Palmer Amaranth, Sicklepod, Goosegrass, Cutleaf Groundcherry; | Weeds: Amaranthus tuberculatus, Ipomoea spp., Portulaca oleracea, Euphorbia maculata, Mollugo verticillata, Ambrosia artemisiifolia, Eclipta prostrata, Sida spinosa, Amaranthus palmeri, Senna obtusifolia, Eleusine indica, Physalis angulata; | Leaf | Weed Detection | Bounding Boxes |  | 5648 | https://www.sciencedirect.com/science/article/pii/S0168169923000431 | https://zenodo.org/records/7535814 ,  https://weed-ai.sydney.edu.au/datasets/2c14915b-0827-4b65-9908-d2a6df0d48f3  |



## Acknowledgements

This work and the Rubin Feldschwarm® ÖkoSystem project are funded by the German Federal Ministry of Education and Research (BMBF) (grant no. 03RU2U051F, 03RU2U053C).


## License

This dataset collection is provided for research purposes. Please refer to the individual dataset licenses for usage terms and conditions.

