<template>
    <div class="flex">
        <!-- side bar -->
        <div class="ml-4 fixed top-1/3 z-10">
            <ul class="mb-3">
                <li>
                    <a href="#hero" class="transition ease-in-out duration-700 hover-trigger 
                    bg-gray-100 text-gray-700 hover:text-white hover:bg-blue-800 
                    rounded-full p-4 w-14 hover:w-28 hover:-mt-1 flex items-center">
                        <div><svg class="w-5 mr-1" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" /> </svg></div>
                        <div class="hover-target">Home</div>
                    </a>
                </li>
            </ul>

            <ul class="mb-3">
                <li>
                    <a href="#about" class="btn-fade-in transition ease-in-out duration-700 hover-trigger 
                    bg-gray-100 text-gray-700 hover:text-white hover:bg-blue-800 active:bg-blue-800
                    rounded-full p-4 w-14 hover:w-28 hover:-mt-1 flex items-center">
                        <div> <svg class="w-5 mr-1"  xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" /> </svg> </div>
                        <div class="hover-target">Tentang</div>
                    </a>
                </li>
            </ul>

            <ul class="mb-3">
                <li>
                    <a href="#skill" class="transition ease-in-out duration-700 hover-trigger 
                    bg-gray-100 text-gray-700 hover:text-white hover:bg-blue-800 
                    rounded-full p-4 w-14 hover:w-28 hover:-mt-1 flex items-center">
                        <div> <svg class="w-5 mr-1" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4" /> </svg> </div>
                        <div class="hover-target">Keahlian</div>
                    </a>
                </li>
            </ul>

            <ul class="mb-3">
                <li>
                    <a href="#portfolio" class="transition ease-in-out duration-700 hover-trigger 
                    bg-gray-100 text-gray-700 hover:text-white hover:bg-blue-800 
                    rounded-full p-4 w-14 hover:w-28 hover:-mt-1 flex items-center">
                        <div> <svg class="w-5 mr-1" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" /> </svg> </div>
                        <div class="hover-target">Portfolio</div>
                    </a>
                </li>
            </ul>
            
        </div>
        <div class="w-screen">
            <main class="w-full">
                <!-- hero -->
                <div id="hero" class="h-screen">
                    <div><img class="h-screen w-screen object-cover object-top" src="https://bootstrapmade.com/demo/templates/MyResume/assets/img/hero-bg.jpg"></div>
                    <div class="relative">
                        <div class="absolute bottom-0 bg-white opacity-75 h-screen w-full"></div>
                    </div>
                    <div class="absolute text-5xl text-gray-700 font-bold font-sans top-52 left-40 z-10 h-screen">Helfanza Nanda Alfara</div>
                    <div class="absolute text-gray-700 text-2xl flex font-sans top-72 left-44 z-10 h-screen">
                        <p class="mr-2">i'm</p>
                        <typical class="typicalWrapper" :steps="['Web Developer', 1000, 'Laravel Developer', 1000]" :loop="Infinity" :wrapper="'h3'" > </typical>
                    </div>
                </div>

                <!-- about -->
                <div id="about" class="pt-10 h-screen px-36" >
                    <div class="text-center text-2xl uppercase font-bold text-gray-700">Tentang</div>
                    <div class="flex flex-wrap justify-center text-blue-800 my-2">
                        <svg class="w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" /> </svg>
                    </div>
                    <div class="px-14 text-center text-gray-700">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloremque culpa vitae asperiores ut tenetur vero nesciunt similique sit fugiat veritatis eos harum amet, blanditiis mollitia. Maiores, doloribus. At, repudiandae doloremque.</div>

                    <div class="mt-10 flex justify-center">
                        <div class="w-2/6 mr-5"><img src="https://bootstrapmade.com/demo/templates/MyResume/assets/img/profile-img.jpg" alt=""></div>
                        <div class="justify-start">
                            <div class="mb-3 text-3xl font-bold text-gray-500 capitalize">web developer.</div>
                            <div class="text-gray-700">Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus fugit illo aperiam culpa sed facilis accusantium dicta assumenda sit magnam.</div>
                            <div class="flex mt-2">
                                <div class="mr-44">
                                    <div class="flex items-center">
                                        <div class="text-blue-800 mr-2"><svg class="w-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /> </svg></div>
                                        <div class="text-gray-700"><strong>Tanggal Lahir</strong>: 19 Desember 1998</div>
                                    </div>
                                </div>
                                <div>
                                    <div>
                                        <div class="flex items-center">
                                            <div class="text-blue-800 mr-2"><svg class="w-5" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /> </svg></div>
                                            <div class="text-gray-700"><strong>Umur</strong>: 22 Tahun</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- skill -->
                <div id="skill" class="pt-10 h-screen px-24 pb-16">
                    <div class="text-center text-2xl uppercase font-bold text-gray-700">Keahlian</div>
                    <div class="flex flex-wrap justify-center text-blue-800 my-2">
                        <svg class="w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" /> </svg>
                    </div>
                    <div class="px-14 text-center text-gray-700">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloremque culpa vitae asperiores ut tenetur vero nesciunt similique sit fugiat veritatis eos harum amet, blanditiis mollitia. Maiores, doloribus. At, repudiandae doloremque.</div>

                    <div class="w-3/4 m-auto mt-6 ">
                        <div class="flex flex-wrap justify-between">
                            <div class="mb-2 ">
                                <div class="flex w-96 justify-between font-sans uppercase font-semibold text-gray-700">
                                    <div>tailwind</div>
                                    <div>9%</div>
                                </div>
                                <div>progress</div>
                            </div>

                            <div class="mb-2 ">
                                <div class="flex w-96 justify-between font-sans uppercase font-semibold text-gray-700">
                                    <div>tailwind</div>
                                    <div>50%</div>
                                </div>
                                <div>progress</div>
                            </div>

                            <div class="mb-2 ">
                                <div class="flex w-96 justify-between font-sans uppercase font-semibold text-gray-700">
                                    <div>tailwind</div>
                                    <div>50%</div>
                                </div>
                                <div>progress</div>
                            </div>

                            <div class="mb-2 ">
                                <div class="flex w-96 justify-between font-sans uppercase font-semibold text-gray-700">
                                    <div>tailwind</div>
                                    <div>50%</div>
                                </div>
                                <div>progress</div>
                            </div>

                            <div class="mb-2 ">
                                <div class="flex w-96 justify-between font-sans uppercase font-semibold text-gray-700">
                                    <div>tailwind</div>
                                    <div>50%</div>
                                </div>
                                <div>progress</div>
                            </div>

                            <div class="mb-2 ">
                                <div class="flex w-96 justify-between font-sans uppercase font-semibold text-gray-700">
                                    <div>tailwind</div>
                                    <div>50%</div>
                                </div>
                                <div>progress</div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- portfolio -->
                <div id="portfolio" class="pt-10 h-screen px-24">
                    <div class="text-center text-2xl uppercase font-bold text-gray-700">Portfilio</div>
                    <div class="flex flex-wrap justify-center text-blue-800 my-2">
                        <svg class="w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" /> </svg>
                    </div>
                    <div class="px-14 text-center text-gray-700">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Doloremque culpa vitae asperiores ut tenetur vero nesciunt similique sit fugiat veritatis eos harum amet, blanditiis mollitia. Maiores, doloribus. At, repudiandae doloremque.</div>

                    <div class="w-3/4 m-auto mt-6 ">
                        <div class="flex flex-wrap justify-between">
                            <div class="mb-2 ">
                                <div class="flex w-96 justify-between font-sans uppercase font-semibold text-gray-700">
                                    <div>tailwind</div>
                                    <div>50%</div>
                                </div>
                                <div>progress</div>
                            </div>
                        </div>
                    </div>
                </div>


                <!-- footer -->
                <div id="footer" class="h-20 flex text-center font-semibold items-center justify-center bg-gray-200 ">
                    <div>
                        <p>© Copyright 2021</p>
                        <p>Designed by Helfanza Nanda Alfara</p>
                    </div>
                </div>
            </main>
        </div>
    </div>
</template>

<style>
.hover-trigger .hover-target {
    display: none;
}

.hover-trigger:hover .hover-target {
    display: block;
}
</style>

// <script>
// import typical from '@/components/typical.js'
// export default {
//     components: {
//         typical,
//     }
// }
// </script>
