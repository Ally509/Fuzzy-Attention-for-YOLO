# EnFA: A Novel Entropy-based Fuzzy Attention Mechanism for Blurred Object Detection Task Based on YOLOv8

## Abstract

Attention mechanisms, as an effective approach to simulate human visual systems,  have been extensively employed in object detection tasks based on YOLO to enhance detection accuracy and robustness. 
However, existing YOLO-based models still encounter certain limitations in dealing with the issues of blurred object detection.
Specifically, when confronted with feature uncertainty stemming from the intricate environment of image acquisition, such as underwater and medical imaging scenarios, the detection performance of these models has room for enhancement.  
To address this challenge, this paper proposes a novel attention mechanism based on information entropy and fuzzy logic, named EnFA, to enhance the performance of YOLOv8-based blurred object detection models. 
This mechanism can effectively handle uncertainty issues among feature channels by constructing novel fuzzy membership functions with an adaptive fuzzy factor, thereby enhancing the model's feature extraction capability for blurred objects. 
Moreover, by replacing hard thresholding in YOLOv8’s multi-scale heads with a learnable fuzzy gate, EnFA both bridges uncertainty in degraded imaging pipelines and unlocks creative re-use of previously-discarded low-confidence features. This step guarantees the accurate and comprehensive capture of the boundaries of blurred objects, leaving less omissions. 
Experimental results demonstrate that the proposed EnFA outperforms some existing attention mechanisms across multiple public datasets with blurred objects, thus validating the efficiency of the EnFA-enhanced models. 

## Pre-trained Weights

Download the pre-trained model weights trained on four datasets:

| Dataset | weights |
|---------|---------|
| LUNA16 | [LUNA16.pt](LUNA16.pt) |
| Ultrasound | [Ultrasound.pt](Ultrasound.pt) |
| NEU-DET | [NEU-DET.pt](NEU-DET.pt) |
| UPRC2018 | [UPRC2018.pt](UPRC2018.pt) |

