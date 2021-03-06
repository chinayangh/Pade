P&agrave;d&eacute;
=====

[P&agrave;d&eacute;] is the Yoruba word for "Meet". P&agrave;d&eacute; (the "p" is pronounced explosively) is the renamed [Openfire Meetings] Chrome Extension. It is a unified communications client for Openfire Meetings and uses the following front end web applications.

* [Jitsi Meet](https://jitsi.org/jitsi-meet/) for audio/video conferencing, screen share and real-time application collaboration
* [ctxPhone](https://collecttix.github.io/ctxSip/) for SIP based telephony with FreeSWITCH
* [Candy Chat](https://candy-chat.github.io/candy/) for instant messaging and group chat

All applications run from within a chrome extension and together provide:

* Modern HTML5 user interface;
* Openfire user authentication;
* Chat, Audio and Video conferencing;
* Telephone (SIP) conferencing;
* Online Meeting/Conference hosting and planner with a calendar or CRON trigger;
* Screen sharing;
* Co-browsing;
* Application sharing (PDF presentation, realtime collaborative scrum board, drawing and shared WOOT text editor) 
* Simple API for making any web page collaborative.
* Fastpath agent support with audio and video conferencing.

To install, visit the [Chrome Web Store](https://chrome.google.com/webstore/detail/pade-openfire-meetings/fohfnhgabmicpkjcpjpjongpijcffaba?hl=en)

On your [Openfire] server, you will need at least the two [Openfire Meetings] plugins and the [bookmarks](https://www.igniterealtime.org/projects/openfire/plugins.jsp) plugin. If you are running an [Openfire] server lower than 4.2, you will also need the websocket plugin. 

For the advanced telephony features with SIP and a REST API, you will need the [Etherlynk version of Openfire Meetings which includes the ofswitch and ofchat plugins](https://github.com/Traderlynk/ofmeet-openfire-plugin) and the [Openfire SIP Phone](http://www.igniterealtime.org/projects/openfire/plugins/sip/readme.html) plugin.

-------
[Openfire Meetings]:https://discourse.igniterealtime.org/c/openfire-plugins/openfire-meetings
[P&agrave;d&eacute;]: https://chrome.google.com/webstore/detail/pade-openfire-meetings/fohfnhgabmicpkjcpjpjongpijcffaba?hl=en-GB
[Openfire]:http://www.igniterealtime.org/projects/openfire/index.jsp
[Ignite Realtime]:http://www.igniterealtime.org
