# nvidia-jasper-determinism
For most of the instruction please follow https://github.com/NVIDIA/DeepLearningExamples/tree/master/PyTorch/SpeechRecognition/Jasper.

Some parts have been modified, for example, train.py can now accept det flag (add "--det" to enable deterministic mode, --cudnn must not be set). Furthermore, scripts/train_benchmark.sh is also modified to take $CUDNN_DET env variable as an argument (Not using command line argument here in order to not mess with the command line arguments of the other scripts).


