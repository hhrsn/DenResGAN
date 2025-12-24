# DenResGAN
Image De-blurring Algorithm

# How to run
Download weights:

Put the weights into  
`./checkpoints/experiment_name`

To test a model put your blurry images into a folder and run:  
`python test.py --dataroot /.path_to_your_data --model test --dataset_mode single --learn_residual`

To calculate PSNR and SSIM:  
python SSIM.py

To calculate LPIPS:  
