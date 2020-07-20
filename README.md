# firstServices.github.io

## Updating plan prices
1. Open the appropriate .html file 
2. Click the pencil icon in the top right to edit this file
3. Update the prices where you see this block of code

```
<div class="row">
  <div class="col-3"><p><b>One Semester</b></p></div>
  <div class="col-3"><h4>$[PRICE]</h4></div>
  <div class="col-3"><h4>$[PRICE]</h4></div>
</div>
<div class="row">
  <div class="col-3"><p><b>Two Semesters</b></p></div>
  <div class="col-3"><h4>$[PRICE]</h4></div>
  <div class="col-3"><h4>$[PRICE]</h4></div>
</div>
```
4. Scroll to the bottom of the page and enter a commit message (i.e. "update water plan prices")
5. Make sure "Commit directly to the master branch" is selected
6. Click "Commit changes"

## Adding service updates
1. Open the updates.html file 
2. Click the pencil icon in the top right to edit this file
3. Scroll to where you see this block of code
```
 <div class="container-fluid" style="margin-top:50px">
      <div class="container">
        <h1>Service Updates</h1>
```

4. Directly under `<h1>Service Updates</h1>`, insert the following code & edit the contents as necessary (for multiple paragraphs, put each paragraph inside its own set of `<p></p>` tags)
```
<h3>[DATE]</h3>
<p>
  [ANNOUNCEMENT]
</p>
```
5. Scroll to the bottom of the page and enter a commit message (i.e. "add new service update")
6. Make sure "Commit directly to the master branch" is selected
7. Click "Commit changes"

## Updating headshots & bios

### Deleting old headshots
1. Open the folders img > headshots
2. Open the appropriate image file
3. Click the trash can icon in the top right to delete this file

### Uploading new headshots
1. Open the folders img > headshots
2. Click "Add file" > "Upload files"
3. Upload files from your computer

### Updating image links on "About Us"
1. Open the about.html file
2. Update the file names, names, and class years where you see this block of code
```
<div class="container-fluid exec" style="margin-top:70px">
  <div class="container">
    <h1>Executive Team</h1>
    <div class="row">
      <div class="col-3">
        <img class="headshot" src="img/headshots/[FILENAME]">
        <h2 style="text-align:center;">[NAME]</h2>
        <h4 style="text-align:center">Executive Director</h4>
        <p style="text-align:center">[SCHOOL ##]</p>
      </div>
      <div class="col-3">
        <img class="headshot" src="img/headshots/[FILENAME]">
        <h2 style="text-align:center;">[NAME]</h2>
        <h4 style="text-align:center">Director of Laundry Operations</h4>
        <p style="text-align:center">[SCHOOL ##]</p>
      </div>
      <div class="col-3">
        <img class="headshot" src="img/headshots/[FILENAME]">
        <h2 style="text-align:center;">[NAME]</h2>
        <h4 style="text-align:center">Director of Water Operations</h4>
        <p style="text-align:center">[SCHOOL ##]</p>
      </div>
      <div class="col-3">
        <img class="headshot" src="img/headshots/[FILENAME]">
        <h2 style="text-align:center;">[NAME]</h2>
        <h4 style="text-align:center">Director of Customer Relations</h4>
        <p style="text-align:center">[SCHOOL ##]</p>
      </div>
    </div>
  </div>
</div>
```
3. Scroll to the bottom of the page and enter a commit message (i.e. "update executive team headshots")
4. Make sure "Commit directly to the master branch" is selected
5. Click "Commit changes"
