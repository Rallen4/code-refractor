# code-refractor
HTML, CSS: Code-refractor assignment.

#GitIntro:

This assignment focused on cleaning up Horiseon's webpage by adjusting their current HTML semantics to more accurately reference the CSS coding. There was also multiple instances where we were required to clean up the CSS code to reflect the desireable output in a more concise, efficient manner. 


For example, header semantic adjustments went as follows:
    - Changing <div> headers to [ex]<header class="header">
        - These html semantics allow for linked CSS files to group portions of header-assigned HTML code and apply the same translations/effects/outputs to the website. 
        - By grouping html sub sections via headers, we were able to reduce the amount of necessary CSS files required to achieve the desired outputs. 

For example, CSS file cleansing went as follows:
    - Assigning an <aside class="benefits>
        - This "benefits" class applied CSS code to all HTML code inside the lines 51-73, with the specially impacted lines of code being found between HTML lines 52-70. 
            - In doing so, we were able to eliminate the following CSS subheaders because each required the same CSS outputs and thus, could be compartmentalized under one singular <aside class="benefits"> header. 
                -Removed header [ex] are:
                     <section id="benefit-lead>, <section id="benefits-brand">, and <section id ="benefit-cost"> 

    - To reiterate, there we're multiple unnecessary repeat CSS header blocks that were functioning with the same way/style/inputs-output commands. 
        - By grouping HTML packets into less css header groups, we were able to reduce the amount of CSS code lines needed to produce the same output. 

Lastly, we applied comment-headers to the CSS file to indicate where changes were made, in what ways, and why. 

    For example, refer to CSS code lines 52, 79, 91 to see a detailed notation of changes made to the HTML/CSS files.

Below are screenshot previews of the finalized HORISEON website:



