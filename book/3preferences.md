# 3.0 Preferences

The customization level of Publisher is very high, enabling the Webmaster to define the behavior of Publisher at a very granular level.


**SEO**

| **Item** | **Description** | **Choices** |
| --- | --- | --- |
| URL rewrite method | If you choose htaccess, then don't forget to put “.htaccess” file under your root folder | None, <br>Path-Info,<br> htaccess  |
| URL Rewriting module name | If URL Rewriting is enabled for the module, this is the name of the module that will be used. For example: http://yoursite.com/publisher/... | publisher |
| Meta Keywords|This keywords will be merged with the keywords set by articles. Use ', ' to separate them.| -- |

**Index and category pages**


||<b>Index and category pages</b>||
|---|---|---|
|Display the welcome title and message:|If this option is set to “Yes”, the module index page will display the title “Welcome in the Publisher of...”, followed by the welcome message defined below. If this option is set to “No”, none of these lines will be displayed.|Yes, No |
|Index page welcome message:|Welcome message to be displayed in the index page of the module.||
|Display the list of newly published articles?|Select “Yes” to have the list at the bottom of the first page of the module.|Yes, No|
|Index Footer|Footer that will be displayed at the index page of the module.||
||<b>Category page</b>||
|Display the category summary?|Select “No” to not display the category summary on a category page that has no subcategories.|Yes No |
|Category list image width|Specify the width of category images when listing the categories.|90|
|Category main image width|Specify the width of the category main image.|150|
||Item page||
|Title size:|Set the maximum size of the title in the single item display page.|60|
|Display comment count?|Set to “Yes” to display the comments count in the individual article.|Yes No |
|Display the poster and date?|Set to “Yes” to display the poster and date information in the individual article.|Yes No |
|Admin counter reads?|Allow administrator hits for the counter stats?|Yes No |
|Item footer|Footer that will be displayed for each article.||
|Other articles display type|Select how you would like to display the other articles of the category in the article page.|None<br> Previous & Next Article<br> All Articles|
||<b>Index and category pages</b>||
|Display sub categories|Select if you want to display the subcategories in the categories list of the index and category page of the module.|Do not display subcategorios <br> Display non-empty subcategorios <br> Display all subcategories <br> Do not display subcategories in index page, just in category page <br>|
|Display last item column?|Select “Yes” to display the last item in each category in the index and category page.|Yes No |
|Last item size:|Set the maximum size of the title in the Last item column.|50|
|Articles display type:|if “Summary View” is selected, only the Title, Date and Hits of each item will be displayed in a selected category. If “Full View” is selected, each article will be fully displayed in a selected category.|Summary View <br> Full View <br> Bullet View <br> WF-Section Style| 
|Display sub-categories description?|Select “Yes” to display the description of sub-categories in the index and category page.|Yes No |
|Display the 'Published on' column?|When the 'Summary' display type is selected, select “Yes” to display a “Published on” date in the items table on the index and category page.|Yes No |
|Display the “Hits” column?|When the “Summary” display type is selected, select “Yes” to display the “Hits” column in the items table on the index and category page.|Yes No |
|Show link for RSS feed||Yes No |
|Display the collapsible bar?|If you set this option to “Yes”, the categories summary will be displayed in a collapsible bar as well as the articles. If you set this option to “No”, the collapsible bar will not be displayed.|Yes No |
|Maximum Categories per page (User side)?|Maximum number of top categories per page to be displayed at once in the user side?|5, 10, 15, 20, 25, 30, 50|
|Maximum articles per page (Admin side):|Maximum number of articles per page to be displayed at once in the admin side.|5, 10, 15, 20, 25, 30, 50|
|Maximum articles per page (User side):|Maximum number of articles per page to be displayed together in the user side.|5, 10, 15, 20, 25, 30, 50|
|Partial view message|Message for articles that allow only partial view.|To view the complete article, you must register.|
|Display articles count|Select “Yes” to display the article count within each category in the category summary table. Please note that the module currently only counts articles within each category and does not count within subcategories.|Yes No |
||<b>Print page</b>||
|Print page header|Header that will be printed for each article||
|Logo print URL|URL of the logo that will be printed at the top of the page.<br>http://YouSite/images/logo.gif|
|Print page footer|Footer that will be printed for each article||
||<b>Format</b>||
|Date format:|Select a display style. Example: "d-M-Y H:i" translates to "30-Mar-2004 22:35" (Refer to the PHP manual for more display options)|d-M-Y H:i|
|Sort order|Select the sort order of the items throughout the module.|Date DESC <br> Dates DESC <br>Hits DESC <br>Rating DESC <br>Votes DESC <br>Comments DESC <br>Weight ASC|
|Use the image Page Navigation:|If you set this option to “Yes”, the Page Navigation will be displayed with images, otherwise, the original Page Naviagation will be used.|Yes No |
|Use the Real Name of users|When displaying a username, use the real name of that user if he has a set his real name.|Yes No |
|Highlight color for keywords|Color of the keywords highlighting for the search function.|#FFFF80|
|Enable links on the current path:|This option allows the user back-track by clicking on an element of the current path displayed on the top of the page.|Yes No |
|Show the module name in the breadcrumb?|If you select “Yes”, the breadcrumb will show "Publisher > category name > article name". <br>Otherwise, only "category name > article name" will be shown.|Yes No |
||Search page||
|Display category path in search results||	Yes No |
||Submit page||
|Submit page intro message:|Intro message to be displayed in the submit page of the module.||
|Default editor type|What kind of editor would you like to use by default? You can also allow submitters to choose editors in the permissions menu.|Plain Text<br>DHTML<br>TinyMCE|
|Editor number of rows	||35|
|Editor number of columns	||60|
|Editor width	||100%|
|Editor height	||400px|
|Select default status for submitted article	||Published<br>Offline<br>Submitted<br>Rejected|
|“Allow comments” set to TRUE||	Yes No |
|“Enable HTML tags” set to TRUE||	Yes No |
|“Enable smiley icons” set to TRUE||	Yes No |
|“Enable XOOPS codes” set to TRUE||	Yes No |
|“Enable images” set to TRUE||	Yes No |
|“Enable line break” set to TRUE||	Yes No |
||<b>Permissions</b>||
|User submissions?|Allow users to submit articles on your website?|Yes No |
|User article edit?|Allow users to edit their own articles?|Yes No |
|User article delete?|Allow users to delete their own articles?|Yes No |
|Allow anonymous posting?|Allow anonymous users to submit articles?|Yes No |
|User file upload?|Allow users to upload files linked to articles on your website?|Yes No |
|Allow article duplication?|Select “Yes” to allow users with appropriate permissions to duplicate an article.|Yes No |
|Allow rating feature|You can select who can rate in permissions tab|Yes No |
|Allow extended search feature|You can select who can search in permissions tab|Yes No |
|Allow author items feature||	Yes No |
|Control comments at the article level?|if you set this option to “Yes”, you will see comments only on those items that have their comment checkbox marked. <br>Select “No” to have comments managed at the global level (look below under the tag 'Comment rules'.|Yes No |
|Auto approve submitted articles?|Auto approves submitted articles without admin intervention?|Yes No |
||<b>Others</b>||
|Display the breadcrumb| Breadcrumb navigation displays the current page's context within the site structure.|Yes No |
|Display PDF Icon|Select Yes to show PDF icon and allow users to create PDF files|Yes No |
|Maximum file size|Maximum size (in bytes) of a file that can be uploaded.|1000000|
|Maximum uploaded image width|Maximum width of an image file that can be uploaded.|800|
|Maximum uploaded image height|Maximum height of an image file that can be uploaded.|800|
|Display block summary on items page?||	Yes No |
|Display items subtitles in index page?||	Yes No |
|Display items subtitles in categories pages?||	Yes No |
|Display item subtitle in item page?|Publisher has the option to provide "subtitles". If you're using them, do you want to display them?|	Yes No |
|Comment Rules	||- Disable Comments<br>- Comments are always approved<br>- Comments by Registered users are always approved<br>- All comments need to be approved by Admin|
|Allow anonymous comments?|Decide if you want allow anonymous users to post comments. Very often, this results in a lot of spam messages|	Yes No |
|Enable Notification|This module allows users to be notified when certain events occur. Select if users should be presented with notification options in a Block (Block-style), within the module (Inline-style), or both. For block-style notification, the Notification Options block must be enabled for this module.|Disable Notification<br> Enable only Block-style <br> Enable only Inline-style<br> Enable Notification (both styles)|
|Enable Specific Events|Select which notification events to which your users may subscribe.|Global Articles:  New category<br>  Global Articles:  Article submitted<br> Global Articles: New article published<br> Category Items: Article submitted<br> Category Items: New article published<br> Category Items: BookmarkArticle : Comment Added<br> Article: Comment Submitted<br> Article : Bookmark|
