AccDC Bootstrap 1.6 for jQuery
=====

IMPORTANT: All of the AccDC projects have been deprecated as of May4, 2021. All future development will instead be done through the Apex 4X project, which is much more powerful and feature rich. To learn more, read the Apex 4X release article at:  https://www.linkedin.com/pulse/released-apex-4x-comprehensive-aria-development-suite-bryan-garaventa

AccDC Bootstrap is an HTML parser that renders advanced, accessible interactive controls using semantic HTML markup.

Supported by the Royal Society of Arts, AccDC was awarded the "Above and Beyond Accessibility Award" from the United States Department of Labor, and was presented at the Developing with Accessibility Event, hosted by the Federal Communications Commission in Washington DC in 2012.

This version of AccDC interfaces with jQuery as an extension.
All of the AccDC accessible component modules plug into this interface.

Bootstrapping refers to the use of semantic HTML markup to configure advanced controls, which are then magically converted into dynamic interactive components when the content finishes loading.

This allows developers to include complex functionality that is fully configurable across thousands of web pages, without having to program individual components using JavaScript.

Benefits:

* Easy implementation
* Consistent layouts
* Reliable functionality
* Full customization
* Automatic accessibility

AccDC Bootstrap is module based, so it can be extended or reduced as needed for any site-wide implementation.

The style sheets for all bootstrap components are fully configurable, so they can be customized to fit the user interface design of any site while maintaining the same level of reliability and accessibility.

The bootstrap module itself is also fully configurable, so that new features and components can easily be added and customized for global integration.

All AccDC Bootstrap components are WCAG 2.0 compliant, ARIA standards compliant, and Section-508 compliant.

Tested using:

1. JAWS 11+&gt; using IE 8 and 9, and Firefox.
2. NVDA using IE 8 and 9, and Firefox.
3. Voiceover using iOS Safari.

AccDC Bootstrap is designed to automatically enforce accessibility, while making it possible to populate individual components with any type of content, in any language, using any visual styling.

Recursive processing is also supported, so that new content, when rendered, will automatically be bootstrapped; even when pulled from an external resource.

Bootstrapping can also be manually invoked using the $A.bootstrap method for individual DOM nodes.<br />

AccDC Bootstrap is distributed under the terms of the Open Source Initiative OSI - MIT License.

Bootstrapped Modules
-----

Bootstrapping occurs using modules from the AccDC Component Library.

The AccDC Component Library is a collection of accessible control types that automate the structural and functional accessibility of each control according to relevant accessibility best practices. The controls can be populated with any type of content, and can be styled to fit any type of user interface layout, in any language, without negatively impacting accessibility. The controls tap into the accessibility features of the AccDC API to render content in an accessible manner, then apply supporting markup and scripting to automatically ensure accessibility for screen reader and keyboard only users. This makes it possible for developers to add fully customizable components, that look and feel exactly as they desire, while ensuring functional accessibility at the same time without the risk of coding misinterpretation by those who are unfamiliar with ATs. 

The following modules are included:

* Accessible Modal controls.
* Accessible Banner controls.
* Accessible Tooltip controls.
* Accessible Popup controls.
* ARIA Tab controls.
* ARIA context sensitive dropdown Menu controls. 
* ARIA Tree controls. 
* ARIA Date Picker controls. 
* Accessible Accordion controls. 
* Accessible Carousel, Slideshow, and Wizard controls.  
* Keyboard accessible Scrollable Div controls.  
* ARIA Toggle controls.    
* Accessible Footnote controls

For specific coding guidance, visit: http://whatsock.com/tsg

Distributed under the terms of the Open Source Initiative OSI - MIT License.

Developed and maintained by: Bryan Garaventa https://www.linkedin.com/in/bgaraventa
Or on Twitter at https://twitter.com/bryanegaraventa

Includes contributions by: Danny Allen (dannya.com) / Wonderscore Ltd (wonderscore.co.uk) https://www.linkedin.com/in/danny-allen-49690451/

Note: All visual design by Angela Ricci (web designer and web front-end developer). You can check her work at her personal site http://gericci.me/
Or you can follow her on Twitter at https://twitter.com/gericci

Project home:
-----

http://whatsock.com/bootstrap/jquery/

Related projects:
-----

* WhatSock Organization: https://github.com/whatsock
* Visual ARIA: https://github.com/accdc/visual-aria

Understanding AccDC: A Quick Start Guide
-----

It helps to understand precisely what AccDC is and how it works at the most basic level.

The AccDC API is designed to process and normalize code across the three most widely used JavaScript libraries and frameworks, jQuery, Dojo, and MooTools.

To be specific, the AccDC API is an extension for jQuery, Dojo, and MooTools.

The AccDC API module interfaces with each of these libraries and frameworks in order to utilize all of the available rendering, AJAX, event handling, and associated processes, and extends them, so that any relevant command that is processed using the $A namespace, is automatically powered by the core processes within jQuery, Dojo, or MooTools.

An example showing the value of this, is described in the LinkedIn article at
http://lnkd.in/b9VGQxf

This means that, any widget that uses the following AccDC API methods, will automatically normalize equally across jQuery, Dojo, and MooTools, without requiring any coding changes to work correctly.

* $A.getEl // Get the element with the specified ID
* $A.createEl // Create a new element node, plus optional attributes, styling, and content
* $A.getAttr // Get the value of a specified attribute
* $A.setAttr // Set the value of one or more attributes
* $A.remAttr // Remove one or more attributes
* $A.getText // Get the textual content of a container element
(Coding documentation: WhatSock.com > Core API > Misc)

* $A.css // Get or Set the styling properties of one or more elements
* $A.hasClass // Check if an element includes one or more class names
* $A.addClass // Add one or more class names to an element
* $A.remClass // Remove one or more class names from an element
(Coding documentation: WhatSock.com > Core API > CSS)

* $A.bind // Add event handlers for one or more elements
* $A.unbind // Remove event handlers for one or more elements
* $A.trigger // Fire the specified event on an element
(Coding documentation: WhatSock.com > Core API > Events)

* $A.load // Pull markup code from an external resource and load into a container element
* $A.get // Pull code from an external resource and process it
* $A.getJSON // Pull JSON code from an external resource and process it
* $A.getScript // Execute an external JavaScript file
* $A.post // Submit data to a server side script using a POST request
* $A.ajax // Manually configure custom AJAX GET or POST requests
(Coding documentation: WhatSock.com > Core API > AJAX)

* $A.announce // Announce a string or the content of a container element to screen reader users
(Coding documentation: WhatSock.com > Core API > Accessibility)

There are many more AccDC API commands and customizable rendering functionalities documented on the Core API tab at WhatSock.com, but these cover all of the most commonly used public methods.

In order to test and verify this functionality, there are three dedicated TSG GitHub projects, all of which use the same component code for each widget type shared between them, which tie into the AccDC API for automatic normalization.

* Powered by jQuery: https://github.com/whatsock/tsg
* Powered by Dojo: https://github.com/whatsock/tsg-dojo
* Powered by MooTools: https://github.com/whatsock/tsg-mootools

In order to ensure the highest level of accessibility possible for all user types, including non-sighted screen reader users, mobility impaired keyboard only users, voice navigation software users, and low vision screen magnification software users, all of the scalable widgets provided within the TSG archives are programmed specifically to be as accessible as possible using all current standards, with specific adherence to the principles and guidelines documented at:

http://whatsock.com/training

Also available for download at:
https://github.com/whatsock/training

For community support, please address any questions to the Accessibility Innovators LinkedIn group, at:
https://www.linkedin.com/groups/Accessibility-Innovators-4512178

Future updates and announcements will be posted on Twitter, at
https://twitter.com/bryanegaraventa