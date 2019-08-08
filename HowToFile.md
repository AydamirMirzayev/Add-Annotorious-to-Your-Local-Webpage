# Add-Annotorious-to-Your-Local-Webpage
A quick guide on how to add Annotorious to your local webpage. 

1. 
Before adding Annotorious to your webpage you first need to create one. If you already have your webpage you can omit this step.
1.1 To create the webpage to your project folder i.e whenever you want to store the files of this project and create a .txt file. 
Omit special chracter in the name of the .txt file. 
1.2 Open your txt file and paste the text provided in this link 
https://www.codecademy.com/articles/local-web-page. This will be the main body of your webpage. Save and close the txt file and rename
it to .html file.  When you click on the file a local webpage on your browser will pop up

2. 
2.1 Then go ahead and download Annotorious from this link: https://github.com/annotorious/annotorious/releases/tag/v0.6.4
Note that you only need the .zip file. Download it to a random location and extract.

Note: The .zip file already contains an example webpage which you can also use as a reference. But it contains a bunch of other
decorative elements which makes it hard to read for inexperienced deveopers. In this project, we will use only necessary elemnts 
without decoration. 

2.2 The files that you need from the .zip file are:
"annotorious.min.js", "annotorious-dark.css", "DarkSprite.png" and "feather_icon.png" locate and copy them to your project folder where 
your .txt file is. 

2.3 Pick an image of your choice and place it into your project folder as well, if you want to store the image elsewhere that is ok, you
will just need to provide the full address of the image. 

3. Add the final lines 
3.1 open your .txt that you recently converted to .html (convert it back to .txt first) and insert these lines into it after  'title' :
<link rel="stylesheet" href="annotorious-dark.css" />
<script src="annotorious.min.js"></script>
      
and this in 'body' 
<img src="file:a.jpeg" class="annotatable">
make sure to account for your image name. 

3.2 Now your txt file is ready, convert it back to the .html and click on it you should see the webpage
   
