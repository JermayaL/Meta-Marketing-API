# MetaMarketingAPI v1
Using the Facebook Marketing API with Google Sheets can be beneficial for marketers who want to automate their Facebook ad campaigns and analyze their ad performance in a more efficient way.

Please copy this script: https://docs.google.com/spreadsheets/d/1pWuE2D1UN8sqPH10TRVYmmwnunRCbkRZUorqyjmIPkQ/copy

Here are some reasons why you might want to use this combination:

𝗔𝘂𝘁𝗼𝗺𝗮𝘁𝗲 𝘁𝗮𝘀𝗸𝘀: With the Facebook Marketing API, you can automate tasks like creating and editing campaigns, ad sets, and ads. By integrating this with Google Sheets, you can create a more streamlined workflow where data can be pulled and updated automatically.

𝗔𝗻𝗮𝗹𝘆𝘇𝗲 𝗮𝗱 𝗽𝗲𝗿𝗳𝗼𝗿𝗺𝗮𝗻𝗰𝗲: The Facebook Marketing API allows you to extract data on ad performance, such as impressions, clicks, and conversions. By using Google Sheets, you can easily organize this data and create custom reports and visualizations to gain insights into your ad performance.

𝗦𝗵𝗮𝗿𝗲 𝗱𝗮𝘁𝗮 𝘄𝗶𝘁𝗵 𝘁𝗲𝗮𝗺 𝗺𝗲𝗺𝗯𝗲𝗿𝘀: With Google Sheets, you can easily share data with team members, allowing everyone to access and collaborate on the same information in real-time. This can help improve communication and coordination between team members working on Facebook ad campaigns.

Overall, using the Facebook Marketing API with Google Sheets can help businesses and marketers save time, improve data analysis and reporting, and enhance collaboration between team members. You could download this from Github.

Steps:
1. Go to https://developers.facebook.com/apps;
2. Create a new app: Company > give the App a descriptive name and select your business account;
3. Set-up Marketing API > do not fulfill the set-up and go left bar to 'Tools' > now you see 3 toggles you could select. Only go for ads_read and read_insights ( permission ads_management, we also need OAuth Permissions which is a complex setup. And we don't even need ads_management permission to read reports);
4. After selecting ads_read and read_insights click 'Get Token';
5. Go back to the Google Sheet > Navigate to 'Extensions' > Apps script;
6. Put your token at 'TOKEN_HERE' and click on 'Save';
7. Click on 'Meta Marketing API' (near 'Help');
8. Click 'Refresh Ad accounts' > log into your mail > click on unsecure and give this Google sheet document permission.
9. Click again on 'Refresh Ad accounts and now it will generate all Add accounts.
10. In the first tab all Ad account will appear. In Column A you will see Follow as columnName. Select only the Ad accounts you would like to extract data into the sheet.
11. Go back to the Meta Marketing API and refresh the data sets on campaign level, ad set level and ads level.
