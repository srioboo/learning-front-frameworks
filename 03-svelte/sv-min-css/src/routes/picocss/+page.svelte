<script>
    import './styles-pico.css'; // styles pico css
    import Main from "$lib/components/main.svelte";
</script>

<svelte:head>
    <title>Bulma test page</title>
    <meta name="description" content="Bulma test page" />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
</svelte:head>

<Main />

<!-- TODO test especificos
<div class="container">
    <div class="columns">
        <div class="column col-6">col-6</div>
        <div class="column col-3">col-3</div>
        <div class="column col-2">col-2</div>
        <div class="column col-1">col-1</div>
    </div>
</div>


<div class="column">
    <h1>About this app</h1>

    <div class="coll">
        This is a <a href="https://kit.svelte.dev">SvelteKit</a> app. You can make your own by typing the
        following into your command line and following the prompts:
    </div>

    <pre>npm create svelte@latest</pre>

    <p>
        The page you're looking at is purely static HTML, with no client-side interactivity needed.
        Because of that, we don't need to load any JavaScript. Try viewing the page's source, or opening
        the devtools network panel and reloading.
    </p>

    <p>
        The <a href="/sverdle">Sverdle</a> page illustrates SvelteKit's data loading and form handling. Try
        using it with JavaScript disabled!
    </p>
</div> -->
