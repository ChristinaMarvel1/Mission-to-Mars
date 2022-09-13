# Mission-to-Mars
Scrape Full-Resolution Mars Hemisphere Images and Titles; Update the Web App with Mars Hemisphere Images and Titles; Add Bootstrap 3 Components
## Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles (40 points)


1. Make a copy of your Mission_to_Mars.ipynb file, and rename it Mission_to_Mars_Challenge.ipynb.

2. Download the Mission_to_Mars_Challenge_starter_code.ipynb, copy the starter code, and paste at the end of your Mission_to_Mars_Challenge.ipynb file.

3. In Step 1, use your browser to visit the Mars Hemispheres (Links to an external site.) website to view the hemisphere images.
![1-0](https://user-images.githubusercontent.com/107659667/189799235-5bae0e90-dc6c-495f-9eeb-e87b11b5c400.jpg)
![1-0-1](https://user-images.githubusercontent.com/107659667/189799243-8e5ff0ab-7b6b-49cd-9881-28e21bd6681a.jpg)
![1-0-2](https://user-images.githubusercontent.com/107659667/189799249-d242decc-5c67-4f19-8db1-043a1f05e131.jpg)
![1-0-3](https://user-images.githubusercontent.com/107659667/189799261-a68a1032-523e-4848-9fad-8497356b8236.jpg)
![1-0-4](https://user-images.githubusercontent.com/107659667/189799274-c280f5fb-4179-4157-9179-60c6583d2674.jpg)

4. Use the DevTools to inspect the page for the proper elements to scrape. You will need to retrieve the full-resolution image for each of Mars's hemispheres.
![1-1](https://user-images.githubusercontent.com/107659667/189799279-086b6a5a-9d67-4507-9425-039cee310056.jpg)

5. In Step 2, create a list to hold the .jpg image URL string and title for each hemisphere image.
![1-2 3](https://user-images.githubusercontent.com/107659667/189799284-2cb20b1c-e120-4df1-a763-0c9b7f1719b4.jpg)

6. In Step 3, write code to retrieve the full-resolution image URL and title for each hemisphere image. The full-resolution image will have the .jpg extension.

![1-2 3](https://user-images.githubusercontent.com/107659667/189799909-87e5d672-ec33-4b99-8fe1-56eca71da3ce.jpg)

7. Loop through the full-resolution image URL, click the link, find the Sample image anchor tag, and get the href.

8. Save the full-resolution image URL string as the value for the img_url key that will be stored in the dictionary you created from the Hint.

9. Save the hemisphere image title as the value for the title key that will be stored in the dictionary you created from the Hint.

10. Before getting the next image URL and title, add the dictionary with the image URL string and the hemisphere image title to the list you created in Step 2.

11. In Step 4, print the list of dictionary items. Your list should look like the following image:
![1-4](https://user-images.githubusercontent.com/107659667/189799848-fd3a9ec0-45f6-4737-b1de-8cc0b6953c1b.jpg)

12. After you have confirmed that you have the image URLs and titles for all four hemisphere images, quit the browser by executing Step 5.
![1-5](https://user-images.githubusercontent.com/107659667/189799884-f10abb40-7bd8-416c-b89a-5c598f2a9166.jpg)

## Deliverable 2: Update the Web App with Mars’s Hemisphere Images and Titles (40 points)

Using your Python and HTML skills, you’ll add the code you created in Deliverable 1 to your scraping.py file, update your Mongo database, and modify your index.html file so the webpage contains all the information you collected in this module as well as the full-resolution image and title for each hemisphere image.

1. Export the Mission_to_Mars_Challenge.ipynb file as a Python file, and save it as Mission_to_Mars_Challenge.py.

2. In the def scrape_all() function in your scraping.py file, create a new dictionary in the data dictionary to hold a list of dictionaries with the URL string and title of each hemisphere image.

3. Below the def mars_facts() function in the scraping.pyfile, create a function that will scrape the hemisphere data by using your code from the Mission_to_Mars_Challenge.py file. At the end of the function, return the scraped data as a list of dictionaries with the URL string and title of each hemisphere image.

4. Run the app.py file, then check your Mongo database to make sure that you are retrieving all of the data.

5. Modify the index.html file to access your database, and retrieve the img_url and title as you loop through the dictionary in the database using {% for hemisphere in mars.hemispheres %}. The dictionary in the mars hemispheres database is the dictionary that was created from the Hint after Step 3 in Deliverable 1.

6. Run the app.py file, open the index.html file, and click the "Scrape New Data" button.

7. After you have scraped the data, confirm that your webpage has the full-resolution images and the titles of the four hemisphere images, like the image below.

8. Save your Mission_to_Mars_Challenge.ipynb file, the updated scraping.py file, and the updated index.html file.
 
## Deliverable 3: Add Bootstrap 3 Components 

Follow the instructions below to complete Deliverable 3.

1. Use the Bootstrap 3 grid system (Links to an external site.) examples to update your index.html file so your website is mobile-responsive. Use the DevTools to test the responsiveness of your website.
Click on the Toggle Device Toolbar icon to open the UI that enables you to simulate responsiveness.
Choose a device to test your webpage, as shown in the following image:

2. Add two other Bootstrap 3 components from this list (Links to an external site.). Examples include:
Styling the "Scrape New Data" button.
Customizing the facts table.
Adding the hemisphere images as thumbnails, like the image below.




