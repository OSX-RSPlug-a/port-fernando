<script>

    import { Contact }  from 'lucide-svelte';
	//import Footer from '../footer.svelte'
	//import Header from '../header.svelte'

    export let data;

    export const prerender = true;

    console.log(data);

</script>

<div>

<main>

    <div class='curr'>

        <div class='content'>

            <div class='col'>

                <h1><icon class="icon"><Contact size='40' /></icon>Cover Letter</h1>

                <div class='columns'>

                        <p class='intro'><br/>Hi. I'm Computer Science .
                            <br/> Hobbies and Activities: Cycling; Exercising at the gym; Read books, articlesin general; Playing video games and board games;  
                        </p> 
            
                        <p>Like some people I know and some stories around the world, I'm going back 
                        and forth in the technology field. I've started in the area under the 
                        influence of my mother, who was a programmer in the 80s until the early 90s; 
                        In college I've attended a Technician, where I've had the 
                        opportunity to learn a little about hardware, networks and programming; 
                        A few years later I've started the Computer Engineering college - where 
                        I've attended for 3 years, but I've ended up changing courses and focused on 
                        working as a freelance technical support - I've acted as such, whenever 
                        I've needed and or where I've could in small jobs in the 
                        area of technical support and development or as a seller.
                        </p>  
            
                        <p>So I've decided to study Computer Science, having discovered that I like 
                        communities such as open source and research; Since I met Linux distros 
                        in the technician I have been active in help forums about linux and 
                        servers. For a few months I've been trying to acquire more development 
                        skills, participating in events, studying online courses, participating 
                        in Hackathons and participating in workshops like SemanaOmniStack 
                        (by the Yt channel Roecketseat) that took place online - workshops that 
                        sparked my interest in learning about React, react -native, JS and about
                        other technologies that are on the market .<br/>

                        <br/>- An interesting professional experience I've got was during my 
                        internship at FCCR -Nov/2013 -Nov/2015- where I've the opportunity 
                        to participate in the Public Consultation project, which I could 
                        develop with whatever technologies I've interested, the project 
                        consisted of showing an excerpt of a bill of the municipality to the 
                        citizens, so that he could give his opinion through a send-mail or a chat; 
                        It was a great experience where I could see from the step of upload
                        necessary services on the server, configure it and deploy it;<br/>

                        <br/>- Another interesting experience was participating in a Hackathon 
                        -Jul/2017 - Quero Educação(an education platform to genarate tickets 
                        of discount for students pay less in private graduation); The theme of 
                        the event was communication; So me, my cousin and another colleague 
                        created the idea with the title: TALKI, the project came from the idea
                        that sometimes at events people feel embarrassed, or the excessive 
                        number of questions makes communication with the speaker difficult, 
                        so we created a system that the person logs in via twitter and/or 
                        linkedin and can put the question in a queued chat directly to the 
                        speaker; It was a great experience to have time to produce idea, 
                        slides and code; 

                        <br/>- In 2020 I've been changing my focus in the IT area, where I 
                        found interest, Devops or related area and it's been another good 
                        challenge to study and be part of new communyties.

                    </p>

                </div>

            </div>

        </div>
        
    </div>

</main>

</div>

<style>

    .curr {
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        text-align: center;
        align-content: center;
        width: 60%;
        margin: 10% auto;
        border-radius: 15px;
        overflow: hidden;
        box-shadow:
        -8px -4px 8px 0px #ffffff,
        8px 4px 12px 0px #d1d9e6,
        4px 4px 4px 0px #d1d9e6 inset,
        -4px -4px 4px 0px #ffffff inset;
        padding: 3%;
    }

    .columns {
        columns: 250px 3;
        column-rule: 1px dotted #ccc;
        column-gap: 3em;
    }

    .intro {
        column-span: all;
        margin-bottom: 4vh;
        margin-top: 4vh; 
        align-items: center;
        text-align: center;
        margin-left: auto;
    }

    :focus {
        outline: 5px solid;
        outline-offset: 3px;
    }

    .content {
        display: flex;
        align-content: center;
        justify-content: center;
        margin: 5% 5% 15% 5%;
    }

    .icon {
        align-self: center;
        align-items: center;
        text-align: center;
        position: relative;
        margin: auto;
        padding-right: 25px;
        top: 5px;
        float: none;
    }

    [class^="icon"] {
        align-self: center;
        align-items: center;
        text-align: center;
        width: 50px;
        height: 50px;
        position: relative;
        top: 45px;
        margin: auto;
        fill: #fff;
    }

    .col h1 {
        text-align: center;
        align-items: center;
        align-self: center;
        font-size: 50px;
        margin-top: 10%;
        padding-bottom: 20px;
        margin: auto;
    }
    
    @media screen and (max-width: 480px) {
        .curr {
            width: 99%;
			font-size: 0.85em;
        }
        .content {
            width: 90%;
        }
        .col h1 {
            font-size: 25px;
            margin-left: 1%;
        }
    }

</style>