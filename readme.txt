Name: Goodbye Spammer
Description: Makes it easy to delete all traces of a spammer from your forum.
Website: http://mattrogowski.co.uk
Author: MattRogowski
Authorsite: http://mattrogowski.co.uk
Version: 1.1
Compatibility: 1.6.x
Files: 2
Templates added: 5
Template changes: 3
Settings added: 5 (1 group)

Information:
This plugin adds a form to make it easy to remove everything a spammer may have added to your forum.

Includes an admin configurable option for whether spammers should be banned or deleted, and has a setting to stop the tool being used on people with more than a certain amount of posts.

Includes the ability to submit information on the spammer to the StopForumSpam database.

To Install:
Upload ./inc/plugins/goodbyespammer.php to ./inc/plugins/
Upload ./inc/languages/english/goodbyespammer.lang.php to ./inc/languages/english/
Upload ./images/goodbyespammer_postbit.png to ./images/
Go to ACP > Plugins > Activate
Go to ACP > Configuration > Goodbye Spammer Settings > Configure settings > Save.

Change Log:
09/03/11 - v0.1 -> Initial 'beta' release.
10/03/11 - v0.1 -> v0.1.1 -> Fixed a bug where various misc.php actions would display an error from Goodbye Spammer about selecting an invalid user. To upgrade, reupload ./inc/plugins/goodbyespammer.php
29/03/11 - v0.1.1 -> v0.1.2 -> Added a setting to choose which usergroups can use Goodbye Spammer, and it will now add a moderator log when the tool is used. To upgrade, deactivate, reupload ./inc/plugins/goodbyespammer.php and ./inc/languages/english/goodbyespammer.lang.php, activate.
31/07/11 - v0.1.2 -> v1.0 -> Fixed a bug where the reported posts count wasn't always updated. Fixed a bug where the link on the profile showed on banned user's profiles. Fixed a bug where the link showed on a profile if a user had more than the post count limit under certain conditions. Fixed a bug where the birthday would not be cleared. Fixed a bug where an SQL error would occur if you had deleted all custom profile fields. Added the ability to disable the post count limit check. Added the ability to ban spammer's IPs. To upgrade, deactivate, reupload ./inc/plugins/goodbyespammer.php and ./inc/languages/english/goodbyespammer.lang.php, activate. If you have entered a StopForumSpam API key you may want to make a note of it before you upgrade so you can enter it again afterwards.
XX/XX/13 - v1.0 -> v1.1 -> Added link to Goodbye Spammer form in postbit. To upgrade, deactivate, upload ./images/goodbyespammer_postbit.png to ./images/, reupload ./inc/plugins/goodbyespammer.php and ./inc/languages/english/goodbyespammer.lang.php, activate.

Copyright 2010 Matthew Rogowski

 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at

 ** http://www.apache.org/licenses/LICENSE-2.0

 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.