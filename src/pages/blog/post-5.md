---
title: Amet Nulla Facilisi Morbi Tempus
subtitle: >-
  Sit amet consectetur adipiscing elit pellentesque habitant morbi tristique
  senectus.
date: '2020-06-02'
author: src/data/team/gustav-purpleson.yaml
categories:
  - src/data/categories/tutorials.yaml
tags:
  - src/data/tags/stackbit.yaml
  - src/data/tags/netlify.yaml
excerpt: >-
  Estne, quaeso, inquam, sitienti in bibendo voluptas? Iam in altera
  philosophiae parte. Quem Tiberina descensio festo illo die tanto gaudio
  affecit, quanto.
thumb_image: images/classic/post-5.png
thumb_image_alt: Post 5 placeholder image
image: images/classic/post-5.png
image_alt: Post 5 placeholder image
image_position: right
template: post
---

Donec ultrices tincidunt arcu non sodales neque. Et netus et malesuada fames ac turpis egestas sed tempus. Cras pulvinar mattis nunc sed. Turpis cursus in hac habitasse platea dictumst quisque sagittis. Sollicitudin nibh sit amet commodo nulla facilisi nullam. Posuere ac ut consequat semper viverra nam. Ac tortor vitae purus faucibus ornare suspendisse sed nisi lacus. Egestas sed sed risus pretium quam vulputate dignissim suspendisse in. Tempor orci eu lobortis elementum nibh. Senectus et netus et malesuada fames ac turpis egestas integer. Id cursus metus aliquam eleifend mi in nulla posuere sollicitudin. Sed nisi lacus sed viverra tellus. Non curabitur gravida arcu ac tortor dignissim convallis aenean.

Sem et tortor consequat id porta. Diam sit amet nisl suscipit adipiscing bibendum est ultricies. Amet nulla facilisi morbi tempus. Blandit massa enim nec dui nunc mattis. Non enim praesent elementum facilisis leo vel fringilla est. Eleifend quam adipiscing vitae proin sagittis nisl rhoncus. Mauris pellentesque pulvinar pellentesque habitant morbi tristique senectus et netus. Eget nunc lobortis mattis aliquam faucibus purus. Volutpat ac tincidunt vitae semper quis. Cursus eget nunc scelerisque viverra mauris. Purus semper eget duis at tellus at urna. Mauris commodo quis imperdiet massa tincidunt nunc pulvinar sapien. Sit amet consectetur adipiscing elit pellentesque habitant morbi tristique senectus. Nunc non blandit massa enim nec. Ut porttitor leo a diam sollicitudin.

Tincidunt tortor aliquam nulla facilisi cras. Id semper risus in hendrerit. Magna fermentum iaculis eu non. At consectetur lorem donec massa sapien faucibus et. Est placerat in egestas erat imperdiet sed euismod nisi porta. Lacus vel facilisis volutpat est velit egestas dui. Sapien pellentesque habitant morbi tristique senectus et. Ut tellus elementum sagittis vitae et. Et malesuada fames ac turpis. Volutpat commodo sed egestas egestas. Praesent tristique magna sit amet purus gravida quis. Turpis egestas pretium aenean pharetra.

<div>
<style>
#f2dj__table table {
    font-size: 12pt;
    font-weight:bold;
}
#f2dj__table th {
    background: orange;
}
</style>
<script src="https://www.google.com/jsapi" type="text/javascript"></script><script type="text/javascript">
var f2dj_sskey='1gOEU8Oo9rPznYHIEkSSOpH0CyUqnvOVeDQTpBo1ERv0'
var f2dj_sheet=752311914
var f2dj_authkey='CITwr80K'
//google.load('visualization', '1', {'packages':['table']});
google.charts.load('48', {packages:['table','controls']});
//https://spreadsheets.google.com/tq?tqx=out:csv&tq=select%20*&key=1M1HJRX36tQNkHOvmP6uCtVgehdMyNDP1JFiSy22GApk&gid=0
function f2dj_getData(){
  var q='select A,C,D,E'
  var url='https://spreadsheets.google.com/tq?tq='+encodeURIComponent(q)+'&key='+f2dj_sskey+'&authkey='+f2dj_authkey+'&gid='+f2dj_sheet;
  var query = new google.visualization.Query(url);
  query.send(f2dj_displayTable);
}
function f2dj_displayTable(response){
if (response.isError()) {
        alert('Error in query: ' + response.getMessage() + ' ' + response.getDetailedMessage());
        return;
      }
    
      var data = response.getDataTable();
      visualization = new google.visualization.Table(document.getElementById('f2dj__table'));
      visualization.draw(data, null);      


   // Apply a number formatter to the 2nd column.
   // var table = new google.visualization.Table(document.getElementById('f1dj__table'));

   // var formatter = new google.visualization.ArrowFormat();
    // formatter.format(data, 3); // Apply formatter to 4th column

    // table.draw(data, {allowHtml: true, showRowNumber: true});

     var table = new google.visualization.Table(document.getElementById('f2dj__table'));

     var formatter = new google.visualization.ColorFormat();
     formatter.addRange(-20000, -0, 'white', '#e74c3c');
     formatter.addRange(0, 20000, 'white', '#27ae60');
     formatter.format(data, 3); // Apply formatter to second column

   //var formatter = new google.visualization.ColorFormat();
   //formatter.addRange(-20000, -0, 'white', '#e74c3c');
   //formatter.addRange(0, 20000, 'white', '#e74c3c');
   //formatter.format(data, 8); // Apply formatter to second column

   //var formatter = new google.visualization.ColorFormat();
   //formatter.addRange(-20000, -0, 'white', '#2980b9');
   //formatter.addRange(0, 20000, 'white', '#2980b9');
   //formatter.format(data, 8); // Apply formatter to second column

     table.draw(data, {allowHtml: true, showRowNumber: true, width:'100%', height:'100%' });
}     

google.setOnLoadCallback(f2dj_getData)
</script>
<div id="f2dj__table">
</div>
<!-- END: f1dj Google Spreadsheet/viz api table insert --></div>