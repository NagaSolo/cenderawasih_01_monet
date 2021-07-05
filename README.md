### Summary
    - Style transfer using pretrained model by Magenta
    - Pretrained model used Monet

### Prerequisites
    - Link -> https://github.com/magenta/magenta/blob/main/README.md
    - Install necessary packages:
        `sudo apt-get install build-essential libasound2-dev libjack-dev portaudio19-dev`
    - Install magenta:
        `pip install magenta`

### Usage
    - Magenta:
        `image_stylization_transform --num_styles=10 --checkpoint=models/multistyle-pastiche-generator-monet.ckpt --input_image=input/image.jpg --which_styles="[0,1,2,5,14]" --output_dir=output --output_basename="monet"`

### Issue
    - Low LLVM memory, to be tested on Ubuntu setup