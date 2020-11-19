# DeepQuake: A multiresolution approach for the analysis and prediction of earthquakes: from ETAS models to deep learning techniques

Fondecyt grant number 1201478

Earthquakes represent one of the most destructive yet unpredictible natural disasters along the world, with a massive physical, psychological and economical impact in the population worldwide. Chile is considered one of most active seismic country in the world. In addition to the world's largest in- strumentally documented earthquake occurred in Valdivia on May 22, 1960, Chile has recently been affected by three great earthquakes with magnitude major than 8.0 in the Ritcher scale. Thus, to have better approximation or additional information on where, when an event of that magnitude could occur would represents an invaluable tool for managing and designing public policies regarding natural disasters. However, earthquake prediction is a very challenging task, due to the high complexity associated to the process, also due to the fact that their occurrence depends on a multitude of variables, that in most cases could be unidentified. Several techniques has been proposed, most of them are based on the point process theory.

Self-exciting point process models have become essential components in the assessment of seismic hazard. A particular class is given by the Epidemic Time Aftershock Sequence (ETAS) models which have proven to be extremely useful in the description and modeling of earthquake occurrence times and locations. The estimation of these models is based on the definition of a parametric intensity function which should represent the occurrence rate of an earthquake at time t and the location (x, y) conditional on the past history of the occurrence. However, typically these processes make strong assumptions about the functional form of the conditional intensities, which could be not realistic. Furthermore, the estimation procedure normally use the maximum likelihood approach which is known to fail in multi-modal distributions. Recently, a new approach based on recurrent neural networks has been proposed for trying to bypass these restrictions and estimating the temporal intensity function as a nonlinear function of the historical events. Few tentatives have been done to extend the self-exciting point process neural networks to the spatial dimension and, nowadays, few applications to seismic events have been proposed.

The main objective of this project is to improve the estimation and prediction of seismic events in Chile with the development of two new methods, the multiresolution-ETAS and DeepQuake, which incorporate spatio-temporal clusterization of seismic events, anisotropic wavelets and exogenous variables.


## References

Please cite this code as follows:

1. O. Nicolis, F. Plaza and R. Salas (2020). Prediction of intensity and location of seismic events using deep learning. Spatial Statistics. In press. doi: https://doi.org/10.1016/j.spasta.2020.100442
