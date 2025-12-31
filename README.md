# Ex.07 Design of Interactive Image Gallery
## Date:27/12/25

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
    h1 {
        text-align: center;
        margin-bottom: 30px;
        color: darkmagenta;
    }

    .gallery {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 15px;
    }

    .gallery img {
        width: 100%;
        height: auto;
        border-radius: 10px;
        cursor: pointer;
        transition: transform 0.3s, box-shadow 0.3s;
    }

    .gallery img:hover {
        transform: scale(1.05);
        box-shadow: 0 10px 20px rgba(0,0,0,0.3);
    }

    /* Lightbox overlay */
    .lightbox {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(0,0,0,0.8);
        display: none;
        justify-content: center;
        align-items: center;
    }

    .lightbox img {
        max-width: 90%;
        max-height: 80%;
        border-radius: 10px;
    }

    .lightbox:target {
        display: flex;
    }

    .close {
        position: absolute;
        top: 20px;
        right: 30px;
        font-size: 30px;
        color: #fff;
        text-decoration: none;
    }
</style>
```
## OUTPUT:
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/fb193a8b-ef6b-459a-88ec-6bcdc5eb632d" />
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/f1413c77-2656-47fa-a982-e373d558e4dc" />
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/6846da1c-e5e2-4e9b-96e0-97e0da4862dc" />
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/a03ffeca-5a93-4e94-af64-28a664070dfc" />
<img width="1013" height="568" alt="image" src="https://github.com/user-attachments/assets/ee94ff3e-dd1e-4a7b-a41f-894c4bcf29c3" />


## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
