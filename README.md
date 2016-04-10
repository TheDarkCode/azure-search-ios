[![Build Status](https://travis-ci.org/TheDarkCode/azure-search-ios.svg?branch=master)](https://travis-ci.org/TheDarkCode/azure-search-ios)
<h1 align="center">

<!--span style="height:72px;"><img src="https://raw.githubusercontent.com/TheDarkCode/azure-search-ios/master/src/azure-search-basics/azure-search-basics/Assets.xcassets/AppIcon.appiconset/Icon-72.png" alt="AngularAzureSearch"></span-->

<span style="margin-bottom:0.5em;">Azure Search iOS SDK</span>

</h1>

Modular SDK written in Swift 2.2 / Xcode 7.3 that simplifies incorporating Azure Search into native iOS 9 applications for iPhones and iPads (later will be inclusive of tvOS and watchOS). Requires Whole Module Optimization to be enabled for best performance. **Non-commercial use only. Commercial licensing terms will be made available upon first release.**

<p align="center">
<img src="https://raw.githubusercontent.com/TheDarkCode/azure-search-ios/master/img/TrailSearch.png" alt="AngularAzureSearch" height="auto" width="60%">
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/TheDarkCode/azure-search-ios/master/img/AZS3DTouch.png" alt="AngularAzureSearch" height="auto" width="60%">
</p>

##Requirements: 

#####XCode 7.3 (recommended) on OS X El Capitan. Apple Developer License.

You should have a basic understanding of working with Swift 2.x as well as how to use storyboards and views loaded from xib files. You will need to customize the examples to fit your specific data structures. However, later implementations will make use of a different approach to custom views.

####Azure Service Requirements for Deployment

You must configure the project with your own Azure Search Keys, and Bing Maps API Keys.

######If you are new to Azure, you can get a free trial at the following link: 
https://azure.microsoft.com/en-us/pricing/free-trial/

######Bing Maps API (10k transactions/mo for free)
http://www.microsoft.com/maps/Licensing/licensing.aspx#mainTab2

######Azure Search Service are free excluding outbound data transfers (3 data connections / indexes / indexers, 50 MB Total Storage, 10,000 Documents).
https://azure.microsoft.com/en-us/pricing/details/search/

######Data Transfers Pricing Details
https://azure.microsoft.com/en-us/pricing/details/data-transfers/

##Related Projects:

###Example Swift Apps by Mark Hamilton, Dryverless
Collection of example applications written in Swift / Objective-C for iOS 9.x (developed under 9.2.1 SDK - will be migrated to 9.3 when released)
######https://github.com/TheDarkCode/Example-Swift-Apps

###AngularAzureSearch by Mark Hamilton, Dryverless
######https://github.com/TheDarkCode/AngularAzureSearch/

###Azure Search Demos by Liam Cavanagh, Microsoft
######https://github.com/liamca/AzureSearchDemos
######http://azure.microsoft.com/en-us/documentation/services/search/

##Helpful Links

######Azure Search Documentation: https://msdn.microsoft.com/en-us/library/azure/dn798933.aspx

##Related Microsoft Virtual Academy Courses

####Adding Microsoft Azure Search to Your Websites and Apps:
######https://mva.microsoft.com/en-us/training-courses/adding-microsoft-azure-search-to-your-websites-and-apps-10540

##Support:

#####Send any questions or requests to: support@dryverless.com

##Disclaimer:

#####While there may be a general license applied to the repo as a whole, you should not assume all media (example project assets like images or videos) are under that same license. Creative commons and open source images are used throughout with attributions given inside each relevant project's files; however, copyright or trademark use allowances or restrictions can be changed by authors and may not be accurately reflected in the repo. As a rule of thumb, you should use the provided samples only as guides to help you learn, not as commercial assets to use in your new app on the App Store. For example, sample project assets like the dryverless logo are not under the MIT license.
