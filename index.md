## Basic Modal for you website
Create simple modals for your website using the basicModal files.
Simple and very few lines of coding needed.
Created in Vanilla JavaScript and CSS
Just link the js and css files and you are ready to go.

### Features
- Responsive
- Can be used with HTML content, images, videos
- Edit the way the scrollbar looks

What else do you need from a basic modal.

## How to Use

1. link the css files in the header<br>
   ` <link rel="stylesheet" href="scrollbar.css" />`<br>
   ` <link rel="stylesheet" href="modal.css"> `
 
2. Link the js file at the bottom of body tag<br>
      `<script src="modal.js"></script>`
 
### Steps for HTML Modal

3.  Create a link/button to open modal<br>
      `<button type="button" class="open-modal" data-modal-id="modal1">Open Modal</button>`
      
4. Create the modal<br>
  
  `<div class="custom-modal modal" id="modal1">`<br>
   ` <div class="popup">`<br>
    `  <p>Some text in the 2nd Modal..</p>`<br>
     ` <p>`<br>
      `  Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fuga dolores
        sed fugit assumenda. Sint ipsam neque officia laborum recusandae
        voluptate.`<br>
      `</p>     `<br> 
    `</div>`<br>
  `</div>`  <br>
  ###  Steps for images / videos
  
  3. Create a link to open modal and add the img/ video inside the link<br>
  `<a href="#" class="open-image eye">
    <img class="image"
      src="https://images.pexels.com/photos/3732527/pexels-photo-3732527.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
      alt="tree is good">
  </a>`
  ### OR
  `
  <a href="#" class="open-image">
    <video class="video" src="./Assets/video.mp4" controls></video>
  </a>
  `
  
  ## STYLING
  
  For styling css variables are used !
  
  ### Presets<br>
  
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
    To change these you can use this type of css in your stylesheet
       .custom-modal.modal {
      --modal-background: #00000066;
      --width: 30%;
      --max-height: 98%;
      --popup-top: 1%;
    }

    .custom-modal.gallery {
      --modal-background: #00000066;
      --width: 40%;
      --max-height: 98%;
      --popup-shadow: 0px 0px 0px #00000066;
    }
    
    or you can use regular css
    .gallery {
        width:100px;
    }
    but it can cause problems so it is good to use the css variables mentioned before in the presets.
  
