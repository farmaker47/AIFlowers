## AI Flowers

AI Flowers is a demo app that was created for Udacity Project Showcase as part for the Facebook Pytorch scholarship.

### Download

    git clone https://github.com/farmaker47/AIFlowers

### Build
Download libs.zip from url https://drive.google.com/open?id=1-eHu1psGyj4YD0Uz6DGY7IiJfbE5sRWa
Unzip libs.zip to get the static libraries\n
Create a folder named jni in app/src/main\n
Create a folder named armeabi-v7a in app/src/main/jni\n
Copy the static libraries to app/src/main/jni/armeabi-v7a\n

Click the green play button in Android Studio and follow instructions if some classes are missing



Inside Assets folder there are already 2 protobufs soloupis_init_net AND soloupis_predict_net where these have been created after training a SqueezeNet to identify 102 flower species. You can download the colab notebook to see a working example of how protobufs are created from link https://drive.google.com/open?id=1uVTRHIJTo8ziMoC-ClpmTAiqtVdpLgEF


### Tests

At phones with min SDG version 22 aka Marshmallow because Camera2 api is used..

### License

Please see the LICENSE file in the root directory the source tree.
