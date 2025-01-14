# Divi-Custom-CSS
Custom CSS solutions for Divi WordPress projects, designed to solve common styling challenges and enhance design flexibility.  Please test first 
## Disclaimer

This repository is provided "as is" without any warranties. Use the CSS and code snippets at your own risk. While we aim to provide functional and useful code, we are not responsible for any issues, errors, or damages that may occur from its use. Always test the code thoroughly before implementing it in live projects.
/* 
 Unofficial custom CSS for Divi WordPress.
 Not affiliated with or endorsed by Elegant Themes.
 Use at your own risk.
*/

# Divi WordPress CSS Solutions

## Overview
This repository contains custom CSS solutions for Divi WordPress projects, including styling for social media icons, layout enhancements, and other design tweaks.

## How to Use the Custom Social Icon CSS

### Step 1: Upload Your Custom Icon
1. Upload your icon (e.g., `.png` or `.svg`) to your WordPress Media Library.
2. Copy the URL of the uploaded image.

### Step 2: Add the CSS
1. Go to **Divi** > **Theme Options** > **Custom CSS**.
2. Paste the following CSS:
   ```css
   /* Replace Facebook or other Icon with a Custom Icon */
   .et-social-facebook a {
     background: url('YOUR-ICON-URL-HERE') no-repeat center;
     background-size: contain;
     display: inline-block;
     width: 30px;
     height: 30px;
     text-indent: -9999px;
     overflow: hidden;
   }

   /* Optional: Add Hover Effect */
   .et-social-facebook a:hover {
     opacity: 0.8;
   }

   Step 3: Update the Link
3. Go to Divi > Theme Options > Social Media.
In the Facebook URL field, add the link to your desired page.
Step 4: Save and Test
Save your changes.
Verify the icon appears and links correctly on your site.

Note: I am using Facebook because I am not using Facebook.  Any icon can be used.  

