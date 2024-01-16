# PRAC-Visualització de dades

El COVID-19 va ser una pandèmia mundial que va canviar la nostra societat. Ha sigut tema d'estudi arreu del món. En aquest projecte ens centrarem en la població de Corea del Sud. Es tracta d'una base de dades que consta de 10 arxius, basats en els informes de KCDC (Korea Centers for Disease Control & Prevention) i el govern local.

## Datasets
### 1 Informació dels casos
**Case**: Casos d’infeccions de COVID-19 a Corea del Sud.
### 2 Informació dels pacients
**PatientInfo**: Informació epidemiològica dels pacients de COVID-19 a Corea del Sud.
### 3 Informació sobre les series temporals
**Time**: Sèrie temporal sobre els estats de COVID-19 a Corea del Sud.<br>
**TimeAge**: Sèrie temporal sobre els estats de COVID-19 en termes d’edat a Corea del Sud.<br>
**TimeGender**: Sèrie temporal sobre els estats de COVID-19 en termes de gènere a Corea del Sud.<br>
**TimeProvince**: Sèrie temporal sobre els estats de COVID-19 en termes de província a Corea del Sud.
### 4 Informació adicional
**Region**: Informació de les diferents regions de Corea del Sud.<br>
**Weather**: Informació del temps en les regions de Corea del Sud.<br>
**SearchTrend**: Informació de la tendència de busca de paraules en NAVER. Un dels portals més grans a Corea del Sud.<br>
**Policy**: Infromació de la política del govern pel COVID-19 a Corea del Sud.

## Relació entre els datasets
![Relació entre els datasets](Data_structure.png)

## Datasets d'interès
### PatientInfo
**patient_id** -> ID del pacient<br>
**sex** -> sexe del pacient<br>
**age** -> edat del pacient<br>
**country** -> país del pacient<br>
**province** -> província del pacient<br>
**city** -> ciutat del pacient<br>
**infection_case** -> tipus d’infecció. Com el pacient es va contagiar<br>
**infected_by** -> el ID del pacient que el va infectar<br>
**contact_number** -> número de contacte de la gent<br>
**symptom_onset_date** -> quan el símptoma apareix<br>
**confirmed_date** -> data en que va ser detectat el positiu<br>
**released_date** -> data que es va donar d’alta el pacient<br>
**deceased_date** -> data de defunció<br>
**state** -> estat 

### Region
**code** -> el codi de la regió<br>
**provincie** -> província<br>
**city** -> ciutat<br>
**latitude** -> latitud<br>
**longitude** -> longitud<br>
**elementar_school_coun** -> el nombre d’escoles<br>
**kindergarten_count** -> el nombre d’escoles de bressol<br>
**university_count** -> el nombre d’universitats<br>
**academy_ratio** -> el ratio d’acadèmies <br>
**elderly_population_ratiu** -> el ratio de població d’edat avançada<br>
**elderly_alone_ratio** -> el ratio de població d’edat avançada vivint sola<br>
**nursing_home_count** -> el nombre d’infermeres que treballen a cases
