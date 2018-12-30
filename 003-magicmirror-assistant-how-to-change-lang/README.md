Here is the language list supported by gooogle.

https://developers.google.com/assistant/sdk/reference/rpc/languages

var config = {
...
		{
			module: "MMM-AssistantMk2",
			position: "top_right",

			config: {
				record: {
					recordProgram : "arecord",  
					device        : "plughw:1",
				},
				
				notifications: {
					ASSISTANT_ACTIVATED: "HOTWORD_PAUSE",
					ASSISTANT_DEACTIVATED: "HOTWORD_RESUME",
				},
				useWelcomeMessage: "brief today",
				profiles: {
					"default" : {
						lang: "ja-JP"
					}
				}
			},
		},
	]

};

/*************** DO NOT EDIT THE LINE BELOW ***************/
if (typeof module !== "undefined") {module.exports = config;}
