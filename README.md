# Gesturer
I devised a sign language recognition model based on the YOLOv5 architecture, and constructed an intuitive application enabling real-time sign language recognition. Final version of the application [Gesturer](https://play.google.com/store/apps/details?id=com.gesturer.camera_gesture_app) on Google Play. 

## Testing model on your data
From the root of the repository:
```
import predict
predict.predictTree(path_to_folder)
```
As a result you will get a file named "results.csv" with predictions for each file.
