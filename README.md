# Search-Box-with-Search-Icon
CSS tricks to create a custom search box with font awesome search icon.

# References needed
These bootstrap, jQuery and font awesome references are needed to work for this search box.

    <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
    <link rel="stylesheet" href="http://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.4.0/css/font-awesome.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.2/jquery.min.js"></script>
    <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>

# CSS Styles
Add the following styles to your _style_ tag or css file. (Margins given in searchContainer are to display the search box better in demo page)

    <style>
      .searchContainer{
      position: relative;
      margin-top: 150px;
      margin-left: 150px;
      }
      .searchContainer input#search{
      width: 300px;
      float: left;
      padding-left: 40px;
      }
      .searchContainer .searchIcon{
      position: absolute;
      top: 50%;
      margin-left: 15px;
      margin-top: 8px;
      z-index: 1;
      color: gray;
      }
    <style/>

# HTML for the Search Box
    <div class="searchContainer">
      <span class="searchIcon"><i class="fa fa-search"></i></span>
      <input type="text" class="form-control" id="search" placeholder="Search..." />
    </div>

That's it. You are all set for the search box. 
You can customize the _CSS_ properties as you like.

**References:**
[CSS Experiments With a Search Form Input and Button](http://webdesign.tutsplus.com/tutorials/css-experiments-with-a-search-form-input-and-button--cms-22069)
