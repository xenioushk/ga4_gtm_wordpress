# Setup Google Analytics using Google Tag Manager

In this tutorial, we will learn how to add Google Analytics to a WordPress website through Google Tag Manager. Previously, we used to add Google Analytics code directly to a WordPress website’s header section. Now, we will handle all the functionality of Google Analytics using the Google Tag Manager code. This will enable us to manage all tracking with a single code. Additionally, Google Tag Manager allows admin users to customize the tracking settings and publish from its dashboard very easily. In the following steps, we will learn more about the settings.

## Get the GTM code

1. Log in to the [Google Tag Manager](https://tagmanager.google.com/#/home) site.

2. Create a new account for a new website or subdomain.

![Create a new gtm account](/previews/gtm_create_account.jpg)

3. Fill up all the information properly and click on the `Create` button. Next, it will ask you to agree to the terms and conditions. Check the box and click the `Yes` button on the top of the screen.

![Add account information](/previews/add_account_info.jpg)

4. Now, Google Tag Manager will provide us with the code.

![GTM Code information](/previews/gtm_code.jpg)

5. In WordPress, we only use the `GTM-XXXXXX` code. Next, we'll install the WordPress plugin and add the code there. Keep reading the following steps.

![Copy GTM Code](/previews/copy_the_gtm_code.jpg)

## Install GTM4WP WordPress plugin

1. Now, we need to install the `GTM4WP` plugin into our site.

2. Go to your site `admin panel >> plugins` area. Click `Add New` link and search for `GTM4WP`. Install and activate the plugin.

![Install GTM4WP WordPress plugin](/previews/install_GTM4WP_plugin.jpg)

3. Now, navigate to `Settings>>Google Tag Manager`. In the general tab enter the code.

![Add GTM tag ID](/previews/add_gtm_tag_id.jpg)

4. Next, we will move toward a Google Analytics account and create a new account for our site.

## Google Analytics setup

1. Login to your google analytics account.

2. From the left navigation, click on the `Admin` link.

![GA4 admin link](/previews/ga4_admin_link.jpg)

3. Click on the `+Create` button and click the `Account` link.

![Create new GA4 account](/previews/create_new_ga4_account.jpg)

4. Add the account name and click next.

![GA4 add account name](/previews/google_analytics_add_account_name.jpg)

5. Follow all the steps and provide all the information. End of these steps, you will get the Measurement ID.

![Continue steps for measurement ID](/previews/continue_steps_for_measurement_id.jpg)

6. Next, we will add the `Measurement ID` to the Google Tag Manager and connect with Google Analytics.

![get the measurement ID](/previews/ga4_measurement_id.jpg)

## Install and setup Measurement ID to GTM

1. Go to the Google Tag Manager account. Click on the `Tags` link and click the `New` button.

![get the measurement ID](/previews/gtm_tag_links.jpg)

2. Give a name of the Tag folder and click on the `pencil` icon.

![get tags folder](/previews/gtm_tags_folder.jpg)

3. It will popup a new window, and click `Google Analytics` from there.

![gtm google analytics link](/previews/gtm_google_analytics_link.jpg)

4. Next, click on the `Google Tag` link.

![ga4 google tag link](/previews/ga4_google_tag_link.jpg)

5. Paste the `Measurement ID` in the `Tag ID` field. Click the `Save` button.

![Add ga4 measurement ID](/previews/add_measurement_id.jpg)

6. Next, set up the `Triggering` section. Click on the pencil icon.

![Setup triggering](/previews/setup_triggerring.jpg)

7. Click on the `All Pages` check box. Next, Click `Add` button and `Save` the settings.

![All pages for triggering](/previews/choose_all_page_for_triggering.jpg)

8. The setup is done.

![Triggering setup is done](/previews/triggering_setup_done.jpg)

## Test and publish the task

1. Although, the setup is done, we need to test and publish the task. We will complete them in the following steps.

2. For the test, Select the `Tag` and click on the `Preview` button.

![Select Tag for test](/previews/select_tag_for_test.jpg)

3. We have to add our website name in the popup window.

![Connect to our site](/previews/connect_to_our_site.jpg)

4. For improving the debugging experience, we can install [Tag Assistant Companion](https://chromewebstore.google.com/detail/tag-assistant-companion) Browser Extension for Google Chrome. However, it is optional.

![Chrome tag assistant companion](/previews/tag_assistant_companion.jpg)

5. If everything is set up correctly, you will see a summary like the following screenshot.

![GTM trigger output](/previews/gtm_trigger_output.jpg)

6. Now, go back to the `Google Analytics`site and click on the `Data display` link. Click on the Debug View Link.

![GA4 Display data](/previews/ga4_display_data.jpg)

7. The debug view link will show you the result, like the following screenshot.

![GA4 Display data](/previews/debug_view_output.jpg)

8. Now, everything looks fine. So, we can publish the settings from the `Google Tag Manager`. Select the Tag checkbox and click on the Submit button.

![Publish GTM](/previews/publish_gtm.jpg)

9. Note that it is a good practice to create/update tags by the version number or date. Here is an example.

![Update GTM code and versioning](/previews/update_gtm_code_and_versioning.jpg)

10. You can also see the update from the dashboard.

![GTM version update status](/previews/gtm_version_update_status.jpg)
