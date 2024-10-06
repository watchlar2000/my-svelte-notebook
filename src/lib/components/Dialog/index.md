# Dialog

The `<dialog>` element represents a dialog box or other interactive component, such as an alert, inspector, or subwindow. You can find more details in the [MDN Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog).

### Useful links:

- https://www.youtube.com/watch?v=Fl9R8OokMkE&ab_channel=SteveGriffith-Prof3ssorSt3v3

### Usage example:

```javascript
<script>
	import Modal from '$lib/components/Modal.svelte';

	let showModal = false;
</script>

<button on:click={() => (showModal = true)}> show modal </button>

<Modal bind:showModal>
  <!-- content goes here -->
</Modal>
```
