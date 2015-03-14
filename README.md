# android-testapp
TestApp for Android attempting best practices and such

# Short-term Goals

* Use some standard libraries to bring my Android skills up to speed
    * JSON - Jackson
    * REST API - Retrofit
    * Images - Picasso
    * Http - OkHTTP
    * Reactive programming - RxJava/RxAndroid
    * Lambdas - Retrolambda
    * Android components:
        * Recycler view
            * Decent list adapter
            * SQLite cursor adapter
* Target latest APIs (currently 22) ubt port backwards to API 16
    * JellyBean (16, 17, 18), KitKat (19), Lollipop (21)
    * Target phones and tablets
    * see https://developer.android.com/about/dashboards/index.html
* Material design
	* define all layouts
	* layouts - generic view agnostic layouts
	* layouts-port - portrait layout for devices under 7"
	* layouts-land - landscape layouts for devices under 7"
	* layouts-port-sw620 - portrait layouts for 7"+
	* layouts-land-sw620 - landscape layouts for 7"+
* Look for a way to persist pojos to sqlite with audit columns - id, insert_user/insert_date, update_user/update_date

# Long-term Goals

* OpenID log in services
    * Email + password
    * Email only
    * Google+
    * Facebook
    * Twitter (see https://get.fabric.io/)
    * Digits (see https://get.fabric.io/)

# Web services

* placehold.it
* jsonplaceholder.typicode.com
* apiary.io
* https://app.apiary.io/fuhoitestapp/editor

# Resources

* Android Developer Dashboard (https://developer.android.com/about/dashboards/index.html)

# Articles

* https://android-arsenal.com/details/3/1091
* http://saulmm.github.io/2015/02/02/A%20useful%20stack%20on%20android%20%231,%20architecture/
	* https://github.com/saulmm/Material-Movies

# Tools

* GitHub for Windows
* GitHub
* Android Studio
* MarkDownPad2
* GenyMotion - emulator - https://www.genymotion.com/
