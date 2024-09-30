<svelte:head>
    <link rel="stylesheet" href="https://unpkg.com/tailwindcss@2.2.19/dist/tailwind.min.css"/>
</svelte:head>

<script>
    import Button from './Button.svelte';

    let buttonLabel = 'Click Me';
 
</script>

<Button label={buttonLabel} variant="primary" />
<Button label="Secondary Button" variant="secondary" />
