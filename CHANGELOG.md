# Change Log

<a name="1.4.7-release"></a>
# Version 1.4.7 (2017-05-22)

### sdk url
* Iframe SDK
	- `https://mgk.straas.net/sdk/1.4.7/iframe-sdk.js`
* MessageManager SDK
	- `https://mgk.straas.net/sdk/1.4.7/message-sdk.js`

### Features

* Add `getArchivedMessagesMeta` API

<a name="1.4.3-release"></a>
# Version 1.4.3 (2017-05-15)

### sdk url
* Iframe SDK
	- `https://mgk.straas.net/sdk/1.4.3/iframe-sdk.js`
* MessageManager SDK
	- `https://mgk.straas.net/sdk/1.4.3/message-sdk.js`

### Features

* Add `getArchivedMessages` API

<a name="1.4.1-release"></a>
# Version 1.4.1 (2017-04-19)

### sdk url
* Iframe SDK
	- `https://mgk.straas.net/sdk/1.4.1/iframe-sdk.js`
* MessageManager SDK
	- `https://mgk.straas.net/sdk/1.4.1/message-sdk.js`

### Bugs
* MessageManager SDK
	- Fix `getMessages` API perPage parameter issue

<a name="1.4.0-release"></a>
# Version 1.4.0 (2017-04-17)

### sdk url
* Iframe SDK
	- `https://mgk.straas.net/sdk/1.4.0/iframe-sdk.js`
* MessageManager SDK
	- `https://mgk.straas.net/sdk/1.4.0/message-sdk.js`

### Features
* Iframe SDK
	- Add welcome new user notification
	- Add i18n support flag `language`, please refer [this](https://github.com/StraaS/StraaS-web-messaging/wiki/StraaS-Web-Messaging#iframe-sdk-getting-started)

### Bugs
* MessageManager SDK
	- Fix `user_remove` event

<a name="1.3.2-release"></a>
# Version 1.3.2 (2017-03-31)

### sdk url
* Iframe SDK
	- `https://mgk.straas.net/sdk/1.3.2/iframe-sdk.js`
* MessageManager SDK
	- `https://mgk.straas.net/sdk/1.3.2/message-sdk.js`

### Features
* MessageManager SDK
	- Add [`getSendMessageInterval`]((https://straas.github.io/StraaS-web-messaging/MessageManager.html)) API to learn message cold down time
* Both SDK
	- Optimize sdk lib size

<a name="1.3.1-release"></a>
# Version 1.3.1 (2017-03-30)

### sdk url
* Iframe SDK
	- `https://mgk.straas.net/sdk/1.3.1/iframe-sdk.js`
* MessageManager SDK
	- `https://mgk.straas.net/sdk/1.3.1/message-sdk.js`

### Features
* Both SDK
	- Add `straasSupport` flag to disable straas log support, please refer [this](https://github.com/StraaS/StraaS-web-messaging/wiki/StraaS-Web-Messaging#messagemanager-sdk-getting-started)

### Bugs
* MessageManager SDK
	- Fix `messages` event does not work bug

<a name="1.3-release"></a>
# Version 1.3 (2017-03-28)

### sdk url
* Iframe SDK
	- `https://mgk.straas.net/sdk/1.3/iframe-sdk.js`
* MessageManager SDK
	- `https://mgk.straas.net/sdk/1.3/message-sdk.js`
### Bugs
* Both SDK
	- Enhance retry connection mechanism
	- Fix APIs `blockUser` and `updateUserRole` error

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
