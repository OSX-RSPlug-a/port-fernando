<h1>About</h1>

<main>

    <div class="card">
    
        <img src="https://doodleipsum.com/500x500/hand-drawn?i=9b11b7fde5591be86d8928901e68355f" alt="Card image cap">
        <h5>A little about me</h5>
        <p>I'm Computer Science graduated.</p>
        <p>Hobbies and Activities: Cycling; Exercising at the gym; Read books, articlesin general; Playing video games and board games;</p>
    
    </div>

</main>

<style>
	
	
main {
    display: flex;
    flex-flow: row wrap;
    align-items: flex-start;
    justify-content: space-around;
    max-inline-size: calc(var(--size-content-1) * 4);
    gap: var(--size-5);
    padding: var(--size-5);
}

.card {
    flex-basis: var(--size-content-2);
    display: flex;
    flex-direction: column;
    gap: var(--size-2);
    background: var(--surface-3);
    border: 1px solid var(--surface-1);
    padding: var(--size-4);
    border-radius: var(--radius-3);
    box-shadow: var(--shadow-2);
}

.card > h5 {
    line-height: var(--font-lineheight-1);
}

body {
    display: grid;
    place-content: center;
}

	
</style>