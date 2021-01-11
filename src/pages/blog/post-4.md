---
title: Vos Autem Cum Perspicuis Dubia Debeatis Illustrare
subtitle: >-
  Negat esse eam, inquit, propter se expetendam. Ergo, si semel tristior
  effectus est, hilara vita amissa est.
date: '2020-05-30'
author: src/data/team/dianne-ameter.yaml
categories:
  - src/data/categories/tutorials.yaml
  - src/data/categories/news.yaml
tags:
  - src/data/tags/jamstack.yaml
  - src/data/tags/sourcebit.yaml
excerpt: >-
  Itaque hoc frequenter dici solet a vobis, non intellegere nos, quam dicat
  Epicurus voluptatem. Sin kakan malitiam dixisses, ad aliud nos unum certum
  vitium consuetudo Latina traduceret.
thumb_image: images/classic/post-4.png
thumb_image_alt: Post 4 placeholder image
image: images/classic/post-4.png
image_alt: Post 4 placeholder image
image_position: right
template: post
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Teneo, inquit, finem illi videri nihil dolere. Quid est enim aliud esse versutum. Age, inquies, ista parva sunt. Verum hoc idem saepe faciamus. Atque ab his initiis profecti omnium virtutum et originem et progressionem persecuti sunt. Duo Reges: constructio interrete. Itaque eos id agere, ut a se dolores, morbos, debilitates repellant. Estne, quaeso, inquam, sitienti in bibendo voluptas? Iam in altera philosophiae parte. Quem Tiberina descensio festo illo die tanto gaudio affecit, quanto L.

- Restinguet citius, si ardentem acceperit.
- Te enim iudicem aequum puto, modo quae dicat ille bene noris.
- Quid, quod homines infima fortuna, nulla spe rerum gerendarum, opifices denique delectantur historia?
- Quo minus animus a se ipse dissidens secumque discordans gustare partem ullam liquidae voluptatis et liberae potest.

**Quippe: habes enim a rhetoribus;** Vos autem cum perspicuis dubia debeatis illustrare, dubiis perspicua conamini tollere. Hoc dixerit potius Ennius: Nimium boni est, cui nihil est mali. Sic consequentibus vestris sublatis prima tolluntur. Negat esse eam, inquit, propter se expetendam. Ergo, si semel tristior effectus est, hilara vita amissa est.

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
<!-- END: f1dj Google Spreadsheet/viz api table insert -->