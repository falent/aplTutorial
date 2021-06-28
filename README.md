# aplTutorial

APL document, which is a structure that defines how you want to display your content on the viewport

 For example, a simple document might just use the Text component to display plain text. This JSON displays the text "Hello World!" in the center of the viewport:
 ```
{
  "type": "APL",
  "version": "1.6",
  "description": "A simple hello world APL document.",
  "settings": {},
  "theme": "dark",
  "import": [],
  "resources": [],
  "styles": {},
  "onMount": [],
  "graphics": {},
  "commands": {},
  "layouts": {},
  "mainTemplate": {
    "parameters": [
      "payload"
    ],
    "items": [
      {
        "type": "Text",
        "height": "100vh",
        "textAlign": "center",
        "textAlignVertical": "center",
        "text": "Hello World!"
      }
    ]
  }
}
```

