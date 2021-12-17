# lab3mlforcybersecurity
# a backdoor detector for BadNets trained on the YouTube Face dataset using the pruning defense 
# I have used data from th github repository https://github.com/csaw-hackml/CSAW-HackML-2020 for this lab. The data under lab3 folder has been used. The folder 'cl' contains clean test and validation data and the folder 'bd' contains poisoned test and validation data
# The dataset contains images from YouTube Aligned Face Dataset. We retrieve 1283 individuals each containing 9 images in the validation dataset.
# To evaluate the backdoored model, execute eval.py by running: python3 eval.py <clean validation data directory> <model directory>.
# for the mainnotebook file, I used the bd_net.h5 Badnet model
# references:
  https://github.com/csaw-hackml/CSAW-HackML-2020
  https://www.tensorflow.org/model_optimization/guide/pruning/pruning_with_keras
  https://github.com/rishiraj824/YouTube-FaceDataSet-Backdoor-Detection
