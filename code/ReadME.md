The evaluation is done using the code from :https://github.com/qaz812345/TrackNetV3.git . I have used their pre-trained model and used their code and commands for inference.

Specifically,  
python predict.py --video_file test.mp4 --tracknet_file ckpts/TrackNet_best.pt --inpaintnet_file ckpts/InpaintNet_best.pt --save_dir prediction --output_video
