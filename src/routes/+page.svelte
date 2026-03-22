<header>
    <h1>JOY SU(DO)</h1>
    <p>Tall person, short name, long list</p>
</header>
<main>
    <section class="column">
        <div class="column-header">INITIATIVES</div>
    </section>
    <section class="column">
        <div class="column-header">ART</div>
    </section>
    <section class="column">
        <div class="column-header">WRITING</div>
    </section>
</main>
<footer>
    <p>Want to find more information? Check out my <a href="https://byjoysu.com" target="_blank">personal website</a> or <a href="https://github.com/joysudo" target="_blank">Github</a>.</p>
</footer>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Lexend+Exa:wght@200;400;700&display=swap');

    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        font-family: 'Space Mono', monospace;
    }

    header {
        display: inline-block;
        border: 3px solid black;
        padding: 2rem 4rem;
        border-radius: 4rem 1rem;
    }
    
    header h1 {
        font-family: 'Lexend Exa', sans-serif;
    }

    main {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 1rem;
        margin: 0 auto;
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
        top: 10vh;
        font-family: 'Lexend Exa', sans-serif;
    }

    footer {
        padding: 4rem;
        text-align: center;
        background: darkolivegreen;
        color: whitesmoke;
    }

    footer a {
        color: darkseagreen;
    }
</style>