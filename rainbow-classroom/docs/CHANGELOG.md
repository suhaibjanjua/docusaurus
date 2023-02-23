# CHANGELOG of Rainbow Classroom

---

Here is the list of the changes and features provided by the **Rainbow Classroom**



## [1.36.4] - 2023-01-09
-   Auto Join to Rainbow Classroom after a 5 seconds of inactivity at the media verification screen
-   Group messages from the same sender as a single block of messages in a particular minute
-   Fetch the Rainbow Classroom login background only when it is updated by the organisation administrator. Otherwise, render it from cache. 
-   Ability to Rename a Poll/Quiz from inside the Forms UI
-   Removed the step to take Form (Poll/Quiz) name at the time of creation with a default naming convention
-   Show Question Type in the dropdown against all types of questions in the Forms "Creator View" and allow to change question type of supported questions
-   Ability to Sort Classrooms, Meetings and Workgroups by Topic
-   Calendar menu added into the Rainbow Classroom to show list of upcoming meetings
-   Color picker module changed in Whiteboard
-   Fixed: Dashboard missing report image issue
-   Fixed: Whiteboard undo option does not work when the user erases a filled shape
-   Fixed: Lobby permissions should reset after each session
-   Fixed: Double click outside after copy pasting the content in the add note model saves two records


## [1.36.3] - 2022-12-23
-   Live Chat Lag/Performance UI/UX Improvement
-   Dark Theme supported added in Forms
-   Show all reactions received in a sorted list to Host by most recent reaction on top (Except Raised Hand)
-   Consistent Audio Icon state and labels for Exam Room comparing to main classroom
-   Session Recording Intimation to the Host and all other connected Participants that they are being recorded
-   Maintaining the chat context during a live session
-   Updated Session Recording Start/Stop icons
-   Workgroup Preferences/Settings tab to update avatar
-   Font change from "Open Sans Regular" to "Open Sans Light"
-   Avatars with Transparent Background in Rainbow Classroom
-   Apply Classroom UI theme to Forms and Whiteboard when user switch it from the settings
-   Removed/Disabled "Emojis" from Rainbow Classroom to avoid performance lag
-   Kick & Ban Permissions added at classroom level for Host UI customisation
-   Manage Guest Permission added at classroom level for Host UI customisation
-   Ability to Search text messages in Chat History (contact, classroom, meetings, workgroups etc)
-   Fixed: Video/Audio settings are not available after the session started
-   Fixed: No student video broadcast on Exam rooms at the teacher level
-   Fixed: Auto scroll of the Chat function issue
-   Fixed: External camera issue | Video not showing on the other side when switch to external camera


## [1.36.2] - 2022-11-30
-   Improvement in Single Sign-On (SSO) between Moodle and Rainbow Classroom. 
-   Mitigation for the Host to Mute a Participant during a live session to avoid the abnormal behaviour of the Web SDK v3.0.3-LTS.
-   Fixed: Showing "Unable to display content" message multiple times at Welcome Screen when navigating tabs
-   Fixed: Participants with long names are not showing in a single line under the classroom details


## [1.36.1] - 2022-11-25
-   Sharing a Whiteboard during a live session moved to the Call User Interface with a dedicated Whiteboard Tab
-   The ability for the Screen Share Owner to Show/Hide the Content Shared during a live session
-   Call control bar with a more compact view to reduce negative space
-   The ability for the user to Export Live Notes while drafting during a live session
-   Optimised the Rainbow Classroom login time for organisations with custom login backgrounds.
-   By default, Accessibility Menu is hidden. Users can turn it on from the Preferences.
-   Optimised the load time of the Polls & Quizzes page under classrooms and meetings by session management
-   The ability for the user to Export Notes while drafting from the Notes Page
-   Optimised Forms loading time under Learning Centre by session management.
-   Gallery View and Carousel View Tabs are merged to show a single tab at a time
-   Optimised the load time of the Links page under Learning Centre by session management
-   Recording abnormal disconnections by the teacher into the Attendance/Reports KPIs.
-   The ability for the participant to submit the same reaction multiple times except "Raise Hand"
-   Do not highlight the reactions menu at the participant end if the participant has given a reaction except "Raise Hand"
-   Showing the reactions received multiple times at the Host end if a participant has submitted it multiple times
-   Added date/time to the reactions received at the Host end in the Reactions list
-   Showing the most recent reaction in each category on top while maintaining the overall category order
-   Showing reactions sent by the participants as participant's activities at the Attendance/Reports KPIs
-   Infinite scroll pagination was added to the Attendance/Reports page to fetch more sessions automatically once the user reaches the bottom of the scrollbar
-   Show more button added to the Attendance/Reports page to fetch more sessions on demand
-   Whiteboard background Zoom In and Zoom out support
-   Updated the colours palette for the whiteboard background, shapes outline & filled actions
-   Showing only the last reaction received from the student at the host end for each student's tile along with their "Raised Hand" reaction
-   Fixed: Attendance/Reports KPIs: Call end for live sessions under the Reports Page
-   Fixed: Issue with Watch Together session (WT): Video still playing on the participant side when a Teacher stops the WT session
-   Fixed: When the host unshares the whiteboard it remains available on the student side
-   Fixed: When the host stops sharing the whiteboard; its tabs still show in a disabled state


## [1.36.0] - 2022-11-04
-   Face Lift of Rainbow Classroom (Light and Dark Mode)
-   Rainbow Web SDK V2 Conference Support in Rainbow Classroom
-   Dynamic video stream handling for better performance
-   Managing video streams aspect ratio according to the area for better performance
-   Added different shapes to represent Classroom, Meeting, Workgroup and a Contact
-   Notes Management with a Notes Menu in the left sidebar (controlled by the organisation)
-   Notes Sharing in Classroom, Meetings, Workgroups and Contact chats (controlled by the organisation)
-   Export Notes as a word document, a text file or a PDF file
-   Show all chats (classroom, meetings, workgroups along with contacts) in the left panel
-   Show all live sessions in the left panel under the Active section
-   Show unread messages intimation with the number of chats count at the left top toggle icon
-   The ability for the host to share Multiple Content simultaneously (Watch Together, Polls & Quizzes and Screen Sharing)
-   Copy notes content to the clipboard and pastes it anywhere
-   By default, sort notes based on a date; showing the most recent as the first item
-   By default, the camera is off at the joining screen. Users can turn it on by clicking the toggle button
-   By default, the list view is the default view for all pages across Rainbow Classroom (except meetings)
-   See your contact's personal/private information (controlled by the organisation)
-   Added a new view for incoming calls (One2One and Conference Calls at the right top)
-   Add a calendar view to the meetings page and set it as a default view for the meetings
-   Added a new type of Question "Image" in Polls & Quizzes and in form templates
-   Added support for all images to the analytics page for Image Type Questions
-   Added support for Question Description for each type of question in Polls & Quizzes
-   Removed left bottom tabs for meetings and classrooms' quick navigation
-   Ability to take notes during a live classroom and meeting session
-   Collapsible right sidebar across Rainbow Classroom
-   Terminology Changes for industry standards
-   Added new permissions at the "Customisation" page for the organisation admin to manage the end-user experience
-   Quickly customise the end-user UX by selecting any pre-defined UX templates
-   Ability to upload Organisation Logo from Organisation Settings
-   Show the custom logo in the dashboard's top left corner once it is set by the organisation admin
-   Show topics and reactions recorded during a session on Attendance Page
-   Cache Busting to serve the latest content when it is required
-   Removed compact thumbnail call view and added a bottom call control bar
-   Approve all lobby requests automatically if the host disables the lobby
-   Save classroom topic into the attendance at the start of the session; if it is updated during the call record it as well
-   Save all reactions of participants under activities performed into the attendance. Save multiple reactions per participant
-   Ability to filter a session based on the reactions received
-   Ability to filter a session based on the topic
-   Redirect host from lobby to participants tab if there are no pending requests
-   The ability for the host to remove the welcome screen video/watch together links from the course material tab
-   Single Search to search in hosts and participants at the same time
-   Moved the connected user menu to the right side
-   Show custom logo in Rainbow Classroom if it is set by the organisation
-   By default record all sessions and don't show the start/stop icon to the hosts
-   Device Selection Management (Microphone, Speakers and Camera)
-   macOS camera still in use after joining the classroom (High Priority Privacy Issue)
-   Exam Rooms Creation process performance improvement (ALE Training Team reported an issue)
-   Whiteboard Dark Theme Support from the classroom
-   WB: Fixed canvas size according to the available area on the screen
-   WB: Zoom in and Zoom out options added
-   WB: Ability to drag objects in a zoomed state
-   WB: New user interface with primary control bar and respective secondary menu bar
-   WB: Controls Grouping for better user experience
-   WB: Settings inside a menu for easy configuration
-   WB: Object-specific controls at the left of the screen for quick and easy access
-   WB: Undo/Redo process optimisation
-   WB: Backward compatibility support to open previously created boards with the new structure of JSON
-   WB: Added missing styles (Opacity, outline, weightage etc) into the broadcasting queue for synchronisation
-   Fixed: Navigation issues during a live session
-   Fixed: Permission handling during a live session
-   Fixed: Selected camera state for later use
-   Fixed: Recording session in the form of multiple files to avoid larger recording files uploading issue on rainbow
-   Fixed: Recording sessions in small files to avoid memory consumption to increase performance at the host end


## [1.35.1] - 2022-08-12
-   Add a splitter to the course material tab and allow users to create a quick note during a live session
-   Fixed: #CRRAINBAMI-147 -- Atrium#00635941 // Ops Team classroom, list of BP is wrong since the upgrade to 1.35.0
-   Fixed: My profile modal should reset to default view if the user closes and reopens it.
-   Fixed: When user update welcome content, Welcome content intimation icon does not show right away


## [1.35.0] - 2022-07-29
-   "Free Text", A new type of question is added to Forms, Classwork and Meeting Material
-   PWA support in Rainbow Classroom to use offline
-   Ability for the teacher to manually update the marks of the participant for the paragraph-type question
-   Ability for the teacher to update My Meeting name and topic from the classroom
-   Showing the total obtained marks of a participant as an assessment screen
-   Non-verbal feedback support was added to the rainbow classroom.
-   New UI for the Files (chat, filters, list, grid sharing models) across the Rainbow Classroom application
-   New UI for the Polls and Quizzes for visual differentiation (list, grid sharing models) across the Rainbow Classroom application
-   WB shapes outline, size, opacity broadcasting along with font and font styles (bold, italic and underline)
-   New types of files filters added (Spreadsheet, Documents, Presentations and Compressed Files)
-   Ability to send non-verbal feedback along with the raised hand to the host of the live session
-   Replacing N/A for not available items with - Hyphen in Rainbow Classroom
-   Show participants' reaction at the participant avatar in the gallery view at the teacher's end
-   Show the list of reactions received along with "Raised Hand" in the reactions tab during the live session
-   Send Whiteboard Sharing Start/Stop message cards into the chat to intimate all classmates
-   Ability for the participant to join the shared whiteboard from the in-chat message cards during the shared time
-   Send Classwork Assigned/Unassigned message cards into the chat to intimate all classmates
-   Ability for the participants to open the classwork tab from message cards
-   Intimation of all possible types of sharing during a live session in the compact mode (Thumbnail UI of call)
-   UI/UX improvement for the links management under Learning Centre
-   Send live session recording Start/Stop intimation messages into the chat to intimate all classmates
-   Improved UI for the live session start/stop intimation messages in the chat
-   Allow the host to upload custom images as classroom, workgroups and meetings avatar
-   Allow all users to drag and drop to upload an image as a profile picture from a personal computer
-   Allow the host to drag and drop images as classroom, workgroups and meeting avatar
-   Allow users to CROP the image before uploading it as a profile picture, classroom, workgroup and meeting avatar
-   Organisation admin can upload a background image with a maximum of 5MB
-   Improved UI/UX for Rainbow BP onboarding
-   Ability to name breakout rooms while creation
-   Ability to name exam rooms while creation
-   Ability to rename a breakout room after creation (UI for the modal design is pending)
-   Ability to rename an exam room after creation (UI for the modal design is pending)
-   Ability to create breakout rooms even when participants are absent
-   Ability to set YOUTUBE videos as Welcome Screen content
-   Ability to preview YOUTUBE links from course links at Welcome Screen
-   Showing Lobby intimation to notify the host when a user/participant is waiting in the lobby
-   Showing Raised Hand intimation to notify the host when a user/participant Raised their Hand
-   Upload an image from a personal computer as Profile Picture or as a classroom, workgroup and meeting avatar
-   Ability to Crop image before uploading it as Profile Picture or as a classroom, workgroup and meeting avatar
-   Ability for the host to update obtained marks for descriptive-type questions at the classwork assessment screen
-   Showing Others Responses received as Wordcloud and Text at the classwork analytics
-   Rainbow Classroom login background style inherited from the organisation's background style in the dashboard
-   Mitigation for Files temporary URL generation from Rainbow Server to handle the "Unable to display content" issue at Welcome Screen.
-   Import a pdf page as background in WB modal added
-   Preview the imported pdf page before uploading it as a background
-   Ability to fit the background image to the actual size or to cover the whole whiteboard
-   Only supported file types (PDF and Images) are allowed to be uploaded as WB background
-   Added support for an image with a maximum 10MB file size to be uploaded as WB background
-   Validation and intimation for the end user to upload less than 10MB file size for an image to be uploaded as WB background
-   Set Watch Together (YouTube) Player volume to 50% by default for teachers and participants
-   Ability for the teacher to increase the volume of the video from the YouTube Player
-   Intimation for the end user to add at least one question before saving a poll/quiz
-   Whiteboard controls re-ordered and changed the Eraser and Wipe icons
-   Implementation of WB existing features missing broadcasting to synchronise the WB at both ends.
-   WB empty board creation, authentication flow and loading live board for participants connecting late
-   WB text position and bring to front handling
-   Close the Import PDF modal in WB by pressing Escape Key
-   Change the selected control to Cursor if the user presses the Escape key
-   Fixed: #CRRAINBAMI-135 -- Atrium#00625953 // Impossible to add a new Classroom BP admin and the old ones are not working anymore since version 1.34.0


## [1.34.1] - 2022-06-10
-   Rainbow Classroom Login Screen background style based on the background style selected by the organisation admin in the dashboard
-   Showing Course Names for classrooms before the topic. If there is a topic, it will be appended to the course name
-   Whiteboard disconnection before closing the whiteboard in Rainbow Classroom for graceful handling
-   Whiteboard user interface improvement with respect to Rainbow Classroom colour scheming
-   Fixed: Supported file types to be uploaded as course material with case sensitive issue


## [1.34.0] - 2022-06-03
-   Rainbow Classroom is now using the latest Rainbow Web SDK v3.0.3-LTS that supports Unified Plan for WebRTC calls
-   Enhancement in Recording Classroom and Meeting Live Sessions in multiple recorded files to increase performance and eliminate the chance of missing the recording sessions
-   Rainbow OPS Team User: Ability to onboard BP companies via Customer Care Rainbow oAuth details before adding a new BP Admin
-   Rainbow OPS Team User: Ability to manage BP Admins for existing companies in the system
-   Rainbow OPS Team User: Ability to see the actions performed in the whole solution in the Audit logs page
-   BP Admin User: Organisations data sync among multiple BP Admins that belong to the same BP Company.
-   Organisation Admin: Updated descriptions of features at experience manager in the dashboard
-   Organisation Admin: Ability to change dashboard background with different given options or to reset back to the default background
-   Organisation Admin: Ability to reset Teacher, Student and Guest credentials by sending the reset credential email from the dashboard
-   The accessibility icon and menu position is changed to avoid overlapping content
-   Do not allow the host to upload a file in course material over 25MB. Show a respective error message. Also, show an error message when the user tries to upload unsupported file types. (Supported Types: PDF/DOC/DOCX/XLS/XLSX/PPT/PPTX with a maximum file size limit: of 25MB)
-   The ability for the Organisation Admin to Replay all recorded lectures of a particular session from teachers' attendance
-   The ability for the Organisation Admin to test the Canvas LMS connectivity details at Rainbow Classroom Integration from the dashboard.
-   Custom login background set by the organisation admin will show up at Rainbow Classroom for Teachers, Students and Guests. Even if a user logs out; it will still show up on the login screen.
-   New default login background is added to the Rainbow Classroom application.
-   Show customised login background if it is set by the organisation admin at the login screen.
-   Removed the tunnel effect for the locally shared screen by adding a new screen. "You are sharing your screen."
-   Contacts Menu added to show a list of contacts with detail in your network in Rainbow Classroom
-   Do not terminate the live Classroom session when timebound expires
-   Changed the default position of the call overlay in compact/thumbnail mode
-   Manage the state/position of the call overlay where placed by the user
-   Added tooltips to Course and Classroom in the left panel to handle longer names
-   Do not hide the classroom when timebound expires and a live session is running
-   Highlight the call duration on the live collaboration screen when the classroom time expires.
-   New contact icon for the One-2-One conversations tab in the left panel
-   Ability to collapse and expand the left side menu bar by double click on it in the dashboard
-   Ability to filter and sort contacts based on name or presence on the contacts page
-   Forms, Classwork and Meeting Material Close popup heading is changed to a generic one.
-   Saved Whiteboard snapshot preview in the list of Whiteboards
-   Whiteboard list view now shows saved whiteboards as thumbnails in the list.
-   Disable the preview and save action buttons in Forms when the user is creating a new form
-   Removed the default question when creating a new form. Staring a blank form should not have any questions.
-   Added a new screen to show the "Add Questions" option when there are no questions in the form
-   Open One2One Conversation by double click at contact cards in the network tab
-   Keyboard shortcuts added for missing shapes and frequently used menus on Whiteboard
-   Classroom-specific Recorded Lectures are available under the settings tab as Recorded Lectures
-   Files shared in a Classroom/Meeting conversation are also available under the settings tab as Files
-   Classroom specific files section is available under Classroom -> Settings
-   Classroom-specific recorded lectures section available under Classroom -> Settings
-   Editable Classroom and Meeting Topics (Maximum Characters supported: 200 Characters)
-   Whiteboard performance enhancement for multi-user collaboration
-   Diamond and Hexagon Shapes added to Whiteboard Drawing Tools
-   New default login background is added to the dashboard application
-   Recorded Lectures icons updated for audio and video sessions
-   Exam rooms modification: Added option for the host to add offline participants in the exam room
-   Added a drop-down menu on the Classes, Workgroup and Meeting pages.
-   Added a dropdown on classrooms, workgroups and meeting cards for respective quick actions for consistent user experience
-   The default login background has been changed.
-   The ability of the organisation admin to restrict participants to download the course material from the organisation experience manager
-   Password policy is now mentioned on the change password page.
-   Password policy is now mentioned on the account activation page.
-   The ability for the end-user to collapse and expand the left side menu bar by double click on it in Rainbow Classroom
-   Changed the 'reset all' icon for the Translation workbench
-   Whiteboard UI/UX improvement
-   Fixed: Get more messages from conversation history to avoid empty conversation issue
-   Fixed: Forgot password email issue for invalid/not found user in the dashboard
-   Fixed: Translation workbench UI/UX issues
-   Fixed: Multiple Admin Reports exporting by clicking multiple times on the Export button
-   Fixed: Forms white background issue while loading
-   Fixed: Co-host ability to lock/unlock live session
-   Fixed: Ability for the student who has created the workgroup to remove any participant from its workgroup
-   Fixed: Show an error message in the dashboard when the organisation admin tries to upload course material for a call over 25MB file size
-   Fixed: Default whiteboard background removes on Wipe action performed by the end-user
-   Fixed: Save notification is not showing up for poll/quiz
-   Fixed: Auto imports from FTP server using Remote Provisioning Tool
-   Fixed: Search participants in the workgroups


## [1.33.1] - 2022-05-06
-   The Ability for the end user to reset the selected language back to the organisation's custom language/translation
-   The Ability for the end user to override the organisation's Custom Language/Translation with the selected language from preferences


## [1.33.0] - 2022-04-22
-   Editable Topics (Description) for Classrooms and Meetings
-   Client-side experience manager for Teachers only (Show/Hide menus from preferences)
-   Mute/unmute icons toggle instantly without waiting for a confirmation from the SDK for a nice UX
-   Removed the tooltips showing up at Workgroups/Classrooms/Meetings participants to avoid any overlapping
-   The ability for the students to create and manage workgroups in classrooms and meetings
-   Ability for the Guest User to Update their Profile Picture in Rainbow Classroom.
-   "Submit Feedback" changed to "Report a problem" in Rainbow Classroom
-   Ability to download the Rainbow Classroom logs file from the settings
-   Added a Contact Detail Card with contact info
-   Contact Detail Card with contact information to add/remove a contact from your network
-   Open One2One conversation directly from the contact detail card
-   Peer-2-Peer call recording now offers to save the recorded session to Rainbow Storage
-   Added a confirmation message before hanging up a live collaboration session
-   Notify the user when a new watch together session started
-   Ability to Preview YouTube saved links from the learning centre
-   Ability to start a watch together event from the learning centre YouTube links or course material links
-   The ability for the user to override Rainbow Classroom Language set by the organisation for itself
-   Expandable models in Rainbow Classroom for a nice user experience
-   Users can navigate between active documents and active classwork during a live collaboration session
-   Revamped the whole My Profile modal with Flat UI to improve the overall UX
-   Improve the quality of video streams and screen sharing in the live collaboration session
-   Do not show Speaker's dropdown at Media Verification and Preferences Modal in case of Firefox browser
-   Only the workgroup owner can add/remove a participant to/from the existing workgroup
-   The ability for the user to close forms "preview modal" and "answer key" modal  
-   Load more messages from history to handle missing conversation messages fixed by pressing the escape key  
-   Ability to Import Custom Translation in Dashboard
-   Extract Meeting Admin Reports in the Dashboard
-   Notify the organisation administrator when it tries to upload a file as course material with a size of more than 25MB in the Dashboard
-   Server Side Searching added to pages (Courses, Classes, Meetings, Teachers, Students, Guests) to allow organisation admin to search across all records
-   Ability to set a customised login background image for Rainbow Classroom and Dashboard from Organisation Settings
-   The ability for the Organisation Administrator to Reset Teacher, Student and Guest credentials even when their account is not yet activated.
-   Forgot Password validation improvements and updated the forgot password email subject
-   Removed the PWA integration from Dashboard
-   Close all models and popups by pressing the escape key in the dashboard
-   Notify the host when it tries to upload a file as course material with a size of more than 25MB in Rainbow Classroom
-   UI consistency in models with descriptions to explain what a user can do in each modal in Rainbow Classroom.
-   Added initial support for Opera Browser
-   Add a new shape "Hexagon" in Whiteboard drawing shape tools
-   Fixed: Forms/Classwork bugs and UI/UX improvements
-   Fixed: Whiteboard miscellaneous issues
-   Fixed: login screen appears inside the whiteboard and classwork
-   Fixed: Whiteboard fit to screen (orientation) is not working in Opera
-   Fixed: Screen Sharing video is not showing 100% at remote user ends; if they are using smaller screens or small resolution
-   Fixed: #CRRAINBAMI-108 -- [Rainbow Classroom] Icon not shown against Live Classroom Controls option when a label is too long
-   Fixed: #CRRAINBAMI-116 -- Atrium#00609739 // RB Classroom: Speaker access in Firefox not working
-   Fixed: #CRRAINBAMI-120 -- Atrium#00609724 // RB Classroom: Password rules don't accept '-' as a special character
-   Fixed: #CRRAINBAMI-121 -- Atrium#00609741 // RB Classroom - With reduced browser window, the left menu has overlapping icons
-   Fixed: #CRRAINBAMI-123 -- [Rainbow Classroom] Gallery View button disabled in Full-Screen mode


## [1.32.0] - 2022-02-25
-   Proctoring Breakout Rooms are Renamed to "Exam Rooms"
-   New and much more improved UI of Whiteboard Controls
-   Removed "Straight Rectangle" shape and added "Rounded Rectangle" shape as replacement
-   New Shape "Double-Sided Arrow" addition to the list of shapes offered on the Whiteboard
-   New Shape "Dotted Lines" addition to the list of shapes offered in the Whiteboard
-   New Shape "Triangle" addition to the list of shapes offered on the Whiteboard
-   Ability for the user to switch to list view from Icons view on all pages across the rainbow classroom
-   Ability for the organisation admin to upload/update the organisation logo, name and slogan to be shown on the Home Screen of Rainbow Classroom
-   Ability for the organisation admin to generate Admin Detail Reports, of Courses/Classes, Teachers, Students and Guest from the dashboard
-   Ability to Save Admin Report Criteria for later use in the Dashboard
-   Ability for the organisation admin to Export Admin Reports in CSV and PDF Formats from Dashboard
-   Ability for the host to Set the File as Welcome Content from Files Tab under the learning centre
-   Ability for the user to share files with contacts and in classroom/meeting conversations from the Files tab under the learning centre
-   Added a new Chat Tab in the classroom and meeting details to allow the user to chat while connected to a live session
-   Ability for the host to manage Course Material under classrooms directly from the course material tab
-   Ability for the host to manage Course Links under classrooms directly from the course material tab
-   Ability to update classroom and meeting avatar from the settings tab
-   Ability for the user to preview files from the Files tab under the learning centre (Supported Types: PDF/DOC/DOCX/XLS/XLSX/PPT/PPTX with a maximum file size limit: 25MB)
-   Ability for the user to rename the whiteboard by double click
-   Ability for the user to open the whiteboard by double click
-   Ability for the user to open the classwork or meeting material by double click
-   Ability for the user to open file preview by double click
-   Ability for the user to play recorded lectures by double click
-   Ability for the user open classroom/meeting/workgroups by double click
-   Ability for the user to open links in a new tab by double click
-   Ability for the user to add links from existing links
-   Ability for the organisation admin to Mass Import Users in Rainbow Classroom Standalone Offering
-   Ability for the organisation admin to Mass Import Course Creations in Rainbow Classroom Standalone Offering
-   Ability for the organisation admin to Mass Import Classes Creation and Users Enrollment in Rainbow Classroom Standalone Offering
-   Ability to open class Attendance, Copy Class and Delete Class from Edit Class Page in Dashboard
-   Ability to set images (PNG, JPG/JPEG) as Welcome Screen Content
-   Ability for the user to start and end the guided tour in Rainbow Classroom on the "Enter" Key
-   Close all models on 'Escape Key' as default action to close modals
-   Close all pop-up dialogues on 'Escape Key' to cancel the operation
-   Show the main host user in Exam Room details for students so that students can interact with the original user instead of the pseudo-user
-   Disabled Preview and Set as welcome content options for unsupported file extensions (ZIP, 7Z, LOG etc...)
-   Close all models on the escape Key in Rainbow Classroom
-   New and Improved User Interface of Classroom/Meeting Settings
-   Fixed: Disabled options(Edit/Delete) on a Quiz saved as a draft


## [1.31.0] - 2022-02-04
-   ALE Training Team Onboarding (Add support in standalone offering for Mass Provisioning as well as manually creating a class)
-   Remote Provisioning Tool for ALE Training Team to Setup the FTP/SFTP configuration which allows the tool to provision products/training, trainers, trainees and their enrolments in respective training.
-   Proctoring Mode Introduced for hosts to have 2 breakout rooms running simultaneously while a classroom is live
-   Proctoring Tab availability for a host if the host has permission to use proctoring mode
-   Compact View of Rainbow Classroom in the Proctoring window
-   Manage the state of Microphone and Camera access to the respective window where the host wants to share the stream.
-   Ability for a host to see remote videos coming from students in proctoring breakout room at the same time.
-   Ability for org admin to Timebound classes from the dashboard based on class availability time and availability of the class for different users in Rainbow Classroom
-   Ability for org admin to upload and manage course material for a class in the dashboard; set it as welcome screen content (Supported Types: PDF/DOC/DOCX/XLS/XLSX/PPT/PPTX with a maximum file size limit: 25MB)
-   Ability for org admin to add and manage course links for a class in the dashboard
-   Ability for a host to switch welcome screen content from the list of available course material
-   Ability for all users to preview any course material from the list of available course material
-   Ability for all users to download any course material from the list of available course material
-   Ability for all users to open and copy links from the list of available course links
-   Ability for a host to remove the welcome screen content
-   Ability for a user to search and sort the list of available list of course material and course links
-   Ability for a user to directly upload files to Rainbow Storage from Rainbow Classroom
-   Ability for a host to switch/upload welcome screen content during a live classroom session from the rainbow classroom
-   Ability for a user to double click on items to execute default action e.g. open/play/preview (Whiteboards, Classworks, Workgroups, Meetings, Classrooms)
-   Ability for org admin to delete a Class from the dashboard while it is running; will stop the classroom and remove it from the list of classrooms
-   Enable All inactive classrooms and meetings when a user login into Rainbow Classroom so that a host can start a session
-   Export list of data from pages - (Courses, Classes, Meetings, Teachers, Students, Guests, TWB )
-   Whiteboard UI Enhancements (Reordering of menus and grouping of menus etc.)
-   Added a new shape Arrow in whiteboard objects
-   Watch Together intimation and toggle menu on top similar to the existing whiteboard and screen-sharing intimations during a live session
-   Selected conference view intimation during a live session
-   Rainbow Ops user: the ability to see BP name, companies under the BP, Licenses subscribed by the BP for each of the companies
-   Top navigation Tabs replaced with Textual tabs in Rainbow Classroom
-   Ability to edit bubble avatar from classroom/meeting home tab if it is active
-   Rainbow Classroom and Dashboard compatibility as PWA for offline use
-   Ability for a user to hide accessibility icon/option from classroom settings
-   Rooms renamed to Workgroups in the classroom application
-   Fixed: Standard breakout room join back issue
-   Fixed: Standard breakout room join classroom issue
-   Fixed: Classwork submission issues for students
-   Fixed: Mass Provisioning job stuck issues


## [1.30.0] - 2022-01-14
-   PWA support of Rainbow Classroom and Rainbow Classroom Dashboard
-   Export list of data from pages - (Courses, Classes, Meetings, Teachers, Students, Guests)
-   Rainbow Ops user ability to see BP name, companies under the BP, Licenses subscribed by the BP for each of the companies
-   New and improved Flat User Interface of Rainbow Classroom
-   Compact UI of the call overlay in thumbnail mode
-   Export the list of courses as a CSV file from the dashboard
-   Export the list of classes as a CSV file from the dashboard
-   Export the list of meetings as a CSV file from the dashboard
-   Export the list of teachers as a CSV file from the dashboard
-   Export the list of students as a CSV file from the dashboard
-   Export the list of guests as a CSV file from the dashboard
-   Option to see only customised strings in the selected sub-module of a module    
-   Chat message intimation on-call overlay for messages received during a live session
-   Show list of existing whiteboards inside the classroom/meeting/room/breakout room whiteboard tab
-   Show notification LED at messages Tab on receiving a message for unread messages in Classroom/Meeting/Room/Breakout Room/My Meeting
-   Replace All strings with matching input keywords in customised language from Translation Workbench
-   Export Selected module and submodule Translation Strings into a CSV file
-   Export a Teacher's Classroom/Meeting Session Attendance into a CSV file
-   Mass Import Courses/Classes with Additional Columns to address ALE Training requirements
-   Mass Import Host/Participants with Additional Columns to address ALE Training requirements
-   Mass Import Classes Enrollments with Additional Columns to address ALE Training requirements
-   Show intimation of Unread Messages Tab Under Classroom/Meeting
-   Clear the unread messages once the user has visited the respective classroom/meeting chat messages
-   Show intimation of Unread Messages at Classroom Cards in the left panel
-   Show intimation of Unread Messages at Meeting Cards in the left panel
-   Manage unread messages of Classroom/Meeting in session so that it appears after refreshing/revisiting by the user
-   Fixed: for When the user deletes a class from the dashboard; if there is an active session running; it should be stopped first before deleting the classroom


## [1.29.0] - 2021-12-24


## [1.28.0] - 2021-12-17


## [1.27.0] - 2021-12-10
-   Accessibility support in Rainbow Classroom
-   Welcome Content Management by teachers for Classrooms and Meetings in Rainbow Classroom
-   Rainbow File Sharing Modal select an existing document as welcome content
-   Fully Functional Experience Manager to control organisation-level settings
-   Document Read Together during a live session
-   Emojis Integrations in Rainbow Classroom
-   Ability to Upload Profile Picture by Drag & Drop in Rainbow Classroom
-   On the Fly Turn on/Turn Off Lobby for a live classroom and meeting session
-   Browser Push Notifications (Existing intimation will be shown as browser notifications if the permission has been granted)
-   Web-based guided tour for Rainbow Classroom
-   Web-based guided tour for Org Admin Dashboard
-   Web-based guided tour for Business Partner Dashboard
-   Accessibility State Management
-   Show data analytics in a cubical modal on all pages in the dashboard
-   Showing consumed and available licenses at the organisation's grid in the dashboard
-   Ability to Export data from cubical models
-   Recorded Lecturers Section at Learning Centre
-   Move connected users to the home screen of the rainbow classroom as soon as the class/meeting deleted from the dashboard
-   Test the LMS connectivity button in organisation settings for LMS-type integration
-   LTI, Forms and Whiteboard customised language support at the translation workbench
-   Ability to Delete a Class from the dashboard
-   Course rename in Moodle will reflect in Rainbow Classroom after LTI setup or mass provisioning
-   Single Course and Mass Provisioning optimised
-   Showing the name of the user who is actively sharing the screen during a live session
-   Filter all and translated strings at the translation workbench
-   Fixed: Custom translations not saving after navigation
-   Fixed: Ability to export the content from Whiteboard
-   Fixed: Rainbow Classroom UI bugs for Chrome 96 update
-   Fixed: Rainbow Classroom conference videos configuration optimised


## [1.26.0] - 2021-11-19


## [1.25.0] - 2021-10-29


## [1.24.0] - 2021-10-15
-   Classroom Students a new type of license support
-   Ability to Search in the Classwork and Meeting Material tab
-   Show cumulative results for Quizzes in Classwork and Meeting Material
-   Show a list of Responses Received for Quizzes in Classwork and Meeting Material
-   Search students in responses received list view for Quizzes
-   The ability to Open Form Assessment View with Students' Question Sheets for marking
-   Offline and Online sharing of Quizzes in Classrooms and Meetings
-   Filters added for forms in the learning centre, in classwork and meeting material
-   TLS/SSL added in SMTP settings at the Super Admin level in the dashboard for the email-sending server
-   Ability to delete classwork and meeting material
-   Ability to change question type in Forms while creating/editing a form
-   Renamed Standalone Mass Provisioning sample files
-   Added a popup to take the "Forms" name while creating a new Quiz
-   The ability for the owner of the Room to update the Room avatar
-   The ability for the owner of the Room to update the Room name and Room Description/Topic
-   Send "Forms" Start/Stop intimation to the bubble and live session participants
-   Ability to share "Forms" during a live session and without a live session
-   Skipping invalid emails with a description in Standalone Mass Provisioning Jobs
-   Skip users with invalid email format while provisioning via LTI Setup
-   Fixed: Whiteboard issues ((wipe out) on image stretch
-   Fixed: LTI setup stuck at the final step in the pending state
-   Fixed: Special characters support in email addresses
-   Fixed: Form reloads as soon as the end user presses the save button
-   Fixed: Call overlay shouldn't overlap classroom detail


## [1.23.0] - 2021-09-03
-   Polls & Quizzes introduced as "Forms" with two types of questions in Rainbow Classroom
-   The ability for the host to manage a Quiz from the Classwork and Meeting Material tab.
-   The ability for the host to preview, any existing Quiz or Open it to receive responses
-   The ability for the participant to submit feedback to an open Poll/Quiz
-   Added Filters to the "Forms" page under the learning centre
-   Translation workbench for organisations (Dashboard and Classroom)
-   French Translation Support (Newly added strings will be shown in English until they are translated)
-   German Translation Support (Newly added strings will be shown in English until they are translated)
-   Showing all "Forms" created by a teacher under the learning centre
-   Ability for the Host to "Save" an online whiteboard inside a live session
-   Ability for the Host to "Wipe" an online whiteboard inside a live session
-   Multiple roles mapping against the same role in the classroom
-   Multiple roles support in LTI Setup
-   Dynamic Tooltips support in Rainbow Classroom
-   Fixed: Breakout rooms creation and start/stop issues
-   Fixed: Rainbow Classroom UI/UX bugs fixed
-   Fixed: Whiteboard: 'Position of the Shapes does not change for the student if host changes the position of the shapes or other objects


## [1.22.0] - 2021-08-06
-   Map a role of Moodle/Canvas LMS as a Guest in Rainbow Classroom from the dashboard
-   Guest management support in mass provisioning from the dashboard
-   Guest management support while provisioning classrooms via LTI setup
-   Guest user provisioning summary while they are in processing state in LTI Setup
-   Guest user provisioning final summary with detailed (CSV) export once they are processed via LTI Setup
-   Ability to manage guests from inside Rainbow Classroom
-   Ability to Delete a teacher user from the dashboard
-   Ability to Delete a student user from the dashboard
-   Ability to Delete a guest user from the dashboard
-   Save whiteboard content on-demand to later continue from the same state
-   Unsaved whiteboard content will be wiped out on whiteboard disconnection
-   Teacher, Student and Guest email tagging on the Whiteboard for identification of drawn shapes
-   Guest user statistics in the Dashboard
-   Guest user representation in Rainbow Classroom
-   Ability to delete a whiteboard drawn shape with the Delete key as a short-cut
-   Multi-line text support added for text areas on the whiteboard
-   Ability to resize already drawn objects on the whiteboard
-   Ability to make modifications (font, font size, object size, colour, style) to already drawn objects in the whiteboard
-   Ability to enable/disable guest eco-system from the dashboard
-   Safari browser support for Rainbow Classroom
-   Safari browser support for Rainbow Classroom Administration
-   Bug fixed related to the first non-course entity is the name of the LMS (Moodle/Canvas) in mass provisioning
-   License switch bug fixed when license limit reached
-   Classroom/Meeting permissions issue bug fixed
-   Lobby and live session overlay bugs fixed


## [1.21.0] - 2021-07-16
-   Provision for setting up a standalone company in Rainbow Classroom (no LMS required) aka Rainbow Classroom Standalone
-   Support for onboarding UCaaS and CPaaS existing users in Rainbow Classroom using Rainbow Classroom's internal Identity (pseudo users)
-   Configurable Single sign-on (SSO) option while setting up a company of type Rainbow Classroom
-   Multiple types of teacher/student licenses support in the rainbow classroom (custom, monthly, 1 year, 3 years, 5 years)
-   Classroom/Meeting session recording playback in the classroom
-   Classroom/Meeting session recording playback in the dashboard
-   Upgrade to Rainbow Web SDK v2.0.0-LTS in Rainbow Classroom
-   Share recorded sessions in classrooms/meetings from the learning centre
-   Co-host attendance for classroom and meeting
-   Separate attendance will be recorded for a transferred classroom session
-   Classroom host can see co-host and students attendance in the classroom and dashboard
-   Ability for the host to acknowledge and lower the hand of students
-   Teachers selection support in LTI setup
-   License type selection support in LTI setup
-   License count issue fixed in LTI setup
-   Teachers and students provisioning summary while processing during LTI Setup
-   License validation and provisioning issues fixed in the LTI setup
-   Teachers and students' final summary with detailed (CSV) export
-   Forgot Password support in Rainbow Classroom
-   Ability to enable/disable Rainbow Web SDK logs
-   Undo/Redo fix for Whiteboard
-   Classroom Manager service optimization for CPU
-   Dashboard stats issues fixed
-   Rainbow Classroom UI Responsiveness fixed


## [1.20.0] - 2021-06-18
-   Watch Together feature in active Classrooms and Meetings (YouTube Only)
-   Only the host can initiate a Watch Together session
-   Preview for YouTube videos before starting the Watch Together session
-   Play/Pause YouTube videos in Watch Together for all connected participants from the host end.
-   Seek YouTube videos in Watch Together anywhere for all connected participants from the host end.
-   Carousel View added in the active classroom and meetings sessions
-   French Language support in Rainbow Classroom, Dashboard and LTI Setup
-   Rainbow Classroom Dark Mode for new UI
-   Removed C# SDK integration from manager and helper and moved to Rainbow APIs
-   Rainbow Classroom now supports Firefox browser along with Google Chrome
-   Database backward compatibility support in API
-   Administrative Audit Logs support in API
-   Enable Disable Audit Logs
-   Ability to fetch the history of audit logs
-   API Token session maintenance in Rainbow Classroom
-   LTI request handling in case of LMS API not responding
-   LTI avatar selection step has been removed as it is now available in Rainbow Classroom and Dashboard
-   New colour palette on the whiteboard
-   Simplifying colour selection on the whiteboard
-   Ability to change background colours of already drawn objects on the whiteboard
-   By default, a new object will be drawn at the centre of the screen on the whiteboard
-   Object resizing support in the whiteboard
-   Whiteboard Pencil event broadcasting optimization


## [1.19.0] - 2021-05-28
-   Showing the name of the participant who is sharing the screen in classrooms, meetings, rooms and breakout rooms
-   Embedded YouTube interface in classrooms, meetings, rooms and breakout rooms chat
-   Showing picture in picture for the local video while in gallery mode (classrooms, meetings, rooms and breakout rooms)
-   Custom avatar selection powered by Pixabay in Rainbow Classroom and Rainbow Classroom Dashboard
-   Preview of selected avatar for classroom/meeting in Rainbow Classroom and Rainbow Classroom Dashboard
-   Submit Feedback from the classroom takes additional information (short and long descriptions)
-   Custom Tooltips in all grids of Rainbow Classroom Dashboard
-   Mass provisioning job progress bar in Rainbow Classroom Dashboard
-   Additional columns added in mass provisioning jobs grid in Rainbow Classroom Dashboard
-   Preview of selected avatar for the classroom in LTI Setup
-   Classroom rules sync with students' rules count for each permission in LTI Setup
-   Cards Layout Updated in Rainbow Classroom
-   Default Permissions view in Rainbow Classroom Dashboard
-   Mass provisioning optimization and bug fixing
-   License verification and error message in LTI Setup
-   Role verification and error message in LTI Setup
-   LTI Setup failsafe mechanism to always end the current process with success or failure status and detailed description
-   Single sign-on (SSO) process optimized for (.com) production platform


## [1.18.0] - 2021-04-30
-   Upgraded Rainbow WebSDK to the latest version 1.86.0
-   Meetings Menu and Tab Introduced for Meetings
-   Send Chat Messages with Tags [Important] [Information] and [Standard]
-   Disabled browser's next previous navigation controls in Rainbow Classroom
-   Searching in Meetings in Rainbow Classroom
-   Validate User License (Teacher/Student) at login in Rainbow Classroom
-   LMS user roles mapping verification in LTI classroom setup
-   LMS with FQDN and Server IP Port added in LTI classroom setup
-   Select classroom avatar while setting up a course from LTI
-   Pixabay integration in LTI classroom setup
-   Test the SMTP connectivity mechanism in Rainbow Classroom Administration
-   Paginated content in Rainbow Classroom Administration
-   Moodle and Canvas Mass Provisioning and Mass LTI links creation
-   Friendly name option in SMTP settings to append a friendly name to the sender's email address
-   Mass provisioning jobs status UI Improvements


## [1.17.0] - 2021-04-16
-   Submit Rainbow Classroom feedback logs to the organisation's technical contact
-   Rainbow Classroom New User Interface
-   Active Classroom cards layout
-   On the fly allow media devices (microphone and camera) to start working without the page refreshing
-   Moved Classroom Controls of a live classroom session into a dropdown
-   Student Permissions control card for joined students in a live classroom session
-   Moodle and Canvas LMS User Roles mapping interface in the dashboard
-   Mass Provisioning Wizard Interface in Dashboard
-   Mass Provisioning Sync (Existing Provisioned Courses, Sections, Users)
-   Rainbow Classroom LTI External Tool Links Embedding into the sections of the course (Canvas) from the dashboard
-   User Level License Association by BP  
-   Hide user email addresses from other users in Rainbow Classroom  
-   Ability to go into widescreen by double-clicking on any page in Rainbow Classroom
-   Whiteboard reconnection handling in Rainbow Classroom


## [1.16.0] - 2021-04-02
-   Forgot Password page added in the dashboard to send account reset email
-   Show multiple cameras in settings (Plug and Play External Camera without a need to refresh the page)
-   Show email addresses of Teachers and Students when the org admin hovers over the Section/Meeting Tables in the dashboard
-   Ability to select microphone and camera devices while the Rainbow Classroom is initiating the services after authentication
-   Ability to pass Dashboard super admin password via environment variable while deploying as docker images
-   Creation of Rainbow Ops Team User along with changing password echo system in the dashboard
-   Creation of Rainbow BP User along with changing password echo system in the dashboard
-   Show a list of companies that exist in rainbow under the Rainbow BP user to onboard an organisation to Rainbow Classroom
-   Ability for the org admin to manage teachers from the dashboard
-   Ability for the org admin to manage students from the dashboard
-   Ability for the org admin to manage courses from the dashboard
-   Organisation Admin account creation via activation link in an email
-   Show a list of licenses with a total count of each type on the organisations' list
-   New User Interface for Managing Classroom Permission in Rainbow Classroom
-   Ability for the user to go to full screen by double clicking on Call Interface
-   Recorded Screen Sharing Attendance
-   Added Media Devices Permission checks to hide call start/join buttons if the required permissions are not available


## [1.15.0] - 2021-03-12
-   Whiteboard list view with infinite scroll to load boards more and more
-   Ability for the org admin to manage courses from the dashboard
-   Ability for the org admin to manage sections/classes from the dashboard
-   Ability for the org admin to manage teachers from the dashboard
-   Ability for the org admin to manage students from the dashboard
-   Ability for the org admin to manage courses from the dashboard
-   Organisation Admin account creation via activation link in an email
-   New User Interface for Managing Classroom Permission in Rainbow Classroom
-   Ability for the user to go to full screen by double clicking on Call Interface
-   Recorded Screen Sharing Attendance
-   Fixed: for Moodle and Canvas Provisioning view LTI setup
-   Fixed: the Whiteboard Undo/Redo
-   Fixed: the Whiteboard Export PDF issue


## [1.14.0] - 2021-02-26
-   Ability for the student to cancel the classroom and meeting joining request
-   Ability for the host to jump in into the breakout rooms only if there is a co-host connected to the live classroom
-   Sorting breakout rooms based on Ascending/Descending
-   Ability for the host to add participants after creating the breakout room(s)
-   Screen Sharing Intimation during a live classroom and meeting session to allow the user to switch views
-   Meeting Page added in the dashboard to create a meeting from the UI
-   Change Password page added in the dashboard to allow dashboard users to change their passwords
-   Sentry Integration in Rainbow Classroom modules
-   Ability for the user to rename a whiteboard


## [1.13.0] - 2021-01-29
-   Single Sign-On (SSO) support for Custom LMS
-   Multi-Tenancy support in Rainbow Classroom
-   Ability for the host to Block Whiteboard editing for students(participants)
-   Whiteboard auto-naming based on the count
-   Ability for the host to manually create breakout rooms and select students to add to breakout room(s)
-   Show Breakout Rooms in the left panel with unique/temp intimation to the end-user.
-   Ability for the host to Start and Stop all breakout rooms at once
-   Ability for the host to approve or reject classroom joining requests from the lobby
-   Rename the "Groups" to "Rooms" in Rainbow Classroom
-   Ability to configure Moodle/Canvas
-   Notify students if a host or co-host has applied for any permission
-   Change breakout room(s) auto to manual if the host wants to add/drop any participant


## [1.12.0] - 2021-01-15
-   Single Sign-On (SSO) support for Moodle LMS
-   Rainbow Classroom Dark Mode UI
-   The ability for the user to switch between light and dark themes on the fly
-   Manage the user's selected theme to load the same UI from different browsers/device
-   Rainbow Classroom Dashboard(Administration) for Live Stats, Historic Widgets and backend office administration
-   Tabular Reports in Rainbow Classroom Dashboard
-   Attendance KPIs Charts in Dashboard
-   Mute/Unmute notification for students
-   Enable/Disable video notifications for students
-   Enable/Disable chat notifications for students
-   Enable/Disable file-share notifications for students
-   Enable/Disable screen-share notifications for students
-   Enable/Disable notification ding sound that plays upon participant entry and exit from live classroom and group session
-   Prometheus Integration in All Rainbow Classroom modules for metrics
-   Co-Host support to add multiple hosts in classrooms and meetings
-   German Language Support Added in Rainbow Classroom
-   Breakout Rooms are introduced to a created subset of classrooms during a live classroom session
-   Ability for the host to create and delete breakout rooms during a live classroom session
-   Ability for the host to start and close breakout rooms during a live classroom session
-   Ability for the host to record the classroom session and share it with the backend admin  
-   Ability for the host to transfer the live classroom session control to another available host
-   Ability for the host to unban a student and allow it to rejoin the same live classroom
-   Ability for the host to Lock/Unlock a live classroom and meeting session
-   Ability for the host to kick and ban a student from a live classroom and meeting session
-   Ability for the host to Sort and Search students in the lobby list
-   Ability for the host to allow one or all students to connect from the lobby
-   Lobby added to keep students in the waiting room unless the host allows them to join the live classroom and meeting session
-   The gallery layout is now the default layout for classroom/meeting sessions
-   Intimations/Notifications of background processes to the user
-   Gallery Layouts: Active speaker view for videos
-   The ability for the user to forward documents from one conversation to another
-   Update classroom permissions and student permissions from Rainbow Classroom
-   Forward documents in group bubble
-   Fixed: for Rainbow Classroom Latency Issue (SDK Optimization)


## [1.11.0] - 2020-12-11
-   Single Sign-On (SSO) support for Canvas LMS
-   Ability for participants to Raise Hands during a live session
-   External Mic/Camera selection support
-   Show a list of whiteboards in descending order
-   Allow only one user to share its screen at a time
-   Fixed: for students stuck at initiating classroom screen
-   Redirect users to the error screen for unauthorised access via LTI
-   Ability to download files from the conversation
-   Active speaker view added to conference and peer2peer calls
-   Showing network quality on top of the live session
-   Ability for the user to swap remote videos coming from more than 12 connected users
-   Showing muted participants' intimation in grid/gallery view in a live session
-   Showing local video on top of the grid/gallery view in a live session
-   Generate Images thumbnails in One2One and Bubble conversations
-   Showing Popup intimation for recording start and stop
-   Ability to reconnect after a few seconds once disconnected


## [1.10.0] - 2020-11-27
-   Offline whiteboard support to allow users to use it without a call
-   Ability to share offline whiteboards in the classroom and meeting
-   Import PDF as background in Whiteboard
-   Export board from Whiteboard as PDF file
-   Undo and Redo features added to Whiteboard
-   Draw the Image as Object Shape on Whiteboard
-   Export Attendance of Classroom from Rainbow Classroom
-   Added support for Multi-language across the application
-   Attendance KPIs Charts added to Rainbow Classroom
-   Local and Remote Whiteboard Sharing Intimation
-   Grid/Gallery layout for 12 videos support in the live classroom and group session
-   Live Classroom Session Dock View
-   New login screen for Rainbow Classroom
-   Canvas LMS sections/classrooms grouping based on the course name
-   Reset host permissions at classroom sessions end.


## [1.9.0] - 2020-10-30
-   Ability for the host to kick a student from a live classroom and group session
-   PopUp dialogues added for warnings, errors and success messages
-   Whiteboard sharing in live classroom and group session
-   Whiteboard support added for groups
-   Search students in Attendance Session
-   Ability to Select students while provisioning from LTI setup
-   Ability to Sort and filter students from LTI setup
-   State maintenance of selected students on navigating back and forward in the LTI setup
-   Provisioning summary view in LTI Setup
-   Canvas LMS Integration with Rainbow Classroom
-   Export Provisioning summary list from LTI Setup
-   Support Multiple Classes against multiple sections found under a course from Canvas LMS


## [1.8.0] - 2020-10-02
-   Classroom live call session interface updated (Rainbow)
-   Group live call session interface updated (Rainbow)
-   One2One live call session interface updated (Rainbow)
-   Attendance - Presence filter added
-   Whiteboard support in group sessions
-   Whiteboard fullscreen mode added
-   Whiteboard widescreen mode added
-   Update profile picture support added
-   File sharing details tab added in course/classroom conversation details
-   File sharing details tab added in groups conversation details
-   Fixed: connected participant issue
-   Fixed: screen share fullscreen for chrome


## [1.7.0] - 2020-09-18
-   Whiteboard Integration in Rainbow Classroom
-   Start a classroom session with a whiteboard
-   Switch/Jump in-between boards while a live classroom whiteboard session going on
-   Re-open/resume boards from previous classroom sessions
-   Rename a whiteboard
-   Select all students option while setting up a group
-   Added a screen of the live progress of students at the Final Step of Setup Rainbow Classroom Interface
-   New tab for the whiteboard in classroom conversation
-   Whiteboard session connected students' detail
-   Draggable left pane for better visibility of courses and conversations
-   Filters added on the group's tab under conversation
-   Conversation User Interface has been updated
-   Added a company header on the home page
-   Cards Shape for Courses and Groups
-   Course Page User Interface Updated
-   Groups Page User Interface Updated
-   File Page User Interface Updated
-   Left panel redesigned to show relevant groups under a classroom/course
-   Settings and My Profile sections are moved to models with new user interface
-   PNGs are replaced with SVG sprite


## [1.6.0] - 2020-09-11
-   Multi-lingual Support
-   sidebar UI upgraded
-   recent conversations panel UI upgraded
-   connected user UI upgraded
-   active conversation added
-   The ability to search for students inside a classroom
-   Ability to full-screen the incoming screen share video stream
-   Quick access section under each course to show associated groups


## [1.5.0] - 2020-08-28
-   Attendance (Classroom bubble conference session history)
-   Groups Main Menu. With a list of groups and details
-   Add Students to an existing study group
-   Switch/Jumping in-between study groups
-   Single Sign On (From Moodle to Rainbow Classroom)
-   Bigger Screen Sharing Interface for Audio Calls and Conference Sessions
-   By default DOCK classroom and study group conversation details
-   Start/Join icons are updated
-   User Interface Enhancements
-   Respective labels on available students and students in class
-   Navigation buttons behaviour
-   Highlight student name upon selection or movement
- The first student will be selected by default in both lists for easy movements
-   By default, new classroom rules are set to NO (Disabled)
-   By default, all students' rules in the new classroom are set to NO (Disabled)
-   Quick access section for active classroom live sessions


## [1.4.0] - 2020-07-24
-   Active Speaker during a live classroom session
-   Classroom bubble settings - Moodle End
-   Classroom bubble settings - LMS End
-   Study Groups Management Interface inside a classroom
-   Setup (Create, Delete & Update) study group
-   Add or remove students from a study group
-   Conversation with students in a study group
-   Conference in the study group
-   Screen sharing in the study group
-   Delete a study group
-   Archive a study group
-   The ability for the host/LMS administrator to enrol new students from Moodle through Re-Setup
-   Removing students from the rainbow classroom for student deletion in Moodle  through Re-Setup
-   Rainbow Classroom Setup New User Interface
-   Listing of related study groups in a classroom for quick access
-   Classroom bubble settings synchronization
-   Quick access to the study group in the left panel


## [1.3.0] - 2020-06-26
-   Incoming Conference Call intimation
-   Search Students in the classroom and during a live classroom session
-   Sort Students in the classroom and during a live classroom session
-   Conference call recording - (Audio Only, Audio + Video, Audio + Screensharing, Audio + Video + Screensharing).
-   One2One call recording - (Audio Only, Audio + Video, Screensharing Only, Audio + Screensharing, Audio + Video + Screensharing).
-   Enable/Disable Chat for a participant in a conference.
-   Enable/Disable Audio for a participant in a conference.
-   Enable/Disable Video for a participant in a conference.
-   Enable/Disable ScreenShare for a participant in a conference.
-   Enable/Disable FileShare for a participant in a conference.
-   Enable/Disable Chat for all participants in a conference.
-   Enable/Disable Audio for all participants in a conference.
-   Enable/Disable Video for all participants in a conference.
-   Enable/Disable FileShare for all participants in a conference.
-   Enable/Disable ScreenShare for all participants in a conference.


## [1.2.0] - 2020-06-05
-   Display a list of enrolled students from moodle
-   Select students to add to the Rainbow classroom bubble
-   New student enrollment into the Rainbow classroom bubble
-   Conference call recording - Audio Only
-   One2One call recording - Audio Only
-   New student enrollment
-   Presence management
-   Display a list of connected participants in a conference call
-   Files Management
-   Files uploading in conversation and bubble
-   File preview before sending into a conversation/bubble
-   Files sorting
-   Files filtering
-   File details (name, size, type, date, shared with)
-   Storage information
-   Network disconnection (intimation and reconnection)
-   Mute/Unmute yourself in a Conference call
-   Mute/Unmute single participant in Conference call
-   Mute/Unmute all participants in the Conference call
-   Fixed: change password dialogue


## [1.1.0] - 2020-05-08
-   Setup course bubble
-   Add/Update/Remove students from the course bubble
-   Setup (Create, Delete & Update) classroom Bubble
-   Add or remove students to a classroom bubble
-   Conversation with students in classroom bubble
-   Conversation with an individual student
-   Conference in classroom bubble
-   Screen sharing in classroom bubble
-   Classroom bubble notifications
-   Delete classroom bubble
-   Archive classroom bubble
-   Listing of students as joined and absent during a classroom live session
-   Screen sharing to an individual student
-   Ability to manage settings related to audio and camera
-   Audio/Video session with an individual student
-   Auto acceptance of the invitation to a bubble classroom
-   Role-based restricted permissions
-   Classroom bubble notifications
-   Screen sharing in classroom bubble
-   Classroom bubble notifications
-   Conversation with an individual teacher
-   Screen sharing with an individual teacher
-   Audio/Video session with an individual teacher
-   Ability to manage settings related to audio and camera
-   Ability to forward messages to teachers and to other classrooms