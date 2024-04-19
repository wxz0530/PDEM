# PDEM
1、Weight acquisition: https://pan.baidu.com/s/1V5pZMIu5dOPOFt4DXgWevw?pwd=9p33   
2、Data preprocessing: python pre_process_sysu.py   
3、Train command: python train_ext.py --dataset sysu --lr 0.1 --method adp  --augc 1 --rande 0.5  --gpu 0   
4、Test command: python testa.py --mode all --resume 'model_path' --gpu 0 --dataset sysu   
