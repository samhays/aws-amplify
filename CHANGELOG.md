# Changelog for AWS Amplify
<!--LATEST=0.2.8-->
<!--ENTRYINSERT-->

##04/11/2018
* aws-amplify - v0.2.15
    *Enhancement: Preserve error context when loading Cognito credentials. #577
    *Enhancement: Increase test coverage for PubSub. #588
    *Enhancement: Fix StorageCache configure and use InMemoryCache. #635
    *Bug Fix: Sign out fix. #511
    *Bug Fix: Adding Polyfill.js to fix PubSub. #588
    *Bug Fix: Ensure credentials retrieved only once on page reload. #486
    *Bug Fix: Fix empty object returned in componentDidMount when using Auth.currentUserInfo. #608
    *Bug Fix: Setting authData after ConfirmSignIn


## 03/30/2018
* amazon-cognito-identity-js - v2.0.3
    * Bug Fix: missing es folder in npm package
    
## 03/28/2018
* aws-amplify - v0.2.14
    * Enhancement: Refreshing Federated jwt token on need. #191
    * Enhancement: Binding console to console functions #458
    * Enhancement: Customize endpoint userId and attributes #437
    * Enhancement: Analytics turn on/off #479
    * Enhancement: Add params.ContentDisposition to Storage.put() #501
    * Enhancement: Make Storage operations options optional #527
    * Enhaneement: Adding custom federated auth provider #540
    * Feature: Initial implementation of PubSub category #460
    * Bug Fix: Retrieving credentials only once when reloading pages #486
    * Bug Fix: Sign out fix #511
    * Bug Fix: Credentials expired case handle #528
* aws-amplify-react - v0.1.38
    * Enhancement: adding `onError` support for withGoogle Federated login #475

## 03/22/2018
* aws-amplify - v0.2.12@beta
    * Enhancement: Refreshing Federated jwt token on need. #191
    * Enhancement: Binding console to console functions #458
    * Enhancement: Customize endpoint userId and attributes #437
    * Enhancement: Analytics turn on/off #479
    * Bug Fix: Retrieving credentials only once when reloading pages #486
* aws-amplify-react - v0.1.37@beta
    * Enhancement: adding `onError` support for withGoogle Federated login #475

## 03/19/2018
* aws-amplify - v0.2.11
    * Enhancement: Analytics customize endpointId #421
    * Enhancement: Auth TOTP #407
    * Enhancement: Add support for developer authenticated strategies #425
    * Enhancement: Generate declaration file #381
    * Enhancement: Cognito cookie storage #398
    * Feature: Analytics plugin #236
* aws-amplify-react - v0.1.36
    * Enhancement: Make options parameter optional in Storage.put #406
    * Enhancement: Auth TOTP #407
    * Bug Fix: Fix issue #357 for authenticator hidedefault #400
* aws-amplify-react-native - v0.2.7
    * Bug Fix: asyncStorageCache #412
* amazon-cognito-identity-js - v2.0.2
    * Enhancement: Missing types fix #454

## 03/12/2018
* aws-amplify - v0.2.10@beta
    * Enhancement: Analytics customize endpointId #421
    * Enhancement: Auth TOTP #407
    * Enhancement: Add support for developer authenticated strategies #425
    * Enhancement: Generate declaration file #381
    * Enhancement: Cognito cookie storage #398
    * Feature: Analytics plugin #236
* aws-amplify-react - v0.1.35@beta
    * Enhancement: Make options parameter optional in Storage.put #406
    * Enhancement: Auth TOTP #407
    * Bug Fix: Fix issue #357 for authenticator hidedefault #400
* aws-amplify-react-native - v0.2.6@beta
    * Bug Fix: asyncStorageCache #412

## 02/27/2018
* aws-amplify - v0.2.9
    * Bug Fix: Fix for missing endpoint in config #373
    
## 02/27/2018
* aws-amplify - v0.2.8
    * Enhancement: Allow service info config for API #312
    * Enhancement: Add expires key to s3.get() #327
    * Bug Fix: currentUserInfo should check for user if no credentials source #331
    * Enhancement: Push Notification #343
    * Enhancement: Add a method to change password for currently authenticated user #349
* aws-amplify-react - v0.1.34
    * Enhancement: Export VerifyContact #365
* aws-amplify-react-naitve - v0.2.5
    * Enhancement: Push Notification #343
    * Bug Fix: Fix typo #356

## 02/19/2018
* amazon-cognito-identity-js - v2.0.1
    * Enhancement: Fix incorrect RNAWSCognito podspec file extension #278
    * Enhancement: Adds missing 'listDevices' function to CognitoUser class for TypeScript type safety #276
    * Enhancement: Add and update MFA typescript interface for CognitoUser #279
* aws-amplify - v0.2.7
    * Bug Fix: Force the guest credentials to return null when mandatory sign in enabled #295
    * Bug Fix: Fix the Typescript definitions for API, Analytics, Auth and Storage #263
    * Enhancement: Docs/update quick start #274
    * Enhancement: Support centralized tracking #199
    * Enhancement: Support passing and signing of custom domains in API RestClient #310
    * Enhancement: Return full response of api if you set response in the init object to true #300
* aws-amplify-react - v0.1.33
    * Bug Fix:  Check if SMS enabled for RequireNewPassword #296
    * Enhancement: Hide image or text if ```hidden``` props set #291
    * Enhancement: Make `withAuthenticator` HOC configurable #110
* aws-amplify-react-naitve - v0.2.4
    * Bug Fix: Check if SMS enabled for RequireNewPassword #296
    * Enhancement: Add Loading page for React Native authenticator #233
    * Enhancement: Make `withAuthenticator` HOC configurable #110
    * Enhancement: Use ```componentWillReceiveProps``` instead of ```componentWillMount``` to set username in ```confirmSignUp``` #306

## 02/12/2018
* aws-amplify - v0.2.6
    * Bug fix: Wait for current credentials before signOut #247
    * Documentation updated #253 #251 #258 #264 #265 #266 #269 #270 #271 
* amazon-cognito-identity-js - v2.0.0
    * Enhancement: Merge cognito pr 662 and 668 #248
    * Enhancement: Adding migration trigger support #257

## 02/07/2018
* aws-amplify - v0.2.4
    * Bug fix: Safe check for navigator variable
    * Bug fix: Retrieve unauth credentials if not logged in, Fixes #229
* aws-amplify-react-native - v0.2.3
    * Enhancement: warning for configure (deprecated)

## 01/31/2018
* aws-amplify - v0.2.0
    * Enhancement: Allow SignUp with validation data #182
    * Enhancement: Add .patch() interface to API #207
    * Enhancement: Number.isInteger #185
    * Enhancement: Add protected level to Storage #213
    * Bug fix: Cache configure keyPrefix #210
* aws-amplify-react - v0.1.32
    * Bug fix: S3Album private level #213
* aws-amplify-react-native - v0.2.0
    * Enhancement: Refactor to use core library instead of duplicate implemntation #200

## 01/18/2018
* aws-amplify - v0.1.36
    * Enhancement: Sign up with custom attributes #160
    * Bug fix: Api cred refresh #118
    * Bug fix: EndpointId for Pinpoint not get refreshed correctly #161
* aws-amplify-react - v0.1.31
    * Bug fix: Now S3Image can upload files to private folder #133
* aws-amplify-react-native - v0.1.24
    * Enhancement: Remove dependency from aws-mobile-analytics dependency #142
    * Enhancement: Sign up with custom attributes #160
    * Bug fix: EndpointId for Pinpoint not get refreshed correctly #161

## 01/16/2018
* aws-amplify - v0.1.35
    * Improvements to Typescript developer experience. #155
	* fix RN props #158
	* delete ama #142
* aws-amplify-react-native - v0.1.23
    * fix RN props #158

## 01/12/2018
* aws-amplify-react-native - v0.1.22
    * bug fix: fix aws-sdk package
## 01/11/2018
* aws-amplify - v0.1.34
    * bug fix: fix aws-sdk package
    * bug fix: update main script

## 01/09/2018

* aws-amplify - v0.1.32
* aws-amplify-react - v0.1.30
* aws-ampliify-react-native - v0.1.21

* Enhancement: remove aws-sdk-mobile-analytics dependency from package.json

## 01/08/2018

* aws-amplify - v0.1.31
* aws-amplify-react - v0.1.30
* aws-ampliify-react-native - v0.1.21

* Feature: Export Authenticator in aws-amplify-react-native
* Enhancement: Reduce bundle size by removing aws-mobile-analytics dependency
* Security issue: Change dependency on typedoc for security issue
* Bug fix: Timezone error for Windows
* Bug fix: Npm badge fix
* Bug fix: Doc syntax error fix
* Bug fix: Add charset on default header for API

## 12/22/2017

* aws-amplify - v0.1.30
* aws-amplify-react - v0.1.30
* aws-amplify-react-native - v0.1.20

* feature: Federated Authentication with Google and Facebook in React
* bugFix: Federated auth token fixes
* feature: Automatic S3 Analytics tracking with React components
* feature: Increase unit test coverage
* feature: Jest snapshot update
* feature: Update default auth theme
* feature: Export Signer interface for 3rd party HttpModules
* bugFix: aws-amplify-react-native: Update pinpoint region in React Native
* feature: Better support for guest (Unauthenticated) credentials
* bugFix: documentation: Fix broken link (to authentication)
