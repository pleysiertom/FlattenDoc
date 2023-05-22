# FlattenDoc
A Flattening Tool for InDesign, which is used before exporting.
Put simply, its an overengineered JPEG Exporter/Importer designed to give a brute force flatten solution to indesign

FlattenDoc is a powerful tool that enhances your workflow with Adobe InDesign by providing an efficient way to flatten your documents. in most cases this is used before exporting as a PDF.
Flattening is a process that merges all layers of the document into one. This is typically done to preserve document appearance, increase compatibility with more devices and applications, and secure the document's contents. Here are several reasons why flattening can be helpful:
- Preserve layout and content: Flattening ensures that the layout, fonts, images, and other elements remain in place and appear as intended, no matter what software or device is used to open the PDF. Without flattening, some elements might move or display incorrectly due to software differences, device settings, or font availability.
- Reduce file size: A flattened PDF often has a smaller file size than an unflattened one, especially if the original contains many layers or interactive elements. This can make the document easier to send via email, upload to a website, or store on devices with limited storage space.
- Increase compatibility: While many modern PDF viewers can handle layers and interactive elements, not all can. Flattening can help ensure that your PDF can be viewed as intended on a wider variety of software and devices.
- Secure content: When you flatten a PDF, all annotations, form fields, and other interactive elements become part of the document's main layer and can't be easily changed or removed. This can be useful for securing content and preventing tampering, particularly in legal, business, or educational settings. It's a simple way to make sure that the final version of the document remains as you intended it to be.
- Prevent editing: If you don't want others to be able to edit certain elements of your document, flattening can help. Once a PDF is flattened, the individual layers can no longer be manipulated separately, making it more difficult to change the document's content or layout.

Main Features of FlattenDoc:
- Option to include document bleed
- Colourspace options (CMYK, RGB, Greyscale)
- Simulate overprint 
- Fine Text Rendering (More on that Later)
- Being an awesome tool in your arsenal

How to install FlattenDoc:
- On InDesign go to: Window > Utilities > Scripts
- Right Click "User" within the Scripts Panel and select "Reveal in Finder/Explorer".
- Open the "Scripts Panel" folder and place "FlattenDoc.jsxbin" inside
- Taadaaaa! you now have installed the script and all you need to do is run the script by double clicking it

Fun Fact: You can assign keyboard shortcuts to scripts by going to: Edit > Keyboard Shortcuts. then selecting "Scripts" for Product Area. you can then find the script and assign a keyboard shortcut. I would recommend: CMD + F for Mac and ALT + SHIFT + F for Windows

So What is "Fine Text Rendering"
Fine Text Rendering is an option to ensure text is flattened properly, due to InDesign's JPEG exporter text can sometimes look a bit bumpy, and this option makes sure that does not happen. However, this setting should only be enabled if you notice that you need it, as it adds a fair bit of processing power to the equation.

Important Note on running the script multiple times on one document:
if you need to run the script twice, it needs to unhide all layers within the document, but in many cases people do not want certain layers to be shown, in order to get around this, naming a layer "Hide" in any way will hide the layer from the script, other names include "Revision", "Dont Flatten" and more will also work, if you have any names to add, please let me know and I will be more than happy to add them :)

If there is any problems, please let me know! and I hope you enjoy!
