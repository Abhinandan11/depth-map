# depth-map

1. Clone this repository:
```
git clone https://github.com/Abhinandan11/depth-map.git
```

2. Install the dependencies:
```
pip install -r requirements.txt 
```


3. Download these two files: https://drive.google.com/open?id=1ztQTAoDOzfG9IiZc4rxB5FMJgi40ngvf
                            
   https://drive.google.com/open?id=1W7SexKT0Wb8-wqmf23q94tDLmd48wkxK
                             
   and move them to **models** folder.


4. Rename your input image as **input.jpg** and place it in the main folder.


5. Run **predict.py** file with command: 
 
```
python predict.py models/NYU_FCRN.ckpt input.jpg
```


6. It will save two depth maps as **final.jpg** and **finalgray.jpg** in the main folder.




> Please fork this repository, if you want to use this code and give it a star.
