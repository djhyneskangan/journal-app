<script>
    let showModal = true;
    
    function toggleModel () {
        
    }
</script>

{#if showModal}
<div class="backdrop" on:click={toggleModel}>
    <div class="modal">
<p>This is a modal</p>
    </div>
</div>
{/if}


<style>
    .backdrop {
        width: 100%;
        height: 100%;
        background: rgba(0, 0, 0, 0.6);
        position: absolute;
    }
    
    .modal {
        height: 100px;
        background-color: rgb(255, 255, 255);
        width: 400px;
border-radius: 5px;
margin: 100px auto;
    }

    

    p {
        text-align: center;
        padding: 10px;
    }

</style>