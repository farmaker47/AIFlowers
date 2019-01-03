## AI Flowers

AI Flowers is a demo app that was created for Udacity Project Showcase as part for the Facebook Pytorch scholarship.

### Download

    git clone https://github.com/farmaker47/AIFlowers

### Build

Click the green play button in Android Studio and follow instructions if some classes are missing

WARNING= Take in mind that this build is at the moment available only for NDK 17c version. So download this version to run it
https://developer.android.com/ndk/downloads/older_releases
and then inside AS go to File -> Project Structure -> SDK Location -> NDK Path (Put extracted path here)

Because of this, demonstration APP uses protobufs inside assets folder that come from original AIDemo application
where classification is from Imagenet with 1.000 different classes of images.
Tweeks have been made to correspond to how this app will look like when Demo app will work with newer NDK 18 where you can work with your own protobufs.

Inside Assets folder there are already 2 protobufs soloupis_init_net AND soloupis_predict_net where these have been created after training a SqueezeNet
to identify 102 flower species. You can download the colab notebook to see a working example of how protobufs are created from link
https://drive.google.com/open?id=1uVTRHIJTo8ziMoC-ClpmTAiqtVdpLgEF


### Tests

At phones with min SDG version 22 aka Marshmallow because camera2 api is used..

### License

Please see the LICENSE file in the root directory the source tree.
