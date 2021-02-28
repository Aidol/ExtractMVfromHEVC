# ExtractMVfromHEVC
Extracting motion vectors from HEVC in HM

[Guideline](https://mp.weixin.qq.com/s/iGrjw1jTAgGes_XjFnZoZQ)

Quick start:

1. Clone this project to your pc.

2. Using Visual Studio open ```./ExtractMVfromHEVC./HM-16.15./build/HM_vc2015.sln```

3. Put your video sequence in a sequence folder.

4. Modify ```./ExtractMVfromHEVC./HM-16.15./workspace/encoder_lowdelay_P_main.cfg``` by your YUV video info.

5. First run TAppEncoder in Visual Studio.

6. Second delete the file ```mv.csv``` in workspace.

7. Finally, run TAppDecoder in Visual Studio. The motion vector info will be saved in ```mv.csv```.