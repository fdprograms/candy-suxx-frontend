<template>
  <div class="h-screen">
    <div class="min-h-screen flex flex-row bg-gray-100">
        <Navbar/>
        <div>
          <div class="flex bg-white p-5 flex-row h-20 w-screen shadow-md">
              <div class="w-1/3">
                  <input type="text" placeholder='Buscar Video' class="shadow appearance-none border rounded w-full py-2 px-3 mt-2 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" value="">
              </div>
          </div>
        </div> 
        <div>
          Videos
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
export default {}
</script>
