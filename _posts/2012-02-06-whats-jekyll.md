---
layout: post
title: Data Wrangling

---
1. “Transforming and mapping data from one form into another with the intent of making it more appropriate for analytics” - [Wikipedia](https://en.wikipedia.org/wiki/Data_wrangling)
2. “Process of cleaning and unifying messy and complex data sets for easy access and analysis.” - [Altair](https://www.altair.com/what-is-data-wrangling/)

**Goals of wrangling data**

1. derive value out of data through analysis
2. make data-driven decisions
3. optimize some business metrics; cost, expenditure etc.
4. save the world

**Time spent on preparing data**

!\[\](https://lh4.googleusercontent.com/2pHvFLqFPcpC0P07KIfGpbN9PmrzlriCzHoWfDx-Z0_kRfq0jXyN8iRX0QlcYvr782i13awNTuDhphPU7exYwXsDp6fic2wmUuPIMr85YnDiph44uj8B0dEMHmhM-XcKJi4tzkqqZiE =928px;x395px;)

\**  
The data analysis pipeline**!\[\](https://lh3.googleusercontent.com/xrgaC9tkUQchYd8wx43Q_pyKfc1KaL_rJc-LeQT5j47taXFfKkhxh0CmaxS0O6U0poKv1kwIKrUNX2_IERNIdClQZmskvD_5oDARn3wfZTwybZW0p3pPERXew5drJ4642ismv_wI7V4 "https://www.trifacta.com/data-munging/" =910px;x350px;)

**Discovering;**

**Understanding** and **exploring** the dataset then **planning** on the actions to get it from a “raw” form to some final state.

1. defining all entities and variables,
2. visualizing the dataset,
3. etc.

**Structuring**

Actions that **change** the form or schema of the data.

1. reordering columns,
2. filtering records,
3. aggregating/pivoting records,
4. etc

\**Cleaning  
\**Actions that **standardize** or **fix irregularities** in a dataset.

Addressing:

1. **MISSING** values,
2. **INVALID** values,
3. **MISSPELLED** values,
4. different **DATE FORMATS,**
5. Different **UNITS** of measurements.
6. etc.

**Enriching**

Actions that introduce **new** variables/observations to the dataset.

1. unions,
2. joins,
3. deriving new fields from old ones,
4. etc.

**Validating**

Actions that ensure the transformed data is **consistent** with the agreed-upon **definitions** and **assumptions**.

1. consistency in variable definition,
2. outlier/anomaly detection,
3. etc.

**Publishing**

Actions that **integrate**, **expose** or **present** the wrangled dataset to the final consumers of the data.

1. download,
2. DB integrations,
3. exposing through APIs,
4. presentations,
5. etc.