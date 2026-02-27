# MA-HybridBTS: Modality-Aware Multi-Scale Hybrid 3D Conv-Transformer for Brain Tumor Segmentation
## [update]
[2026.2.27] Please link to a more comprehensive version [MA-HyridBTS](https://github.com/Jia7888/MA-HybridBTS).

## [train & test]
if you want to train my model, you can run
python main.py --exp-name "CKD" --devices 0 --dataset-folder "dataset/" --batch-size 1 --workers 1 --lr 1e-4 --end-epoch 300 --mode "train"

if you want to evaluate the model, you can run
python main.py --mode test --dataset-folder dataset --exp-name CKD --devices 0
