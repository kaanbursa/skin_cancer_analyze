# Mole Analyzer with 7 types of Mole
## Implemented with Tensorflow Keras
Dataset is HAM10000 data downloaded from [Kaggle](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000)



### Types of Moles
####akiec 

Actinic Keratoses (Solar Keratoses) and Intraepithelial Carcinoma (Bowen’s disease) are common noninvasive, variants of squamous cell carcinoma that can be treated locally without surgery. Some authors regard them as precursors of squamous cell carcinomas and not as actual carcinomas. There is, however, agreement that these lesions may progress to invasive squamous cell carcinoma – which is usually not pigmented. Both neoplasms commonly show surface scaling and commonly are devoid of pigment.

Actinic keratoses are more common on the face and Bowen’s disease is more common on other body sites. Because both types are induced by UV-light the surrounding skin is usually typified by severe sun damaged except in cases of Bowen’s disease that are caused by human papilloma virus infection and not by UV. Pigmented variants exist for Bowen’s disease20 and for actinic keratoses21, and both are included in this set. The dermatoscopic criteria of pigmented actinic keratoses and Bowen’s disease are described in detail by Zalaudek et al. 22,23 and by Cameron et al. 20. 

####bcc

 Basal cell carcinoma is a common variant of epithelial skin cancer that rarely metastasizes but grows destructively if untreated. It appears in different morphologic variants (flat, nodular, pigmented, cystic), which are described in more detail by Lallas et al. 24. 
####bkl 

"Benign keratosis" is a generic class that includes seborrheic keratoses ("senile wart"), solar lentigo - which can be regarded a flat variant of seborrheic keratosis - and lichen-planus like keratoses (LPLK), which corresponds to a seborrheic keratosis or a solar lentigo with inflammation and regression25. The three subgroups may look different dermatoscopically, but we grouped them together because they are similar biologically and often reported under the same generic term histopathologically. From a dermatoscopic view, lichen planus-like keratoses are especially challenging because they can show morphologic features mimicking melanoma26 and are often biopsied or excised for diagnostic reasons. The dermatoscopic appearance of seborrheic keratoses varies according to anatomic site and type27. 

####df 
Dermatofibroma is a benign skin lesion regarded as either a benign proliferation or an inflammatory reaction to minimal trauma. The most common dermatoscopic presentation is reticular lines at the periphery with a central white patch denoting fibrosis28. 

####nv 

Melanocytic nevi are benign neoplasms of melanocytes and appear in a myriad of variants, which all are included in our series. The variants may differ significantly from a dermatoscopic point of view. In contrast to melanoma they are usually symmetric with regard to the distribution of color and structure29. 

####mel

 Melanoma is a malignant neoplasm derived from melanocytes that may appear in different variants. If excised in an early stage it can be cured by simple surgical excision. Melanomas can be invasive or noninvasive (in situ). We included all variants of melanoma including melanoma in situ, but did exclude non-pigmented, subungual, ocular or mucosal melanoma. Melanomas are usually, albeit not always, chaotic, and some melanoma specific criteria depend on anatomic site23,30. 

####vasc

 Vascular skin lesions in the dataset range from cherry angiomas to angiokeratomas31 and pyogenic granulomas32. Hemorrhage is also included in this category. Angiomas are dermatoscopically characterized by red or purple color and solid, well circumscribed structures known as red clods or lacunes. The number of images in the datasets does not correspond to the number of unique lesions, because we also provide images of the same lesion taken at different magnifications or angles (Fig. 4), or with