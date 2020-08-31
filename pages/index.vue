<template>
    <div class="md:w-5/6 mx-auto py-10 px-6 md:px-0 min-h-screen">
        <h1
            class="text-center font-bold text-4xl"
        >The VITL stack is the vital stack for your Laravel apps</h1>
        <div class="text-center mt-5">
            <p>Vue.js, Inertia.js, Tailwind and Laravel.</p>
        </div>

        <div class="text-left mt-8">
            <div>
                <p
                    class="text-xl text-center font-semibold text-gray-800"
                >The stack for making full-stack applications with the power of modern tech.</p>
            </div>
            <div class="bg-vue-opacity vue-shadow text-gray-900 rounded p-4 my-8">
                <a class="https://vuejs.org/">
                    <span class="font-bold">Vue.js</span> - Build all your pages with the popular and magical Vue.js.
                </a>
            </div>
            <div class="bg-inertia-opacity inertia-shadow text-gray-900 rounded p-4 my-8">
                <a href="https://inertiajs.com/">
                    <span class="font-bold">Inertia.js</span> - Make the front-end an SPA without building an API with Inertia.js and create the modern monolith.
                </a>
            </div>
            <div class="bg-tailwind-opacity tailwind-shadow text-gray-900 rounded p-4 my-8">
                <a class="https://tailwindcss.com">
                    <span class="font-bold">Tailwind CSS</span> - Style with the powerful and productive Tailwind, you won't believe how easy it is.
                </a>
            </div>
            <div class="bg-laravel-opacity laravel-shadow text-gray-900 rounded p-4 my-8">
                <a href="https://laravel.com/">
                    <span class="font-bold">Laravel</span> - Handle the logic with mature and powerful Laravel, which handles most of the complex stuff for you and become an Artisan.
                </a>
            </div>
        </div>
        <div>
            <p>
                Built by
                <a href="https://twitter.com/SamNewby_">Sam Newby</a> at
                <a href="https://renderlabs.io">Render Labs</a> |
                <a href="https://github.com/render-labs/vitlstack.dev">Open source on GitHub</a>
            </p>
        </div>
    </div>
</template>

<style scoped>
.bg-laravel-opacity {
    background-color: rgba(255, 45, 32, 0.35);
}
.bg-vue-opacity {
    background-color: rgba(66, 184, 131, 0.35);
}
.bg-tailwind-opacity {
    background-color: rgba(56, 178, 172, 0.35);
}
.bg-inertia-opacity {
    background-color: rgba(183, 148, 244, 0.35);
}
.vue-shadow {
    -webkit-box-shadow: 8px 8px 0px 0px rgba(66, 184, 131, 1);
    -moz-box-shadow: 8px 8px 0px 0px rgba(66, 184, 131, 1);
    box-shadow: 8px 8px 0px 0px rgba(66, 184, 131, 1);
}
.inertia-shadow {
    -webkit-box-shadow: 8px 8px 0px 0px rgba(183, 148, 244, 1);
    -moz-box-shadow: 8px 8px 0px 0px rgba(183, 148, 244, 1);
    box-shadow: 8px 8px 0px 0px rgba(183, 148, 244, 1);
}
.tailwind-shadow {
    -webkit-box-shadow: 8px 8px 0px 0px rgba(56, 178, 172, 1);
    -moz-box-shadow: 8px 8px 0px 0px rgba(56, 178, 172, 1);
    box-shadow: 8px 8px 0px 0px rgba(56, 178, 172, 1);
}
.laravel-shadow {
    -webkit-box-shadow: 8px 8px 0px 0px rgba(255, 45, 32, 1);
    -moz-box-shadow: 8px 8px 0px 0px rgba(255, 45, 32, 1);
    box-shadow: 8px 8px 0px 0px rgba(255, 45, 32, 1);
}
</style>