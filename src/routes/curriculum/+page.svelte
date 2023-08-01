<script>
	
    //import Footer from '../footer.svelte'
	//import Header from '../header.svelte'

    import { Linkedin, Mail, Github, Codepen, Contact, Link, Scroll, Languages  } from 'lucide-svelte';

    export let data;

    export const prerender = true;

    console.log(data);

</script>

<main>

    <section>

        <div class='curr'>

            <div class='content'>
                    
                <div class='col'>
            
                    <h1>Fernando da Rosa Santini</h1>
            
                    <div class='columns'>
            
                        
                        <div class='intro'><strong><icon class="icon"><Contact size='16' /></icon> Profile</strong>
            
                            <ul>

                                <li><icon class="icon"><Contact size='16' /></icon> 31 Yo</li>
                                <li><icon class="icon"><Mail size='16' /></icon> kern.log@outlook.com</li>
                                <li><icon class="icon"><Linkedin size='16' /></icon> https://www.linkedin.com/in/fernando-r-682739124/</li>
                                <li><icon class="icon"><Link size='16' /></icon> https://portfolio-fernando.now.sh/</li>
                                <li><icon class="icon"><Github size='16' /></icon> https://github.com/OSX-RSPlug-a</li>
                                <li><icon class="icon"><Codepen size='16' /></icon> https://codepen.io/Log-N </li>

                            </ul>
                        
                        </div> 
            
                                <p><strong><icon class="icon"><Contact size='16' /></icon> Experience</strong><br/>
                                    <br/>DEVOPS Engineer -
                                    IBM | Oct/2022 - current <br/>
                                    - K8S clusters administration local baremetal
                                    or cloud providers(IBM cloud and OpenShift);
                                    Scripting and IAC: Shell;
                                    Tests with Jmeter; Pipelines with Bamboo;
                                    <br/>
                                    <br/>DEVOPS Jr -
                                    Cedro | May/2021 - Ago/2022 <br/>
                                    - Docker Swarm clusters administration local baremetal
                                    or cloud providers(AWS, GCP, Azure e Equinix);
                                    Scripting and IAC: Python, Shell, Ansible, Terraform and Helm;
                                    Administratration of repositories with
                                    Bitbucket; Learning and begining implementation of
                                    clusters with K8S; Trouble shooting and monitoring 
                                    on servers with tools like Kibana, Grafana and Prometheus.<br/>
                                    <br/>DEVOPS Jr -
                                    SETY | June/2020 - April/2021 <br/>
                                    - AWS, docker, PostgreSQL and Proxmox server administration; 
                                    Automation with Python, Golang and Shell;<br/>
                                    <br/>FULLSTACK DEVELOPER  - Jr <br/> 
                                    LabsConnections | April/2019 - July/2019 <br/>
                                    - Backend: nodejs and typescript. DB:
                                    PostgreSQL; AWS, Proxmox and Docker as infrastructure. 
                                    Frontend: Vuejs and Vuetify.<br/>
                                    <br/>INTERN - TECHNICAL SUPPORT - 
                                    Câmara Municipal de São José dos Campos(municipality)|
                                    May/2018 - March/2019 <br/>
                                    - Technical support for users on AD server, hardware and printers.<br/>
                                    <br/>FREELANCER - TECHNICAL SUPPORT
                                    Dec/2015 - Feb/2018 <br/>
                                    - Technical support for computers and printers.<br/>
                                    <br/>INTERN - SYSTEMS ANALYST -
                                    Fundação Cultural Cassiano Ricardo(cultural municipality) | Nov/2013 -
                                    Nov/2015
                                    <br/>- Web development of internal systems with CMS Joomla and
                                    wordpress; Stacks: PHP, JavaScript, Jquery, Html, CSS e
                                    SQL;<br/>
                                    <br/>SELLER -
                                    Santini Ferragens Ltda-me | Jan/2006 –
                                    Oct/2013. <br/>
                                    - I've started as seller, evolved to Purchasing Agent and some years latter
                                    Manager jr;
                                </p><br/>  
                                <p><strong><icon class="icon"><Scroll size='16' /></icon> Education</strong><br/>
                                <br/>Computer Science
                                - ETEP - Bachelor graduation - July/2015 - ~tdb<br/>
                                High school + IT technical course
                                - ECOMPO –
                                Jan/2007 - Dec/2009<br/><br/>
                                <strong><icon class="icon"><Scroll size='16' /></icon> Courses</strong><br/>
                                <br/>- Information Security I – Intel - Dialog TI; - 6H,
                                February de 2016;<br/>
                                - Pentester course–
                                2°semester/2015 – http://tecnicasdeinvasao.com; <br/>
                                - PHP Security – 4Linux; - 22H, 1ºsemester/2015 <br/>
                                - Python para zumbis –
                                https://www.pycursos.com/python-para-zumbis/<br/>
                                - Docker Mastery: The Complete Toolset From a Docker
                                Captain -
                                https://www.udemy.com/docker-mastery/ - 12.5h July
                                2019;<br/>
                                - React - The Complete Guide (incl Hooks, React Router,
                                Redux) - https://www.udemy.com/react-the-complete-
                                guide-incl-redux/ - in trainning;<br/>
                                - DevOps Deployment Automation with Terraform, AWS and Docker
                                – in trainning –
                                https://www.udemy.com/course/devops-deployment-automation-terraform-aws-docker/;<br/>
                                - Kubernetes for the Absolute Beginners - in trainning -
                                https://www.udemy.com/course/learn-kubernetes/; <br/>
                                - JavaScript - The Complete Guide(Beginner +
                                Advanced) – https://www.udemy.com/course/javascript-
                                the-complete-guide-2020-beginner-advance;<br/>
                                - Introduction to Golang - 
                                https://www.udemy.com/course/getgoing/<br/>
                                
                                <br/><strong><icon class="icon"><Languages size='16' /></icon> Languages</strong><br/>
                                <br/>- English - Advanced; - Jan/2010 - Feb/2014;<br/>
                                - Spanish - Basic; Jan/2007 - Dec/2007;<br/>
                                - Italian - Basic; - in trainning;<br/>
                                - Portuguese - native;<br/>
                            </p>  <br/>
                            <p><strong><icon class="icon"><Scroll size='16' /></icon> Skills</strong><br/>
                            <br/>- Hardware technical support - advanced;<br/>
                            - Servers and cloud providers:
                            Linux, Windows, BSD, AWS, OCI, GCP e Azure; - intermediary;<br/>
                            - Shell, ES/JS, Nodejs, YAML, Html, CSS e SQL; - intermediary;<br/>
                            - Python, Java, Clojure, PHP, Golang; - basic;<br/>
                            - DB: MySql, PostgreSQL e MongoDB; - intermediary;<br/>
                            - Frameworks: React, React-Native, Vue, Svelte, Flask; - basic;<br/>
                            - Tools: Kubernetes, Terraform, Ansible, Istio, Jenkins, Argo-CD
                            Grafana e Prometheus, K8S e Helm Docker and Swarm; - basic/intermediary;<br/>
                            </p>
                        
                    </div>
                </div>
            </div>
        </div>
    </section>
</main>

<style>

    .curr {
        display: flex;
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
        flex-direction: column;
        column-span: all;
        margin-bottom: 4vh;
        margin-top: 4vh;
        text-align: left; 
        align-items: center;
        align-content: center;
        align-self: start;
        
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
        top: 20px;
        margin: auto;
        fill: #fff;
    }

    strong {
        align-self: center;
        align-items: center;
        text-align: start;
        padding: 0% auto;
        margin: auto;
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

    .col h1 {
        margin: auto;
        text-align: center;
        align-items: center;
        align-self:center;
        font-size: 50px;
        margin-top: 10%;
        padding-bottom: 20px;
    }

    @media screen and (max-width: 480px) {
        .curr {
            width: 99%;
            font-size: 0.85em;
        }
        .content {
            width: 83%;
            padding-left: 30px;
            margin: 4%;
            align-items: center;
            text-align: center;
        }
        .col h1 {
            font-size: 25px;
            margin-left: 1%;
        }
        [class^="icon"] {
            margin-left: 15px;
            position: relative;
            float: none;
        }
    }


</style>