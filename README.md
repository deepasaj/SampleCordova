1. Install cordova using npm:

npm install -g cordova

2. Create a new cordova application

cordova create hello com.example.hello HelloWorld

3. Specify target platform

- Download android sdk.. Add /sdk/tools and /sdk/platform-tools to your path
- cordova platform add android 	

4. Build project

cordova build 
(or)
cordova prepare
cordova compile

5. Run on actual android phone

cordova run android

6. Run on ios

npm install -g ios-deploy
npm install -g ios-sim

.
