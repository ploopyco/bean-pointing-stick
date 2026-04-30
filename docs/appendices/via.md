# Appendix F: Using VIA

The Bean's can be customized using a web application called "VIA". Currently, a bit of additional work is necessary to get VIA to work, but it should only take about thirty seconds.

Begin by copying and pasting the following into a text file, saving it as *bean.json*:

    {
      "name": "Ploopy Bean Pointing Stick",
      "vendorId": "0x5043",
      "productId": "0x81DC",
      "matrix": {
        "rows": 1,
        "cols": 4
      },
      "customKeycodes": [
        {
          "name": "DPI Config",
          "title": "DPI Config",
          "shortName": "DPI"
        },
        {
          "name": "Drag Scroll",
          "title": "Drag Scroll",
          "shortName": "DragScl"
        }
      ],
      "layouts": {
        "keymap": [
          [
            {
              "w": 2,
              "h": 2
            },
            "0,1",
            {
              "x": 0.25,
              "w": 2,
              "h": 2
            },
            "0,2"
          ],
          [
            {
              "y": 1.25,
              "w": 2,
              "h": 2
            },
            "0,0",
            {
              "x": 0.25,
              "w": 2,
              "h": 2
            },
            "0,3"
          ]
        ]
      }
    }

- Next, navigate to [the VIA web app](https://usevia.app), using **Microsoft Edge, Chrome, or Opera**. Any other browser that supports WebHID will work, too.
- Look at the top toolbar of the web application, and click the tab called *DESIGN*.
- Uncheck *Use V2 definitions (deprecated)*.
- Click *Load* and upload the *bean.json* file that you saved on your computer.
- Plug in the Bean if it wasn't plugged in already.
- Look at the top toolbar of the web application, and click the tab called *CONFIGURE*.
- Click *Authorize Device*. A modal window should pop up, and you should see the *Ploopy Bean* as an option to connect. Do so now.

You should now see a representation of the buttons of the Bean in the web app. You are now free to modify the button's functionality.
