
### Student #1
![image](http://imgur.com/52EG07Z)




<script src="//pencilcode.net/lib/pencilcodeembed.js"></script>
<div id="embed1" style="width:100%;height:350px"></div>
<script type="example" id="ex1">
# Your goal: return the larger
# of two parameters.
test (x, y) ->
  return x + y
</script>
<script type="checker" id="ch1">
remove(turtle);
function test(fn) {
  var cases = 6;
  var t = table(cases + 1, 4);
  t.css({margin: 'auto'});
  t.cell(0, 0).text('x');
  t.cell(0, 1).text('y');
  t.cell(0, 2).text('got');
  t.cell(0, 3).text('ok');
  for (var j = 1; j <= cases; ++j) {
    var x = random(5);
    var y = random(5);
    var z = Math.max(x, y);
    var a = fn(x, y);
    t.cell(j, 0).text(x);
    t.cell(j, 1).text(y);
    t.cell(j, 2).text(a);
    t.cell(j, 3).text(a === z);
    if (a !== z) {
      t.cell(j).css({background: red});
    } else {
      t.cell(j, 3).css({color: green});
    }
  }
}
</script>
<script>
function script(id) {
  return document.getElementById(id).textContent.trim();
}
var pce = new PencilCodeEmbed(document.getElementById('embed1'));
pce.beginLoad();
pce.on('load', function() {
  pce.setupScript([
    {code: script('ch1'), type: 'text/javascript'}
  ]);
  pce.setCode(script('ex1'));
});
</script>



### Student #1
![image](http://clipart-finder.com/data/mini/97-David_Livingstone_small_portrait.png)
My name is Bob, my favorite part of this apprenticeship was the Facebook tour



<div id="embed2" style="width:100%;height:350px"></div>
<script type="example" id="ex2">
speed(100);
pen(red);
var j;
for (j = 0; j < 200; ++j) {
  fd(j);
  rt(j * 3);
}
</script>
<script>
var test = new PencilCodeEmbed(document.getElementById('embed2'));
test.beginLoad();
test.on('load', function() {
  test.setCode({data: script('ex2'), meta: {type: 'text/javascript'}});
});
</script>





























