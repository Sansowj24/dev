<select id="classSelect" onchange="aFunction()">
    <option value="0">Choose Class</option>
    <option value="1">Class 1 Cost 1</option>
    <option value="2">Class 2 Cost 2</option>
    <option value="3">Class 3 Cost 3</option>
    <option value="4">Class 4 Cost 4</option>
    <option value="5">Class 5 Cost 5</option>
</select>
<div id="result"></div>
<script>
function aFunction(){
    classCost = Number(document.getElementById("classSelect").value);
    fee = 5;
    if (classCost > 0){
        total = classCost + fee;
        document.getElementById("result").innerHTML = total;
    }else{
        document.getElementById("result").innerHTML = ("Select Class");
    }
}
</script>
