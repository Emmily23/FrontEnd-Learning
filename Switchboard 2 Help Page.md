- DO NOT edit switchboard or syndication edges unless you are on the Network Team or have explicit permission to do so. 
- Overview
- What has changed?
- Using Switchboard
- Common Tasks
    - Clients
        - Searching for a client
        - Enabling/Disabling a Client
        - Modify BrandVoice Reports
        - Deleting a Client
    - Edges
        - Adding an Edge
        - Change Edge Settings
            - Data Settings
                - Configuring Syndication Delay Days or Stop Date
            - Display Settings
                - Uploading an attribution logo
            - Configuring All Edges Settings
        - Deleting an Edge
    - Reports
        - Live Network Report
        - Client level Network API
        - Edge Level API
        - Audit Reports
    - Brand-specific logo configuration
        - Add a brand-specific logo
        - Edit the logo for a particular brand
        - Delete the logo for a particular brand
        -Gotchas on using the brand logos feature
- Why can't I...?
    - ...see anything on the homepage (Clients page)?
    - ...find a particular client in the Clients list?
    - ...see PRR picking up my changes to a client?
    - ...click the "Create" button in the "Create New Edge" modal window?
    - ...see the edge I just created in the Edges list on a client's configuration page?
    - ...see an edge I deleted disappear from the Edges list on a client's configuration page?
    - ...upload an attribution logo?
    - ...see any list when I click to add a display code, locale, or product matching strategy?
    - ...make a display code, locale, or product matching strategy stay visible the textbox when I type it in?
    - ....see/delete/update a brand specific logo?
    - ....type in a brand name in the brand name dropdown while uploading a logo?
    - ....see the logo I uploaded (I see more than one logo in the UI when I uploaded only one?)
    - ....see a (specific brand name) in the brand name dropdown?
- Glossary

#DO NOT edit switchboard or syndication edges unless you are on the Network Team or have explicit permission to do so.
##Overview
Switchboard 2 is a syndication configuration service that allows you to set up edges between source clients and a destination clients enabling reviews and questions to be syndicated.

##What has changed?
This is a quick revamp of the previously archived help page.  Screenshots have been updated.  New feature of Syndication Stop Date is included.



##Links to Switchboard

 - SB 2.0 QA
 - SB 2.0 Staging
 - SB 2.0 Production



##Using Switchboard
The following are the actions you can perform using Switchboard 2.0

 1. Navigate to an existing client
 2. Add or view edges. Note that this also includes display properties and uploading attribution logos.
 3. Modify edges.
 4. Configure Brandvoice reports for a client
 5. Generate live edges report and edge audit report
 6. Enable or disable a client
 7. Delete clients
 8. Delete edges
 9. Search for a client by name or platform type
 10. Search for edges based on the source client name, destination client name
 11. Filter by fully configured and misconfigured edges
 12. Configure brand logos

#Common Tasks
##Clients
###Searching for a client
There is a search bar on the top right corner of the home page that allows the user to search for clients by name.
![Image of search bar on Switchboard](https://www.google.co.uk/search?q=food&hl=en-GB&tbm=isch&source=hp&biw=1680&bih=845&ei=eExMYbWfJciC8gLP66qAAQ&oq=food&gs_lcp=CgNpbWcQAzIICAAQgAQQsQMyCAgAEIAEELEDMggIABCABBCxAzIICAAQgAQQsQMyBQgAEIAEMggIABCABBCxAzIICAAQgAQQsQMyCAgAELEDEIMBMgsIABCABBCxAxCDATIICAAQgAQQsQNQrA5Y-hFgiRNoAXAAeACAAUCIAeoBkgEBNJgBAKABAaoBC2d3cy13aXotaW1nsAEA&sclient=img&ved=0ahUKEwi1u-3O55TzAhVIgVwKHc-1ChAQ4dUDCAc&uact=5#imgrc=AhZbOQLcBbxfTM)


As you type in a client's name, the list of clients on the home page will change to reflect possible matches.



You can filter by conversations clients or PRR clients if needed.



You can also sort by any column by selecting the column header.







####Enabling/Disabling a Client
A client is enabled if it is configured to send syndication configuration settings to PRR. A disabled client does not send data to PRR. New clients are added automatically by syncing with Rosetta clients on a regular basis (every 30 minutes).  New clients are enabled by default.

From the clients page, locate the client you want to enable or disable. You can click through the pages or use the search bar at the top right of the screen to find the client. Find the "Enabled" column. Under that column for your client you'll see either a red "x" button if it is not enabled or a green checkmark button if it is enabled.



Click the button. There will be a pop-up message asking you to confirm enabling or disabling the client. Click the appropriate button to enable or disable the client.



You should see that your client's "Enabled" column button has switched to be the opposite of what it was.

####Modify BrandVoice Reports
Search for the client that you want to configure reports for. Click on the client's name. You will be redirected to that client's configuration page.

In the top right corner of the page is a gray button with a cog wheel on it. Click this button. A drop-down menu appears. Click "Reports".




A modal window will appear with a list of BrandVoice reports. If they are enabled for that client, there will be a checkmark in the box next to the report.




Select the reports you want enabled for this client, and then click "Save Changes". The modal window will disappear.

####Deleting a Client
When you delete a client, you delete all of the client's settings, including any syndication edges or displays configured for that client.

Search for the client you want to delete.

Hover your mouse over that client's row in the Clients table. You should see a red trashcan icon appear on the far right side of the row.



Click the trashcan button. A message will pop up that asks if you are sure you want to delete the client. If you are sure, click the "Delete Configuration" button.



You should no longer see that client in the UI. If you do, try refreshing the page.

###Edges
####Adding an Edge
You can add an edge between any two clients that exist in Switchboard 2. The following instructions explain how to quickly create a syndication edge.

From the Clients page, click on either of the clients that will be part of the edge. That client's page will load, showing a list of edges that the client is part of.

Click the "Add New Edge" button at the bottom of the screen below the Edges table.

Choose the source and destination client for the edge you are creating. One of the clients you select must be the client whose page you are viewing. Start typing and a drop-down box will appear to help you enter the clients' names correctly.

Click "Create". The button will not be clickable until you provide valid client names.


You should see your new edge appear in the Edges table. If you don't, try refreshing the page or searching for it with the search bar at the top of the page.

When you create an edge, default properties are set on the edge for you, and the edge is fully configured.. To change any properties, see the Change Edge Settings section.

###Change Edge Settings
From the Clients page, click on one of the clients that is part of the edge you want to modify. (E.g. if the edge is between Scotts and Sears, click on either of those clients). You will be redirected to that client's page.



Find your edge in the Edges table, either by paging through or by searching with the search bar and filter options. Click on the edge.



The edge will expand to show its configuration options, including its display options.





You'll notice there are two sections: Data Settings and Display Settings. Data settings have to do with configuring the syndication of data for the edge. Display settings configure the display on the destination client's side of the edge.

#####Data Settings


Configuring Syndication Delay Days or Stop Date
A radio button selection can be made to chose either Syndication Delay Days or Syndication Stop Date.

Syndication Delay Days is a number field allowing value of 0 or greater.  This indicates how many days before a native review on the source client can be syndicated to the destination client.  When an edge is created, by default Syndication Delay Days is selected with a value of 7 days.



Syndication Stop Date is a date field that indicates when to stop syndicating reviews to the destination client. Reviews submitted before this date will continue to be syndicated.

To add a stop date, first select the Syndication Stop Date radio button.



Click on the date field to display the date input box.  You can either manually enter the date or use the date picker () to select a date.



After entering a date, click the check button to chose the date.



NOTE: The updated date may not show until you save the edge and refresh the page.

Display Settings


Uploading an attribution logo
To upload an attribution logo, press the "Upload File" button under the Attribution Logo header. A window will pop up for you to select your file. Attribution logos can only be 300px wide x 100px tall.



If there is a problem in uploading your image, you will be given a warning pop up followed by red message under the "Upload File" button:







When you've finished editing ANY set of properties on the edge, click the green "Save Edge Settings" button in the lower right-hand corner of the properties box. If you don't click this button, your changes won't be saved!





Configuring All Edges Settings
An “Apply All” option is located within the gear icon on the top left corner of client’s page:





You can chose to update either Display Codes or Source Display Name for all edges for this client.

Make change to one of these properties as you would on each individual edge, then click “Apply All” to apply the changes to all of current client’s edges. Note the “Apply All” button is disabled until valid property changes have been made. Click “Cancel” or close icon to cancel the changes and close the modal.

– Display Codes















– Source Display Name:







Deleting an Edge
From the Clients page, click on one of the clients that is part of the edge you want to delete. (E.g. if the edge is between Scotts and Sears, click on either of those clients). You will be redirected to that client's page.




Find the edge you want to delete in the Edges table, either by paging through or by searching with the search bar and filter options.



Click the red trashcan button on the right side of the edge's row in the table. A modal will pop up.





If you are sure you want to delete the edge, click "Delete Edge Configuration". You should see your edge disappear from the Edges table, if not try refreshing the page.

Reports
Live Network Report
The live network report is a list of all the live edges in the network-- the ones that have syndication fully configured and turned on.  Edges that are not source and destination enabled will not appear, nor will edges belonging to a disabled client.  For every live edge, the report includes the source client, the destination client, enabled product matching strategies, edge status (should always be enabled), the date the edge was last modified, the content types defined on the edge, and the included and excluded locales.  The report can be generated by either directly hitting our API or via the Switchboard UI:

Via the API using a browser or via CURL:  
GET  /api/reporting/livenetwork/snapshot
The response you get back will be a report in JSON format.



Via the UI:
From the Clients page, click the cog wheel button in the top right corner of the screen and select "Generate Live Network Report"



A modal window will pop up informing you that, that generating the report is intensive for Switchboard.  If you are sure you want to generate it, click "Generate Anyway".  The report will be a tab-delimited CSV file and will be downloaded to your computer.





###Client level Network API
This API provides access to all the live edges per client, where the client is the source or the destination. The API returns data in a JSON format and can be obtained by issuing the following command via CURL or a browser

    [SB2_URL]/api/reporting/livenetwork/client/[CLIENT_ID]
    curl -XGET [SB2_URL]/api/reporting/livenetwork/client/[CLIENT_ID]

###Edge Level API
Given a source and a destination, returns the status of whether the edge is live.

    [SB2_URL]/api/reporting/livenetwork/edge/[SOURCE]:[DESTINATION]
    curl -XGET [SB2_URL]/api/reporting/livenetwork/edge/[SOURCE]:[DESTINATION]


###Audit Reports
To get the history of a client, edge, or display, you can generate an audit history report.  These reports detail all the changes made to that client, edge, or display, along with the time each action was done and the name of the use who did the action.  An audit report can be generated via the API or the UI, and includes the following fields: timestamp, username of the person who did the action, client id or source and destination id of the edge, the record type (client, edge, or display), the action taken (create, modify, or delete), and the details of the action.  The API returns a report in JSON format, while the UI returns a report in a tab-delimited CSV file.

Via the API (HTTP):
GET /api/reporting/audithistory/{client, edge, or display}/{clientId, edgeId, or displayId}
ex: /api/reporting/audithistory/client/2000flushes
Request Parameters:

startDate - optional - A string in the form of YYYY-MM-DD which retrieves all records beginning on this date (inclusive).
endDate - optional - A string in the form of YYYY-MM-DD which retrieves all records ending on this date (inclusive).
Example Response:

{
date: "2014-05-21T02:38:38",
data: [
{
timestamp: "2014-05-20T00:43:34",
username: "aoudenne",
type: "client",
client: {
~table: "switchboard:client2",
~id: "2000flushes"
},
sourceClient: null,
destinationClient: null,
action: "create",
details: "DisplayConfig(client=Reference(table=switchboard:client2, id=2000flushes), sourceClientName=3m-animalcare, sourceDisplayName=, displayCodes=[], displayOrder=0, maxSyndicatedSummaries=0, logoImageName=, contentConfigurations=[DisplayConfig.ContentConfiguration(contentType=REVIEW, contentTruncationEnabled=false, showAttribution=false, showLogo=true, useAttributionLink=false, syndicationDisplayType=INLINE)])"
}
}

Via the UI:
To generate a client report:
From a client page, click the cog wheel button in the top right corner and select "Generate Client Audit Report" from the dropdown menu.





A modal will pop up.  If desired, select the dates for the start and end of the report.  If you are sure you want to generate the report, click "Generate Anyway".  A tab-delimited CSV file will be downloaded to your computer.





















To generate an edge report:
From a client page, expand the edge for which you want to generate the report and click the "Edge Audit" button located next to the green "Save Edge Settings" button.  A modal will pop up.  Follow the instructions above to finish generating the report.






Brand-specific logo configuration
The Switchboard UI allows you to configure brand-specific logos for a client.

Add a brand-specific logo
From a client page, click the cog wheel button in the top right corner and select "Configure brand logos" from the dropdown menu.



Clicking on the menu option loads the logo configuration page for that client. If that client already has brand logos, those are displayed. There is a dropdown at the bottom right which is a type-ahead list of the brands present in the clients catalog. Select a brand from this dropdown

Note: You cannot free-form type a brand name in that dropdown. You must choose a value from the dropdown



A file upload dialog pops up that allows you to upload an image file from your local file system. The image needs to be no more than 300px * 100px and must be either JPEG, JPG, GIF, PNG images.



Once an image is selected, click on Open, which uploads the image.  Wait while the image uploads. After the image uploads it is displayed in the UI



Edit the logo for a particular brand
Click on the Edit button on the row of the brand name that your want to change.















A file upload modal pops up as before. Upload the new logo, wait for it to upload. You should see the new logo once its finished uploading.

Delete the logo for a particular brand
Click on the Delete button on the row of the brand name that your want to delete.















When you click the Delete button, a confirmation modal pops up asking you to confirm if you really want to delete the logo. Click "Delete logo" if you are sure and "I changed my mind" if you want to cancel.



















The logo will now be deleted

####Gotchas on using the brand logos feature
There is no way to free form type a brand name in the dropdown as mentioned above. You must select a brand name from the dropdown
If there are no values in the dropdown, you will not be able to type in your own values
##Why can't I...?
- ...see anything on the homepage (Clients page)?
You must be logged into the UI using your ldap username and password. If you don't get a prompt asking you for this information, try closing your browser program and restarting it.

- ...find a particular client in the Clients list?
Try using the search bar in the upper right-hand corner of the page. You can also filter by PRR or CV (Conversations) client. There may be multiple pages of clients matching your search term, so don't forget to use the pagination bar under the filter options. You can also try sorting by clicking the column header of the column you want to sort by.

- ...see PRR picking up my changes to a client?
Is the client enabled? Check to make sure that there is a green checkmark button under the "Enabled" column for this client in the Clients list. If the client is enabled, make sure you pressed the "Save Edge Settings" button for every edge you modified in the client's configuration page.

- ...click the "Create" button in the "Create New Edge" modal window?
The button won't be clickable until you enter a valid source and destination client.  You can only create edges to clients that are already in Switchboard.  Additionally, you can't create an edge where

    - PowerReviews is the source client
    - the source and destination client match
    - the source or destination client is empty
    - the source or destination client doesn't match any of the options in the dropdown list of possible clients
    - neither the source nor the destination client is the client whose configuration page you are on
- ...see the edge I just created in the Edges list on a client's configuration page?
Try clicking on the "Last Modified" column to sort the edges by date.  Try paging through the edges using the pagination bar underneath the search filter options. You can also use the search bar to search for one of the clients of the edge. Otherwise, try refreshing the page.

- ...see an edge I deleted disappear from the Edges list on a client's configuration page?
Try refreshing the page.

- ...upload an attribution logo?
You can only upload images, so first check that the file type of your attribution logo is a .gif, .png, or .jpg or .jpeg. There is also a size limit on attribution logos: they must be no larger than 300px wide x 100px tall. Ensure that your attribution logo meets these size requirements.

- ...see any list when I click to add a display code, locale, or product matching strategy?
If the field is not read-only, all of the possible options for that field have already been chosen, and there are no more available to add.

- ...make a display code, locale, or product matching strategy stay visible the textbox when I type it in?
Only the pre-defined options for that field can be entered. Try selecting an option from the drop-down list that appears when you click on the textbox. If you don't see the option you are expecting, contact the Switchboard team.

- ....see/delete/update a brand specific logo?
It might take a while for the logo to show up. If you didn't see an error message when you uploaded the logo or deleted or attempted to update it, the action was successful. Try refreshing after a couple of minutes and if you still don't see what you expect, file a ticket for the SB project.

- ....type in a brand name in the brand name dropdown while uploading a logo?
This is intentional. This feature working is very much dependent on having the logo configured for the right brand name and the right brand external ID.

- ....see the logo I uploaded (I see more than one logo in the UI when I uploaded only one?)
The dropdown that you used to upload brand logos surfaces the brand names. Clients sometimes reuse the same brand names across their catalog. External IDs for brands however are unique. If you use a brand name "samsung" we have no way of identifying if you meant "samsung with external ID A" or "samsung with external ID B". To avoid any confusion we upload the same logo for both external ID A and B. If you don't want that to happen, simply delete the logo after its finished uploading or change it to another logo if that is the desired behavior.

- ....see a (specific brand name) in the brand name dropdown?
Switchboard uses the Catalog Lookup Service (CLS) API to get brand information. If you don't see a brand that you would expect to see in the dropdown, check the response of the CLS API.

    - SB2 Bazaar (Production) talks to CLS Bazaar:  You will need API keys to use this API.  Ask the SB2 developers to help you out with this
    - Other SB2 environments talk to CLS Anon environment. Use the API call below and replace [client_id] with the client that you are trying to upload logos for
        - https://catalog-lookup-service-anon.qa.us-east-1.nexus.bazaarvoice.com/1/brands/[client_id]?limit=0
If you don't get a response back from that API endpoint in a reasonable amount of time (roughly 5 seconds) it might mean that the CLS service is down, which will prevent you from configuring logos. Contact the SB2 team ("Switchboard" hipchat) or use the Hipchat room "Rogue Squadron" to ask for status on CLS.
###Glossary
- Edge: A syndication relationship between two clients in which the source clients sends content to the destination client, who displays that content.
- Fully-Configured: An edge is fully configured if the source client is set up to syndicate to the destination client, and the destination client is configured to receive syndication content from the source clients.
- Misconfigured: An edge is misconfigured if client A is configured to syndicate with client B, but client B is not set up for syndication with client A.
- Source: A client that is set up to send syndication content to another client.
- Destination: A client that is set up to receive syndication content from another client
- Enabled: A client sends syndication configurations to PRR.
- Disabled: A client does not send syndication configurations to PRR.


