# Mission-to-Mars
Scrape Full-Resolution Mars Hemisphere Images and Titles; Update the Web App with Mars Hemisphere Images and Titles; Add Bootstrap 3 Components
## Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles

Deliverable 1 Instructions
Using BeautifulSoup and Splinter, you’ll scrape full-resolution images of Mars’s hemispheres and the titles of those images.

1. Make a copy of your Mission_to_Mars.ipynb file, and rename it Mission_to_Mars_Challenge.ipynb.
![1-0](https://user-images.githubusercontent.com/107659667/189803685-9260f3d8-0937-4702-96ba-e3a34be3feaa.jpg)
![1-0-1](https://user-images.githubusercontent.com/107659667/189803690-4b7f6dc1-7fff-4cf9-8bfc-8fe03e988994.jpg)
![1-0-2](https://user-images.githubusercontent.com/107659667/189803695-998071e3-02d3-4888-a497-47b90f233bcc.jpg)
![1-0-3](https://user-images.githubusercontent.com/107659667/189803698-a266a978-2ca8-460e-9ed8-98e2e67e21eb.jpg)
![1-0-4](https://user-images.githubusercontent.com/107659667/189803709-7a5379e8-aea4-4065-b65a-2e5a58f72a7f.jpg)
![1-1](https://user-images.githubusercontent.com/107659667/189803718-ca6e66a8-c756-41fa-be5b-fd61c95ef2ad.jpg)

2. Download the Mission_to_Mars_Challenge_starter_code.ipynb, copy the starter code, and paste at the end of your Mission_to_Mars_Challenge.ipynb file.

3. In Step 1, use your browser to visit the Mars Hemispheres (Links to an external site.) website to view the hemisphere images.
![1-2 3](https://user-images.githubusercontent.com/107659667/189803738-c0823900-7c02-49b9-b3fe-a83158066620.jpg)

4. Use the DevTools to inspect the page for the proper elements to scrape. You will need to retrieve the full-resolution image for each of Mars's hemispheres.
![1-4](https://user-images.githubusercontent.com/107659667/189803745-ab805259-2320-456c-b208-6e06bf59779a.jpg)

5. In Step 2, create a list to hold the .jpg image URL string and title for each hemisphere image.
![1-5](https://user-images.githubusercontent.com/107659667/189803770-d1f27fa7-cecc-48dc-9165-a5a90c276332.jpg)

6. In Step 3, write code to retrieve the full-resolution image URL and title for each hemisphere image. The full-resolution image will have the .jpg extension.

7. Loop through the full-resolution image URL, click the link, find the Sample image anchor tag, and get the href.

8. Save the full-resolution image URL string as the value for the img_url key that will be stored in the dictionary you created from the Hint.

9. Save the hemisphere image title as the value for the title key that will be stored in the dictionary you created from the Hint.

10. Before getting the next image URL and title, add the dictionary with the image URL string and the hemisphere image title to the list you created in Step 2.

11. In Step 4, print the list of dictionary items. Your list should look like the following image:
![1-4](https://user-images.githubusercontent.com/107659667/189803762-2a1e54d5-d046-4bd9-b0f1-375d370eeec7.jpg)

12. After you have confirmed that you have the image URLs and titles for all four hemisphere images, quit the browser by executing Step 5.



