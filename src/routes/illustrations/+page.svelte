<script>
    import { base } from "$app/paths";
</script>

<h1>illustrations</h1>
<p>this is an illustrations page</p>

<div class="project">
    <img
        class="thumbnail"
        alt="a thumbnail for my smile illustration"
        src="{base}/smile2.png"
    />
    <h2>SMiLE</h2>
    <div class="description">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
        veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
        commodo consequat.
    </div>
    <a target="_blank" href="https://www.instagram.com/p/DEbtzE2NB_n/"
        >instagram</a
    >
    <!-- _blank opens link on diff page -->
</div>

<style>
    .project {
        margin-top: 30px;
        margin-bottom: 30px;
        margin-left: 30px;
        margin-right: 30px;
        background: white;
        max-width: 600px;
    }

    .description {
        font-size: 1rem;
    }

    .thumbnail {
        width: 100%;
        border: 1px solid black;
        margin-bottom: -20px;
    }
</style>
