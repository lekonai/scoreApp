
<script>
    let count1 = $state(0);
    let count2 = $state(0);
    function increment1(){
        count1++;
    }
    function increment2(){
        count2++;
    }
</script>

<p> football page </p>
<h3>{count1}</h3>
<h3>{count2}</h3>
<button onclick={increment1}>
    Increment Score 1
</button>
<button onclick={increment2}>
    Increment Score 2
</button>