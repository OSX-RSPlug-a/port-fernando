<script>

    import { Linkedin, Twitter, Github, Codepen  } from 'lucide-svelte';
    
    import 'open-props/style'
	import 'open-props/normalize'
	import 'open-props/buttons'

</script>

<main>

    <header>
        
        <section class="hero">
        
            <h1 class="hero-message">
        
                <div> Fernando Santini </div>
        
                <div>DevOps</div>
        
            </h1>
        
            <p class="under-hero">I HELP COMPANIES MAKE A NICE INFRA AS CODE.</p>
        
            <div class="button-list">
        
                <button class="primary"><Linkedin size='18' color="#de6161" /></button>

                <button class="primary"><Codepen size='18' color="#de6161" /></button>

                <button class="primary"><Github size='18' color="#de6161" /></button>
        
                <button class="primary"><Twitter size='18' color="#de6161" /></button>
        
            </div>
        
        </section>
        
        <picture class="promo-art">
        
            <img src="https://doodleipsum.com/700x700/outline?bg=3b5bdb" height="800" width="800" alt="a random doodle">
        
        </picture>  
    </header>

    <section>

        <hr><hr>

    </section>

</main>

<style>

    header {
        display: grid;
        align-items: center;
        grid-template-columns: 1fr 1fr;
        background: var(--grape-0);
    }

    .hero {
        padding: var(--size-10);
        display: grid;
        gap: var(--size-5);
    }

    .hero-message {
        display: grid;
        grid-template-columns: max-content;
        line-height: var(--font-lineheight-0);
    }

    .hero-message > div:last-child {
        color: var(--indigo-7);
    }

    .under-hero {
        color: var(--gray-7);
        font-size: var(--font-size-4);
        margin-block-end: var(--size-3);
    }

    .button-list {
        display: flex;
        gap: var(--size-3);
    }

    button {
        background: white;
        color: var(--indigo-8);
        font-size: var(--font-size-3);
        padding-inline: var(--size-8);
        padding-block: var(--size-3);
        border-radius: var(--radius-5);
        box-shadow: var(--shadow-2);
    }

    button.primary {
        background: var(--cyan-5);
        text-shadow: 0 1px 0 var(--indigo-9);
        color: white;
    }

    button.primary:hover {
        background: var(--indigo-7);
    }

    .promo-art {
        align-self: stretch;
    }

    .promo-art > img {
        block-size: 100%;
        object-fit: cover;
    }

</style>