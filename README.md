---
title: "BaselineTestpages2"
layout: default
permalink: /
---

# BaselineTestPages2

-----

This repository houses test cases that serve as a central test case repository for testing accessibility test methodologies, both manual and automated, specifically against the Harmonized Process for Revised Section 508: Baseline Tests for Web Accessibility/TTv5.

The test cases below are available for testing scenarios related to accessibility and the ICT Baseline. Updated: Sunday 03/08/2020 7:08 PM.

-----

<span class="h2">ICT Baseline Tests</span>

1.  <span class="accessibilityCategory">Keyboard Access</span>
    1.  <span class="TestStep">4.A: All functionality can be accessed and executed using only the keyboard</span>
        1.  [TC0104A001 - Scrollable Regions](test-cases/TC0104A001.md)
    2.  <span class="TestStep">4.B: Individual keystrokes do not require specific timings for activation of functionality</span>
        1.  \<none\>
    3.  <span class="TestStep">4.C: There is no keyboard trap</span>.
        1.  \<none\>
2.  <span class="accessibilityCategory">Focus Visible</span>
    1.  <span class="TestStep">4.D: A visible indication of focus is provided when focus is on the interface component</span>.
3.  <span class="accessibilityCategory">Focus Order</span>
    1.  <span class="TestStep">4.E: When an interface component receives focus, it does not initiate an unexpected change of context</span>
        1.  \<none\>
    2.  <span class="TestStep">4.F: The focus order preserves the meaning and operability of the web page</span>
        1.  \<none\>
    3.  <span class="TestStep">4.G: Focus is moved to revealed content </span>
        1.  \<none\>
    4.  <span class="TestStep">4.H: Focus is returned to the logical sequence</span>
        1.  \<none\>
4.  <span class="accessibilityCategory">Repetitive Content</span>
    1.  <span class="TestStep">9.A: A keyboard-accessible method is provided to bypass repetitive content </span>
        1.  \<none\>
    2.  <span class="TestStep">9.B: Each navigational element occurs in the same relative order with regard to other repeated components on each web page where it appears. </span>
        1.  \<none\>
    3.  <span class="TestStep">9.C: The accessible name and description is consistent for components that perform the same function </span>
        1.  \<none\>
5.  <span class="accessibilityCategory">Changing Content</span>
    1.  <span class="TestStep">2.D: The page provides notification of each automatic update/change in content </span>
        1.  \<none\>
    2.  <span class="TestStep">5.E: The page provides notification of each form-related change in content. </span>
        1.  \<none\>
    3.  <span class="TestStep">6.B: The page provides notification of each change in content that is the result of interaction with a link or button </span>
        1.  \<none\>
6.  <span class="accessibilityCategory">Images</span>
    1.  <span class="TestStep">7.A: The accessible name and accessible description for a meaningful image provides an equivalent description of the image </span>
        1.  [TC0607A001 - \<img\> Image Labeling](test-cases/TC0607A001.md)
        2.  [TC0607A002 - Role='img' Image Labeling](test-cases/TC0607A002.md)
    2.  <span class="TestStep">7.B: There is no accessible name and accessible description for a decorative image </span>
        1.  \<none\>
    3.  <span class="TestStep">7.C: The background image is not the only means used to convey important information </span>
        1.  \<none\>
    4.  <span class="TestStep">7.D: Alternative forms of CAPTCHA are provided. </span>
        1.  \<none\>
    5.  <span class="TestStep">7.E: The image of text cannot be replaced by text or is customizable </span>
        1.  \<none\>
7.  <span class="accessibilityCategory">Sensory Characterstics</span>
    1.  <span class="TestStep">13.A: Color is not used as the only visual means of conveying information, indicating an action, prompting a response, or distinguishing a visual element </span>
        1.  \<none\>
    2.  <span class="TestStep">13.B: Instructions provided for understanding and operating content do not rely solely on sensory characteristics of components, such as shape, size, visual location, orientation, or sound </span>
        1.  \<none\>
8.  <span class="accessibilityCategory">Contrast</span>
    1.  <span class="TestStep">13.C: The visual presentation of text and images of text have sufficient contrast </span>
        1.  [TC0813C001 - Color Contrast for 12;x and smaller text (4.5:1)](test-cases/TC0813C001.md)
        2.  [TC0813C002 - Color Contrast for text larger that 12px (3:1)](test-cases/TC0813C002.md)
9.  <span class="accessibilityCategory">Flashing</span>
    1.  <span class="TestStep">Step 1: Determine the flashing frequency. If the flashing frequency is at or below 3Hz (three flashes in any one second period), no further testing is necessary. </span>
        1.  \<none\>
    2.  <span class="TestStep">Step 2: If frequency cannot be determined or is above 3Hz, test that the combined, contiguous area that is flashing simultaneously within any 10-degree angle of view is less than the equivalent of the small safe area for flashing </span>
        1.  \<none\>
    3.  <span class="TestStep">Step 3: The opposing transitions that flash do not involve a saturated red AND The darkest image's relative luminance is above 0.80, or The darkest image's relative luminance is below 0.80 and the maximum change in relative luminance between the darkest image and the brightest image is less than 10%</span>.
        1.  \<none\>
10. <span class="accessibilityCategory">Forms</span>
    1.  <span class="TestStep">5.A: Labels or instructions are provided for form elements</span>
        1.  \<none\>
    2.  <span class="TestStep">5.B: Each form label is sufficiently descriptive </span>
        1.  \<none\>
    3.  <span class="TestStep">5.C: The combination of the accessible name, accessible description, and other programmatic associations (e.g., table column and/or row associations) describes each input field and includes all relevant instructions and cues (textual and graphical). </span>
        1.  [TC1005C001 - InputText Labeling](test-cases/TC1005C001.md)
        2.  [TC1005C002 - InputFile Labeling](test-cases/TC1005C002.md)
        3.  [TC1005C003 - InputPassword Labeling](test-cases/TC1005C003.md)
        4.  [TC1005C004 - InputCheckbox Labeling](test-cases/TC1005C004.md)
        5.  [TC1005C005 - InputRadio Button Labeling](test-cases/TC1005C005.md)
        6.  [TC1005C006 - InputSelect Control Labeling](test-cases/TC1005C006.md)
        7.  [TC1005C007 - Textarea Labeling](test-cases/TC1005C007.md)
        8.  [TC1005C008 - Hidden Focus Labeling](test-cases/TC1005C008.md)
        9.  [TC1005C009 - ARIA Role Input Field Labeling](test-cases/TC1005C009.md)
        10. [TC1005C010 - ARIA Role Toggle Element Labeling](test-cases/TC1005C010.md)
        11. [TC1005C011 - Multiple Labels bound to Single Element](test-cases/TC1005C011.md)
    4.  <span class="TestStep">5.D: Changing field values/selections (e.g., entering data in a text field, changing a radio button selection) does NOT initiate an unexpected change of context </span>
        1.  \<none\>
    5.  <span class="TestStep">5.F: The item in error is identified in text and sufficiently described to the user in text </span>
        1.  \<none\>
    6.  <span class="TestStep">5.G: Guidance (e.g., suggestion for corrected input) is provided about how to correct errors for form fields</span>
        1.  \<none\>
    7.  <span class="TestStep">5.H: The web page allows the user to check, reverse, and/or confirm submission </span>
        1.  
11. <span class="accessibilityCategory">Page Titles</span>
    1.  <span class="TestStep">12.A: A \<title\> element is defined for the web page </span>
        1.  [TC1112A001 - No Title Element (missing)](test-cases/TC1112A001.md)
        2.  [TC1112A002 - Empty Title element (null)](test-cases/TC1112A002.md)
    2.  <span class="TestStep">12.B: The \<title\> element identifies the contents or purpose of the web page</span>
        1.  
12. <span class="accessibilityCategory">Tables</span>
    1.  <span class="TestStep">14.A: Each data table has programmatic markup to identify it as a table </span>
        1.  
    2.  <span class="TestStep">14.B: All data cells are programmatically associated with relevant headers </span>
        1.  
    3.  <span class="TestStep">14.C: The layout table DOES NOT designate the layout table using ARIA role="table" AND DOES NOT include table header structure and relationship elements and/or associated attributes</span>
        1.  
13. <span class="accessibilityCategory">Content Structure</span>
    1.  <span class="TestStep">10.A: Each heading describes the topic or purpose of its content. </span>
        1.  
    2.  <span class="TestStep">10.B: Each programmatically determinable heading is a visual heading and each visual heading is programmatically determinable </span>
        1.  
    3.  <span class="TestStep">10.C: Programmatic heading levels logically match the visual heading presentation within the heading structure </span>
        1.  
    4.  <span class="TestStep">10.D: All visually apparent lists are programmatically identified according to their type</span>
        1.  
14. <span class="accessibilityCategory">Links and Buttons</span>
    1.  <span class="TestStep">6.A: The purpose of each link or button can be determined from any combination of the link/button text, accessible name, accessible description, and/or programmatically determined link/button context</span>
        1.  
15. <span class="accessibilityCategory">Language</span>
    1.  <span class="TestStep">11.A: The default human language of each web page can be programmatically determined </span>
        1.  
    2.  <span class="TestStep">11.B: The human language for any content segment that differs from the default human language of the page can be programmatically determined</span>
        1.  
16. <span class="accessibilityCategory">Autio-Only and Video-Only</span>
    1.  <span class="TestStep">16.A: A text-based alternative is provided for audio-only content that provides an accurate and complete representation of the audio-only content </span>
        1.  
    2.  <span class="TestStep">16.B: The video-only content information is also available through an equivalent text or audio alternative</span>
        1.  
17. <span class="accessibilityCategory">Synchronized Media</span>
    1.  <span class="TestStep">17.A: The multimedia provides accurate captions for the audio content </span>
        1.  
    2.  <span class="TestStep">17.B: The multimedia provides an equivalent soundtrack (combination of narration and audio descriptions) for the video content </span>
        1.  
    3.  <span class="TestStep">17.C: The live multimedia provides accurate captions for the audio content </span>
        1.  
    4.  <span class="TestStep">17.D: The media player provides user controls for closed captions and audio descriptions </span>
        1.  
    5.  <span class="TestStep">17.E: User controls for captions are provided at the same menu level as the user controls for volume or program selection </span>
        1.  
    6.  <span class="TestStep">17.F: User controls for audio descriptions are provided at the same menu level as the user controls for program selection or volume</span>
        1.  
18. <span class="accessibilityCategory">CSS Content and Positioning</span>
    1.  <span class="TestStep">15.A: For the meaningful content provided via CSS pseudo-elements ::before and ::after, equivalent information is available in another way </span>
        1.  
    2.  <span class="TestStep">15.B: The reading order of the content (in context) is correct and the meaning of the content (in context) is preserved without CSS positioning</span>
        1.  
19. <span class="accessibilityCategory">Frames and iFrames</span>
    1.  <span class="TestStep">12.C: Each \<frame\> has a title attribute that describes its content </span>
        1.  
    2.  <span class="TestStep">12.D: The combination of accessible name and description for each \<iframe\> describes its content. </span>
        1.  
20. <span class="accessibilityCategory">Conforming Alternate Version</span>
    1.  
21. <span class="accessibilityCategory">Timed Events</span>
    1.  <span class="TestStep">2.A: The user can pause, stop, or control the volume of audio content that plays automatically </span>
        1.  
    2.  <span class="TestStep">2.B: The user can pause, stop, or hide moving, blinking, or scrolling content </span>
        1.  
    3.  <span class="TestStep">2.C: The user can pause, stop, hide, or control the frequency of automatically updating content. </span>
        1.  
    4.  <span class="TestStep">8.A: The user can turn off, adjust, or extend the time limit </span>
        1.  
22. <span class="accessibilityCategory">Resize Text</span>
    1.  <span class="TestStep">18.A: There is a mechanism to resize, scale, or zoom in on the text to at least 200% of its original size without loss of content or functionality </span>
        1.  
23. <span class="accessibilityCategory">Multiple Ways</span>
    1.  
24. <span class="accessibilityCategory">Parsing</span>
    1.  <span class="TestStep">Step 1: HTML elements have complete start and end tags </span>
        1.  
    2.  <span class="TestStep">Step 2: HTML elements are nested according to their specifications </span>
        1.  
    3.  <span class="TestStep">Step 3: HTML elements do not contain duplicate attributes </span>
        1.  
    4.  <span class="TestStep">Step 4: Id values are unique within a single HTML document </span>
        1.  
25. <span class="accessibilityCategory">Non-Interference</span>
    1.
