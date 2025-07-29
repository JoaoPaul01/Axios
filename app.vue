<script setup>
    axios.get('todos')
    .then((response) => {
        console.log(response.date)
    }) 

</script>
