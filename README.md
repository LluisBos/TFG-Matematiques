### README del Repositori

# TFG Grau en Matemàtiques - Lluís Boscà

Aquest repositori conté el codi utilitzat en el Treball de Fi de Grau titulat "Models de predicció de mortalitat basats en models ocults de Màrkov Bayesians" del Grau en Matemàtiques de la Universitat de València. Inclou implementacions en R i NIMBLE per als models desenvolupats en les seccions de Metodologia i Resultats del treball, com ara models de regressió, models de barreja i models ocults de Màrkov (HMM).

## Contingut del Repositori

### Carpetes Principals

- **models/**: Conté els scripts per a la implementació dels models descrits en les seccions de Metodologia i Resultats del TFG.
- **resultats/**: Resultats obtinguts de les diferents anàlisis i models.

### Scripts Principals

- **momo-tidy-data.Rmd**: Script per a la neteja i preparació de les dades.
- **momo-Model-Lineal-Simple.Rmd**: Implementació del model de regressió lineal simple.
- **momo-Model-Fourier.Rmd**: Implementació general del model de regressió lineal harmònica.
- **momo-Model-Fourier-1sincos.Rmd**: Implementació del model de regressió lineal harmònica amb una sola component sinusoïdal.
- **momo-Model-Fourier-3sincos.Rmd**: Implementació del model de regressió lineal harmònica amb tres components sinusoïdals.
- **momo-Model-Fourier-DiesSetmana.Rmd**: Implementació del model de regressió lineal harmònica amb tendències setmanals.
- **momo-Model-Fourier-Setmana-OnlinePred.Rmd**: Implementació de la predicció online amb el model de regressió lineal harmònica amb tendències setmanals.
- **momo-Model-Mixtures-dies-setmana.Rmd**: Implementació del model de barreja independent sense predicció.
- **momo-Mixtures-Setmana-OnlinePred**: Implementació de la predicció online model de barreja independent.
- **momo-HMM-DiesSetmana.Rmd**: Implementació d'un model ocult de Màrkov (HMM) sense predicció.
- **momo-HMM-Setmana-OnlinePred.Rmd**: Implementació de la predicció online del HMM.
