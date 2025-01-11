<script>
    let { children } = $props();
</script>


<div class="container">
    <nav>
        <a class="nametag" href="/">kai okorodudu</a>
        <a href="/contact">contact</a>
        <a href="/motion">motion</a>
        <a href="/code">code</a>
        <a href="/about">about</a>
    </nav>
    {@render children()}
</div>

<style>
    :global {
        a {
            color: black;
            text-decoration: underline;
            font-weight: 800;
        }
    }
    

    .container {
        font-family: "IBM Plex Mono", serif;
        max-width: 1000px;
        margin: 1rem auto;
        padding: 1rem;

    }

    .nametag {
        font-size: 2rem;
    }
</style>