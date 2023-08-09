# Code Reference for Bootstrap 5
## Include Bootstrap via CDN
Bootstrap can be included within a given HTML file by using the CDN (Content Delivery Network) as follows
```HTML
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm" crossorigin="anonymous"></script>
```
## Container in Bootstrap
Container are elements to structure layout in Bootstrap. 

### Standard 
The standard container is given by
```HTML
<div class="container">
  <!-- Content here -->
</div>
```
### Fluid
The fluid container is used by
```HTML
<div class="container-fluid">
  ...
</div>
```
## Grid in Bootstrap
We may use the basic grid system of Bootstrap to organize layout vertically or horizontally.
As an example we consider the following grid of one row and three columns
```HTML
<div class="container text-center">
  <div class="row">
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
  </div>
</div>
```
# References
We refer to the official documentation of Bootstrap: [https://getbootstrap.com/docs/5.3/getting-started/download/](https://getbootstrap.com/docs/5.3/getting-started/download/)
