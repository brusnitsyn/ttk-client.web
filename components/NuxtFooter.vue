<template>
  <div class="py-6 flex flex-row justify-between items-center">
    <div>
      <NuxtLogo />
    </div>
    <form class="flex flex-col gap-y-1">
      <label class="block">
        <span class="block">Подпишитесь на рассылку новостей</span>
        <div class="flex">
          <input
            type="email"
            name="newsletter"
            id="newsletter"
            placeholder="example@domain.ru"
            class="
              peer
              border-l border-t border-b border-[#D3D3D3]
              p-3
              focus:outline-none focus:border-accent
              invalid:border-pink-500
              focus:invalid:border-pink-500
            "
          />
          <button class="w-12 bg-accent flex items-center justify-center">
            <svg
              width="24"
              height="24"
              viewBox="0 0 48 48"
              fill="none"
              class="text-dark"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M38.0928 6.54218C40.1426 6.13224 41.8678 7.85776 41.4578 9.90726L41.4398 9.99734L31.611 39.6846L31.61 39.6874C31.1462 41.0786 29.8456 41.6088 28.7698 41.5062C27.7174 41.406 26.544 40.6682 26.308 39.2632L26.3074 39.2596L23.7414 24.2586L8.74038 21.6926C8.73912 21.6924 8.73784 21.6922 8.73658 21.692C7.33174 21.456 6.59396 20.2824 6.49376 19.2302C6.39134 18.1545 6.9215 16.8537 8.3127 16.39L8.31558 16.389L38.0028 6.56018L38.0928 6.54218V6.54218ZM38.4168 9.58325L10.2529 18.9078L24.3384 21.3172C24.9294 21.3494 25.5174 21.5722 25.9726 22.0274C26.428 22.4826 26.6506 23.0706 26.6828 23.6616L29.0922 37.747L38.4168 9.58325V9.58325Z"
                fill="currentColor"
              />
            </svg>
          </button>
          <p class="mt-2 invisible peer-invalid:visible text-pink-600 text-sm">
            Пожалуйста, укажите действующий адрес электронной почты.
          </p>
        </div>
      </label>
    </form>
  </div>
</template>
