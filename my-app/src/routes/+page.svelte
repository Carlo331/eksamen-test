<script>
    import "tailwindcss/tailwind.css"
    import "../app.css";

    let knapp1 = "1"
    let knapp2 = "2"
    let knapp3 = "3"
    let knapp4 = "4"
    let knapp5 = "5"
    let knapp6 = "6"
    let knapp7 = "7"



</script>
<div class="snap-y snap-mandatory overflow-y-scroll h-screen w-screen scroll-smooth">
    <section id="main" class="flex snap-always snap-center items-center justify-between  bg-slate-300 h-screen w-screen">
        <div id="overskrift" class="flex w-1/3 justify-center border-2 border-red-900">
            <span id="pc komponenter overskrift" class="text-green-600 text-4xl">PC komponenter</span>
        </div>
        <div id="pc bilde div" class="flex w-2/3 relative h-5/6 border-2 items-center justify-center border-red-900">
            <img id="pc bilde" class="h-full" src='pc.png' alt="gaming pc">
            <div id="knappe div" class="flex flex-col absolute items-center h-full border-2 border-red-900 w-2/3">
                <div class="flex w-full mt-44 items-center h-10 ">
                    <button class="flex w-6 ml-8 h-6 btn btn1 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:mouseenter={()=> {knapp1 = "Vifte"}} on:mouseleave={()=> {knapp1 = "1"}}>{knapp1}</button>
                </div>
                <div class="flex w-full mt-1 items-center h-10 ">
                    <div class="ml-2"></div>
                    <button class="flex w-6 ml-36 h-6 btn btn2 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:mouseenter={()=> {knapp2 = "CPU"}} on:mouseleave={()=> {knapp2 = "2"}}>{knapp2}</button>
                    <button class="flex w-6 ml-1 h-6 btn btn3 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:mouseenter={()=> {knapp3 = "kjøler"}} on:mouseleave={()=> {knapp3 = "3"}}>{knapp3}</button>
                    <button class="flex w-6 ml-11 h-6 btn btn4 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:mouseenter={()=> {knapp4 = "RAM"}} on:mouseleave={()=> {knapp4 = "4"}}>{knapp4}</button>
                </div>
                <div class="flex w-full mt-5 items-center h-10  ">
                    <button class="flex w-6 ml-24 h-6 btn btn5 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:mouseenter={()=> {knapp5 = "Hovedkort"}} on:mouseleave={()=> {knapp5 = "5"}}>{knapp5}</button>
                </div>
                <div class="flex w-full mt-10 items-center h-10  ">
                    <button class="flex w-6 ml-20 h-6 btn btn6 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:mouseenter={()=> {knapp6 = "GPU"}} on:mouseleave={()=> {knapp6 = "6"}}>{knapp6}</button>
                </div>
                <div class="flex w-full mt-36 items-center h-8  ">
                    <button class="flex w-6 ml-20 h-6 btn btn7 rounded-xl items-center justify-center border-2 border-blue-600 bg-slate-200" on:mouseenter={()=> {knapp7 = "PSU"}} on:mouseleave={()=> {knapp7 = "7"}}>{knapp7}</button>
                </div>
            </div>
        </div>
    </section>
    <section class="flex snap-always snap-center items-center justify-between bg-orange-300 h-screen w-screen">

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
