---
title: "Alerts"
description: "Alerts pattern description"
layout: "guide"
weight: 1
---

## Definition

Alerts are used to capture the attention of the user in an intrusive way. Sometimes just to say that something went right, others to say that something needs to be reviewed.

Alerts are possible to define in 4 different colors, grey for the default type of message and four other corresponding to status colors.

## Usage

### Types

|Type|Usage|
|-----|-----|
|Information|**Blue color**. Information alerts are used to inform users about things that occur while they are carry out a task.|
|Success|**Green color**. Success alert messages will appear when everything was ok. (E.g.: “The user was created successfully”).|
|Warning|**Yellow color**. This alert lets users know that the action they performed was done but there are some issues with it. (E.g. The item was created but with there were some issues).|
|Error|**Red color**. This alert indicates that something went wrong after performing an action. (E.g.: Form couldn’t be saved because some data was missing)|



### Variations

#### Temporary alert stripe
This message is meant to disappear after a short period of time, so it must be the case that the user doesn't have time to read it and there must not be a consequence for not reading it. This type of alerts have embedded links in case you need them.

![temporary information alert stripe](../../../images/alertTemporaryInfo.png)

![temporary success alert stripe](../../../images/alertTemporarySuccess.png)

![temporary warning alert stripe](../../../images/alertTemporaryWarning.png)

![temporary error alert stripe](../../../images/alertTemporaryError.png)

#### Dismissible alerts stripe
Use this kind of alerts to inform users about something and to ensure they don‘t miss the information. These alerts can contain links to carry out actions such as undoing actions or visiting a page.
This alert is placed right below the navigation bar.

![dismiss information alert stripe](../../../images/alertDismissInfo.png)

![dismiss success alert stripe](../../../images/alertDismissSuccess.png)

![dismiss warning alert stripe](../../../images/alertDismissWarning.png)

![dismiss error alert stripe](../../../images/alertDismissError.png)

#### Alert notification				
Notifications display information about something that has happened or is happening in the system. These alerts are not related to actions that are being performed by the user at that moment. Unlike alerts, notifications are displayed on the top right corner of the screen. Both desktop and mobile notifications have similar dimensions.

![notification info alert](../../../images/alertNotificationInfo.png) 
![notification success alert](../../../images/alertNotificationSuccess.png)

![notification warning alert](../../../images/alertNotificationWarning.png) 
![notification error alert](../../../images/alertNotificationError.png)

