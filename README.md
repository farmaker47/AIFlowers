## AI Flowers

AI Flowers is a demo app that was created for Udacity Project Showcase as part for the Facebook Pytorch scholarship. You can use the camera of your app to classify flowers and see their names.

### Download

    git clone https://github.com/farmaker47/AIFlowers

### Build

To build the necessary libraries for the project follow super instructions by Soumith and Thomas from this repository
https://github.com/t-vi/AICamera

1.First you have to set some paths to Linux as shown at the picture. Use commands

cd ~

gedit .profile


![ubu3](https://user-images.githubusercontent.com/26084498/50677461-ab370700-1002-11e9-9d2e-04672e143e05.png)

2.Then run ./build_android.sh script
![ubu2](https://user-images.githubusercontent.com/26084498/50677631-90b15d80-1003-11e9-9aa0-e315124110d6.png)

3.Wait until libraries are generated
![ubu1](https://user-images.githubusercontent.com/26084498/50677686-da9a4380-1003-11e9-9e74-86831a66eace.png)

4.When everything is ready find the libraries inside path pytorch/pytorch/build_android/lib:
![ubu5](https://user-images.githubusercontent.com/26084498/50677722-20efa280-1004-11e9-882c-a291c982ac56.png)


## If you cannot build or you dont have a clue about linux use below instructions:

Download libs.zip from url https://drive.google.com/open?id=1-eHu1psGyj4YD0Uz6DGY7IiJfbE5sRWa

Unzip libs.zip to get the static libraries

Create a folder named jni in app/src/main

Create a folder named armeabi-v7a in app/src/main/jni

Copy the static libraries to app/src/main/jni/armeabi-v7a

Click the green play button in Android Studio and follow instructions if some classes are missing


## Info
Tested and working with NDK17 and 18.
Inside Assets folder there are already 2 protobufs soloupis_init_net AND soloupis_predict_net where these have been created after training a SqueezeNet to identify 102 flower species. You can download the colab notebook to see a working example of how protobufs are created from link https://drive.google.com/open?id=1uVTRHIJTo8ziMoC-ClpmTAiqtVdpLgEF

## Small video 
https://www.youtube.com/watch?v=LOeFcHR9d9s&feature=youtu.be

## Credits
Soumith Chintala, Thomas V, Ioannis Anifantakis

## Special links for more info
https://github.com/t-vi/AICamera

https://github.com/wangnamu/AICamera_new

### Tests

At phones with min SDG version 22 aka Marshmallow because Camera2 api is used..

### License

Please see the LICENSE file in the root directory the source tree.
