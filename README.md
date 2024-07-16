# BUGSDM-orthodontics
Teeth Segmentation using 3D UNet with MIScnn Framework

## How to Use 
Install MIScnn following the directions provided in https://github.com/frankkramer-lab/MIScnn

Prepare your data in the expected file structure format.
The expected file structure:
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



## Author 
Min Seok Kim 
Email: minkim@bu.edu 
DScD/CAGS Orthodontics & Dentofacial Orthopedics Resident
Boston University Goldman School of Dental Medicine
Massachusetts, USA

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License. To view a copy of this license, visit [http://creativecommons.org/licenses/by-nc/4.0/](http://creativecommons.org/licenses/by-nc/4.0/).
