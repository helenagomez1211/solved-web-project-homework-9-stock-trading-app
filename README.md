Download Link: https://assignmentchef.com/product/solved-web-project-homework-9-stock-trading-app
<br>
1. Objectives




<ul>

 <li>Become familiar with Java, JSON, Android Lifecycle and Android Studio for Android app development.</li>

 <li>Build a good-looking Android app.</li>

 <li>Learn the essentials of Google’s Material design rules for designing Android apps ● Learn to use the tiingo APIs and the Android SDK.</li>

 <li>Get familiar with third party libraries like Picasso, Glide and Volley.</li>

</ul>




The objective is to create an Android application as specified in the document below and in the video.




<h1>2. Background</h1>

<h2><strong>2.1 Android Studio  </strong></h2>

<a href="https://developer.android.com/studio/">Android Studio</a> is the official Integrated Development Environment (IDE) for Android application development, based on <a href="https://www.jetbrains.com/idea/">IntelliJ IDEA</a> – a powerful Java IDE. On top of the capabilities you expect from IntelliJ, Android Studio offers:

<ul>

 <li>Flexible Gradle – based build system.</li>

 <li>Build variants and multiple apk file generation.</li>

 <li>Code templates to help you build common app features.</li>

 <li>Rich layout editor with support for drag and drop theme editing.</li>

 <li>Lint tools to catch performance, usability, version compatibility, and other problems.</li>

 <li>ProGuard and app-signing capabilities.</li>

 <li>Built-in support for Google Cloud Platform, making it easy to integrate Google Cloud Messaging and App Engine.</li>

</ul>




More information about Android Studio can be found at: <a href="https://developer.android.com/tools/studio/index.html">http://developer.android.com/tools/studio/index.html</a> <a href="https://developer.android.com/tools/studio/index.html"> </a>




<h2><strong>2.2 Android </strong></h2>

Android is a mobile operating system initially developed by Android Inc. a firm purchased by

Google in 2005. Android is based upon a modified version of the Linux kernel. As of Nov 2018, Android was the number 1 mobile OS, in unit sales, surpassing iOS, while iOS was still the most profitable platform.




The Official Android home page is located at:  <a href="https://www.android.com/">http://www.android.com/ </a><a href="https://www.android.com/"> </a>

The Official Android Developer home page is located at:

<a href="https://developer.android.com/index.html">http://developer.android.com/</a>

<h2><strong>2.3 Amazon Web Services (AWS) </strong></h2>

AWS is Amazon’s implementation of cloud computing. Included in AWS is Amazon Elastic Compute Cloud (EC2), which delivers scalable, pay-as-you-go compute capacity in the cloud, and AWS Elastic Beanstalk, an even easier way to quickly deploy and manage applications in the AWS cloud. You simply upload your application, and Elastic Beanstalk automatically handles the deployment details of capacity provisioning, load balancing, auto-scaling, and application health monitoring. Elastic Beanstalk is built using familiar software stacks such as the Apache HTTP Server, PHP, and Python, Passenger for Ruby, IIS for .NET, and Apache Tomcat for Java.

The Amazon Web Services homepage is available at: <a href="https://aws.amazon.com/">http://aws.amazon.com/</a>

<h2><strong>2.4 Google App Engine (GAE) </strong></h2>

Google App Engine applications are easy to create, easy to maintain, and easy to scale as your traffic and data storage needs change. With App Engine, there are no servers to maintain. You simply upload your application and it’s ready to go. App Engine applications automatically scale based on incoming traffic. Load balancing, micro services, authorization, SQL and noSQL databases, memcache, traffic splitting, logging, search, versioning, roll out and roll backs, and security scanning are all supported natively and are highly customizable.

To learn more about GAE support for PHP visit this page:

<a href="https://cloud.google.com/appengine/docs/php/">https://cloud.google.com/appengine/docs/php/</a>

To learn more about GAE support for Node.js visit this page:  <a href="https://cloud.google.com/appengine/docs/flexible/Node.js/">https://cloud.google.com/appengine/docs/flexible/Node.js/</a>

<h2><strong>2.5 Microsoft Azure</strong></h2>




The Azure cloud platform is more than 200 products and cloud services designed to help you bring new solutions to life—to solve today’s challenges and create the future. Build, run, and manage applications across multiple clouds, on-premises, and at the edge, with the tools and frameworks of your choice.




To learn more about the Azure services, visit this page:




<a href="https://azure.microsoft.com/en-us/solutions/">https://azure.microsoft.com/en</a><a href="https://azure.microsoft.com/en-us/solutions/">–</a><a href="https://azure.microsoft.com/en-us/solutions/">us/solutions/</a>




To learn more about Azure support for Node.js visit this page:

<a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">https://docs.microsoft.com/en</a><a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">–</a><a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">us/azure/devops/pipelines/targets/webapp?view=azure</a><a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">devops&amp;tabs=yaml#deploy</a><a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">–</a><a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">a</a><a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">–</a><a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">javascript</a><a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">–</a><a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">nodejs</a><a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">–</a><a href="https://docs.microsoft.com/en-us/azure/devops/pipelines/targets/webapp?view=azure-devops&amp;tabs=yaml#deploy-a-javascript-nodejs-app">app</a>
















<h1>3. Prerequisites</h1>




This homework requires the use of the following components:

<ul>

 <li>Download and install <a href="https://developer.android.com/studio/index.html">Android Studio</a><a href="https://developer.android.com/studio/index.html">.</a> Technically, you may use any IDE other than Android Studio such as Eclipse, but the latest SDKs may not be supported with Eclipse. We will not be providing any help on problems arising due to your choice of alternate IDEs.</li>

 <li>You must use the <strong>emulator</strong>. Everything should just work out of the box.</li>

 <li>If you are new to Android Development, <u>Hints</u> are going to be your best friends!</li>

</ul>

































































































<h1>4. High Level Design</h1>

This homework is an extended mobile app version of Homework 6 and Homework 8.

In this exercise, you will develop an Android application, which allows users to search for different stock symbols/tickers and look at the detailed information about them. Additionally, the users can trade with virtual money and create a portfolio. Users can also favorite stock symbols to track their stock prices. The App contains 2 screens: Home screen and the Detailed Stock Information screen. However, the App has multiple features on each of these screens.




<strong>This homework contains 5 API calls. There are 4 calls to the tiingo APIs for company description, stock prices, autocomplete and chart data points, and the additional newsapi endpoint. Each of these 5 API calls are the same as Homework #8. So, you can use the same Node.js backend as HW8 with an additional call added as a new endpoint.</strong> In case you need to change something in Node, make sure you do not break your Angular assignment (or deploy a separate copy) as the grading for homework will not be finished at least until 1 week later.  <strong>  </strong>

<strong>You must use Java strictly. <u>Kotlin is not allowed.</u> </strong>

<strong> </strong>

<strong><u>PS: This app has been designed and implemented in a Pixel 2XL emulator by using SDK</u> <u>API 29. It is highly recommended that you use the same virtual device and API to ensure</u> <u>consistency.</u>  </strong>

<strong> </strong>

<strong><u>Demo will be on an emulator using Zoom Remote Control, no personal devices allowed,</u> <u>see the rules:</u>  </strong>

<strong> </strong>

<a href="https://csci571.com/courseinfo.html#homeworks">https://csci571.com/courseinfo.html#homeworks</a>























































<h1>5. Implementation</h1>

<h2>5.1 App Icon and Splash Screen</h2>

In order to get the app icon/image, please see the <strong><u>hints</u></strong> section.

The app begins with a welcome screen (Figure 2) which displays the icon provided in the hint above.




This screen is called Splash Screen and can be implemented using many different methods. The simplest is to create a resource file for the launcher screen and add it as a style to AppTheme.Launcher (see <strong><u>hints</u></strong>).




This image is also the app icon as shown in Figure 1







<strong>      Figure 1: App Icon</strong>                                                                <strong>Figure 2: Splash Screen </strong>

<strong> </strong>




<h2>5.2 Home screen</h2>

When you open the app, there will be an initial spinner while the data is being fetched using volley as shown in Figure 3. The home screen will have a toolbar at the top with Stocks title and the search icon. Below that, it will show the current date as shown in Figure 3.

<h3>         Figure 3: Home screen</h3>




There are 2 sections on the home screen:

<table width="604">

 <tbody>

  <tr>

   <td width="26">●</td>

   <td width="578"><strong><em>Portfolio Section</em></strong> – This section will show the total net worth of the user, which is calculated as the sum of number of shares of a stock multiplied by the current price, plus uninvested cash. This is followed by the list of stocks in the user portfolio with their current price, change in price and total shares owned information.</td>

  </tr>

 </tbody>

</table>

<ul>

 <li><strong><em>Favorites Section</em></strong> – This section will show all the stocks that have been favorited by the user to allow the user to easily check the prices of stocks in their watchlist. The stock symbol, current price, change in price and company name should be displayed as shown</li>

</ul>

in Figure 3. In case the favorited stock is present in the user portfolio, instead of the company name, the stocks owned should be displayed.




Additionally, the symbol next to the change in price value should either be trending down or up based on the change price value. For example, if the change in price is positive, a trending up symbol should be displayed and the symbol as well as the change price value should have green color. In case the change in price is zero i.e. no change, no symbol should be displayed, and the change price value should be grey.




Each stock listing also has a button on the extreme right, next to the current price field. On clicking the button or the stock listing, the detailed information screen will open for the selected stock.




The home screen view should support multiple functionalities like:

<ul>

 <li>The <strong>swipe to delete functionality</strong> allows the user to remove/delete the stock from the favorite section. On removing a stock from the favorite section, the stock should be removed from the favorite stocks in the local storage and the view.</li>

 <li>The <strong>drag and reorder functionality</strong> allows the user to reorder the stocks in either section. The user should be able to long press the stock listing and drag it to the new position. The list should be updated accordingly to ensure the new order going forward. Note: The user cannot drag the stock from the favorite section into the portfolio section. The stock can only be dragged and dropped in the same section.</li>

</ul>




At the bottom of the 2 sections, we have a ‘Powered by tiingo’ text in italic. On clicking this text, the App should open the Tiingo homepage in chrome. (The URL should be: <a href="https://www.tiingo.com/">https://www.tiingo.com/</a> )




The field mappings for the stock information is the same as Homework #8.




<strong>Note:</strong> <strong>The price information for each stock should be updated every 15 seconds, same as Homework #8. Additionally, the progress spinner should only be shown whenever the home screen is opened initially or when navigating back from the detailed stock screen. </strong>

<strong>While refreshing the stock price every 15 seconds, the spinner SHOULD NOT be displayed. </strong>

<strong> </strong>

The home screen has been implemented by using a <strong>RecyclerView </strong>with the <strong>SectionedRecyclerViewAdapter. </strong>Each of the stock listings has been implemented using <strong>ConstraintLayout, TextView, ImageView. </strong>




The <strong>Search </strong>button on the toolbar opens the search bar to type the stock symbol to search. The search bar uses the <strong>autocomplete </strong>functionality































5.2.1 Search Functionality




<h3> Figure 4: Search Functionality</h3>

<strong> </strong>

<ul>

 <li>On top right side, there will be a search button which opens a textbox where the user can enter a keyword to search for a stock symbol. See hints for icon.</li>

 <li>The user is provided with suggestions of keywords using the Tiingo Autocomplete API. (Same as homework #8)</li>

 <li>When the user taps on a suggestion, it is filled inside the search box and clicking enter/next takes the user to the detailed information screen.</li>

 <li>Before you get the data from your backend server, a progress bar should display on the screen as indicated in the detailed information section.</li>

 <li>The user can only search for valid stock symbols in the search bar. The search should redirect to the detailed information screen only if the user selected one of the autocomplete suggestions to fill the search field.</li>

 <li>In the Autosuggest, only make an API call after the user enters 3 characters. Example: “am” should not display any suggestions but “ama” should have suggestions. Refer to the video for better understanding.</li>

</ul>




This component involves 2 things:

<ul>

 <li>Implementing a searchable – see <u>hints</u></li>

 <li>Implementing autocomplete – see <u>hints</u></li>

</ul>

<h2>5.3 Detailed Stock Information Screen</h2>




<strong>Figure 4: Loading                     Figure 5: Detailed                    Figure 6: Detailed </strong>




On clicking the <strong>Goto</strong> button on any stock listing or searching for a stock symbol, the loading spinner symbol should be displayed while the details are being fetched (see Figure 4). Once the data has been fetched except the chart (since the chart takes longer to load), the spinner should disappear and information regarding the stock should be available to the user (Figure 5 and Figure

6).




The top action bar should have the ‘Stock’ title and the back button to go back to the home screen (which has the filter values that were used for the current search if triggered by using the search functionality). The action bar should also contain a favorite icon to add or remove the stock from favorites. The favorite icon will either be filled or bordered based on whether the stock is favorited or not. Adding/Removing the stock from favorites should also display a toast message as shown in the video.




Below the action bar, there should be 4 fields: stocks symbol, current price with ‘$’ sign, company name and the change price with ‘$’ sign (the text color should be green, red or grey based on the change price value being positive, negative or zero respectively). The App then has a <strong>WebView</strong> element which is blank till the chart loads. (More details later in this section)




The <strong>Portfolio section </strong>allows the user to trade the shares of the stock. It contains a left section which shows the market value of the stock in the user portfolio and the number of shares the user owns. The right section contains the trade button. Initially, when the user starts the app for the first time, they will not have any stocks/shares in the portfolio and an initial pre-loaded amount of <strong>$20,000 </strong>to trade on the app. This amount can change based on the trading done by the user.

(For example, if the user sells shares at a loss, it can become less than 20,000 and so forth)




If the user does not own any shares of the given stock, the left section will have the message as shown in Figure 7, else the left section will look like Figure 6.







<h3>Figure 7: Portfolio section</h3>

<strong> </strong>

The <strong>Stats section</strong> displays the trading statistics for the given stock in a grid. The grid has 7 fields namely: Current price, Low, Bid price, Open price, Mid, High and Volume. If any of these fields are missing in the JSON, set them as 0.0. The <em>GridView element </em>is to be used for this section.




The <strong>About section </strong>displays the description of the company. If the description is longer than 2 lines, ellipsize the end of the 2nd line and display a ‘Show more…’ button. On clicking this button, the complete description becomes visible and the button text changes to ‘Show less’. (Figure 8) If the description is less than 2 lines, do not display the button.







<h3>Figure 8: About section</h3>

<em> </em>

The API response used is the same<strong> as HW8. </strong>

<strong> </strong>

The <strong>News section </strong>displays the news articles related to the given stock symbol. The first article has a different format/layout than the rest of the articles in the list. On clicking the news article, the original article is opened in chrome using the article URL. On long press, a dialog box opens with options to share on twitter and open in chrome. (Figure 9) Refer the <u>hints</u> section for help in setting up twitter share and open in chrome functionalities. For each article, the information displayed is Article source, Article title, Article image and the time ago when the article was published. The time ago should support ‘days ago’ and ‘minutes ago’ by calculating the difference between the timestamp the article was published and the current timestamp. (see the <u>hints</u>) The news section uses <strong>RecyclerView </strong>and <strong>ArticleDialog </strong>elements.







<h3>Figure 9: News section</h3>




From every twitter button, on clicking the button, the article should be shared by opening a browser with Twitter Intent. Use the following link to implement the Twitter Intent:

<a href="https://developer.twitter.com/en/docs/twitter-for-websites/tweet-button/guides/web-intent">https://developer.twitter.com/en/docs/twitter</a><a href="https://developer.twitter.com/en/docs/twitter-for-websites/tweet-button/guides/web-intent">–</a><a href="https://developer.twitter.com/en/docs/twitter-for-websites/tweet-button/guides/web-intent">for</a><a href="https://developer.twitter.com/en/docs/twitter-for-websites/tweet-button/guides/web-intent">–</a><a href="https://developer.twitter.com/en/docs/twitter-for-websites/tweet-button/guides/web-intent">websites/tweet</a><a href="https://developer.twitter.com/en/docs/twitter-for-websites/tweet-button/guides/web-intent">–</a><a href="https://developer.twitter.com/en/docs/twitter-for-websites/tweet-button/guides/web-intent">button/guides/web</a><a href="https://developer.twitter.com/en/docs/twitter-for-websites/tweet-button/guides/web-intent">–</a><a href="https://developer.twitter.com/en/docs/twitter-for-websites/tweet-button/guides/web-intent">intent</a>
















<h3>Figure 10: Trade Dialog</h3>

<strong> </strong>




<h3>Figure 11: Trade Success Message</h3>




The Trade button in the <strong>Portfolio section </strong>opens a new dialog box for trading (Figure 10). The dialog shows an input box which only accepts numeric input. Below the input field, there is a calculation text box which updates based on the numeric input to display the final price of the trade. The trade dialog also displays the current available amount to trade for the user. The user can either buy or sell the shares. Based on the trade, the amount available to trade will be updated accordingly. There are 5 error conditions to be checked before executing the trade and displaying the trade successful dialog (Figure 11).  The error conditions are:




<ul>

 <li><strong><em>Users try to sell more shares than they own</em></strong><em> – </em>The trade dialog box should remain open and a toast message with text ‘Not enough shares to sell’ should be displayed.</li>

 <li><strong><em>User tries to buy more shares than money available – </em></strong>The trade dialog box should remain open and a toast message with text ‘Not enough money to buy’ should be displayed.</li>

 <li><strong><em>User tries to sell zero or negative shares – </em></strong>The trade dialog box should remain open and a toast message with text ‘Cannot sell less than 0 shares’ should be displayed.</li>

 <li><strong><em>User tries to buy zero or negative shares – </em></strong>The trade dialog box should remain open and a toast message with text ‘Cannot buy less than 0 shares’ should be displayed.</li>

 <li><strong><em>User enters invalid input like text or punctuations – </em></strong>The trade dialog box should remain open and a toast message with text ‘Please enter valid amount’ should be displayed.</li>

</ul>




5.3.1 HighCharts in Android

The <strong>Chart section </strong>in the detailed stock information screen uses a <em>WebView </em>element to load the HighCharts stock chart (same as homework #8). It provides the same features as Homework #8 and the JavaScript code for loading the chart can be reused. To load the chart, the App will load a local HTML file with the necessary JavaScript to request the data from the NodeJS server and display the chart when the data is fetched (See the <u>hints</u>).

<strong> </strong>

<strong>Note: All the Images needed to display the section heading icons as well as the 3 tabs are provided in the zip file for Homework #9. </strong>

<h2>5.4 Progress bar</h2>

Every time the user has to wait before they can see the data, you must display a progress bar as shown in Figure 4. The progress bar is to be present across the <strong>Home screen, Detailed Stock screen </strong>and just says “Fetching Data…”. One idea would be to display the progress bar by default (where needed) and then hide it as soon as the data is received/view is prepared. See <u>hints</u> for progress bar related ideas and styling.




<strong><u>Note:</u></strong> <strong>Based on your implementation, you might need to put progress bars on different places. During the demo, there should NOT be any screen with default/dummy/placeholder values or an empty screen.</strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong> </strong>

<h2>5.5 Summary of detailing and error handling</h2>

<ol>

 <li>Make sure there are no conditions under which the app crashes</li>

 <li>Make sure all icons and texts are correctly positioned as in the video/screenshots</li>

 <li>Make sure the screens and toasts are correctly displayed.</li>

 <li>Make sure there is a progress bar every time there is nothing to show Make sure the styling for different features matches the video/screenshots.</li>

 <li>All API calls are to be made using Node.js backend.</li>

</ol>

<h2>5.6 Additional Info</h2>

For things not specified in the document, grading guideline, or the video, you can make your own decisions. But keep in mind about the following points:

<ul>

 <li>Always display a proper message and do not crash if an error happens.</li>

 <li>You can only make HTTP/HTTPS requests to your backend Node.js on GAE/AWS/Azure.</li>

 <li>All HTTP requests should be asynchronous and should not block the main UI thread. You can use third party libraries like Volley to achieve this in a simple manner</li>

 <li></li>

 <li>6. Implementation Hints</li>

</ul>

6.1 Icons

The images used in this homework are available in the zip file mentioned in the Piazza post for Homework #9.

You can choose to work with xml/png/jpg versions. We recommend using xml as it is easy to modify colors by setting the Fill Colors.

6.2 Third party libraries

Sometimes using 3<sup>rd</sup> party libraries can make your implementation much easier and quicker. Some libraries you may have to use are:

<h2>6.2.1 Volley HTTP requests</h2>

Volley can be helpful with asynchronous http request to load data. You can also use Volley network ImageView to load photos in Google tab. You can learn more about them here: <a href="https://developer.android.com/training/volley/index.html">https://developer.android.com/training/volley/index.html</a>

<h2>6.2.2 Picasso</h2>

Picasso is a powerful image downloading and caching library for Android.  <a href="https://square.github.io/picasso/">http://square.github.io/picasso/</a>




If you decide to use RecycleView to display the photos with Picasso Please use version 2.5.2 since the latest version does not support RecycleView well. <a href="https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Picasso-Library">https://github.com/codepath/android_guides/wiki/Displaying</a><a href="https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Picasso-Library">–</a><a href="https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Picasso-Library">Images</a><a href="https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Picasso-Library">–</a><a href="https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Picasso-Library">with</a><a href="https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Picasso-Library">–</a><a href="https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Picasso-Library">the</a><a href="https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Picasso-Library">–</a><a href="https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Picasso-Library">Picasso</a><a href="https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Picasso-Library">–</a><a href="https://github.com/codepath/android_guides/wiki/Displaying-Images-with-the-Picasso-Library">Library</a>

<h2>6.2.3 Glide</h2>

Glide is also a powerful image downloading and caching library for Android. It is similar to Picasso. You can also use Glide to load photos in Google tab.

<a href="https://bumptech.github.io/glide/">https://bumptech.github.io/glide/</a>

6.3 Working with action bars and menus

<a href="https://developer.android.com/training/appbar/setting-up">https://developer.android.com/training/appbar/setting</a><a href="https://developer.android.com/training/appbar/setting-up">–</a><a href="https://developer.android.com/training/appbar/setting-up">up</a>

<a href="https://stackoverflow.com/questions/38195522/what-is-oncreateoptionsmenumenu-menu">https://stackoverflow.com/questions/38195522/what</a><a href="https://stackoverflow.com/questions/38195522/what-is-oncreateoptionsmenumenu-menu">–</a><a href="https://stackoverflow.com/questions/38195522/what-is-oncreateoptionsmenumenu-menu">is</a><a href="https://stackoverflow.com/questions/38195522/what-is-oncreateoptionsmenumenu-menu">–</a><a href="https://stackoverflow.com/questions/38195522/what-is-oncreateoptionsmenumenu-menu">oncreateoptionsmenumenu</a><a href="https://stackoverflow.com/questions/38195522/what-is-oncreateoptionsmenumenu-menu">–</a><a href="https://stackoverflow.com/questions/38195522/what-is-oncreateoptionsmenumenu-menu">menu</a>

6.4 Displaying Progress Bars

<a href="https://stackoverflow.com/a/28561589">https://stackoverflow.com/a/28561589</a>

<a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">https://stackoverflow.com/questions/5337613/how</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">–</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">to</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">–</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">change</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">–</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">color</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">–</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">in</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">–</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">circular</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">–</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">progress</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">–</a><a href="https://stackoverflow.com/questions/5337613/how-to-change-color-in-circular-progress-bar">bar</a>

6.5 Implementing Splash Screen

There are many ways to implement a splash screen. This blog highlights almost all of them with examples: <a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">https://android.jlelse.eu/the</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">–</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">complete</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">–</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">android</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">–</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">splash</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">–</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">screen</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">–</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">guide</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">–</a><a href="https://android.jlelse.eu/the-complete-android-splash-screen-guide-c7db82bce565">c7db82bce565</a>

6.6 Adding the App Icon

<a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">https://dev.to/sfarias051/how</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">–</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">to</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">–</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">create</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">–</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">adaptive</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">–</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">icons</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">–</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">for</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">–</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">android</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">–</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">using</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">–</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">android</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">–</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">studio</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">–</a><a href="https://dev.to/sfarias051/how-to-create-adaptive-icons-for-android-using-android-studio-459h">459h</a>

6.7 Adding ellipsis to long strings

<a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">https://stackoverflow.com/questions/6393487/how</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">can</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">i</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">show</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">ellipses</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">on</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">my</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">textview</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">if</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">it</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">is</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">greater</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">than</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">the</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">1</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">–</a><a href="https://stackoverflow.com/questions/6393487/how-can-i-show-ellipses-on-my-textview-if-it-is-greater-than-the-1-line">line</a>

6.8 Adding a button to ActionBar

<a href="https://developer.android.com/training/appbar/actions">https://developer.android.com/training/appbar/actions</a>

<a href="https://stackoverflow.com/questions/12070744/add-back-button-to-action-bar">https://stackoverflow.com/questions/12070744/add</a><a href="https://stackoverflow.com/questions/12070744/add-back-button-to-action-bar">–</a><a href="https://stackoverflow.com/questions/12070744/add-back-button-to-action-bar">back</a><a href="https://stackoverflow.com/questions/12070744/add-back-button-to-action-bar">–</a><a href="https://stackoverflow.com/questions/12070744/add-back-button-to-action-bar">button</a><a href="https://stackoverflow.com/questions/12070744/add-back-button-to-action-bar">–</a><a href="https://stackoverflow.com/questions/12070744/add-back-button-to-action-bar">to</a><a href="https://stackoverflow.com/questions/12070744/add-back-button-to-action-bar">–</a><a href="https://stackoverflow.com/questions/12070744/add-back-button-to-action-bar">action</a><a href="https://stackoverflow.com/questions/12070744/add-back-button-to-action-bar">–</a><a href="https://stackoverflow.com/questions/12070744/add-back-button-to-action-bar">bar</a>

6.9 Implementing a Recycler view in android

<a href="https://developer.android.com/guide/topics/ui/layout/recyclerview">https://developer.android.com/guide/topics/ui/layout/recyclerview</a> <a href="https://stackoverflow.com/a/40217754">https://stackoverflow.com/a/40217754</a>

<a href="https://abhiandroid.com/materialdesign/recyclerview-gridview.html">https://abhiandroid.com/materialdesign/recyclerview</a><a href="https://abhiandroid.com/materialdesign/recyclerview-gridview.html">–</a><a href="https://abhiandroid.com/materialdesign/recyclerview-gridview.html">gridview.html</a>

6.10 Adding Toasts

<a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">https://stackoverflow.com/questions/3500197/how</a><a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">–</a><a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">to</a><a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">–</a><a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">display</a><a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">–</a><a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">toast</a><a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">–</a><a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">in</a><a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">–</a><a href="https://stackoverflow.com/questions/3500197/how-to-display-toast-in-android">android</a>

6.11 Passing variables to intent

<a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">https://stackoverflow.com/questions/2405120/how</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">–</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">to</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">–</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">start</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">–</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">an</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">–</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">intent</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">–</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">by</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">–</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">passing</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">–</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">some</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">parameters</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">–</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">to</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">–</a><a href="https://stackoverflow.com/questions/2405120/how-to-start-an-intent-by-passing-some-parameters-to-it">it</a>

6.12 Formatting Text using HTML in TextView

<a href="https://stackoverflow.com/a/27462961">https://stackoverflow.com/a/27462961</a>




6.13 Open Link in browser

<a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">https://www.tutorialkart.com/kotlin</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">–</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">android/android</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">–</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">open</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">–</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">url</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">–</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">in</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">–</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">browser</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">–</a><a href="https://www.tutorialkart.com/kotlin-android/android-open-url-in-browser-activity/">activity/</a>




6.14 Back press behavior on Back button

<a href="https://stackoverflow.com/a/27807976">https://stackoverflow.com/a/27807976</a>




6.15 SearchBar and AutoCompleteTextView

To implement the search functionality, these pages will help: https://www.youtube.com/watch?v=9OWmnYPX1uc <a href="https://developer.android.com/guide/topics/search/search-dialog">https://developer.android.com/guide/topics/search/search</a><a href="https://developer.android.com/guide/topics/search/search-dialog">–</a><a href="https://developer.android.com/guide/topics/search/search-dialog">dialog</a>

Working with the AutoCompleteTextView to show the suggestions might be a little challenging.

This tutorial goes over how it is done to help implement it.

<a href="https://www.truiton.com/2018/06/android-autocompletetextview-suggestions-from-webservicecall/">https://www.truiton.com/2018/06/android</a><a href="https://www.truiton.com/2018/06/android-autocompletetextview-suggestions-from-webservicecall/">–</a><a href="https://www.truiton.com/2018/06/android-autocompletetextview-suggestions-from-webservicecall/">autocompletetextview</a><a href="https://www.truiton.com/2018/06/android-autocompletetextview-suggestions-from-webservicecall/">–</a><a href="https://www.truiton.com/2018/06/android-autocompletetextview-suggestions-from-webservicecall/">suggestions</a><a href="https://www.truiton.com/2018/06/android-autocompletetextview-suggestions-from-webservicecall/">–</a><a href="https://www.truiton.com/2018/06/android-autocompletetextview-suggestions-from-webservicecall/">from</a><a href="https://www.truiton.com/2018/06/android-autocompletetextview-suggestions-from-webservicecall/">webservicecall/</a>

In order to link your Search Bar with autocomplete suggestions, these links might help:

<a href="https://www.dev2qa.com/android-actionbar-searchview-autocomplete-example/">https://www.dev2qa.com/android</a><a href="https://www.dev2qa.com/android-actionbar-searchview-autocomplete-example/">–</a><a href="https://www.dev2qa.com/android-actionbar-searchview-autocomplete-example/">actionbar</a><a href="https://www.dev2qa.com/android-actionbar-searchview-autocomplete-example/">–</a><a href="https://www.dev2qa.com/android-actionbar-searchview-autocomplete-example/">searchview</a><a href="https://www.dev2qa.com/android-actionbar-searchview-autocomplete-example/">–</a><a href="https://www.dev2qa.com/android-actionbar-searchview-autocomplete-example/">autocomplete</a><a href="https://www.dev2qa.com/android-actionbar-searchview-autocomplete-example/">–</a><a href="https://www.dev2qa.com/android-actionbar-searchview-autocomplete-example/">example/</a>

6.16 To implement favorites and portfolio sections

<a href="https://developer.android.com/reference/android/content/SharedPreferences">https://developer.android.com/reference/android/content/SharedPreferences</a> <a href="https://www.journaldev.com/9412/android-shared-preferences-example-tutorial">https://www.journaldev.com/9412/android</a><a href="https://www.journaldev.com/9412/android-shared-preferences-example-tutorial">–</a><a href="https://www.journaldev.com/9412/android-shared-preferences-example-tutorial">shared</a><a href="https://www.journaldev.com/9412/android-shared-preferences-example-tutorial">–</a><a href="https://www.journaldev.com/9412/android-shared-preferences-example-tutorial">preferences</a><a href="https://www.journaldev.com/9412/android-shared-preferences-example-tutorial">–</a><a href="https://www.journaldev.com/9412/android-shared-preferences-example-tutorial">example</a><a href="https://www.journaldev.com/9412/android-shared-preferences-example-tutorial">–</a><a href="https://www.journaldev.com/9412/android-shared-preferences-example-tutorial">tutorial</a>

6.17 Implementing Dialogs

<a href="https://mkyong.com/android/android-custom-dialog-example/">https://mkyong.com/android/android</a><a href="https://mkyong.com/android/android-custom-dialog-example/">–</a><a href="https://mkyong.com/android/android-custom-dialog-example/">custom</a><a href="https://mkyong.com/android/android-custom-dialog-example/">–</a><a href="https://mkyong.com/android/android-custom-dialog-example/">dialog</a><a href="https://mkyong.com/android/android-custom-dialog-example/">–</a><a href="https://mkyong.com/android/android-custom-dialog-example/">example/</a> <a href="https://androidexample.com/Custom_Dialog_-_Android_Example/index.php?view=article_discription&amp;aid=88&amp;aaid=111">https://androidexample.com/Custom_Dialog_</a><a href="https://androidexample.com/Custom_Dialog_-_Android_Example/index.php?view=article_discription&amp;aid=88&amp;aaid=111">–</a>

<a href="https://androidexample.com/Custom_Dialog_-_Android_Example/index.php?view=article_discription&amp;aid=88&amp;aaid=111">_Android_Example/index.php?view=article_discription&amp;aid=88&amp;aaid=111</a> <a href="https://medium.com/@suragch/creating-a-custom-alertdialog-bae919d2efa5">https://medium.com/@suragch/creating</a><a href="https://medium.com/@suragch/creating-a-custom-alertdialog-bae919d2efa5">–</a><a href="https://medium.com/@suragch/creating-a-custom-alertdialog-bae919d2efa5">a</a><a href="https://medium.com/@suragch/creating-a-custom-alertdialog-bae919d2efa5">–</a><a href="https://medium.com/@suragch/creating-a-custom-alertdialog-bae919d2efa5">custom</a><a href="https://medium.com/@suragch/creating-a-custom-alertdialog-bae919d2efa5">–</a><a href="https://medium.com/@suragch/creating-a-custom-alertdialog-bae919d2efa5">alertdialog</a><a href="https://medium.com/@suragch/creating-a-custom-alertdialog-bae919d2efa5">–</a><a href="https://medium.com/@suragch/creating-a-custom-alertdialog-bae919d2efa5">bae919d2efa5</a>

6.18 Sectioned Adapter for RecyclerView

<a href="https://github.com/luizgrp/SectionedRecyclerViewAdapter">https://github.com/luizgrp/SectionedRecyclerViewAdapter</a>

<a href="https://github.com/luizgrp/SectionedRecyclerViewAdapter/tree/master/app/src/main/java/io/github/luizgrp/sectionedrecyclerviewadapter/demo/example1">https://github.com/luizgrp/SectionedRecyclerViewAdapter/tree/master/app/src/main/java/io/githu </a><a href="https://github.com/luizgrp/SectionedRecyclerViewAdapter/tree/master/app/src/main/java/io/github/luizgrp/sectionedrecyclerviewadapter/demo/example1">b/luizgrp/sectionedrecyclerviewadapter/demo/example1</a>

<a href="https://github.com/luizgrp/SectionedRecyclerViewAdapter/blob/master/app/src/main/res/layout/section_ex1_header.xml">https://github.com/luizgrp/SectionedRecyclerViewAdapter/blob/master/app/src/main/res/layout/s </a><a href="https://github.com/luizgrp/SectionedRecyclerViewAdapter/blob/master/app/src/main/res/layout/section_ex1_header.xml">ection_ex1_header.xml</a>

<a href="https://github.com/luizgrp/SectionedRecyclerViewAdapter/blob/master/app/src/main/res/layout/section_ex1_item.xml">https://github.com/luizgrp/SectionedRecyclerViewAdapter/blob/master/app/src/main/res/layout/s </a><a href="https://github.com/luizgrp/SectionedRecyclerViewAdapter/blob/master/app/src/main/res/layout/section_ex1_item.xml">ection_ex1_item.xml</a>

<a href="https://github.com/luizgrp/SectionedRecyclerViewAdapter/blob/master/app/src/main/res/layout/fragment_ex1.xml">https://github.com/luizgrp/SectionedRecyclerViewAdapter/blob/master/app/src/main/res/layout/fr </a><a href="https://github.com/luizgrp/SectionedRecyclerViewAdapter/blob/master/app/src/main/res/layout/fragment_ex1.xml">agment_ex1.xml</a>

6.19 Rounded buttons/Images

<a href="https://stackoverflow.com/a/13872391">https://stackoverflow.com/a/13872391</a>

6.20 GridView

<a href="https://abhiandroid.com/ui/gridview#:~:text=In%20android%20GridView%20is%20a,item%20by%20clicking%20on%20it">https://abhiandroid.com/ui/gridview#:~:text=In%20android%20GridView%20is%20a,item%20by </a><a href="https://abhiandroid.com/ui/gridview#:~:text=In%20android%20GridView%20is%20a,item%20by%20clicking%20on%20it">%20clicking%20on%20it</a><a href="https://abhiandroid.com/ui/gridview#:~:text=In%20android%20GridView%20is%20a,item%20by%20clicking%20on%20it">.</a>

6.21 Using Recyclerview inside ScrollView

<a href="https://stackoverflow.com/questions/27083091/recyclerview-inside-scrollview-is-not-working">https://stackoverflow.com/questions/27083091/recyclerview</a><a href="https://stackoverflow.com/questions/27083091/recyclerview-inside-scrollview-is-not-working">–</a><a href="https://stackoverflow.com/questions/27083091/recyclerview-inside-scrollview-is-not-working">inside</a><a href="https://stackoverflow.com/questions/27083091/recyclerview-inside-scrollview-is-not-working">–</a><a href="https://stackoverflow.com/questions/27083091/recyclerview-inside-scrollview-is-not-working">scrollview</a><a href="https://stackoverflow.com/questions/27083091/recyclerview-inside-scrollview-is-not-working">–</a><a href="https://stackoverflow.com/questions/27083091/recyclerview-inside-scrollview-is-not-working">is</a><a href="https://stackoverflow.com/questions/27083091/recyclerview-inside-scrollview-is-not-working">–</a><a href="https://stackoverflow.com/questions/27083091/recyclerview-inside-scrollview-is-not-working">not</a><a href="https://stackoverflow.com/questions/27083091/recyclerview-inside-scrollview-is-not-working">–</a><a href="https://stackoverflow.com/questions/27083091/recyclerview-inside-scrollview-is-not-working">working</a>




6.22 Loading local HTML files into WebView

<a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">https://stackoverflow.com/questions/27104185/webview</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">–</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">load</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">–</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">html</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">–</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">from</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">–</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">assets</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">–</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">directory</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">–</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">and</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">send</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">–</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">data</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">–</a><a href="https://stackoverflow.com/questions/27104185/webview-load-html-from-assets-directory-and-send-data-to">to</a>

<a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">https://stackoverflow.com/questions/17180491/highcharts</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">–</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">wont</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">–</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">load</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">–</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">in</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">–</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">android</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">–</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">webview</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">–</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">on</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">android</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">–</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">4</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">–</a><a href="https://stackoverflow.com/questions/17180491/highcharts-wont-load-in-android-webview-on-android-4-x">x</a>

<a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">https://stackoverflow.com/questions/27709995/load</a><a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">–</a><a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">a</a><a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">–</a><a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">javascript</a><a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">–</a><a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">method</a><a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">–</a><a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">from</a><a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">–</a><a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">android</a><a href="https://stackoverflow.com/questions/27709995/load-a-javascript-method-from-android-webview?rq=1">webview?rq=1</a>

<a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">https://stackoverflow.com/questions/18302603/where</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">–</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">to</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">–</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">place</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">–</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">the</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">–</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">assets</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">–</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">folder</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">–</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">in</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">–</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">android</a><a href="https://stackoverflow.com/questions/18302603/where-to-place-the-assets-folder-in-android-studio">studio</a>

<a href="https://stackoverflow.com/a/4029605">https://stackoverflow.com/a/4029605</a>

6.23 Swiping to delete feature in RecyclerView <a href="https://www.journaldev.com/23164/android-recyclerview-swipe-to-delete-undo#code">https://www.journaldev.com/23164/android</a><a href="https://www.journaldev.com/23164/android-recyclerview-swipe-to-delete-undo#code">–</a><a href="https://www.journaldev.com/23164/android-recyclerview-swipe-to-delete-undo#code">recyclerview</a><a href="https://www.journaldev.com/23164/android-recyclerview-swipe-to-delete-undo#code">–</a><a href="https://www.journaldev.com/23164/android-recyclerview-swipe-to-delete-undo#code">swipe</a><a href="https://www.journaldev.com/23164/android-recyclerview-swipe-to-delete-undo#code">–</a><a href="https://www.journaldev.com/23164/android-recyclerview-swipe-to-delete-undo#code">to</a><a href="https://www.journaldev.com/23164/android-recyclerview-swipe-to-delete-undo#code">–</a><a href="https://www.journaldev.com/23164/android-recyclerview-swipe-to-delete-undo#code">delete</a><a href="https://www.journaldev.com/23164/android-recyclerview-swipe-to-delete-undo#code">–</a><a href="https://www.journaldev.com/23164/android-recyclerview-swipe-to-delete-undo#code">undo#code</a>

6.24 Drag and Reorder feature in RecyclerView

<a href="https://www.journaldev.com/23208/android-recyclerview-drag-and-drop">https://www.journaldev.com/23208/android</a><a href="https://www.journaldev.com/23208/android-recyclerview-drag-and-drop">–</a><a href="https://www.journaldev.com/23208/android-recyclerview-drag-and-drop">recyclerview</a><a href="https://www.journaldev.com/23208/android-recyclerview-drag-and-drop">–</a><a href="https://www.journaldev.com/23208/android-recyclerview-drag-and-drop">drag</a><a href="https://www.journaldev.com/23208/android-recyclerview-drag-and-drop">–</a><a href="https://www.journaldev.com/23208/android-recyclerview-drag-and-drop">and</a><a href="https://www.journaldev.com/23208/android-recyclerview-drag-and-drop">–</a><a href="https://www.journaldev.com/23208/android-recyclerview-drag-and-drop">drop</a>

































































