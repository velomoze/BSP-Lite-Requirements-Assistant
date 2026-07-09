|   |   |
|---|---|
|**[[lite] History & Nauvoo (2026 Q2)](https://icseng.atlassian.net/browse/CCDCON-1182)** ([CCDCON-1182](https://icseng.atlassian.net/browse/CCDCON-1182))<br><br>### ![](data:image/gif;base64,R0lGODlhEAAQAIAAAJkAAP///yH5BAUUAAEALAAAAAAQABAAAAIYjB+Ay+3vFERy2vtqgnpnCYRYl2HmiS4FADs=)[WEBCON-4865] [B.Lite\| New Single Track Audio Player](https://icseng.atlassian.net/browse/WEBCON-4865) Created: 23/Mar/26  Updated: 06/May/26|   |
|**Status:**|In Dev|
|**Project:**|[Web Consolidation](https://icseng.atlassian.net/secure/BrowseProject.jspa?id=10269)|
|**Components:**|None|
|**Affects versions:**|None|
|**Fix versions:**|None|
|**Parent:**|[[lite] History & Nauvoo (2026 Q2)](https://icseng.atlassian.net/browse/CCDCON-1182)|

|   |   |   |   |
|---|---|---|---|
|**Type:**|User Story|**Priority:**|P2 - Medium|
|**Reporter:**|[Jeff Mousley](https://icseng.atlassian.net/secure/ViewProfile.jspa?accountId=712020%3A2ca27b42-2e7d-4a4e-be5c-81ce662ebd0b)|**Assignee:**|[Natalia Shelley](https://icseng.atlassian.net/secure/ViewProfile.jspa?accountId=712020%3A794db19f-0d72-4f42-85be-c3aa3d8c62e6)|
|**Resolution:**|Unresolved|**Votes:**|0|
|**Labels:**|AudioPlayer, CCDWebTheme, DesignComplete, WebCon|   |   |
|**Remaining Estimate:**|Not Specified|   |   |
|**Time Spent:**|Not Specified|   |   |
|**Original estimate:**|Not Specified|   |   |

|   |   |
|---|---|
|**Attachments:**|![PNG File](data:image/gif;base64,R0lGODlhEAAQAMQAAP////f39/Pz8+rq6uLi4tra2tLS0srKysXFxbm5ubGxsa2trZiYmJSUlJCQkIyMjIiIiISEhHt7e3d3d3Nzc29vb////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEHABYALAAAAAAQABAAAAVhoCWOZGkFDaWurNqg0ADMdF1EKVHbdFFRO5qj4qCpgrNJZWIEAg4R3czgMDQBCdUDOVMpWAlaILEIAFor3WDRaCDOaMrj0K4H4irII8KXMCgOeCwSEg0CgYIuASaMjY4iIQA7)image-20260413-140622.png     ![PNG File](data:image/gif;base64,R0lGODlhEAAQAMQAAP////f39/Pz8+rq6uLi4tra2tLS0srKysXFxbm5ubGxsa2trZiYmJSUlJCQkIyMjIiIiISEhHt7e3d3d3Nzc29vb////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEHABYALAAAAAAQABAAAAVhoCWOZGkFDaWurNqg0ADMdF1EKVHbdFFRO5qj4qCpgrNJZWIEAg4R3czgMDQBCdUDOVMpWAlaILEIAFor3WDRaCDOaMrj0K4H4irII8KXMCgOeCwSEg0CgYIuASaMjY4iIQA7)image-20260413-213510.png     ![PNG File](data:image/gif;base64,R0lGODlhEAAQAMQAAP////f39/Pz8+rq6uLi4tra2tLS0srKysXFxbm5ubGxsa2trZiYmJSUlJCQkIyMjIiIiISEhHt7e3d3d3Nzc29vb////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEHABYALAAAAAAQABAAAAVhoCWOZGkFDaWurNqg0ADMdF1EKVHbdFFRO5qj4qCpgrNJZWIEAg4R3czgMDQBCdUDOVMpWAlaILEIAFor3WDRaCDOaMrj0K4H4irII8KXMCgOeCwSEg0CgYIuASaMjY4iIQA7)image-20260415-164807.png     ![PNG File](data:image/gif;base64,R0lGODlhEAAQAMQAAP////f39/Pz8+rq6uLi4tra2tLS0srKysXFxbm5ubGxsa2trZiYmJSUlJCQkIyMjIiIiISEhHt7e3d3d3Nzc29vb////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEHABYALAAAAAAQABAAAAVhoCWOZGkFDaWurNqg0ADMdF1EKVHbdFFRO5qj4qCpgrNJZWIEAg4R3czgMDQBCdUDOVMpWAlaILEIAFor3WDRaCDOaMrj0K4H4irII8KXMCgOeCwSEg0CgYIuASaMjY4iIQA7)image-20260415-164534.png|
|**Epic Link:**|[[lite] History & Nauvoo (2026 Q2)](https://icseng.atlassian.net/browse/CCDCON-1182)|
|**Acceptance Criteria:**|- An audio player can be added to a generic page with an audio file, podcast, or music recording attached.<br>- Only 1 file can be attached to the audio player.<br>- All the controls on the audio player work as expected - volume, playback speed, play/pause, jump forward 10 seconds, jump backward 10 seconds, and the scrubber.<br>- All the controls are accessible using the keyboard.|
|**Severity:**|S2 - Medium|
|**Team:**||
|**Ranking:**|none|
|**Requester:**|Marshall Tapp|
|**Story Points:**|10|
|**Developer Estimate:**|8|
|**QA Estimate:**|2|
|**Sprint:**|Webcon Japan 162 - 6 May|
|**Assigned Designer:**|Scott Raney|

|   |   |
|---|---|
|**Description**||

|   |
|---|
|**Found a Single Audio Track Module used by small sites. We need to add it to Web and style it for our use.**<br><br>Church History is requesting an audio player for a single audio file. They want something much more compact than the album player.<br><br>We need an Audio Player component that just plays one audio file. Album and Audio List do not cover this scenario.<br><br>**Figma:** [https://www.figma.com/design/LVvES3zJMJhKJpmAbGcJjt/BSP-Lite-Documentation-Imagery?node-id=2007-4673&t=N08wB2adJuXYQlZb-4](https://www.figma.com/design/LVvES3zJMJhKJpmAbGcJjt/BSP-Lite-Documentation-Imagery?node-id=2007-4673&t=N08wB2adJuXYQlZb-4 "smart-link")<br><br>### Style Tab Requirements<br><br>- Vertical Spacing<br><br>- Single select dropdown. <br>- Options are None (0px), Unite (16px), Related (32px), Separated Small (64px), Separated Large (128px), 4px, 8px, 96px.<br>- Default to Separated Small (64px).<br><br>- Hide Image<br><br>- Boolean, default to false<br><br>- Component Width<br><br>- Single select dropdown. <br>- Options are Read (672px), Pop (1024px)<br>- Default to Read<br><br>- Hide from In Page Navigation (boolean) Default to False<br><br>### Front End Requirements<br><br>- Display the audio file Image if one exists and the Hide Image is set to False. If an image does not exist or the Hide Image is set to true, do not display any image.<br>- Display the Album name if available. Start justified. This is the Album field on the audio asset.<br>- Display the Audio Track Name in h5, Start justified. This is the Title of the audio asset.<br>- Display the Artist Name if available. Start justified. This is the Lyricists field on the audio asset.<br>- Display an ellipsis icon. Selecting the ellipsis opens a small modal with a download icon and localized text to Download. Selecting the Download downloads the audio file to the user’s computer. Make the entire modal the click target.<br><br>- Display a scrubber bar with a knob at the current location within the audio file playback. Also show the current time and total time of the track.<br>- Display a volume control icon. Selecting the icon opens a vertical scrubber where the user can adjust the volume. Make sure it is keyboard accessible.<br>- The volume icon should change to the muted icon if the volume is turned all the way down or is muted per the computer’s volume mute setting.<br><br>- Playback Speed<br><br>- Display a gear icon.<br>- Selecting the gear icon opens a scrubber of the available playback speeds.<br>- A scrubber with a range of .5 to 3 is what Eden uses. This is what is desired. Make sure it is keyboard accessible. Steps for keyboard are every .25x.<br><br>- Display controls to skip forward or backward 10 seconds.<br>- Display a play/pause icon button.<br>- Ensure all the standard style options work as expected. This is the Vertical Spacing, Component Width, and Hide from In-page Navigation.<br>- If the audio file fails to load, display the component with the localized message “Audio file failed to load.”<br>- If there is a page navigation on the page and the Hide from In Page Navigation is set to true, do not add the player to the Page Navigation.<br><br>### Accessibility Considerations<br><br>- Use <audio> for compatibility with assistive technology.<br>- Full keyboard support. All settings must be accessible with the keyboard. Tab order should be logical.<br>- The scrubber should use role=”slider” and use the keyboard to adjust the scrubber position.<br>- The play/pause button state must be announced.<br>- Time display must be readable - a screen reader must be able to announce the time.<br>- Skip controls need clear labels for screen readers.<br>- All icon-only buttons need accessible names.<br><br>### QA Requirements<br><br>- Create an All Options page for the Audio Player. Create automated tests for the player.|



Generated at Thu May 14 16:31:45 UTC 2026 by Jeff Mousley using Jira 1001.0.0-SNAPSHOT#100291-rev:3639528be2848fa84a5613fe3ad0b7f02b359607.