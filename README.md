# cvdl-assignment

# Lancer un entraînement
python3 train.py --img 640 --batch 16 --epochs 50 --data /cluster/home/tbguyot/assignment/datasets/data.yaml --weights yolov5m.pt

# Test inferences (marche pas bizarre)
python3 detect.py --weights runs/train/exp/weights/best.pt --source /cluster/home/tbguyot/assignment/datasets/images/test --view-img# cvdl-project
