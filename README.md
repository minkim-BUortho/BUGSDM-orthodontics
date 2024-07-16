# BUGSDM-orthodontics
Teeth Segmentation using 3D UNet with MIScnn Framework

## How to Use 
Install MIScnn following the directions provided in https://github.com/frankkramer-lab/MIScnn

1. Prepare your data in the expected file structure format.

The expected file structure:
```sh
 data/
      imgname001/
              any_id/
                      000000.dcm
                      000001.dcm
                      ...
                      000139.dcm
              annotation_tag.any_id/
                      000000.dcm
      imgname002/
              0.000000-CT2p2b2 50 Ex-45938/
                      000000.dcm
                      000001.dcm
                      ...
                      000160.dcm
              annotation_tag.simplified-15042/
                      000000.dcm
      ...
```

2. Following the comments, Change the necessary fields in the "miscnn_segment_teeth.ipynb".

   The changes should include the number of folds, directory and data paths, and samples to be included in the training and validation set.

3. Complete the training of the 3D UNet model and check the Training / Validation DSC and Loss 

4. Load the trained model and Create Predictions with the trained model

5. Use "miscnn_evaluation_teeth.ipynb" to calculate the metrics for ground truth vs prediction to evaluate the model performance.

## Sample of Trained Model

A sample of the trained model is available to download at request. 

https://drive.google.com/file/d/1S6U7kEo1xz_-T9IMWUq_pptop08_p-AV/view?usp=sharing

## Author 
Min Seok Kim 
Email: minkim@bu.edu 
DScD/CAGS Orthodontics & Dentofacial Orthopedics Resident
Boston University Goldman School of Dental Medicine
Massachusetts, USA

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License. To view a copy of this license, visit [http://creativecommons.org/licenses/by-nc/4.0/](http://creativecommons.org/licenses/by-nc/4.0/).
