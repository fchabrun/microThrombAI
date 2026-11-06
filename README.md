# White Thrombi Retrieved During Mechanical Thrombectomy Are Associated With Atypical Stroke Etiologies

## Authors
Jacques BUREAU<sup>1,2</sup>, Floris CHABRUN<sup>2,3</sup>, Julien CHAIGNEAU<sup>2,4</sup>, Anne CROUE<sup>2,5</sup>,
Sarah BELLAL<sup>2,5</sup>, Jean-Baptiste GIROT<sup>2,6</sup>, Anne PASCO-PAPON<sup>2,6</sup>, Aldéric LECLUSE<sup>1,2</sup>,
Sophie GODARD<sup>1,2</sup>, Philippe CODRON<sup>*1,2</sup>, Vincent L’ALLINEC<sup>*2,5,7</sup>
<sup>*</sup>These authors contributed equally to the manuscript

### Author affiliations:
<sup>1</sup> Department of Neurology, Angers University Hospital, Angers, France
<sup>2</sup> Mitolab Team, MITOVASC Mixed Research Unit, INSERM 1083 CNRS 6015, University of Angers, Angers, France
<sup>3</sup> Department of Biochemistry and Molecular Biology, Angers University Hospital, Angers, France
<sup>4</sup> HIFIH, Angers University Hospital, SFR ICAT, France
<sup>5</sup> Department of Cellular and Tissue Pathology, Angers University Hospital, Angers, France
<sup>6</sup> Department of Radiology, Angers University Hospital, Angers, France
<sup>7</sup> Department of Neuroradiology, University Hospital and University of Zürich, Zürich, Switzerland

### Correspondence to: 
Dr Jacques BUREAU, ORCID: 0000-0002-3036-1216
Service de neurologie, CHU d'Angers, 4 rue Larrey, 49933 Angers, France
Email: jacques.bureau@chu-angers.fr; Tel: +33 2 41 35 35 88 

### Keywords:
Ischemic Stroke; Thrombectomy; Thrombosis; Histological Techniques; Deep Learning

## ABSTRACT
<b>Background:</b> Thrombi retrieved during mechanical thrombectomy may provide clues to the underlying stroke mechanism. We investigated whether macroscopic appearance and histological composition were associated with atypical stroke etiologies and whether deep learning–derived histological features provided additional discriminatory information.

<b>Methods:</b> We conducted a prospective observational study of patients undergoing mechanical thrombectomy. Retrieved thrombi were classified as red or white and analyzed histologically for red blood cell, fibrin/platelet, and leukocyte content. Stroke etiologies were classified as typical, atypical, or undetermined after diagnostic work-up and follow-up. Exploratory self-supervised deep learning was used to extract histological features, with evaluation in a temporally separate validation cohort.

<b>Results:</b> Among 239 thrombi, 197 (82.4%) were red, 33 (13.8%) white, and 9 (3.8%) non-interpretable. White thrombi were strongly associated with atypical etiologies compared with red thrombi (45.5% versus 2.5%; P<0.001), with cancer being the most frequent atypical cause. Fibrin/platelet content was higher in white than red thrombi (86.1% versus 73.8%; P<0.001), but did not distinguish typical from atypical etiologies among white thrombi. Deep learning–derived histological features discriminated atypical from typical etiologies among white thrombi (ROC-AUC, 0.84).

<b>Conclusions:</b> White thrombi are strongly associated with atypical stroke etiologies, particularly cancer, and may provide an early clue prompting targeted etiological investigations. Deep learning–based histological analysis may provide complementary information but requires further validation.

### Files

(Encoder inference.ipynb)["./Encoder inference.ipynb"]

Run inference: use self-supervised contrastive learning trained encoder to convert thrombus whole slide image patches into encodings.

(Latent space exploration.ipynb)["./Latent space exploration.ipynb"]

Analyze encodings: compare expression of patterns detected by the deep learning encoder depending on thrombus origin or color.
