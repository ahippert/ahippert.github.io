## Research interests

I am interested in the analysis of incomplete data in various paradigms and applications. My research focuses on two kind of approaches to deal with missing data : _predictive_ and _parametric_ approaches. In the former, I use EOF analysis and EM algorithms to predict missing values. In the latter, the aim is to estimate statistical parameters using the EM algorithm from incomplete data. In a broader sens, I am attentive to PCA-types methods to deal with missing data, geophysical applications from remotely sensed data and statistical inference.

### Predictives approaches : gap-filling with EOF decomposition
In this scope, I mainly use a variety of Empirical Orthogonal Functions (EOF, EEOF) to decompose heterogeneous and incomplete signals. This decomposition, which shares a link with the spectral representation of the signal, can be embedded in EM-types algorithms to iteratively predict missing values. Such methods allow the extraction of temporal and/or spatial features of the data along with their interpolation. Application to various geophysical datasets from SAR and optical imagery (glacier velocity) confirm the possibilities to denoise and interpolate highly incomplete data, which is a key step to facilitate their interpretation by geophysicists.

### Robust parameter estimation with missing values
The aim is build robust estimators of statistical parameters (as the mean and the covariance matrix) using the EM algorithm from incomplete data following both Gaussian and non-Gaussian distributions, as mixed-effects and compound Gaussian models. I am also interested in finding solutions when the signal has a low-rank structure. Various scenarios need to be considered depending of the distribution of missing data across observations and variables.