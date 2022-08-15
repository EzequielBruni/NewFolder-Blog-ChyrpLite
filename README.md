# NewFolder Blog -- for Chyrp Lite

NewFolder Blog is a blog theme based on the [NewFolder SCSS framework](https://newfolder.dev) created by yours truly. This particular version was created for Chyrp Lite, a fantastic flat-file blogging  and micro-blogging CMS.

**Notes:** 
* This theme supports all feathers and almost all functionality except pingbacks. I've just... never had any use for them.
* All posts *must* have a title to work properly with this theme.
* Some theme functionality depends on having a static home page. This is non-essential.
    * However, all of the aforementioned functionality depends on the static home page having a slug called "home". If you want a different slug, you'll need to edit the theme.

## NewFolder is a SCSS-based design framework

It's meant to be minimalist, easy to read, and easy to drop in to new projects. Customize your colors and fonts, compile the SCSS files, then go. You can find the documentation for this framework on newfolder.dev.

## How to use this theme (the short, short version):
* Install Chyrp Lite.
* Upload this theme (or clone it via git) into the /themes folder wherever you installed Chyrp Lite.
* Activate the theme in the Chyrp Lite admin section, and check out the `_variables.scss` file in `newfolderblog/stylesheets/NewFolder/`.

Note, you'll need a way to compile the SCSS into regular CSS. I use the Watch SASS extension in Visual Studio Code.

## Screenshots:

The (optional) static home page:
![homepage](https://user-images.githubusercontent.com/1215780/184600619-1be92bd9-f803-4c7a-9723-5d10cff00cd0.png)

The blog index page:
![index](https://user-images.githubusercontent.com/1215780/184600713-7176dca0-dccb-46fe-8643-2401ca32a8e7.png)

The automatic dark mode:
![darkmode](https://user-images.githubusercontent.com/1215780/184600807-b30df987-83ae-41d4-a1a7-556a50ef5bcf.png)
