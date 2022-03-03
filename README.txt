Open file "Adpruner_cifar.py ",execute the following commands in sequence(Resnet56, for example):

--dataset cifar10 
--data_path /data/CIFAR10/ 
--pretrain_model /data/model/resnet56.pt 
--job_dir /data/experiment/resnet56 
--arch resnet 
--cfg resnet56 
--init_method centroids 
--preference_beta 0.76 
--lr 0.01 
--lr_decay_step 50 100 
--num_epochs 150 
--train_batch_size 256 
--weight_decay 5e-3 
--gpus 0

Note:Please download the datasets and the official weight file yourself,you can adjust the above parameters.

