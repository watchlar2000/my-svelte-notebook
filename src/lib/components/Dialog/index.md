## Dialog

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog

```javascript
<script>
	import Modal from './Modal.svelte';

	let showModal = false;
</script>

<button on:click={() => (showModal = true)}> show modal </button>

<Modal bind:showModal>
  <!-- content goes here -->
</Modal>
```
