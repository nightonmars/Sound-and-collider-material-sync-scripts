# Sound-and-collider-material-sync-scripts

Scripts to create scriptable objects for materials and add int identifier that can be used to control parameters/switches in middlewares such as FMOD, Wwise, etc. 
E.g., matIdx = physicsToSound.matIntIdxValue; -> footStep.setParameterByName("Terrain", physicsPM_MatDetector.matIdx);
Walkthrough here: https://youtu.be/sF_hE6dw5Z4
