<template>
  <div class="mb-auto h-10">
    <!-- Main Area -->
    <div class="container mx-auto px-10 mt-9 mb-10">
      <div class="flex justify-between">
        <span class="font-bold text-2xl tracking-normal">LOGIN</span>
        <NuxtLink to="/">
          <button class="rounded-full bg-gray-200 px-3.5 py-1.5 font-bold">
            Registrieren
          </button>
        </NuxtLink>
      </div>

      <!-- Form Area -->
      <div>
        <div class="grid grid-cols-1 gap-6 mt-10">
          <label class="block">
            <span class="text-gray-700">E-mail Adresse</span>
            <input
              type="email"
              class="
                mt-1
                block
                w-full
                rounded-full
                bg-gray-100
                border-transparent
                focus:border-gray-500
                focus:bg-white
                focus:ring-0
              "
              placeholder="E-mail Address"
            />
          </label>
          <label class="block">
            <span class="text-gray-700">Passwort</span>
            <input
              type="password"
              class="
                mt-1
                block
                w-full
                rounded-full
                bg-gray-100
                border-transparent
                focus:border-gray-500
                focus:bg-white
                focus:ring-0
              "
              placeholder="Passwort"
            />
          </label>
          <span class="-mt-3.5 ml-4 underline cursor-pointer text-sm"
            >Passwort vergessen?</span
          >

          <label class="block">
            <button class="bg-indigo-600 rounded-full p-4 w-full text-white">
              Login
            </button>
          </label>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Login',
}
</script>

<style scoped></style>
