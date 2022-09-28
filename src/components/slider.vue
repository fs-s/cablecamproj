<template>
    <header>
        <div class="range-input">
            <input type="range" class="range-min" min="0" max="1" value="0.5" step="0.05">
            <input type="range" class="range-max" min="0" max="1" value="0.5" step="0.05">
            
        </div>
    </header>
</template>

<script>

    let rangeValue

    function setEndPos(value){
        alert(value)
    }

    /* slider.onchange() = function(){
        rangeValue = slider.value
    }*/




    //console.log(document.getElementById('rangeSelector').value)

    export default {
        components:{
            name: 'Header'
        }
    }

</script>
