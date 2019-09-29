<script>
    const employeeCount = document.getElementById('employees__count');
    const resource = 1234;
    function handleEmployee() {
        employeeCount.innerHTML = Math.round(resource);
    }

</script>

<button on:click={handleEmployee}>
    Hire employee
</button>


<div id="employees__count" class="employees__count">
    0
</div>
<!-- 
 resource += upgrade;
 display.innerHTML = Math.round(resource);
 setTimeout(startCount, 15);
 startcount.style.display = 'none'; -->