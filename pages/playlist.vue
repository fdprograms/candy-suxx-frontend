<template>
  <div class="h-screen overflow-hidden">
    <div class="min-h-screen flex flex-row bg-gray-100">
      <div class="w-1/6">
        <Navbar />
      </div>
      <div class="w-5/6 flex flex-col">
        <div class="flex bg-white p-5 flex-row h-20 w-full shadow-md">
          <div class="w-1/2 md:w-1/3">
            <input
              type="text"
              placeholder="Buscar Video"
              class="
                shadow
                appearance-none
                border
                rounded
                w-full
                py-2
                px-3
                mt-2
                text-gray-700
                leading-tight
                focus:outline-none focus:shadow-outline
              "
              value=""
            />
          </div>
        </div>
        <div class="w-full overflow-y-auto overflow-x-hidden h-2/3 p-4">
          <PlaylistTile />
          <PlaylistTile />
          <PlaylistTile />
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.mt-10 {
  margin-top: 8rem !important;
}
</style>
<script>
export default {};
</script>
