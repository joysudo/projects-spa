<header>
    <h1>JOY SU(DO)</h1>
    <p>Tall person, short name, long list</p>
</header>
<main>
    <section class="column">
        <h2 class="column-header">INITIATIVES</h2>
        <div class="project-card">
            <h3>This is an h3 element hooray.</h3>
            <p>This is text that goes underneath that h3 element. This is filler text. I am writing filler text right now. This will show what it looks like once the page is filled with yap. Filler text. Consider this area filled. With text.</p>
            <img src="https://ceiling.hackclub.com/ceiling.jpg" alt=""/>
            <a href="https://byjoysu.com" target="_blank">This is a link.</a>
        </div>
    </section>
    <section class="column">
        <h2 class="column-header">ART</h2>
    </section>
    <section class="column">
        <h2 class="column-header">WRITING</h2>
    </section>
</main>
<footer>
    <p>Want to find more information? Check out my <a href="https://byjoysu.com" target="_blank">personal website</a> or <a href="https://github.com/joysudo" target="_blank">Github</a>.</p>
</footer>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Lexend+Exa:wght@200;400;700&display=swap');

    :global(body) {
        margin: 0;
        text-align: center;
        background-color: color-mix(in srgb, darkolivegreen 15%, whitesmoke);
    }

    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        font-family: 'Space Mono', monospace;
    }

    h1, h2, h3 {
        font-family: 'Lexend Exa', sans-serif;
    }
    
    header {
        display: inline-block;
        background-color: whitesmoke;
        border: 2px solid darkolivegreen;
        padding: 2rem 4rem;
        border-radius: 4rem 1rem;
        margin-top: 2rem;
        margin-bottom: 3rem;
        box-shadow: 0.75rem 0.75rem 0 darkolivegreen;
        animation: hover 2s ease-in-out infinite alternate;
    }

    @keyframes hover {
        from { transform: translateY(0); }
        to { transform: translateY(1rem); }
    }
    
    main {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 1rem;
        margin: 0 2vw;
        align-items: start;
    }

    .column {
        display: flex;
        flex-direction: column;
        gap: 1rem;
    }

    .column-header {
        position: sticky;
        padding: 1rem;
        z-index: 67;
        background: darkolivegreen;
        color: whitesmoke;
        text-align: center;
        border-radius: 6767px;
        transition: transform 0.1s ease-in-out, box-shadow 0.1s ease-in-out;
    }

    .column-header:hover {
        transform: translate(0.25rem, -0.25rem);
        box-shadow: -0.25rem 0.25rem 0 color-mix(in srgb, darkolivegreen 50%, whitesmoke);
    }

    .project-card {
        display: flex;
        flex-direction: column;
        background: whitesmoke;
        border: 2px solid darkolivegreen;
        border-radius: 1rem;
        padding: 1rem;
        gap: 0.5rem;
        text-align: left;
        box-shadow: 0 0 0 color-mix(in srgb, darkolivegreen 25%, whitesmoke);
        transition: transform 0.1s ease-in-out, box-shadow 0.1s ease-in-out;
    }

    .project-card:hover {
        transform: translate(0.5rem, -0.25rem);
        box-shadow: -0.25rem 0.5rem 0 color-mix(in srgb, darkolivegreen 50%, whitesmoke);
    }

    .project-card img {
        width: 100%;
        border-radius: 1rem;
        object-fit: fill;
    }

    .project-card a {
        display: block;
        background-color: sienna;
        color: whitesmoke;
        padding: 0.5rem 1rem;
        border-radius: 1rem;
        font-weight: bold;
        text-decoration: none;
        transition: background-color 0.1s ease;
    }

    .project-card a:hover {
        background-color: saddlebrown;
    }

    footer {
        padding: 4rem;
        margin-top: 2rem;
        text-align: center;
        background: darkolivegreen;
        color: whitesmoke;
    }

    footer a {
        color: darkseagreen;
    }
</style>