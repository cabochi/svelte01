<script>
    import Logo from "./Logo.svelte";
    const name = 'Svelte';
    const content = "<h2>Hello HTML</h2>";
</script>


<style>
    h1 {
        color: red;
    }
</style>

<h1>Hello {name.toLocaleUpperCase()}!</h1>
{@html content}
<!-- <img src={src} alt='PZN Logo' /> -->
<Logo />
