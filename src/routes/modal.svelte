<script>
export let message;
export let showModal = false;

</script>


{#if showModal}
<div class="backdrop">
    <div class="modal">
<p>{message}</p>
    </div>
</div>
{/if}



<style>
    .backdrop {
        width: 100%;
        height: 100%;
        position: absolute;
    }
    
    .modal {
        height: 100px;
        background-color: rgb(225, 129, 129);
        width: 400px;
border-radius: 5px;
margin: 100px auto;
    }

    

    p {
        text-align: center;
        padding: 10px;
    }

</style>