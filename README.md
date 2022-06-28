# GifMauiSample

# GIF image is not working in .net MAUI application

I would like to display some gif animation images in my application. The library I used to do it with Xamarin.Forms was Xamarin.FFImageLoading.Svg.Forms. Now that we are migrating our application to .net MAUI, I see that the MAUI document says that it supports GIF files. I tried a sample, but it did not work.

I have seen a gif related bug and workaround in the following link, and I also tried it, but for me the gif animation is still not working.

https://github.com/dotnet/maui/issues/5034


I posted a question on stackoverflow, here's the link: 

https://stackoverflow.com/questions/72780267/gif-image-is-not-working-in-net-maui-application
You can use this sample application to replicate the problem

#Latest Update - June 28
When connected to hotreload on the Android platform, the animation does not work.
If you set IsAnimationPlaying to false and then back to true, while in hot reload mode, it should work.

Besides the hot reload issue, Android is working fine, but iOS and macOS are still not working.

Below is the ticket for GIF issue with iOS and macOS
https://github.com/dotnet/maui/issues/866

The gif image I used in this sample application was downloaded from @giphy.

https://gph.is/g/4MzD71w?tc=1 via @giphy
