# Microsoft Teams APIs

Microsoft Teams is the ultimate hub for teamwork and intelligent communications. Built on the strength and scale of Microsoft 365 with over 120 million users, Microsoft Teams delivers chat-based collaboration, meetings, calling, and enterprise voice features.

![Microsoft Graph's general view](/img/microsoft-graph-dataconnect-connectors-rebrand-800.png "Microsoft Graph's general view")

You can see all the details about the Team's APIs giving a click on [this link](https://docs.microsoft.com/en-us/graph/teams-concept-overview). From now on, we're going to list the APIs we think have a great fit with digital courts processess and its solutions.

## Communication in Virtual Hearings

Communications API is perfect to build service applications (bots) that act like participants in a virtual hearing, and that create and retrieve meetings on behalf of users. This API provides calling functionality as well as the ability to create and retrieve online hearings. You can use service applications (bots) with this API, where the bot can act as a participant in your Microsoft Teams hearings, for example.

* [Call Resource Type](https://docs.microsoft.com/en-us/graph/api/resources/call?view=graph-rest-1.0): The call resource is created when there is an incoming call for the application or the application creates a new outgoing call via a `POST` on `app/calls`.
  * [Get](https://docs.microsoft.com/en-us/graph/api/call-get?view=graph-rest-1.0)
  * [Delete](https://docs.microsoft.com/en-us/graph/api/call-delete?view=graph-rest-1.0)
  * [KeepAlive](https://docs.microsoft.com/en-us/graph/api/call-keepalive?view=graph-rest-1.0)
  * [Answer](https://docs.microsoft.com/en-us/graph/api/call-answer?view=graph-rest-1.0)
  * [Reject](https://docs.microsoft.com/en-us/graph/api/call-reject?view=graph-rest-1.0)
  * [Redirect](https://docs.microsoft.com/en-us/graph/api/call-redirect?view=graph-rest-1.0)

* [Participant Resource Type](https://docs.microsoft.com/en-us/graph/api/resources/participant?view=graph-rest-1.0): Represents a participant in a virtual hearing.
  * [List](https://docs.microsoft.com/en-us/graph/api/participant-get?view=graph-rest-1.0)
  * [Get](https://docs.microsoft.com/en-us/graph/api/participant-get?view=graph-rest-1.0)
  * [Delete](https://docs.microsoft.com/en-us/graph/api/participant-delete?view=graph-rest-1.0)
  * [Mute participant](https://docs.microsoft.com/en-us/graph/api/participant-invite?view=graph-rest-1.0)
  * [Invite participant](https://docs.microsoft.com/en-us/graph/api/participant-invite?view=graph-rest-1.0)