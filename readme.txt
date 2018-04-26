hico_det_dataset : 
    transform ground truth data(HICO_DET) from .mat to csv file
    
hico_det_paired_proposals : 
    utilize Mask RCNN to generate human and object bounding boxes for each image in HICO_DET
    
Train model : 
    Build HO-RCNN model refered to 'Learning to Detect Human-Object Interactions' paper