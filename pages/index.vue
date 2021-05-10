<template>
  <div>
    <!-- Main Area -->
    <div class="container mx-auto px-10 mt-9 mb-10">
      <div class="flex justify-between">
        <span class="font-bold text-2xl tracking-normal">Registrieren</span>
        <NuxtLink to="/login">
          <button class="rounded-full bg-gray-200 px-3.5 py-1.5">Log in</button>
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
            <span>Name</span>
            <input
              type="text"
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
              placeholder="Name"
            />
          </label>
          <label class="block">
            <span class="text-gray-700">Password</span>
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
              placeholder="Password"
            />
          </label>
          <label class="block">
            <span class="text-gray-700">Country</span>
            <select
              class="
                block
                w-full
                mt-1
                rounded-full
                bg-gray-100
                border-transparent
                focus:border-gray-500
                focus:bg-white
                focus:ring-0
              "
            >
              <option>Switzerland</option>
              <option>Germany</option>
              <option>France</option>
              <option>Netherlands</option>
              <option>Belgium</option>
              <option>Austria</option>
              <option>Luxembourg</option>
              <option>Monaco</option>
              <option>Italy</option>
              <option>Spain</option>
            </select>
          </label>
          <label class="block">
            <button class="bg-indigo-600 rounded-full p-4 w-full text-white">
              Register
            </button>
          </label>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
