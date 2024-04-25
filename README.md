
# Assignment 2

### Part 1: Getting started with HTML structuring

1.	Download ex2-1.txt and make a HTML page. It’s up to you to decide which element is the best semantic match for each chunk of content. 
2.	Add the document structure elements (html, head, meta, title, body). Give the document the title “The Black Goose Bistro News.”
3.	The News page has two posts titled “Summer Menu Items” and “Low and Slow.” Mark up each one as an article.
4.	Identify the publication date for the article with the time element,
5.	You’ll use paragraphs, headings, lists, and at least one special content element. 
6.	The final HTML page should look like figure 1.

Hint 1: 	the location, hours and copyright parts are a footer of this page. Mark each line of content within the footer as a paragraph. You can use

<footer>        </footer> tag

Hint 2: 	the location and hours information some context by putting them inside a div with a name “about” 

<div id=“about.”>      </div> 

Make the labels “Location” and “Hours” appear on a line by themselves by adding line breaks after them. Mark up the hours with the time element (you don’t need the date or time zone portions).

Hint 3: Finally, copyright information is typically “small print” on a document, so mark it up accordingly. As the final touch, add a copyright symbol after the word “copyright” using the keyboard or the &copy; character entity.

Don’t forget to save the file as “index.html” in the folder “part1”. Make sure you double check by accessing the link by yourself too.


<img width="419" alt="image" src="https://github.com/Shibaura-WebDesign-2024/assignment-2-nb23506/assets/167288305/c3c45e78-844e-4442-8090-d010072572a0">


### Part 2: Adding and linking images![image](https://github.com/Shibaura-WebDesign-2024/assignment-2-nb23506/assets/167288305/0cc1d7d8-8db6-4c0f-a048-d34ad13de31a)


In this exercise, you’ll add images to pages and use them as links. All of the full-size photos and thumbnails (small versions of the images) you need have been created for you, and I’ve given you a head start on the HTML files with basic styles as well. Please download the zip file ex2-2.zip from SCOMB and unzip the file. You will find gallery folder. 

Put a copy of the gallery folder on your hard drive, making sure to keep it organized as you find it.

This little site is made up of a main page (index.html) and three separate HTML documents containing each of the larger image views. First, we’ll add the thumbnails, and then we’ll add the full-size versions to their respective pages. Finally, we’ll make the thumbnails link to those pages. Let’s get started.

1.	Open the file index.html, and add burgers-200.jpg and fish-200.jpg to this page to accompany the text. There are already some examples of code for adding images and link from the image. Since the thumbnails will appear 200 x 200 pixels on all devices, I included width and height attribute to tell the browser how much space to leave in the layout. 
Be sure to include the pathnames and thoughtful alternative text descriptions. 
Finally, add a line break (<br>) after the img element. 

2.	Next, add the images (800 x 600 px images) to the individual HTML documents. Check the code in bread.html for example. Don’t forget the path for photo files. Notice also that because this page is not designed to be responsive, and the images will be a fixed size across devices.

3.	Back in index.html, link the thumbnails to their respective files.
** Notice that the URL is relative to the current document (index.html), not to the location
of the image (the thumbnails directory).
Be sure to save each file, and check your work by opening them in the browser window along each step.

If all the images are visible and you are able to link to each page and back to the home page again, then
congratulations, you’re done! The finish version should look like this.


<img width="388" alt="image" src="https://github.com/Shibaura-WebDesign-2024/assignment-2-nb23506/assets/167288305/9c9a6f5f-376c-41cf-a0c6-49d6b4833f88">

Don’t forget to save the file as “index.html” and put all necessary files and subfolders in the folder “part2”. Make sure you double check by accessing the link by yourself too.![image](https://github.com/Shibaura-WebDesign-2024/assignment-2-nb23506/assets/167288305/46ba5b0a-1a46-4171-8363-e16c7efa3d50)


### Part 3: Table

Create a HTML file that include your school timetable, using the format as the following figure. 

Note: The content of timetable should be different than the figure because this is only a fake one.

The only requirement is that this class (Web Design and Programming) must span for two rows, like in the figure.
<img width="496" alt="image" src="https://github.com/Shibaura-WebDesign-2024/assignment-2-nb23506/assets/167288305/eb6a0f33-57e3-4856-9487-5d46558166b1">



Don’t forget to save the file as “index.html” in the folder “part3”. Make sure you double check by accessing the link by yourself too.

