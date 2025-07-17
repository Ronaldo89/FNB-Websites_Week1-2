# Lesson 1: Introduction to HTML
About HTML
HTML5 is a programming language, and is the language of the Web.

HTML codeHTML stands for Hyper Text Markup Language, and is used for structuring and presenting content on websites.  

HTML 5
HTML has gone through numerous versions in the past, and the current version is HTML5. HTML versions are standardised by an organisation called the World Wide Web Consortium (W3C). 

Benefits of HTML 5
HTML5 provides support for the latest multimedia 
It is easily readable by humans and consistently understood by computers and devices (web browsers, parsers, etc.). 
Many features of HTML5 have been built to run on low-powered devices such as smartphones and tablets.
HTML5 is a good language to develop cross-platform mobile applications (applications that work on various devices running various operating systems, such as iOS and Android).
What's new in HTML5
HTML5 adds many new syntactic features. These include the following new features:

<video> element: to display video in web pages
<audio> element: to play audio within web pages
<canvas> element: to draw graphical objects
Integration of scalable vector graphics (SVG) content (replacing generic <object> tags)
MathML for mathematical formulas
These features are designed to make it easy to include and handle multimedia and graphical content on the web without having to resort to proprietary plugins and APIs.

HTML5 also includes the following new features, among others:

HTML Geolocation - for making navigation apps
HTML Drag and Drop - for dragging and dropping objects on the screen
HTML Local Storage - for storing data on mobile devices
HTML Web Workers - for speeding up page loading times by running multiple processes at the same time.

Tips:
1.Folders: Be careful which folder you save your work into. Very often, people create a folder, but save their files to another folder by mistake, and then they cannot find their files.
2.Extension file names: the extension file name is the part of the name after the 'dot'. For example, the file index.html has an extension filename of html. The extension file name is very important! Having the wrong extension file name will cause your page not to load in the browser. When you are saving your file for the first time, check (and then double-check!) that you have the correct extension file name: .html not .txt
3.Double extension file name: If you are not careful, your file can be saved with a double extension filename like index.txt.html.
4.HTML tags: this is what an open tag looks like:<html>
5.HTML tags: this is what a close tag looks like:</html>
6.HTML tags: the difference between an open tag and a close tag is the forward slash: /
7.HTML tags: be careful not to use the back slash \ in your tags. This is wrong.
8.Save your work: make it a habit of saving your work regularly.


Lesson 5: Web File Formats
About Web Files
By now you have noticed we are using the file extension .html or .htm for your web pages. These are the file types for HTML pages.

Similarly, there are other types of files you will come across as you work with websites and apps. As a developer, it is important to understand these file types, and what types of content they contain.

Popular Web File Types
Some of the major web file formats you will encounter are:

.html and .htm: As the format suggests, all HTML files are stored in either of these formats.

.css: Cascade Style Sheets are stored in .css files.

.jpeg .jpg .png .gif: These are image types. See the next section to decide which image type is best for different purposes.

.mp4 .webm .ogg: These are video file formats.

.xml: XML files are usually used for configuration information.

.php: PHP scripts contain backend server-side scripts for your application.

Working with images:

n HTML images are defined with the Image tag. 

The Image tag contains attributes only, and does not have a closing tag. 

The src attribute defines the url (web address) of the image. You can use PNG, JPEG or GIF image files. Make sure you specify the correct image file name in the src attribute. 

Remember: the image name is always case sensitive. In other words, if your image is called "Car.jpg" (with an uppercase "c") and you type "car.jpg" (with a lower case "c") then your image will not be found. 

Make sure you have the correct extension file name too. These are also case-sensitive, so .JPG and .jpg are regarded as totally different. 

Tips
If your browser does not show your image:

1. Spelling: be careful with how you spell img and src.
2. Double quotes: make sure you have your double quotes " in place, as in the code snippet above.
3. Folder name: ensure you have the correct folder name before the file name. So if your file is called "car.jpg" and is stored in a folder called images, then you will type src="images/car.jpg"
4. Case sensitive: as mentioned in the lesson, your computer will recognise the file name image.jpg and Image.jpg as two completely different files. So make sure you match the correct case of each letter.
5. Forward slash: are you using the forward slash / and not the back slash?


HYPERLINKS
A hyperlink is a text or an image you can click on, and jump to another page, website or document.

In HTML, links are defined with the <a> tag

The href attribute specifies the destination address (http://www.compukids.me)

The link text is the visible part (visit our website)


About File Names
When naming your files, keep the following in mind:

Avoid spaces in your filenames:

about-us.html          -->Right

about us.html           -->Wrong



Use small (lowercase) letters:

about.html              -->Right

ABOUT.HTML         -->Wrong



Use a descriptive name:

lions.html              -->Right

p1532.html            -->Wrong



Keep the names short:

lions.html                -->Right

a-page-about-lions-in-the-pine-city-zoo.html              -->Wrong

What is CSS?
Cascading Style Sheets,  or CSS, is a simple design language that we use to make web pages beautiful and presentable.

Using CSS, you can set the colours, fonts and background images.

CSS is different from HTML, and they both serve completely different functions. Using HTML you create the structure of your page, and with CSS you add colors and styles to your page.

Benefits of CSS
CSS helps your pages load faster
CSS saves time
CSS makes maintaining a site easy


A div box acts like a container on your page. It limits styles to a specific area on the screen, and prevents these styles from being applied elsewhere.

We add a DIV box to our page using the <div> tag.

The  <div>  tag must be given an id or a class name. Our CSS will identify a div box by its id or class name.