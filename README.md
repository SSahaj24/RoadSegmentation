# RoadSegmentation
Comparison of UNet, UNet++, LinkNet, FPN, PSPNet on the task of semantic segmentation of roads. This task was part of my application for Team Abhiyaam at IIT Madras

## Task Details

I have conducted binary semantic segmentation of roads on the CamVid dataset using the ResNext encoder backbone. I have tried 5 different encoders and documented the results in the code below.
<br><br>
Heavy reference has been taken from the [**Segmentation Models PyTorch**](https://github.com/albu/albumentations/) GitHub repo by [**Qubvel**](https://github.com/qubvel) and the example code provided.
<br>
(P.S. Training takes WAY TOO LONG to run, took me 3.5 hours to run everything. You can run the training again since I have best model parameters from my testing saved (will be imported from GDrive), but note that the inference comments may seem a bit irrelevant then depending on output)

```
More explanation and ideas discussed within the Jupyter Notebook
```

### References:
- [Segmentation Models PyTorch](https://github.com/albu/albumentations/) GitHub repo by [Qubvel](https://github.com/qubvel)
- Research papers for the decoders used
- Indian Driving Dataset
- [Indian Roads Semantic Segmentation](https://datasetninja.com/indian-roads-semantic-segmentation) (IIT Bombay dataset)
- https://medium.com/analytics-vidhya/semantic-segmentation-on-indian-driving-dataset-aaf556a0f353
- https://chtalhaanwar.medium.com/pytorch-num-workers-a-tip-for-speedy-training-ed127d825db7
- https://github.com/AbhayVAshokan/Semantic-Segmentation-of-Road-Surface
