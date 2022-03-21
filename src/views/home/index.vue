<template>
  <div class="home-container bg-gray-200 font-sans font-thin flex flex-col">
    <div class="mx-auto max-w-xl py-10 sm:py-20 text-center">
      <a href="#" class="block text-2xl mb-8 sm:mb-12">Hal Wang</a>

      <ul class="flex justify-center uppercase text-xs">
        <li>
          <a href="#" class="mx-4 hover:text-gray-600">Home</a>
        </li>
        <li>
          <a href="https://blog.hal.wang" target="_blank" class="mx-4 hover:text-gray-600">Blog</a>
        </li>
        <li>
          <a href="https://github.com/hal-wang" target="_blank" class="mx-4 hover:text-gray-600">
            GitHub
          </a>
        </li>
        <li>
          <a href="#" class="mx-4 hover:text-gray-600">Contact</a>
        </li>
      </ul>
    </div>

    <div class="mx-auto max-w-6xl bg-white sm:py-20 py-8 px-12 lg:px-24 shadow-xl mb-24">
      <div class="mb-0 sm:mb-8">
        <h1 class="text-3xl lg:text-4xl text-center mb-6 tracking-wider">About Me</h1>

        <p class="tracking-wide text-sm mb-4 leading-relaxed mx-auto max-w-xl text-left">
          Hello.
          <br class="hidden md:block" />
          My name is Hal Wang.
        </p>

        <p
          class="tracking-wide text-xs mb-2 text-gray-600 leading-loose mx-auto max-w-xl text-left"
        >
          I am a developer working in Beijing.
        </p>

        <p
          class="tracking-wide text-xs mb-2 text-gray-600 leading-loose mx-auto max-w-xl text-left"
        >
          Things I code with:
        </p>

        <div class="badges mx-auto max-w-xl flex flex-wrap flex-row">
          <img src="https://img.shields.io/badge/C%23-WPF-lightgreen" alt="" />
          <img src="https://img.shields.io/badge/C%23-UWP-red" alt="" />
          <img src="https://img.shields.io/badge/C%23-Asp.NET Core-purple" alt="" />
          <img src="https://img.shields.io/badge/C%23-Xamarin-%233498db" alt="" />
          <img src="https://img.shields.io/badge/C%23-Blazor-%23572a8a" alt="" />

          <img src="https://img.shields.io/badge/JS-TypeScript-blue" alt="" />
          <img src="https://img.shields.io/badge/JS-Vue2/3-%2341b883" alt="" />
          <img src="https://img.shields.io/badge/JS-UniApp-%232a9938" alt="" />
          <img src="https://img.shields.io/badge/NodeJS-Koa-yellow" alt="" />
          <img src="https://img.shields.io/badge/NodeJS-Express-pink" alt="" />
          <img src="https://img.shields.io/badge/NodeJS-NestJS-red" alt="" />
          <img src="https://img.shields.io/badge/Dart-Flutter-%235ec8f7" alt="" />

          <img src="https://img.shields.io/badge/SQL-MySql-%2300758f" alt="" />
          <img src="https://img.shields.io/badge/SQL-SqlServer-red" alt="" />
          <img src="https://img.shields.io/badge/SQL-MongoDB-%2300ed64" alt="" />

          <img src="https://img.shields.io/badge/Docker-%230b8ece" alt="" />
          <img src="https://img.shields.io/badge/Nginx-%2304a351" alt="" />
          <img src="https://img.shields.io/badge/Photoshop-%2300bad9" alt="" />
        </div>
      </div>
    </div>

    <div class="bg-white px-6 py-4 sm:py-10 mt-4">
      <div class="mx-auto container text-gray-800 text-sm flex justify-center">
        <a
          target="_blank"
          href="http://www.beian.gov.cn/portal/registerSystemInfo?recordcode=34122602000299"
        >
          <p>皖公网安备 34122602000299号</p>
        </a>
        <span class="mx-2">|</span>
        <a href="https://beian.miit.gov.cn" target="_blank">
          <p> 京ICP备19029465号-5 </p>
        </a>
      </div>
    </div>
  </div>
</template>

<style lang="less" scoped>
  .home-container {
    height: 100%;

    .badges {
      img {
        margin-right: 4px;
        margin-bottom: 4px;
      }
    }
  }
</style>
