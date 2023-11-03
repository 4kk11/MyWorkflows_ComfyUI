https://zenn.dev/4kk11/articles/384ce6675f3125
## Requires 
https://civitai.com/models/126660/architectureexteriorsdlifechiasedammev60   
https://civitai.com/models/68286?modelVersionId=72978   
https://civitai.com/models/4201?modelVersionId=130072

## Original
![original](images/original.png)


## ControlNet
![workflow_ControlNet_01](images/workflow_ControlNet_01.png)

## ControlNet + LoRA
![workflow_LoRA_01](images/workflow_LoRA_01.png)

## ControlNet + LoRA + Inpainting
![workflow_InPainting_01](images/workflow_InPainting_01.png)
![workflow_InPainting_02](images/workflow_InPainting_02.png)
![workflow_InPainting_03](images/workflow_InPainting_03.png)

# Extra(Cube)
ControlNetの検証（Seed値は固定）
## Original
![cube_original_base](images/extra/cube/original_base.jpg)
![cube_original_depth](images/extra/cube/original_depth.png)
![cube_original_normal](images/extra/cube/original_normal.png)

## depth
![cube_ControlNet_depth](images/extra/cube/ControlNet_depth.png)
## lineart
![cube_ControlNet_lineart](images/extra/cube/ControlNet_lineart.png)
## scribble
![cube_ControlNet_scribble](images/extra/cube/ControlNet_scribble.png)
## depth + lineart
![cube_ControlNet_depth+lineart](images/extra/cube/ControlNet_depth+lineart.png)
## depth+ scribble
![cube_ControlNet_depth+scribble](images/extra/cube/ControlNet_depth+scribble.png)
## upscale
![cube_ControlNet_upscale_01](images/extra/cube/upscale_01.png)
![cube_ControlNet_upscale_02](images/extra/cube/upscale_02.png)
![cube_ControlNet_chaos](images/extra/cube/chaos.png)

# Extra(Interior)
Inpaintでフローリング→壁の順で生成し、最後にupscaleで仕上げる
## Original
![interior_original_color](images/extra/interior/color.png)
![interior_original_depth](images/extra/interior/depth.png)

## Floor
![interior_floor](images/extra/interior/floor.png)

## Wall
![interior_wall_pre_wood](images/extra/interior/wood_pre.png)
![interior_wall_pre_concrete](images/extra/interior/concrete_pre.png)

## Finish(upscale)
![interior_wall_wood](images/extra/interior/wood.png)
![interior_wall_concrete](images/extra/interior/concrete.png)

