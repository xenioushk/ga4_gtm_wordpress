# Setup Google Analytics using Google Tag Manager

In this tutorial, we will learn how to add Google Analytics to a WordPress website through Google Tag Manager. Previously, we used to add Google Analytics code directly to a WordPress website’s header section. Now, we will handle all the functionality of Google Analytics using the Google Tag Manager code. This will enable us to manage all tracking with a single code. Additionally, Google Tag Manager allows admin users to customize the tracking settings and publish from its dashboard very easily. In the following steps, we will learn more about the settings.

## Get the GTM code

1. Log in to the Google Tag Manager site.

[Google Tag Manager](https://tagmanager.google.com/#/home)

2. Create a new account for a new website or subdomain.

![Create a new gtm account](/previews/gtm_create_account.jpg)

3. Fill up all the information properly and click on the Create button. Next, it will ask you to agree to the terms and conditions. Check the box and click the Yes button on the top of the screen.

![Add account information](/previews/add_account_info.jpg)

4. Now, Google Tag Manager will provide us with the code.

![GTM Code information](/previews/gtm_code.jpg)

5. For the WordPress, we only use the code. Using a plugin we can easily install that code on our WordPress site.

![Copy GTM Code](/previews/copy_the_gtm_code.jpg)

## Install GTM4WP WordPress plugin

1. Now, we need to install the `GTM4WP` plugin into our site.

2. Go to your site `admin panel >> plugins` area. Click add new and search for `GTM4WP`. Install and activate the plugin.

![Install GTM4WP WordPress plugin](/previews/install_GTM4WP_plugin.jpg)

3. Now navigate to `Settings>>Google Tag Manager`. In the general tab enter the code.

![Add GTM tag ID](/previews/add_gtm_tag_id.jpg)

4. Next, we will move toward a Google Analytics account and create a new account for our site.

## Google Analytics setup

1. Login to your google analytics account.

2. From the left navigation click on the `Admin` link.

![GA4 admin link](/previews/ga4_admin_link.jpg)

3. Click on the `+Create` button and click the `Account` link.

![Create new GA4 account](/previews/create_new_ga4_account.jpg)

4. Add the account name and click next.

5. Follow all the steps and provide all the information. End of these steps, you will get the Measurement ID.

6. Next, we will add the `Measurement ID` to the Google Tag Manager and connect with Google Analytics.

## Install and setup Measurement ID to GTM

1. Go to the Google Tag Manager account. Click on the `Tags` link and click the `New` button.

2. Give a name of the Tag folder and click on the `pencil` icon.

3. It will popup a new window, and click `Google Analytics` from there.

4. Next, click on the `Google Tag` link.

5. Paste the `Measurement ID` in the `Tag ID` field. Click the `Save` button.

6. Next, set up the `Triggering` section. Click on the pencil icon.

7. Click on the `All Pages` check box. Next, Click `Add` button and `Save` the settings.

8. The setup is done.

## Test and publish the task

1. Although, the setup is done, we need to test and publish the task. We will complete them in the following steps.

2. For the test, Select the `Tag` and click on the `Preview` button.

3. We have to add our website name in the popup window.

4. For improving the debugging experience, we can install `Tag Assistant Companion` Browser Extension for Google Chrome. However, it is optional.

5. If everything is set up correctly, you will see a summary like the following screenshot.

6. Now, go back to the `Google Analytics`site and click on the `Data display` link. Click on the Debug View Link.

7. The debug view link will show you the result, like the following screenshot.

8. Now, everything looks fine. So, we can publish the settings from the `Google Tag Manager`. Select the Tag checkbox and click on the Submit button.

9. Note that it is a good practice to create/update tags by the version number or date. Here is an example.

10. You can also see the update from the dashboard.
