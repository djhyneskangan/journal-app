<script>
    import Modal from './modal.svelte';
    let showModal = false;

    const toggleModal = () => {
    showModal = !showModal;
    } 
    </script>

    <Modal message="Jatz Crackers" {showModal} />

    <button on:click={toggleModal}>Open Model</button>