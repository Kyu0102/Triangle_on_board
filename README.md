# Triangle_on_board
Making camera calibration and pose estimation on chessboard with Triangle!

We can get parameter of my viedo by calibration my chessboard video.
The parameter can be found below:

## Camera Calibration Results
* The number of selected images = 53
* RMS error = 1.931168898003303
* Camera matrix (K) = 
[[1.29466630e+03 0.00000000e+00 6.18498680e+02]
 [0.00000000e+00 1.22051972e+03 3.69674333e+02]
 [0.00000000e+00 0.00000000e+00 1.00000000e+00]]
* Distortion coefficient (k1, k2, p1, p2, k3, ...) = [-0.03204318 -0.20808783 -0.00046016  0.00349807  0.2555784 ]
![image](https://user-images.githubusercontent.com/128031528/235366382-22c9774f-11de-491e-9f4a-32486a54d533.png)

Then we also do pose estimation on my video.
I make a triangle object over the board like below:
![triangle](https://user-images.githubusercontent.com/128031528/235366439-e9dac22e-df18-4bca-8e53-cd29dcde2d7b.png)
