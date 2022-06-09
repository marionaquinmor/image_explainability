# ESTUDI SOBRE L’APLICACIÓ DE TÈCNIQUES D’EXPLICABILITAT EN ALGORISMES D’INTEL·LIGÈNCIA ARTIFICIAL BASATS EN IMATGE MÈDICA
L'estudi consisteix en l’aplicació de diverses tècniques d’explicabilitat a un algorisme de Deep Learning per tal d’analitzar-les i dur a 
terme una comparació entre elles. Es parteix d’un model entrenat amb un conjunt de dades que corresponen a radiografies de tòrax de nadons d’un a cinc anys. 
El dataset ha estat extret d’una plataforma web pública i el propòsit del model és la detecció de pneumònia. 
Posteriorment, s’implementen els mètodes d’explicabilitat i es realitza una anàlisi i una parametrització per l’optimització dels resultats. 

L’objectiu final del projecte és veure si les explicacions de les diferents tècniques poden ser útils per un professional com a eina de suport al diagnòstic, 
donant-li confiança i transparència a la predicció d’un algorisme d’intel·ligència artificial. 

## Contingut
En el respositori "image_explainability" es troben un seguit d'arxius:

1. "Estudi_Explicabilitat_imatge.ipynb" on es mostra tot el treball, incloent l'anàlisi de dades, les mètriques del model entrenat i 
l'aplicació de les tècniques d'explicabilitat amb la seva parametrització. 

2. "model_entrenat_MobileNet.ipynb" on es troba l'entrenament del model utilitzat en el document esmentat anteriorment.

Per tal de poder executar els dos documents de codi són necessaris els següents fitxers:

1. El conjunt de dades en format .ZIP. Conté totes les imatges separades primer en dues carpetes de 'train' i 'test' i posteriorment dividies segons si pertànyen a
la classe 'PNEUMONIA' o 'NORMAL'. 
Aquest enllaç dirigeix a Google Drive on pot ser descarregat: https://drive.google.com/file/d/16FaEPf5yEZg9x1OTUgLxYUHTSQ5ZBkPU/view?usp=sharing

2. El model en format .h5. És entrenat i descarregat en "model_entrenat_MobileNet.ipynb" i s'utilitza en "Estudi_Explicabilitat_imatge.ipynb" per dur a terme l'estudi.
Aquest enllaç dirigeix a Google Drive on pot ser descarregat: https://drive.google.com/file/d/1sKxTvxzpbV1QNs87oyo_5RifZkrDmDj1/view?usp=sharing

### Recomanacions
