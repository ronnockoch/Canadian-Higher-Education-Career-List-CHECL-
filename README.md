Ontario Higher Education Career Bookmark List - CHEBCL
======

This is a comprehensive collection of links, importable into your bookmarks in Chrome/Firefox/Netscape/Edge, to non-academic career pages at post-secondary / higher education institutions in Canada.

This includes publicly funded, non-profit institutions.

**Not** included are for-profit, private or institutions which exclusively offer religious degrees.


## Organization

The project folder contains three import files to add all bookmarks at once:
 1. [all-colleges.html](/all-colleges.html)
 2. [all-universities.html](/all-universities.html)
 3. [all-colleges-universities.html](/all-colleges-universities.html)

Each top-level folder (Province or Territory) will be populated with two sub-folders and a file:
4. University
5. College

The file will be something similar to `province-uni-college.html` and contains all the data for listed Higher Education insitutions in that Province or Territory.

Within each folder, you will find a `README.md` and a `bookmark-list.html` file.

The `README.md` will provide a linked list of the career pages in browser, whereas the `province-list.html` file will allow you to import the files into your browser's bookmark manager for quicker access.


## Adding Bookmarks

The `bookmark-list.html` files are setup to be imported into your browser's bookmark manager. The format is, to the best of my knowledge, based off of the Netscape Bookmark file format which is still in use in modern browswers.

The file contains code that will look like the following:
```html
<!DOCTYPE NETSCAPE-Bookmark-file-1>
<!-- This is an automatically generated file.
     It will be read and overwritten.
     DO NOT EDIT! -->
<META HTTP-EQUIV="Content-Type" CONTENT="text/html; charset=UTF-8">
<TITLE>Bookmarks</TITLE>
<H1>Bookmarks</H1>

<DL><p>
<DT><H3>Nova Scotia - University</H3>
    <DL><p>
    <DT><A HREF="https://hr.acadiau.ca/employment/career-opportunities/administrativesupport.html">Acadia University</A>
    <DT><A HREF="https://www.cbu.ca/faculty-staff/human-resources/employment-opportunities/">Cape Breton University</A>
    <DT><A HREF="https://dal.peopleadmin.ca/postings/search?query=&query_v0_posted_at_date=&query_position_type_id%5B%5D=1&query_position_type_id%5B%5D=6&query_position_type_id%5B%5D=7&435=&commit=Search">Dalhousie University</A>
    <DT><A HREF="https://www.careerbeacon.com/en/employer-showcase/company-tnsbv8">Mount Saint Vincent University</A>
    <DT><A HREF="https://nscad.ca/careers/">Nova Scotia College of Art and Design University</A>
    <DT><A HREF="https://www2.mystfx.ca/hr/employment-opportunities">Saint Francis Xavier University</A>
    <DT><A HREF="https://www.smu.ca/about/staff-employment-opportunities.html">Saint Mary's University</A>
    <DT><A HREF="https://www.usainteanne.ca/offres-d-emploi/">Université Sainte-Anne</A>
    <DT><A HREF="https://ukings.ca/campus-community/employment/">University of King's College</A>
    </DL><p>
</DL><p>
```
This structured `<!DOCTYPE NETSCAPE-Bookmark-file-1>` file contains all of the information your browser needs to create new bookmarks, and contains instructions on the folder hierachy.

In order to import the bookmarks in the next [section](#importing-bookmarks) you will need to download the files. This can be accomplished in a few ways:

1. Download all of the repository code clicking on the green CODE ![](resources/images/code-button.png?raw=true) button and selecting 'Download Zip' ![](resources/images/download-zip.png?raw=true). You will need to extract it using an archive tool such a [7Zip](https://www.7-zip.org/).

2. Navigate to the folder or `bookmark-list.html` file you would like to import, and right click on the 'RAW' button and click `Save Link As`, ensuring to keep it as a `.html` file.
3. Navigate to the folder or `bookmark-list.html` file you would like to import, and click on the 'RAW' button. Copy and paste the text that is displayed into a text editor and save it as a `.html` file.

## Importing Bookmarks
### Adding bookmarks to Chrome

### Adding bookmarks to Firefox

### Adding bookmarks to Edge







## Credits
1. [Link to BookmarkGenerator Repo](/)
2. [Turndown](https://domchristie.github.io/turndown/)
3.
