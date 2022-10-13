# Scripts_Kaggle
Competencia Kaggle Data_mining 20221012

A continuación se explica como es el orden para correr cada script y características técnicas de las VM


1. z815_FE_final_2022108_v1.8.r -->
  CPU=16
  Memory=256GB
  Disk=256GB
  
  El script se corrió con los siguientes parametros
  - lags ciclo for de 4
  - canaritos_ratio = 0.3
  - Machine Learning
  - NA
  - Todo lo demas original.

2. z633_lght_RBO_under_v6_GC -->
  CPU=16
  Memory=64GB
  Disk=256GB
  
  El script se corrió con los siguientes parametros
  - kBO_iter=100, 
  - ktraining=202011,202012,202101
  - kundersampling=30%, 
  - repeat= 5 seed, 
  - coverage=80%
  - learning_rate_low<- 0.01
  - learning_rate_high<- 0.3  
  - feature_fraction_low<- 0.2
  - feature_fraction_high<- 0.9 
  - min_data_size_low<-0.004 
  - min_data_size_high<-0.05

3. z844_lightgbm_final_sem_m3_v6_GC.r -->
  CPU=24
  Memory=128GB
  Disk=256GB
  
  El script se corrió con los siguientes parametros
  - meses =202011,202012,202101
  - Semillas=100
  - kmax_bin<-31
  - klearning_rate<-0.0102829236789846
  - knum_iterations<-2231
  - knum_leaves<-121
  - kmin_data_in_leaf<-2905
  - kfeature_fraction<-0.557037694162002
  - kdirectoriotrabajo   <-"~/buckets/b1/" #Directorio de trabajo
  - kdirectortiodataset  <-"./exp/FE8150_test_20221008_v1.8/FE8150_test_20221008_v1.8.csv.gz"   #Directorio de dataset y archivo datase
  - kdirectortioexp      <-"./exp/"  #Directorio donde queda el experimiento
  - kexperimento         <- "KA8440_K100-M3_seed5_20%_v6" 
