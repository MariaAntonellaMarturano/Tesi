# Tesi



## Struttura delle cartelle

--file_nifti
  --MAPPE2021
    --MAPPE_ADC_D
      --PAZ01_AN
        --ADC.nii
        --D.nii
        --PAZ01_AN-label.nii
      --PAZ02_AR
        --ADC.nii
        --D.nii
        --PAZ02_AR-label.nii
        

Il programma è stato scritto in codice  python per la realiazzazione della tesi sull'analisi di immagini di risonanza magnetica nucleare pesata in diffusione con algoritmi di Machine Learning
#
Nella prima parte dello script sono estati estratti gli istrogrammi di D(diffusion coefficient) e ADC(apparent diffusion coefficient) per ogni singolo paziente dai file nifti forniti.
#
Nella seconda parte dello script sono state ricavati i valori di: media,deviazione standard,numero e grandezza linfonodi,standard_error, percentili, e esportati in un file excel.
#
Nell'ultima parte dello script sono stati realizzati gli istogrammi di media, deviazione standard e percentili per pazienti positivi e negativi sia nel caso di D(diffusion coefficient) e ADC(apparent diffusion coefficient). 
