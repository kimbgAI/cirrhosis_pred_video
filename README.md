# Descriptions

- This study aims to develop a deep learning model for real-time assessment of severe liver fibrosis using laparoscopic images during hepatocellular carcinoma surgery. 
- The research found that the DenseNet-121 architecture-based model achieved a high performance in distinguishing severe fibrosis from non-severe fibrosis, with an AUROC of 0.927, sensitivity of 0.918, and specificity of 0.910, outperforming traditional non-invasive methods. 
- This approach offers an objective assessment of liver fibrosis during surgery, potentially enhancing surgical decision-making for patients with hepatocellular carcinoma.

## Usage

- You can reproduce this model using jupyter notebook we provided.
- You just need to modify the `video_path` within the `inference.ipynb` file.
- You can also download the model weights and a sample video from the link below.
    - https://1drv.ms/f/c/9db2e01a687d3baf/EqcixWmjsQJLi2xYIhiV8_wBcA45QZ5B4jd0e9U-IcXY4g?e=DOz2wI

## Preview

![figure1.png]
                             
## Requiremenets

pytorch==2.2.1

opencv==4.6.0

albumentations==1.3.1

segmentation-models-pytorch==0.3.1

numpy==1.26.4