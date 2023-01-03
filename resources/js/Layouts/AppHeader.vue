<template>
    <body class="bg-green-50">
        <nav
            class="p-3 border-gray-200 rounded bg-green-100 dark:bg-gray-800 dark:border-gray-700"
        >
            <div
                class="container flex flex-wrap items-center justify-between mx-w-full"
            >
                <a href="#" class="flex items-center">
                    <img
                        src="https://cdn-icons-png.flaticon.com/512/5798/5798171.png"
                        class="fill-green-200 h-6 mr-3 sm:h-10"
                        alt="Flowbite Logo"
                    />
                    <span
                        class="self-center text-xl font-semibold whitespace-nowrap dark:text-white"
                        >fer.crochets</span
                    >
                </a>

                <button
                    data-collapse-toggle="navbar-solid-bg"
                    type="button"
                    class="bg-green-50 inline-flex items-center p-2 ml-3 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600 group"
                    aria-controls="navbar-solid-bg"
                    aria-expanded="false"
                >
                    <span class="sr-only">Open main menu</span>
                    <svg
                        class="w-6 h-6"
                        aria-hidden="true"
                        fill="currentColor"
                        viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <path
                            fill-rule="evenodd"
                            d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
                            clip-rule="evenodd"
                        ></path>
                    </svg>
                    <div
                        class="rounded absolute top-0 -right-full w-screen h-90 bg-emerald-50 border opacity-0 group-focus:right-0 group-focus:opacity-100 transition-all duration-300"
                    >
                        <a href="#" class="flex items-center mt-5 ml-5">
                            <img
                                src="https://cdn-icons-png.flaticon.com/512/5798/5798171.png"
                                class="fill-green-200 h-8 mr-5 sm:h-10"
                                alt="Flowbite Logo"
                            />
                            <span
                                class="self-center text-3xl font-semibold whitespace-nowrap dark:text-white"
                                >fer.crochets</span
                            >
                        </a>
                        <ul
                            class="flex flex-col items-center w-full text-2xl cursor-pointer pt-10"
                        >
                            <li
                                class="rounded hover:bg-gray-200 py-4 px-6 w-full"
                            >
                                Home
                            </li>
                            <li
                                class="rounded hover:bg-gray-200 py-4 px-6 w-full"
                            >
                                Services
                            </li>
                            <li
                                class="rounded hover:bg-gray-200 py-4 px-6 w-full"
                            >
                                Pricing
                            </li>
                            <li
                                class="rounded hover:bg-gray-200 py-4 px-6 w-full"
                            >
                                Contact
                            </li>
                        </ul>
                    </div>
                </button>

                <div
                    class="hidden w-full md:block md:w-auto"
                    id="navbar-solid-bg"
                >
                    <ul
                        class="flex flex-col mt-4 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:text-lg md:font-medium md:border-0 md:bg-transparent dark:bg-gray-800 md:dark:bg-transparent dark:border-gray-700"
                    >
                        <li>
                            <a
                                href="#"
                                class="block py-2 pl-3 pr-4 text-white bg-blue-700 rounded md:bg-transparent md:text-green-700 md:p-0 md:dark:text-white dark:bg-blue-600 md:dark:bg-transparent"
                                aria-current="page"
                                >Home</a
                            >
                        </li>
                        <li>
                            <a
                                href="#"
                                class="block py-2 pl-3 pr-4 text-gray-700 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-green-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
                                >Services</a
                            >
                        </li>
                        <li>
                            <a
                                href="#"
                                class="block py-2 pl-3 pr-4 text-gray-700 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-green-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
                                >Pricing</a
                            >
                        </li>
                        <li>
                            <a
                                href="#"
                                class="block py-2 pl-3 pr-4 text-gray-700 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-green-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
                                >Contact</a
                            >
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </body>
</template>
