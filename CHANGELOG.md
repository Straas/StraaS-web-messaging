# Change Log

<a name="1.2-release"></a>
# Version 1.2 (2017-03-23)

### sdk url
* Iframe SDK
	- `https://mgk.straas.net/sdk/1.2/iframe-sdk.js`
* MessageManager SDK
	- `https://mgk.straas.net/sdk/1.2/message-sdk.js`
### Features
* Iframe SDK
	- Master and MODs highlight
	- New message notification button
	- Add `showMessageSource` flag to determine if show message source icon
		- Default is `false`
		- Please refer [Iframe SDK](https://github.com/StraaS/StraaS-web-messaging/wiki/StraaS-Web-Messaging#iframe-sdk-getting-started) to learn how to set flag
### Bugs
* Iframe SDK
	- Fix that can't remove a moderator by cross button
	- Moderators cold down time bug
* Both SDK
	- raw_data_add event schema bug

<a name="1.1-release"></a>
# Version 1.1 (2017-03-08)

### sdk url
* Iframe SDK
	- `https://mgk.straas.net/sdk/1.1/iframe-sdk.js`
* MessageManager SDK
	-	`https://mgk.straas.net/sdk/1.1/message-sdk.js`
### Features
* MessageManager SDK
	- Add new API `updateUserRole`
	- Modify `blockUser` API's paramter userLabel to user object
	- Modify `reviveUser` API's paramter userLabel to user object
	- Remove `updateUserRoleByUserId` API
	- Remove `updateUserRoleByUserChatId` API
