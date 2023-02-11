---
name: Enhance Chrome App V1 
about: With the proof of concept (POF) complete, we need to enhance the chrome app to read data from an outside source. We will start with a simple JSON file. Within the file we will have specific video Id's that will correlate to specific videos within Netflix. When an Id with the JSON file matches the Netflix Id, the corresponding categories and time spans will show within the chrome addon.

title: Acceptance Criteria

* The Stream Skip (SS) extension should not load if not on a Netflix video.
* If no video Id is found within the JSON that correlates to the Netflix Id, then show a message within the SS extension stating "No entries found"
* When a video entry has been found, only show categories that have a time span entry.
* Time span entries should be shown as mm:ss  (minutes and seconds) rather than seconds.
* When viewing the next video, the previous video categories and time spans should be removed. Only the current video timespans should be shown

This task is for setting a service to consume and filter the incoming data based on the Netflix Id. The Netflix Id will be read in from the client Url.


Future Enhancements
[Add/Edit] button shoudl be avialable top left corner. No functionality at this time.
[Log in] button should be available top left corner. Nofunctionality at this time.
[Enable] button should be available top right corner. No functionality at this time.
[Default Settings] Should be shown bottom left corner. No functionality at this time.
[Reset to Defaults] Should be shown bottom right corner. No functionality at this time.


