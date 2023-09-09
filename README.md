# Upscayl - Custom Models

This repository will contain extra models that users can download and use in Upscayl. Upscayl v2.5 comes with a Custom Models option where users can select a `models` folder and use their own imported models.

## Instructions

### Using Models
1. [Download this repository](https://github.com/upscayl/custom-models/archive/refs/heads/main.zip)
2. Extract the downloaded ZIP file.
3. Open Upscayl and click the Settings tab.
4. Click on `Select Folder` button under _CUSTOM MODELS_ section.
5. Select the `models` folder in the earlier extracted folder.
6. Go back to Upscayl screen and select your custom models.

# Convert your own Models!

[The Upscayl wiki has a guide on how to convert pre-existing ESRGAN models!](https://github.com/upscayl/upscayl/wiki/%F0%9F%96%A5%EF%B8%8F-Model-Conversion---Create-more-AI-models!)

# Models

## General
* `4x_NMKD-Siax_200k` - NMKD Siax - Universal upscaler for clean and slightly compressed images (JPEG quality 75 or better), based on CX loss + PatchGAN.
* `4x_NMKD-Superscale-SP_178000_G` - NMKD Superscale - Perfect upscaling of clean (artifact-free) real-world images.
* RealESRGANv3 - Lightweight and faster versions of the default model, with (very slightly) worse quality.
  * `RealESRGAN_General_WDN_x4_v3` - wide and deep network model
  * `RealESRGAN_General_x4_v3`
* `ultrasharp-2.0.1` - "Ultrasharp" - We still don't know what this model is, but we accidently included it in place of Ultrasharp in v2.0.1 and @royal-rigolo liked it, so here it is!
* `uniscale_restore` by Kim2091.

## Digital Art
[animevideo](https://github.com/xinntao/Real-ESRGAN/blob/master/docs/anime_video_model.md) models for scales x2, x3 and x4. You can use Upscayl's scale option according to the model selected.
* `realesr-animevideov3-x2`
* `realesr-animevideov3-x3`
* `realesr-animevideov3-x4`

## Model Credits:

@xinntao [LICENSE](https://github.com/xinntao/Real-ESRGAN-ncnn-vulkan/blob/master/LICENSE)   
[@Kim2091](https://upscale.wiki/wiki/User:Kim2091)  
[NMKD](https://nmkd.de/?esrgan)
