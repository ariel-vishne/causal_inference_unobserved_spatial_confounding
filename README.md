# causal_inference_unobserved_spatial_confounding
Project on unobserved spatial confounding in causal inference, reproduction of "Papadogeorgou, Georgia, Choirat, Christine and Zeigler, Corwin M. (2019), "Adjusting for unmeasured spatial confounding with distance adjusted propensity score matching: Supplementary Materials", Biostatistics 20, 2, pp. 1-11".
See github repo at: https://github.com/gpapadog/DAPSm

This project was completed as part of the "Causal Inference" (52306) course for graduate students at Tel Aviv University by Dr. Daniel Nevo, fall 2021/2022.
The project considers simulated data and real-world data for dealing with unobserved confounders that have a geographical (spatial) property.
See full discussion in pdf (in Hebrew).

The literature considers several approaches for dealing with unobserved spatial confounding
![image](https://user-images.githubusercontent.com/18293025/174754697-9a40e5f9-b639-4052-9094-50bee7e018ff.png)



The article (and hence the project) suggests a distance-adjusted propensity score (DAPSm) approach, where the unobserved confounder is adjusted for distances between observations.

## Reproduction of Article Results
We reproduce the figures in the paper and consider further possible settings
![image](https://user-images.githubusercontent.com/18293025/174754201-83d76fe5-1f76-4b7d-8f18-a19b3a9cfa15.png)

![image](https://user-images.githubusercontent.com/18293025/174754351-7c1ad6fa-a4b5-4904-8a52-0fb7144cad72.png)

## Increased effect on Y
![image](https://user-images.githubusercontent.com/18293025/174754397-f67a6127-b5a8-4f41-9713-111c0c804dde.png)

## No Effect on Y
![image](https://user-images.githubusercontent.com/18293025/174754437-ceba6139-0420-414e-8220-1a4b1b0e483d.png)

## Interaction between observed and unobserved covariates
![image](https://user-images.githubusercontent.com/18293025/174754477-ebff17eb-c9af-433d-a647-77a11432e345.png)

## Multiple geographical confounders
![image](https://user-images.githubusercontent.com/18293025/174754529-a81889e2-69f1-4ba4-888a-b8b2a1d00adc.png)

![image](https://user-images.githubusercontent.com/18293025/174754575-2c59f678-de20-471e-94b8-4e96ae545b55.png)

![image](https://user-images.githubusercontent.com/18293025/174755197-01da447c-bc1f-4abb-9edb-cb3e6dbec763.png)
