# The process of reproducing F-LSeSim
## Dataset download
before running the code, remember to go to `./datasets/download_cyclegan_dataset.sh` to change the target path and dic
```
TAR_FILE=../../../data3/shuyuan/$FILE.tar.gz
TARGET_DIR=../../../data3/shuyuan/$FILE/
wget -N $URL -O $TAR_FILE
mkdir -p $TARGET_DIR
tar -zxvf $TAR_FILE -C TARGET_DIR
rm $TAR_FILE
```
```bash ./datasets/download_cyclegan_dataset.sh horse2zebra```
## Library Download
配環境可能有點麻煩，早日開始hhh
我是之前配的虛擬環境，
主要需要pytorch, cv2 

pip install visdom dominate

## fix the data root
