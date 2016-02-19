# These files are posted in response to the Olapic TIM Technical Test:

Solution Description:
1. Scrollable Image Carousel using JQuery
2. Six Images derived from the Olapic API (not ingested, hardcoded in - I had to review the API response and pull some of the images manually)
3. Lightbox Modal view on click of images

Solution Notes:
- Visited the API Documentation and read through the API responses plugging in the Auth Key provided
- Visited the Source Code and analyzed the Olapi Widget snippet on both the Maurice's/Guess websites
- Found out where the photos where stored, found out they could be retrieved via the media endpoints
- Manually pulled the images from the API response (wasn't sure how to ingest/parse into the image tags
- To save time, searched through various proper JS plugins for image-carousels:
-   Used Jcarousel for the Image Carousel
-   Used Featherlite for the Lightbox modal.
- Other notes:
-   Page is responsive, so it will adjust to screen size
-   Page takes a few seconds to load, not sure how to optimize
-   Gathered the images from the following response: //photorankapi-a.akamaihd.net/customers/215757/media/recent?auth_token=0a40a13fd9d531110b4d6515ef0d6c529acdb59e81194132356a1b8903790c18&version=v2.2
