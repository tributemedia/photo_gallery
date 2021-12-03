# Photo Gallery
The Photo Gallery module provides the Gallery Photo content type, and view with page, standard block, and rotating block displays.

## Getting the Files

1. Clone the feature from the Github repository where you would like (If you already have the repository on your computer, skip this step).

`git clone https://github.com/tributemedia/photo_gallery.git`


2. If you already have a local repository make sure to pull down any new changes that might have occurred since your last use.

`git pull`


3. This directory is now up to date with all the information and files you need to install and set up the Photo Gallery Feature.

## Installation and Configuration

1. Open the Pantheon dashboard to the development environment for the site.
2. Make sure the environment is in SFTP mode and connect to the environment in your SFTP client of choice.
3. Edit the .gitignore file in the site root folder.
4. Under the custom modules section add the following line: !/web/modules/custom/photo_gallery
5. Save the changes to the .gitignore file and commit the changes.
6. Drop the photo_gallery folder into the custom folder (/code/web/modules/custom).
7. Commit the changes.
8. Navigate to the modules panel in the Drupal interface to see if you can enable the Photo Gallery module. Found by clicking on extend in the menu (/admin/modules). If you are unable to enable the testimonials module, follow the steps here.
9. Navigate to /gallery on the development site and remove all blocks that are associated with the gallery page except for the page title block.
10. Add the gallery photos to the site through Content/Add Content/Gallery Photo (/node/add/gallery_photo).
11. Configure blocks as necessary
