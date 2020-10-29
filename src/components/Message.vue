<template>
<div>
    <h2>{{ getGreeting }}</h2>
<p>A simple example of Vue</p>
</div>
</template>



<script>
export default {
name: 'Reverse',
data () {
return {
reversedGreeting: '!dlrow olleH'
}
},
computed: {
getGreeting() {
return this.reversedGreeting.split("").reverse().join("");
}
}
}
</script>