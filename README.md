# basicModal
A very simple way to create modals with very less code to be written

### Features

- Responsive modal
- Works with HTML Content(for popups, alerts, and much more any where you want ) , Images ( for gallery )

# How to use 

1. Link css files

`<link rel="stylesheet" href="scrollbar.css" />`
`<link rel="stylesheet" href="modal.css">`

2. Link js file

`<script src="modal.js"></script>`


FOR HTML CONTENT MODAL

3. Add link/button for opening

`<button type="button" class="open-modal" data-modal-id="modal1">Open Modal</button>`

4. Add the modal

`<div class="custom-modal modal" id="modal1">
    <div class="popup">
        <p>
            Some text in the 1st Modal..
        </p>
        <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fuga dolores sed fugit assumenda. Sint ipsam neque officia laborum recusandae voluptate.
        </p>
        <button type="button" class="open-modal" data-modal-id="hahaha">Open 2nd Modal</button>
    </div>
</div>`

FOR IMAGE MODAL

3. Add link for opening

`<a href="#" class="open-image">
    <img class="image" src="https://images.pexels.com/photos/2661176/pexels-photo-2661176.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=500" alt="nice background">
</a>`

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
