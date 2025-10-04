# image-recognition-mobilenetv3-tflite-deployment

#Image Recognition with TensorFlow & Keras (MobileNetV3 + TFLite)

I built this project to explore how deep learning models can recognize images and run directly on mobile devices.  
It uses **TensorFlow-Keras** with **MobileNetV3** as the backbone, trained on a banana ripeness dataset to classify stages like *green*, *ripe*, and *overripe*.  

After training, I converted the model into **TensorFlow Lite** so it can be deployed in a mobile app and make real-time predictions through a phone’s camera.

---

### What’s Inside
- Transfer learning with **MobileNetV3Small**
- Data augmentation and caching for efficient training  
- Early stopping and model checkpoints  
- Export to `.tflite` for mobile integration  
- Clear graphs showing training progress

I’m still fine-tuning the model to push accuracy higher, but it already demonstrates how lightweight CNNs can work well on resource-limited devices.
