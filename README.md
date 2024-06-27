# ComfyUI-workflow-anime

![workflow](https://iili.io/d34HNqJ.png)

Use ComfyUI on Kaggle：https://www.kaggle.com/code/zhuangerror/comfyui

# Currently workflow
* OpenPose2Image
* Text2Image
* Fix Hand
* Upscale Image

# Example
## OpenPose2Image + Fix Hand + Upscale Image

<table>
  <tr>
    <td style="text-align: center;">OpenPose2Image</td>
    <td style="text-align: center;">Fix Hand</td>
    <td style="text-align: center;">Upscale Image</td>
  </tr>
  <tr>
    <td><img src="https://iili.io/d3wLnXj.png" alt="OpenPose2Image" width="300"/></td>
    <td><img src="https://iili.io/d3rB7ZN.png" alt="Fix Hand" width="300"/></td>
    <td><img src="https://iili.io/d3rC1WB.png" alt="Upscale Image" width="300"/></td>
  </tr>
</table>

## Models Used
* Text-to-Image：[AOM3A3_orangemixs.safetensors](https://huggingface.co/WarriorMama777/OrangeMixs#aom3a3)
* VAE：[orangemix.vae.pt](https://huggingface.co/WarriorMama777/OrangeMixs)
* OpenPose：[control_v11p_sd15_openpose_fp16.safetensors](https://huggingface.co/comfyanonymous/ControlNet-v1-1_fp16_safetensors)
* HandRefiner：[control_sd15_inpaint_depth_hand_fp16.safetensors](https://huggingface.co/hr16/ControlNet-HandRefiner-pruned)
* Depth：[control_v11f1p_sd15_depth_fp16.safetensors](https://huggingface.co/comfyanonymous/ControlNet-v1-1_fp16_safetensors)
* Upscale：[4x-NMKD-YandereNeo.pth](https://openmodeldb.info/models/4x-NMKD-YandereNeo)
