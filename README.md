# Gifs App ![Bitrise Build](https://app.bitrise.io/app/720a32360a4f66ad/status.svg?token=bchGZrW6HRKshADR7NG9XA&branch=master)
This is a sample app that access [Giphy API](https://developers.giphy.com/) to show the trending GIFs in Giphy Platform.

## Android Dynamic Modules
It uses [Android Dynamic Module](https://developer.android.com/guide/app-bundle/dynamic-delivery) to show how add this feature to your project.
The usage sample is in the access to Favorite Gifs screen, the FavoriteGifListActivity.
To check the implementation details, read my post on [Medium](https://medium.com/@angelica.liv/utilizando-m%C3%B3dulos-din%C3%A2micos-no-seu-app-android-e04875765586)! ;)

## Jetpack Navigation
To navigate between screens and to make Dynamic Module implementation simpler, there is the implementation of [Jetpack Navigation](https://developer.android.com/guide/navigation) library. [Here](https://medium.com/android-dev-br/implementando-jetpack-navigation-component-com-m%C3%B3dulos-de-features-din%C3%A2micas-no-android-e604c13d235f) you can find a post about this library integration on an existing app.

## How can I build?
To build the project in your own machine, please update the **keys.gradle** file with your **own** keys in Giphy platform access (click [here](https://developers.giphy.com/dashboard/?create=true) to create an app).



> Written with [StackEdit](https://stackedit.io/).
