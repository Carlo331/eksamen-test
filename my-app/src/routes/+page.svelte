<script>
    import "tailwindcss/tailwind.css"
    import "../app.css";

    let knapp0 = "^"
    let knapp1 = "1"
    let knapp2 = "2"
    let knapp3 = "3"
    let knapp4 = "4"
    let knapp5 = "5"
    let knapp6 = "6"
    let knapp7 = "7"



</script>
<div class="snap-y snap-mandatory overflow-y-scroll h-screen w-screen scroll-smooth">
    <section id="section0" class="flex snap-always snap-center items-center justify-between  bg-slate-300 h-screen w-screen">
        <div id="overskrift" class="flex w-1/3 justify-center   ">
            <span id="pc komponenter overskrift" class="text-green-600 text-4xl">PC komponenter</span>
        </div>
        <div id="pc bilde div" class="flex w-2/3 relative h-5/6   items-center justify-center ">
            <img id="pc bilde" class="h-full" src='pc.png' alt="gaming pc">
            <div id="knappe div" class="flex flex-col absolute items-center h-full w-2/3">
                <div class="mt-1"></div>
                <div class="flex w-full mt-44 items-center h-10 ">
                    <button class="flex w-6 ml-8 h-6 btn btn1 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:click={() => {const section1 = document.getElementById('section1')
                     section1.scrollIntoView({ behavior: 'smooth' });}} on:mouseenter={()=> {knapp1 = "Vifte"}} on:mouseleave={()=> {knapp1 = "1"}}>{knapp1}</button>
                </div>
                <div class="flex w-full mt-1 items-center h-10 ">
                    <div class="ml-3"></div>
                    <button class="flex w-6 ml-36 h-6 btn btn2 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:click={() => {const section2 = document.getElementById('section2')
                        section2.scrollIntoView({ behavior: 'smooth' });}} on:mouseenter={()=> {knapp2 = "CPU"}} on:mouseleave={()=> {knapp2 = "2"}}>{knapp2}</button>
                    <button class="flex w-6 ml-1 h-6 btn btn3 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:click={() => {const section3 = document.getElementById('section3')
                        section3.scrollIntoView({ behavior: 'smooth' });}} on:mouseenter={()=> {knapp3 = "kjøler"}} on:mouseleave={()=> {knapp3 = "3"}}>{knapp3}</button>
                    <button class="flex w-6 ml-11 h-6 btn btn4 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:click={() => {const section4 = document.getElementById('section4')
                        section4.scrollIntoView({ behavior: 'smooth' });}} on:mouseenter={()=> {knapp4 = "RAM"}} on:mouseleave={()=> {knapp4 = "4"}}>{knapp4}</button>
                </div>
                <div class="flex w-full mt-5 items-center h-10  ">
                    <button class="flex w-6 ml-24 h-6 btn btn5 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:click={() => {const section5 = document.getElementById('section5')
                        section5.scrollIntoView({ behavior: 'smooth' });}} on:mouseenter={()=> {knapp5 = "Hovedkort"}} on:mouseleave={()=> {knapp5 = "5"}}>{knapp5}</button>
                </div>
                <div class="flex w-full mt-10 items-center h-10  ">
                    <button class="flex w-6 ml-20 h-6 btn btn6 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:click={() => {const section6 = document.getElementById('section6')
                        section6.scrollIntoView({ behavior: 'smooth' });}} on:mouseenter={()=> {knapp6 = "GPU"}} on:mouseleave={()=> {knapp6 = "6"}}>{knapp6}</button>
                </div>
                <div class="flex w-full mt-36 items-center h-8  ">
                    <button class="flex w-6 ml-20 h-6 btn btn7 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:click={() => {const section7 = document.getElementById('section7')
                        section7.scrollIntoView({ behavior: 'smooth' });}} on:mouseenter={()=> {knapp7 = "PSU"}} on:mouseleave={()=> {knapp7 = "7"}}>{knapp7}</button>
                </div>
            </div>
        </div>
    </section>
    <section id="section1" class="flex snap-always snap-center items-center justify-between bg-orange-300 h-screen w-screen">
        <div class="flex h-full items-center justify-center w-1/2   ">
            <img class="h-3/5" src="vifte.png" alt="vifte">
        </div>
        <div class="flex flex-col h-full w-1/2   justify-center items-center ">
            <span class="text-3xl mb-5">Vifter</span>
            <span class="flex p-3 items-center justify-center text-xl bg-gray-400 rounded-xl w-3/5 h-2/5">Vifter i en pc er vanligvis brukt til å suge kald luft inn og dytte varm luft ut.Når en bygger en pc er det viktig å ha riktig mengde inntak og uttak. Hvis en har for mye inntak blir det for høyt trykk og hvis en har for mye uttak blir det nesten et vakum. Begge deler kan resultere i værre termisk ytelse.</span>
            <button class="flex btn justify-center border-2 border-blue-600 bg-slate-200 rounded w-1/12 h-10 mt-2 text-5xl" on:click={() => {const section0 = document.getElementById('section0')
                section0.scrollIntoView({ behavior: 'smooth' });}}>^</button>
        </div>
    </section>
    <section id="section2" class="flex snap-always snap-center items-center justify-between bg-red-300 h-screen w-screen">
        <div class="flex flex-col h-full w-1/2   justify-center items-center ">
            <span class="text-3xl mb-5">CPU</span>
            <span class="flex p-3 items-center justify-center text-xl bg-gray-400 rounded-xl w-3/5 h-2/5">CPU en eller central prossesing unit som det står for er hjernen av hele pcen. CPUen er ansvarlig for å styre hvilke komponenter gjør hva. CPUen er også ansvarlig for mange av kankulasjonene som må gjøres for tyngere programmer. Den bestemmer også hva som skal lagres hvor og hvordan det blir behandlet.</span>
            <button class="flex btn justify-center border-2 border-blue-600 bg-slate-200 rounded w-1/12 h-10 mt-2 text-5xl" on:click={() => {const section0 = document.getElementById('section0')
                section0.scrollIntoView({ behavior: 'smooth' });}}>^</button>
        </div>
        <div class="flex h-full items-center justify-center w-1/2   ">
            <img class="h-3/5" src="cpu.png" alt="cpu">
        </div>
    </section>
    <section id="section3" class="flex snap-always snap-center items-center justify-between bg-green-300 h-screen w-screen">
        <div class="flex h-full items-center justify-center w-1/2   ">
            <img class="h-4/5" src="kjøler.png" alt="kjøler">
        </div>
        <div class="flex flex-col h-full w-1/2   justify-center items-center ">
            <span class="text-3xl mb-5">Kjøler</span>
            <span class="flex p-3 items-center justify-center text-xl bg-gray-400 rounded-xl w-3/5 h-2/5">Kjølere er brukt for og fjærne varmen fra esensielle komponenter. Dette er spesifikt en CPU kjøler og er ansvarlig for å bruke den nye kalde luften viftene suger inn til og kjøle CPUen. En for varm CPU kan resultere i mye værre ytelse eller i værstefall skade til CPUen.</span>
            <button class="flex btn justify-center border-2 border-blue-600 bg-slate-200 rounded w-1/12 h-10 mt-2 text-5xl" on:click={() => {const section0 = document.getElementById('section0')
                section0.scrollIntoView({ behavior: 'smooth' });}}>^</button>
        </div>
    </section>
    <section id="section4" class="flex snap-always snap-center items-center justify-between bg-blue-300 h-screen w-screen">
        <div class="flex flex-col h-full w-1/2   justify-center items-center ">
            <span class="text-3xl mb-5">RAM</span>
            <span class="flex p-3 items-center justify-center text-xl bg-gray-400 rounded-xl w-3/5 h-2/5">RAM eller random accses memory som det står for er ansvarlig for kortvarig lagring. Dette betyr at ting som google chrome tabs eller lignene ligger lagret i RAM. Alt som er lagret i RAM er der mest sansynlig fordi det trenger å være tilgjengelig i nermere fremtid. Dette er mye raskere en å sende alt til langvarig lagring.</span>
            <button class="flex btn justify-center border-2 border-blue-600 bg-slate-200 rounded w-1/12 h-10 mt-2 text-5xl" on:click={() => {const section0 = document.getElementById('section0')
                section0.scrollIntoView({ behavior: 'smooth' });}}>^</button>
        </div>
        <div class="flex h-full items-center justify-center w-1/2   ">
            <img class="h-3/5" src="ram.png" alt="ram">
        </div>
    </section>
    <section id="section5" class="flex snap-always snap-center items-center justify-between bg-purple-300 h-screen w-screen">
        <div class="flex h-full items-center justify-center w-1/2   ">
            <img class="h-4/5" src="hoverkort.png" alt="hovedkort">
        </div>
        <div class="flex flex-col h-full w-1/2   justify-center items-center ">
            <span class="text-3xl mb-5">Hovedkort</span>
            <span class="flex p-3 items-center justify-center text-xl bg-gray-400 rounded-xl w-3/5 h-2/5">Hovedkortet er egentlig bare ansvarlig for å komble alle komponentene sammen sånn at CPUen kan snakke med dem. Den leverer også strøm til ting som CPUen og RAMen. Ting som USB porter og lignene oppbevarer seg mest sansynlig bare på hovedkortet.</span>
            <button class="flex btn justify-center border-2 border-blue-600 bg-slate-200 rounded w-1/12 h-10 mt-2 text-5xl" on:click={() => {const section0 = document.getElementById('section0')
                section0.scrollIntoView({ behavior: 'smooth' });}}>^</button>
        </div>
    </section>
    <section id="section6" class="flex snap-always snap-center items-center justify-between bg-lime-300 h-screen w-screen">
        <div class="flex flex-col h-full w-1/2   justify-center items-center ">
            <span class="text-3xl mb-5">GPU</span>
            <span class="flex p-3 items-center justify-center text-xl bg-gray-400 rounded-xl w-3/5 h-2/5">GPU eller Graphics processing unit er ansvarlig for å håndtere grafikken til pcen. Dette vil si at skjermen din er mest sansynlig koblet til GPUen. GPUen er også viktig i programmer som Blender eller Premiere Pro. En raskt GPUen er ofte nødvendig for gaming siden spill ogfte må rendre store landskaper.</span>
            <button class="flex btn justify-center border-2 border-blue-600 bg-slate-200 rounded w-1/12 h-10 mt-2 text-5xl" on:click={() => {const section0 = document.getElementById('section0')
                section0.scrollIntoView({ behavior: 'smooth' });}}>^</button>
        </div>
        <div class="flex h-full items-center justify-center w-1/2   ">
            <img class="w-11/12" src="gpu.png" alt="gpu">
        </div>
    </section>
    <section id="section7" class="flex snap-always snap-center items-center justify-between bg-pink-300 h-screen w-screen">
        <div class="flex h-full items-center justify-center w-1/2   ">
            <img class="h-3/5" src="psu.png" alt="psu">
        </div>
        <div class="flex flex-col h-full w-1/2   justify-center items-center ">
            <span class="text-3xl mb-5">PSU</span>
            <span class="flex p-3 items-center justify-center text-xl bg-gray-400 rounded-xl w-3/5 h-2/5">PSU eller Power Suply Unit er hjertet av hele pcen. Dette er fordi PSUen er ansvarlig for å gi strøm til alle komponentene. dette gjør den ved å enten ha en direkte kabel til de som GPUen har, eller og gi strøm til større ting som Hovedkortet som vidre sprer det ut til komponentene som trenger det.</span>
            <button class="flex btn justify-center border-2 border-blue-600 bg-slate-200 rounded w-1/12 h-10 mt-2 text-5xl" on:click={() => {const section0 = document.getElementById('section0')
                section0.scrollIntoView({ behavior: 'smooth' });}}>^</button>
        </div>
    </section>
</div>
<style>

    .btn {
        transition: transform 0.2s ease
    }
    
    .btn:active {
        transform: scale(0.9)
    }
    .btn:hover{
        transform: scale(1.1);
    }
    .btn1:hover{
        width: 3rem;
    }
    .btn2:hover{
        width: 2.5rem;
    }
    .btn3:hover{
        width: 3rem;
    }
    .btn4:hover{
        width: 3rem;
    }
    .btn5:hover{
        width: 5.5rem;
    }
    .btn6:hover{
        width: 3rem;
    }
    .btn7:hover{
        width: 3rem;
    }
</style>
