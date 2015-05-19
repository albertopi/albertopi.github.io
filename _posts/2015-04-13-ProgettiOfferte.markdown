---
layout : post
title : ProgettiOfferte | OBE Italia
---

# ProgettiOfferte | OBE Italia

Between June and September 2014 I’ve developed a sort of PDM software for OBE Italia,  the Italian subsidiary of the German metal precision components industry OBE GmbH.

The company needed a platform to catalog and share the projects they are working on and to generate and catalog quotations sent to its customers as, at the time, everything was managed by creating a folder on the product manager PC, where documents, e-mails and 2D/3D drawings were archived.

For this purpose, in the early stages of software development, I have evaluated various different solutions, spacing between the available OOTB, open-source and customizable ERP and PDM/PLM softwares, but any of these suited the company requirements in terms of functionalities and pricing, so I decided to develop my own solution, tailor-made for the company needs.

I compared various solutions of CRUD DBMSs, desktop and web-based, and the “winner” out of this battle has been FileMaker Pro 13.

With FileMaker I’ve built a database based on two main entities, named Progetti (projects developed by the company) and Offerte (quotations sent to the customers). Both projects and quotations are detailed by child entities, shown as panels in the graphic user interface.

FileMaker allowed me to build a complex database schema keeping at the same time a clean and easy to use user interface, with simple field boxes like calendars, drop-down menus and containers for files and images. Conditional formatting gives the user a direct view of the project status in the key fields.

From the quotation layout the user can choose the most appropriate quotation template by completing one of the panels in addition to the first one containing general informations and then, by clicking on the “Genera PDF…” button, the software will prompt to save the quotation in a PDF file, ready to be sent out to the customer via e-mail or printed.

If you’d like to have a software like this in your company or if you just want to know more, feel free to contact me.