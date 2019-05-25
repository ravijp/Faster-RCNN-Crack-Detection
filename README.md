# Faster RCNN

Here we are trying to build an Faster RCNN model for object detection/classification

To train 
```
!python /content/RCNN-JBM/keras-frcnn/train_frcnn.py -o simple --num_epochs 70 -n 32 -p RCNN-JBM/Fast\ RCNN/annotate1.txt
```
No of epochs trained: 70
RoI filter: 32 (default)

To test
```
!python /content/RCNN-JBM/keras-frcnn/test_frcnn.py -p /content/gdrive/My\ Drive/ModelJBM/Test/Healthy
```

Model prediction: 18/20 correct predictions

Future Scope: 
1. Train it with different anchor settings
2. Train model for more number of epochs. 
3. Further hyper parameter turning during training
