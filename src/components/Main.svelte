<script>
    import Step from "./Step.svelte";

    let steps = [
        {
            name: "Binary Search Tree Optimization",
            icon: "fa-solid fa-diagram-project",
            description:
                "Developed and optimized a Binary Search Tree (BST) for efficient data retrieval, search, and storage operations. The project involved implementing complex algorithms to ensure optimal time complexity and data structure integrity.",
        },
        {
            name: "SQLite Database Management",
            icon: "fa-solid fa-list-check",
            description:
                "Built a lightweight database management interface using SQLite, facilitating easy data storage and retrieval for small to mid-sized web applications. The project involved efficient querying and backend optimization for seamless operations.",
        },
        {
            name: "Minimalistic GPT-3.5 Chatbot Web Interface",
            icon: "fa-solid fa-diagram-project",
            description:
                "Designed and implemented a simple, clean web interface for a GPT-3.5 chatbot, allowing users to interact with the AI model through an intuitive interface. Leveraged the OpenAI API for processing requests and delivering real-time responses.",
        },
    ];

    let benefits = [
        {
            metric: "10x",
            name: "a passionate cloud software engineer",
            description:
                "As a self-taught developer with a degree in computer science, I have the foundational knowledge and hands-on experience in full-stack development, cloud computing, and software engineering. I've developed projects using JavaScript, HTML, CSS, as well as modern frameworks and cloud platforms like AWS. My passion for problem-solving drives me to create efficient, scalable solutions.",
        },
        {
            name: "a cloud architecture enthusiast",
            description:
                "I am fascinated by cloud infrastructure and architecture. I specialize in creating cloud-native applications and leveraging services like AWS, enabling businesses to seamlessly scale and optimize their operations. From cloud migrations to automation and security, I constantly challenge myself to design solutions that meet both performance and cost-efficiency goals.",
        },
        {
            name: "a collaborative team player",
            description:
                "I value collaboration and effective communication within teams. With my transparent, solutions-oriented communication style, I strive to build strong relationships with colleagues. I actively seek feedback, share knowledge, and contribute to a culture of continuous improvement, making me a productive and reliable team member.",
        },
        {
            name: "a proactive problem solver",
            description:
                "Whether it's tackling code challenges or optimizing cloud solutions, I thrive in environments where creative problem-solving is key. I focus on staying current with the latest technologies and best practices, ensuring my solutions are robust, innovative, and align with long-term business goals.",
        },
        {
            name: "a fast learner and adaptable engineer",
            description:
                "I’m always eager to learn new technologies and adapt to changing project needs. My self-driven nature means I am quick to pick up new skills and apply them effectively in real-world scenarios. This versatility ensures I can contribute value across various domains, from front-end to cloud infrastructure.",
        },
    ];
</script>

<main class="flex flex-col flex-1 p-4">
    <section
        id="introPage"
        class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14"
    >
        <div
            class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
        >
            <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
                Hi! I'm <span class="poppins text-violet-400">Laynie</span> Tierney
                <br />Full Stack
                <span class="poppins text-violet-400">Developer</span>
            </h2>
            <p class="text-base sm:text-lg md:text-xl">
                My <span class="text-violet-400"> favorite tech</span> includes Python, JavaScript, Java, C++, React, Django, MongoDB
                (NEXT.JS or SvelteKit), TailwindCSS, Node.js + Express.js & PostgreSQL
                or SQLite!
            </p>
            <button
                class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950"
            >
                <div
                    class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
                />
                <h4 class="relative z-9">Get in touch &rarr;</h4>
            </button>
        </div>
        <div class="relative shadow-2xl grid place-items-center">
            <img
                src={"images/profile.png"}
                alt="Zetane Engine"
                class="object-cover z-[2] max-h-[70vh]"
            />
        </div>
        <!-- <div  class="flex p-0.5 relative max-w-[700px] w-full mx-auto">
            <div
                class="absolute inset-0 overflow-hidden rounded-md flex items-center justify-center"
            >
                <div
                    class="bg-gradient-to-r absolute inset-[-20px]  from-violet-800 to-indigo-800 specialSpin"
                />
            </div>

            <img
                src={"images/zetane-engine.jpeg"}
                alt="Zetane Engine"
                class="w-full h-full object-cover z-[2]"
            />
        </div> -->
    </section>
    <section class="py-20 lg:py-32 flex flex-col gap-24" id="projects">
        <div class="flex flex-col gap-2 text-center">
            <h6 class="text-large sm:text-xl md:text-2xl">
                A few of my creative endeavors.
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                Curious to <span class="poppins text-violet-400">see</span> my work?
            </h3>
        </div>
        <a
            href="https://www.youtube.com/watch?v=jWdEM6XLKqI&pp=ygUnSW50cm9kdWN0aW9uIHRvIENsb3VkIENvbXB1dGluZyBhbmQgQVdT"
            target="_blank"
            class="mx-auto px-4 py-2 rounded-md border border-solid border-white flex items-center gap-2 -mb-4 sm:-mb-0 -mt-10 hover:border-violet-700 duration-200"
        >
            <i class="fa-regular fa-circle-play" />
            <p>What is AWS?</p>
        </a>
    <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
        <!-- Binary Search Tree Optimization Project -->
        <a
            href="https://github.com/lvtierne/mainprojects/blob/main/Enhanced%20Projects/BTS%20(Enhanced).zip"
            target="_blank"
            class="block"
        >
            <Step step={steps[0]}>
                <p>
                    Developed and optimized a Binary Search Tree (BST) <strong class="text-violet-400">
                    for efficient data retrieval, search, and storage operations.</strong> The project involved implementing complex algorithms to ensure optimal time complexity and data structure integrity.
                </p>
            </Step>
        </a>

        <!-- SQLite Database Management Project -->
        <a
            href="https://github.com/lvtierne/mainprojects/blob/main/Enhanced%20Projects/SQLite%20Database%20Management%20Project.zip"
            target="_blank"
            class="block"
        >
            <Step step={steps[1]}>
                <p>
                    Built a lightweight database management interface using <strong class="text-violet-400">SQLite</strong>, facilitating
                    <strong class="text-violet-400">easy data storage and retrieval for small to mid-sized web applications.</strong>
                    The project involved efficient querying and backend optimization for seamless operations.
                </p>
            </Step>
        </a>

        <!-- Minimalistic GPT-3.5 Chatbot Web Interface Project -->
        <a
            href="https://github.com/lvtierne/Minimalistic-GPT-3.5-Chatbot-Web-Interface"
            target="_blank"
            class="block"
        >
            <Step step={steps[2]}>
                <p>
                    Designed and implemented a <strong class="text-violet-400">simple, clean web interface for a GPT-3.5 chatbot</strong>, allowing users to interact with the AI model through an intuitive interface.
                    <strong class="text-violet-400">Leveraged the OpenAI API</strong> for processing requests and delivering real-time responses.
                </p>
            </Step>
        </a>
    </div>
    </section>
    <section
        id="about"
        class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
    >
        <!-- <div class="z-[-1] bg-violet-950 w-screen left-1/2 -translate-x-1/2 top-0 h-full absolute"> </div> -->
        <div
            class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
        >
            <h6 class="text-large sm:text-xl md:text-2xl">
                Want to know more?
            </h6>
            <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
                A bit <span class="poppins text-violet-400">about</span> me.
            </h3>
        </div>
        <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
            I am . . .
        </p>
        <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
            {#each benefits as benefit, index}
                <!-- <div class="flex flex-col gap-2 mx-auto">
                    <div class="flex items-end gap-4">
                        <p
                            class="poppins text-6xl sm:text-7xl md:text-8xl text-slate-500 font-medium"
                        >
                            {benefit.metric}
                        </p>
                        <p
                            class="text-xl sm:text-2xl md:text-3xl capitalize pb-2"
                        >
                            {benefit.name}
                        </p>
                    </div>
                    <p class="text-center italic">- {benefit.description}</p>
                </div> -->
                <div class="flex gap-6 sm:gap-8">
                    <p
                        class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
                    >
                        0{index + 1}
                    </p>
                    <div class="flex flex-col gap-6 sm:gap-8">
                        <h3 class="text-2xl sm:text-3xl md:text-5xl">
                            {benefit.name}
                        </h3>
                        <p>{benefit.description}</p>
                    </div>
                </div>
            {/each}
        </div>
        <h5 class={" text-2xl sm:text-3xl font-semibold text-center poppins "}>
            The <span class="text-violet-400">Complete</span> Package
        </h5>
        <div
            class="flex flex-col overflow-x-scroll gap-10 max-w-[800px] mx-auto w-full"
        >
            <table class="bg-white text-slate-700 rounded text-center">
                <thead class={"border-b border-solid border-slate-200  "}>
                    <tr class="">
                        <th />
                        <th class="whitespace-nowrap p-2 px-4">Candidate #1</th>
                        <th class="whitespace-nowrap p-2 px-4">Candidate #2</th>
                        <th class="whitespace-nowrap p-2 px-4">Candidate #3</th>
                        <th
                            class="bg-violet-700 text-white whitespace-nowrap p-4 px-8"
                            >Me</th
                        >
                    </tr>
                </thead>
                <tbody>
                    <tr class="border-b border-solid border-slate-200">
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            >Dedication</td
                        >
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                    <tr class="border-b border-solid border-slate-200">
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            >Critical Thought</td
                        >
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                    <tr>
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            >Interpersonal Skills</td
                        >
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                    <tr class="border-t border-solid border-slate-200">
                        <td
                            class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm"
                            >Progamming Ability</td
                        >
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-xmark text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-slate-500" /></td>
                        <td><i class="fa-solid fa-check text-green-500" /></td>
                    </tr>
                </tbody>
            </table>
        </div>
        <div class="mx-auto -mt-12 italic sm:hidden opacity-50">
            <p>Scroll to see more &rarr;</p>
        </div>
        <p class="mx-auto">So why not invest?</p>
    </section>
</main>
