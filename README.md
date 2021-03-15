<div id="nav_links" markdown="1" style="width: 70%! important;">
[Description](#description)  
[Example](#example)    
[HTML creative guide](#instruction_html)  
  [HTML code and images prerequisites](#html5_instruction)  
    [Adobe Animate CC — banner with single click area](#html5_Animate_one)  
    [Adobe Animate CC — banner with multiple click areas](#html5_Animate_some)  
    [Google Web Designer](#html5_GWD)  
    [Other editors](#html5_other)  
[Adding banner to ADFOX](#add_adfox)
</div>

<div id="nav_links_to" markdown="1" style="width: 29%! important;">
[Viewability check](https://sites.help.adfox.ru/page/220) <img src="/img/checkmark-xxl.png"  width="18px" height="18px">  
[Insertion code with loader.js](https://sites.help.adfox.ru/page/45/#2-1) <img src="/img/checkmark-xxl.png" width="18px" height="18px">  
[Russian version](/page/289) <img src="/uploads/flag-ru.gif"   width="18px" height="18px">
</div>

<div id="description" markdown="1">
##Description 

[note]<a target="_blank" href="https://sites.help.adfox.ru/page/45/#2-1">This template requires codes with loader.js</a>. [/note]

**Banner HTML5** - serves as banner that displays arbitrary HTML/CSS/JS content or image. HTML code can be an ordinary HTML page with external scripts and styles. It is rendered in the iframe and has limited access to the contents of the parent window.  

There are two ways of using "Banner HTML5 [loader]" template:  
  1\. Upload only image and set banner parameters (dimensions, click tag, etc)  
  2\. Upload zipped HTML5 creative. Documentation on preparing creatives can be found here: [Adobe Animate CC](#html5_Animate_one) or [Google Web Designer](#html5_GWD).   
If both image and HTML creative will be added, priority will be given to HTML.

**Parameters that is being set in ADFOX interface:**  
\- Width and height.  
\- CSS styles of the banner container.  

</div>

<div id="example" markdown="1">
##Example 

[Banner with single click area](https://test1.adfox.ru/testsite/?banner_type=bannerHTML_one)  

[Banner with multiple click areas](https://test1.adfox.ru/testsite/?banner_type=bannerHTML_some)

[Example of the published project](/uploads/289/AdobeAnimate_banner_one_project.zip) in Adobe Animate CC format, source [file](/uploads/289/AdobeAnimate_banner_one.fla).  
[Example of the published project](https://banners.adfox.ru/files/GWD_banner_[project].zip) in Google Web Designer format, source [file](https://banners.adfox.ru/files/GWD_banner_project_[for_test_inGWD].zip).

</div>





<div id="instruction_html" markdown="1">
## HTML creative development

<div id="html5_instruction" markdown="1">
1\. Check out <span id="html5_instruction_btn" style="color: #007FBE;  text-decoration: none; cursor: pointer;">HTML code prerequisites</span> 
<div class="divClass_html5_instruction" markdown="1">

<ul markdown="1">
<li> Maximum HTML file size - 65 000 bytes.</li>

<li>It is preferrable to place JavaScript and  CSS inside creative's HTML.
If resulting HTML code exceeds maximum allowed size, JavaScript and CSS have to be placed in separate files:
\- file size can not exceed 300kb;

Example of using external JS and CSS files: 

    <script type="text/javascript" src="LINK_TO_THE_FILE"></script>

    <link rel="stylesheet" type="text/css" href="LINK_TO_THE_FILE" />

[note]Relative paths are not allowed in HTML code[/note] 
</li>

<li>Only one HTML file is allowed</li>

<li>Maximum amount of files is 50</li> 

<li>Only following filetypes are allowed: css, js, html, gif, png, jpg, jpeg, svg, json, flv, mp4, ogv, ogg, webm, avi, swf; </li> 

<li>Maximum size of each file:  
\- 300Kb;  
\- 1Mb for video files.  
</li>

<li>Only numbers, letters, underscore and English alphabet characters are allowed in filenames.</li>

<li>Only **zip** files are allowed for uploading. </li>
</ul>

## Image files requirements

It's recomended to use high resolution images. It will dramatically improve visual quality on high resolution devices, although will decrease download speed.  

Also it's good practice to reduce image filesize using special services. For example [TinyPng](https://tinypng.com/).

SVG images are allowed. It's vector format, so it's lightweight and will fit any resolution.

Allowed image formats: png, gif, jpg, svg.  
Maximum image filesize: 300Кб.
</div>
</div>


2\. Choose the suitable instruction depending on editor that you use: 

<div id="html5_Animate_one" markdown="1">
<p id="html5_Animate_one_btn">Adobe Animate CC — Banner with single clickable area</p>

<div class="divClass_html5_Animate_one" markdown="1">

**1\.** Download single clickable area banner template

<ul>
          <li><a href="/uploads/289/AdobeAnimate_Adfox_[template_oneclick]_16.html.zip">Adobe Animate CC  16.0 and higher</a></li>
          <li><a href="/uploads/289/AdobeAnimate_Adfox_[template_oneclick]_after_15.html.zip">Adobe Animate CC 15.2 and higher</a></li>
          <li><a href="/uploads/289/AdobeAnimate_Adfox_[template_oneclick]_before_15.1.html.zip">Adobe Animate CC 15.1 and below</a></li>
</ul>

**2\.** Create Adobe Animate HTML5 canvas project or open already existing

<img class="zoomable" title="Click to zoom in" style='width:40%;' src="/help/images/289/1.png" />

**3\.** Open publish settings **File → Publish Settings** and import template from item 1.
 
<img class="zoomable" title="Click to zoom in" style='width:40%;' src="/help/images/289/3.png" />

**4\.** Publish project, selecting appropriate folder.

<img class="zoomable" title="Click to zoom in" style='width:40%;' src="/help/images/289/4.png" />

**5\.** Now the whole banner area is clickable. URL adress will be taken from banner parameters.

</div>
</div>

<div id="html5_Animate_some" markdown="1">
<p id="html5_Animate_some_btn">Adobe Animate CC — Banner with multiple clickable areas</p>

<div class="divClass_html5_Animate_some" markdown="1">

**1\.** Download template for banner with multiple clickable areas

<ul>
                    <li><a href="/uploads/289/AdobeAnimate_Adfox_[template_multi]_16.html.zip">Adobe Animate CC 16.0 and higher</a></li>
                    <li><a href="/uploads/289/AdobeAnimate_Adfox_[template_multi]_after_15.2.html.zip">Adobe Animate CC 15.2 and higher</a></li>
                    <li><a href="/uploads/289/AdobeAnimate_Adfox_[template_multi]_before_15.1.html.zip">Adobe Animate CC 15.1 and below</a></li>
                </ul>

**2\.** Create Adobe Animate HTML5 canvas project or open already existing

<img class="zoomable"  title="Click to zoom in" style='width:40%;' src="/help/images/289/1.png" />

**3\.** It's nesessary to set **instance names** to buttons or movieclips, so you can add click events to appropriate buttons. It's recommenden to use *button1 - button9* instance names.

<img class="zoomable"  title="Click to zoom in" style='width:40%;' src="/help/images/289/2.png" />

**See also:**  
<p id="btn1">• Guide on creating buttons with instance names</p>

<div class="divClass" markdown="1">

####Main scene button 

**1\.** Create an object on the scene for example using Rectangle Tool.  
Then convert it to symbol using context menu "Convert to Symbol..."

<img class="zoomable"  title="Click to zoom in" style='width:40%;' src="/help/images/289/1_1.png" />

**2\.** In the following dialog box choose "Type: Button". "Name" can be left unchanged, press "Ok".

<img class="zoomable" title="Click to zoom in"  style='width:40%;' src="/help/images/289/1_2.png" />

**3\.** Set instance name of this button to add click event later.

<img class="zoomable" title="Click to zoom in"  style='width:40%;' src="/help/images/289/1_3.png" />

**4\.** Put the following code into "Actions" layer: 

    window.buttons.push( 
       //Type in comma separated instance names, adding "this" at the beginning
       this.button1
       //End of instance names 
    );

<img class="zoomable" title="Click to zoom in"  style='width:40%;' src="/help/images/289/1_4.png" />

####Nested button

**1\.** For example you button is nested inside movie clip, its name is "movieClip".

<img class="zoomable" title="Click to zoom in"  style='width:40%;' src="/help/images/289/1_5.png" />

**2\.** Doouble click on "movieClip", and then you will able to observe nested button.

<img class="zoomable" title="Click to zoom in"  style='width:40%;' src="/help/images/289/1_6.png" />

**3\.** If your button is nested to another symbol, for example movie clip, then it's nessary to represent it in "Actions" layer code:

    window.buttons.push( 
       //Type in comma separated button instance names nested to parent movie clip instance adding "this" at the beginning
       this.movieClip.button1
       //End of instance names
    );

</div>


<p id="btn2">• Guide on creating transparent buttons</p>

<div class="divClass2" markdown="1">

**1\.** Select appropriate element and convert it to symbol using context menu "Convert to Symbol..."

<img class="zoomable" title="Click to zoom in"  style='width:40%;' src="/help/images/289/2_1.png" />

**2\.** Set it's name and select "Type: Button".

<img class="zoomable" title="Click to zoom in"  style='width:40%;' src="/help/images/289/2_2.png" />

**3\.** Double click on symbol to step into it.

<img class="zoomable" title="Click to zoom in"  style='width:40%;' src="/help/images/289/2_3.png" />

**4\.** Insert keyframe into frame "hit" using context menu.

<img class="zoomable" title="Click to zoom in"  style='width:40%;' src="/help/images/289/2_4.png" />

**5\.** Remove contents of the frames up, over, down

<img class="zoomable" title="Click to zoom in"  style='width:40%;' src="/help/images/289/2_5.png" />

**6\.** Transparent button is ready:

<img class="zoomable" title="Click to zoom in"  style='width:40%;' src="/help/images/289/2_6.png" />


</div>


**4\.** Add "Actions" layer to the project (we wil add our JS code later).

<img class="zoomable"  title="Click to zoom in" style='width:40%;' src="/help/images/289/5.png" />

**5\.** Open "Actions" editor.

<img class="zoomable"  title="Click to zoom in" style='width:40%;' src="/help/images/289/6.png" />

**6\.** Then put in code to "Actions" layer after modifying it accordingly.

    window.buttons.push( 
       //Type in comma separated instance names, adding "this" at the beginning
       
       //End of instance names 
    );
    setAdfox();

If button is in the main scene, then put it's instance name right after "this", for example:

    this.button1

If button is nesten into another scene, then put in instance name of this scene and then instance name of the button: 

    this.scene_instance_name.button2

Final "Actions" layer code example:

    window.buttons.push( 
       //Type in comma separated instance names, adding вначале this
       this.button1, this.scene_instance_name.button2
       //End of instance names 
    );
    setAdfox();


<img class="zoomable"  title="Click to zoom in" style='width:40%;' src="/help/images/289/7.png" />

**7\.** First comma separated instance name in "Actions" layer will match first event in banner parameters of ADFOX interface.
First instance name will use URL from "Event 1", second instance name will use URL from "Event 2", etc.

[note]Provide information about events and it's matching instance names together with creative archive to manager who will add banner to ADFOX.[/note]

**8\.** Open "Publish Settings...", import appropriate template from item one and publish project, selecting suitable folder.

<img class="zoomable"  title="Click to zoom in" style='width:40%;' src="/help/images/289/8.png" />

**9\.** Use **zip** format for creative archive. Your creative is ready for adding to adfox.</div>
</div>


<div id="html5_GWD" markdown="1">
<p id="html5_GWD_btn">Google Web Designer</p>

<div class="divClass_html5_GWD" markdown="1">
**1\.** Download [Google Web Designer template](https://banners.adfox.ru/files/GWD_Adfox_[template].zip).  

You can use this code as basis for building your own banner.  

<img src="/help/images/GoogleWebDesigner_1.png" width="300">

This template includes *adfox_HTML5.js* library and set of parameters for proper event and click handling:  
%reference%, %user1%, %eventN%, where  N — event index from 1 to 30.

**2\.** Click handling.  

All events are set to the certain elements on the "Events" tab.

<img src="/help/images/GoogleWebDesigner_event11.png" width="250"> <img src="/help/images/GoogleWebDesigner_event2.png" width="250">

To invoke actions use "Intaeractive area" component.
Add it and choose an event **"Tap Area > Touch/Click"**  
<img src="/help/images/GoogleWebDesigner_click.png" width="250">
<img src="/help/images/GoogleWebDesigner_click2.png" width="250">

Specify click function code on the "Code" tab.

**2\.1** If banner contains single button:

    callClick();

**2\.2** It there are several buttons:

    callClick(n);

where **n** is event index that has to be invoked.

**2\.3** If it's nesessary to invoke event from animation without click then use the following code:

    callEvent(n);

where **n** is event index that has to be invoked.

<img src="/help/images/GoogleWebDesigner_click3.png" width="250"><img src="/help/images/GoogleWebDesigner_click4.png" width="250"><img src="/help/images/GoogleWebDesigner_click5.png" width="250">

**Adaptive banner guide.**

<a href="https://support.google.com/webdesigner/answer/7002913?hl=en">GWD responsive layout overview
</a>
In order to make banner adaptive set postition and dimensions in percents on the **Properties** pane.  

<img src="/help/images/Google_Web_Designer_3.png" width="350" >

Also use *"Align to container"* and *"Fluid layout"* options.  
Responsive design uses flexible – rather than fixed – layouts. For ads, this means creating a single ad that can restyle its elements as the orientation or size changes, rather than creating multiple similar ads. Keeping with standard responsive design principles, Google Web Designer uses CSS3 media queries to let you to apply different styling rules for different-sized ads.
[Final project example](https://banners.adfox.ru/files/GWD_Resizeable_banner_[project].zip) Google Web Designer, source [file](https://banners.adfox.ru/files/GWD_Resizeable_banner_project_[for_test_inGWD].zip).

**4\.** Publish your project.

Select the following publishing options:  

<img src="/help/images/GoogleWebDesigner_settings.png" width="400" height="auto">

[note]
Provide information about events and it's matching URLs  to manager who will add banner to ADFOX.
[/note]

<ol>
<li>
Specify the name for the .zip file or folder for the document and supporting files. By default Google Web Designer uses the same name you specified for the HTML file when you created the file.
</li>
<li>
Choose the location where you want to save the .zip file or folder. You can enter the path to the location, or click the folder icon to browse your file system.
</li>
<li>
Select or deselect publishing options. Some options may be unavailable for your document type.
</li>
</ol> 

</div>
</div>


<div id="html5_other" markdown="1">
<p id="html5_other_btn">Другие редакторы</p>

<div class="divClass_html5_other" markdown="1">

**1\.** Click tag

To add click tag use the following variable for the attribute [tag_text]href[/tag_text] of [tag_text]а[/tag_text] tag: 

    %banner.reference_user1%

Also you can use variable in [tag_text]target[/tag_text] attribute [tag_text]%banner.target%[/tag_text].   
If attribute is absent, than link will be opened in banner's iframe.

Click tag HTML example.  

    <a href="%banner.reference_user1%" target="%banner.target%">Сайт рекламодателя</a>   

[note]Use the following variable for mobile app's HTML banners: [code]%reference%@%banner.user2%[/code]
[/note]

**2\.** Banner with multiple click tags

If banner contains multiple clickable areas or buttons with different links. For example:

    <a href="http://site.ru" target="_blank">First link</a>  
    <a href="http://site.ru/about/" target="_blank">Second link</a>

Use the following variables: [tag_text]%request.reference%@%banner.eventN%[/tag_text], where N is event number from 1 to 28.   
Например:  

    <a href="%request.reference%@%banner.event1%" target="%banner.target%">First link</a>  
    <a href="%request.reference%@%banner.event2%" target="%banner.target%">Second link</a>

Provide information about events and it's matching links to manager who will add banner to ADFOX.

First link - http://site.ru - %banner.event1% (Event 1). <br>
Second link - http://site.ru/about/ - %banner.event2% (Event 2).

</div>
</div>
</div>

<div id="add_adfox" markdown="1">
##Adding banner to ADFOX 

To add banner to ADFOX pick appropriate banner type and  **"Banner HTML5 [loader]"** template.  

Set banner parameters:  

1. **Архив с HTML5 креативом** — upload *.zip with your project, **"HTML5 код креатива"** have to be empty.  

2. **HTML5 код креатива** — paste banner code here if you want to make it this way instead of using zipped creative.

3. **URL перехода** — specify the link to the advertiser's site. For correct operation of the transition, please check protocol in the link (http:// or https://).  
   [note]
   If banner contains several links then add them on the <b>events</b> of the banner to the URL fields. <br>
   Ask developers how links should match events.
   [/note]
   
4. **"TARGET" ссылки** - defines widow where link will be opened:  
  [tag_text]_top[/tag_text] - in the current window;  
  [tag_text]_blank[/tag_text] - in the new tab/window, depending on browser settings.  

5. **Ссылка на промерочный пиксель** — ADFOX tracking pixel will be used by default [tag_text]//banners.adfox.ru/transparent.gif[/tag_text], specify third-party link if it's nesessary to collect statistics there.

6. **Ширина креатива (px или %)** — banner width.

7. **Высота креатива (px или %)** — banner height. 

8. **Изображение** — upload image.  
Display priority:  
  \- both HTML code and image were added -- HTML code will be shown.  
  \- only image was added -- an image will be shown.  
  \- only image was added -- an image will be shown.  

26. **Имя атрибута class контейнера баннера** — additonal classes for banner container. 

9. **Использовать SafeFrame (yes|no)** — safeFrame - technology that wraps advertisment with special iframe with certain API. Safeframe blocks it's access to the page context and protects page from collecting it's data.  
  [tag_text]yes[/tag_text] - turn on safeFrame usage and block access to the page;  
  [tag_text]no[/tag_text] - don't turn on safeFrame and allow access to the page.

10. **Стили для блока баннера** — custom CSS styles for banner container except "display" property. All invalid styles won't be used.


</div>
