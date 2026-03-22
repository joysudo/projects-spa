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
    @import url('https://fonts.googleapis.com/css2?family=Nanum+Pen+Script&display=swap'); 

    :global(body) {
        margin: 0;
        text-align: center;
        background-color: color-mix(in srgb, darkolivegreen 15%, mintcream);
    }

    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        font-family: 'Nanum Pen Script', monospace;
        color: darkolivegreen;
        line-height: 1.2rem;
    }
    
    header {
        display: inline-block;
        background-color: mintcream;
        border: 2px solid darkolivegreen;
        padding: 2rem 4rem;
        border-radius: 4rem 1rem;
        margin-top: 2rem;
        margin-bottom: 3rem;
        box-shadow: -0.5rem 0.5rem 0 darkolivegreen;
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
        color: mintcream;
        text-align: center;
        border-radius: 6767px;
        transition: transform 0.4s ease-in-out, box-shadow 0.4s ease-in-out;
    }

    .column-header:hover {
        transform: translate(0.25rem, -0.25rem);
        box-shadow: -0.25rem 0.25rem 0 color-mix(in srgb, darkolivegreen 50%, mintcream);
    }

    .project-card {
        display: flex;
        flex-direction: column;
        background: mintcream;
        border: 2px solid darkolivegreen;
        border-radius: 1rem;
        padding: 1rem;
        gap: 0.5rem;
        text-align: left;
        box-shadow: 0 0 0 color-mix(in srgb, darkolivegreen 25%, mintcream);
        transition: transform 0.4s ease-in-out, box-shadow 0.4s ease-in-out;
    }

    .project-card:hover {
        transform: translate(0.5rem, -0.35rem);
        box-shadow: -0.35rem 0.5rem 0 color-mix(in srgb, darkolivegreen 50%, mintcream);
    }

    .project-card h3 {
        font-size: 1.5rem;
    }
    
    .project-card img {
        width: 100%;
        border-radius: 1rem;
        object-fit: fill;
    }

    .project-card a {
        display: block;
        background-color: sienna;
        color: mintcream;
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
    }

    footer p {
        color: mintcream;
    }

    footer a {
        color: darkseagreen;
    }
</style>