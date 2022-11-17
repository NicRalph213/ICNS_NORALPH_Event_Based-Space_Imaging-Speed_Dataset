# Event_Based-Space_Imaging-Speed_Dataset

### EBC Slew Speed Dataset using the GEN 4 HD ATIS EBC

Supplementary Material for paper titled: "Astrometric Calibration and Source Characterisation of the Latest Generation Neuromorphic Event-based Cameras for Space Imaging" on arxiv by **Nicholas Owen Ralph, Alexandre Marcireau, Saeed Afshar, Nicholas Tothill, André van Schaik, and Gregory Cohen**.

### Observation file format:

- Each observation session YYY-MM-DDTHH-MM-SSZ_speed_survey-DESCRIPTOR 
 - Contains metadata.jsonl for a summary of each observation 
- Each individual observation: YYY-MM-DDTHH-MM-SSZ_speed_survey-RA_DEC_SPEED(DEG/S)
- In each individual observation folder: a psee400.es, psee400.mp4 and reddot.jsonl 
 - The event stream file psee400.es can be read and converted using scripts from https://github.com/neuromorphic-paris/command_line_tools 
 - The reddot.jsonl file contains detailed the telescope commands and metadata 

Files can currently be accessed from: https://drive.google.com/drive/folders/126nz5-6aOyRnWBFaAoPsOYEztO1PFabd?usp=sharing

Contact Nicholas Owen Ralph at N.Ralph@westernsydney.edu.au for support. 
