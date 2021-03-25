## Short bio (<a href="ahippert.github.io/pdfs/curriculum.pdf" target="_blank">CV</a>)

I am a post-doc at [L2S](https://l2s.centralesupelec.fr/) working with [Florent Bouchard](https://sites.google.com/view/florentbouchard/home) and [Nabil El Korso](https://sites.google.com/site/nabkorso/) (LEME, Université Paris Nanterre). I received the M.S degree in environmental engineering from \'Ecole Centrale d'Electronique, Paris, France in 2016 and the M.S degree in [_Remote Sensing Physics_](http://teledetection.lmd.jussieu.fr/mpt/) from the University Pierre et Marie Curie, Paris, France in 2017. I recently received the Ph.D degree from University Savoie Mont Blanc, Annecy, France, supervised by [Philippe Bolon](https://www.univ-smb.fr/listic/presentation/membres/enseignants-chercheurs/philippe-bolon/) and [Yajing Yan](https://www.univ-smb.fr/listic/pages-en/yajing-yan-en/). You can [watch here](https://www.youtube.com/watch?v=RpKIe1dnPz8) my defense at [LISTIC](https://www.univ-smb.fr/listic/) in October 2020.

## Research interests

I am interested in the analysis of incomplete data in various paradigms and applications. My research focuses on two kind of approaches to deal with missing data : _predictive_ and _parametric_ approaches. In the former, I use EOF analysis and EM algorithms to predict missing values. In the latter, the aim is to estimate statistical parameters using the EM algorithm from incomplete data. In a broader sens, I am attentive to PCA-types methods to deal with missing data, geophysical applications from remotely sensed data and statistical inference.

### Predictives approaches : gap-filling with EOF decomposition
In this scope, I mainly use a variety of Empirical Orthogonal Functions (EOF, EEOF) to decompose heterogeneous and incomplete signals. This decomposition, which shares a link with the spectral representation of the signal, can be embedded in EM-types algorithms to iteratively predict missing values. Such methods allow the extraction of temporal and/or spatial features of the data along with their interpolation. Application to various geophysical datasets from SAR and optical imagery (glacier velocity) confirm the possibilities to denoise and interpolate highly incomplete data, which is a key step to facilitate their interpretation by geophysicists.

### Robust parameter estimation with missing values
The aim is build robust estimators of statistical parameters (as the mean and the covariance matrix) using the EM algorithm from incomplete data following both Gaussian and non-Gaussian distributions, as mixed-effects and compound Gaussian models. I am also interested in finding solutions when the signal has a low-rank structure. Various scenarios need to be considered depending of the distribution of missing data across observations and variables.

## Publications (also in [HAL](https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?auteur_exp=hippert-ferrer&CB_auteur=oui&CB_titre=oui&CB_article=oui&CB_DOI=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/styles_publicationsHAL.css))

[_Robust Mean and Covariance Matrix Estimation Under Heterogeneous Mixed-Effects Model._](https://hal.archives-ouvertes.fr/hal-03156771/document)
<br/>
  Alexandre Hippert-Ferrer, M. N. El Korso, Arnaud Breloy, Guillaume Ginolhac
<br/>
Submitted to `Signal Processing`, **2021**.

[_Spatio-temporal flling of missing data in remotely sensed displacement measurement time series._](https://ieeexplore.ieee.org/abstract/document/9173747)
<br/>
Hippert-Ferrer A., Yan Y., Bolon P., Millan R..
<br/>
`IEEE Geoscience and Remote Sensing Letters`, **2020**.
<a href="ahippert.github.io/pdfs/grsl_2020.pdf" target="_blank">PDF</a> -- Code

[_EM-EOF: gap-flling in incomplete SAR displacement time series._](https://ieeexplore.ieee.org/abstract/document/9170898)
<br/>
Hippert-Ferrer A., Yan Y., Bolon P. 
<br/>
`IEEE Transactions on Geoscience and Remote Sensing`, **2020**.
<a href="ahippert.github.io/pdfs/grsl_2020.pdf" target="_blank">PDF</a> 

[_Gap-filling based on EOF analysis of spatio-temporal covariance of satellite image derived displacement time series._](https://ieeexplore.ieee.org/document/9324467)
<br/>
Alexandre Hippert-Ferrer, Yajing Yan, Philippe Bolon
<br/>
`IGARSS`, **Sep 2020**, Hawaii, USA (Online).
<a href="https://hal.archives-ouvertes.fr/hal-02178695v2/document" target="_blank">PDF</a> -- Code

[_Gap-filling based on iterative EOF analysis of temporal covariance : application to InSAR displacement time series._](https://ieeexplore.ieee.org/document/8898952)
<br/>
Alexandre Hippert-Ferrer, Yajing Yan, Philippe Bolon
<br/>
`IGARSS`, **2019**, Yokohama, Japan.

Reconstruction de données manquantes par analyse en EOF : application aux séries temporelles de mesures de déplacement InSAR. 
<br/>
Hippert-Ferrer A., Yan Y., Bolon P. 
<br/>
`GRETSI`, **août 2019**, Lille, France.

## Teaching
### 2017 - 2020 -- Polytech Annecy-Chambéry (School of engineering)
As part of the computer science department, I have taught during my Ph.D several courses, mainly lab sessions and tutorials:
- `Introduction to algorithmics and programming` (1st year students)
<br/>
Tutorials sessions on programming basics. Python was used in lab sessions. Here is an <a href="ahippert.github.io/pdfs/rappel_python.pdf" target="_blank">Python memo example</a> given to students.
- `Object oriented programming with Python` (3rd year students)
<br/>
Lab sessions: supervision of group projects extending to several sessions (example: building a house in 3D, Minesweeper video game, Roof temperature monitoring system, etc.).
- `Introduction to signal processing` (3rd year), lectures by [Philippe Bolon](https://www.univ-smb.fr/listic/presentation/membres/enseignants-chercheurs/philippe-bolon/).
<br/>
In this course, I conducted lab sessions on Signal propagation, Spectral analysis and Digital filtering.
- `Random signal processing` (4th year), lectures by [Guillaume Ginolhac](https://www.univ-smb.fr/listic/presentation/membres/enseignants-chercheurs/guillaume-ginolhac/).
<br/>
I supervised three lab sessions on Autocorrelation functions, Spectral analysis and Adaptive filtering.
- `Image processing` (4th year), lectures by [Yajing Yan](https://www.univ-smb.fr/listic/pages-en/yajing-yan-en/)
<br/>
Lab sessions: Image filtering and 2D correlation with an application to glacier displacement estimation with radar satellite images.
<br/>
Tutorial: Image correlation.
