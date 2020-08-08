# basicModal
A very simple way to create modals with very less code to be written

### Features

- Responsive modal
- Works with HTML Content(for popups, alerts, and much more any where you want ) , Images ( for gallery )

### Things comming in future

- Video support
- iframe support


# Styling

I am using CSS Variables for dynamic changing.

## Presets

    .custom-modal.modal{
      --modal-background: #00000066;
      --width: 60%;
      --max-height: 80%;
      --popup-top: 10%;
      --popup-background-color: white;
      --popup-background: var(--plain-bg);
      --popup-border-width: 6.5px;
      --popup-border-radius: 5px;
      --popup-padding: 20px;
      --popup-overflow: hidden scroll;
      --popup-shadow: 0px 0px 10px #00000066;
      --popup-top: 10%;
      --handlecolor: #fa6d8b;
      --handlecolorhover: #fc4c72;
      --close-color: #888;
    }
    .custom-modal.gallery{
      --modal-background: #00000066;
      --width: 60%;
      --max-height: 98%;
      --popup-top: 10%;
      --popup-background-color: transparent;
      --popup-background: var(--plain-bg);
      --popup-border-width: 0px;
      --popup-border-radius: 0px;
      --popup-padding: 0px;
      --popup-overflow: hidden;
      --popup-shadow: 0px 0px 10px #00000066;
      --popup-top: 50%;
      --close-color: #fff;
    }
    
   If You want changes in how this is you can change thses variables in your custom css or change css for elements directly. But that can disrupt the styling entirely, so you should prefer to change the values of the preset variables in your custom css file.
