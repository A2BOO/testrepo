<template>
  <body class="layout">
  
  <div class="nav"></div>
    <div class="container">
      <div class="content">
          <div class="circlecenter">
            <div class="circle"></div>
          </div>
          <div class="allblock">
            <div class="block1"></div>
            <div class="block2"></div>
              <div class="save">
                <div class="savebutton">Save</div>
              </div>
              <div class="save2">
                <div class="savebutton">Save</div>
              </div>
              
        </div>
      </div>
  </div>

  </body>
</template>

<style>
  .layout {
    @apply w-full h-screen
  }

  .nav {
    @apply bg-gray-500 w-full h-[40px] 
  }

  .container {
    @apply bg-green-200 w-[1000px] h-[1000px] m-auto
  }

  .content {
    @apply grid grid-cols-2 gap-1 
  }

  .circle {
    @apply  w-[120px] h-[120px] rounded-full border-2 border-black mt-6
  }

  .circlecenter {
    @apply flex justify-center
  }

  .block1 {
    @apply w-[450px] h-[40px] border-2 border-black 
  }

  .block2 {
    @apply w-[450px] h-[40px] border-2 border-black 
  }

  .savebutton {
    @apply w-[60px] h-[30px] bg-blue-500 rounded-full text-white text-center
  }

  .save {
    @apply flex justify-end
  }

  .save2 {
    @apply flex justify-end mt-[500px]
  }
  
  .allblock {
    @apply grid grid-cols-1 gap-3 mt-6 max-w-[450px]
  }


</style>