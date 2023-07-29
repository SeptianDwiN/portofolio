<template>
  <br>
  <h5
      class="mb-2 text-xl font-medium text-neutral-800 dark:text-neutral-50 selamatdatang">
     <u id="about">About Me :</u>
    </h5>
    <div
  class=" m-8 flex flex-col rounded-lg bg-white shadow-[0_2px_15px_-3px_rgba(0,0,0,0.07),0_10px_20px_-2px_rgba(0,0,0,0.04)] dark:bg-neutral-700 md:max-w-xl md:flex-row">
  <img
    class="h-96 w-full rounded-t-lg object-cover md:h-auto md:w-48 md:rounded-none md:rounded-l-lg"
    src="https://tecdn.b-cdn.net/img/new/avatars/2.jpg"
    alt="" />
    
  <div class="flex flex-col justify-between p-4 leading-normal ml-10">
    <p class="mb-4 text-base text-neutral-600 dark:text-neutral-200">
      <p class="text-xs text-neutral-600 dark:text-neutral-300">
     Saya Adalah Saya Dan Saya 
    </p>
      <p>
    <p class="font-semibold ">Nama : Septian Dwi Nugraha</p>
    <p class="font-semibold ">Tanggal Lahir : 11 July 2005</p>
    <p class="font-semibold ">Alamat : Kp.Sindang Palay</p>
    <p class="font-semibold ">No.Telp : 0895413764419</p>
    
    </p>
    </p>
    
  </div>
</div>
<hr>
<!--HOBI-->
<br>
<h1 class="mb-2 text-xl font-medium text-neutral-800 dark:text-neutral-50 selamatdatang">
  <u>My Hobi :</u>
</h1>
<div class=" grid grid-cols-2">
<div
  class=" m-8 flex flex-col-2  rounded-lg bg-white shadow-[0_2px_15px_-3px_rgba(0,0,0,0.07),0_10px_20px_-2px_rgba(0,0,0,0.04)] dark:bg-neutral-700 md:max-w-xl md:flex-row">
  <img
    class="h-96 w-full rounded-t-lg object-cover md:h-auto md:w-48 md:rounded-none md:rounded-l-lg"
    src="data:image/jpeg;base64,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"
    alt="" />
  <div class="flex flex-col justify-between p-4 leading-normal ml-10">
    <h5
      class="mb-2 text-xl font-medium text-neutral-800 dark:text-neutral-50 selamatdatang">
     <u>Volly</u>
    </h5>
    <p class="mb-4 text-base text-neutral-600 dark:text-neutral-200">
      <p class="text-xs text-neutral-600 dark:text-neutral-300">
     Saya Suka Bermain Voli Karna Saat Saya Kecil Sering Bermain Bola Voli,Dan Saya Pernah Mengikuti klbu Voli
    </p>
    </p>
    
  </div>
</div>
<div
  class=" m-8 flex flex-col-2  rounded-lg bg-white shadow-[0_2px_15px_-3px_rgba(0,0,0,0.07),0_10px_20px_-2px_rgba(0,0,0,0.04)] dark:bg-neutral-700 md:max-w-xl md:flex-row">
  <img
    class="h-96 w-full rounded-t-lg object-cover md:h-auto md:w-48 md:rounded-none md:rounded-l-lg"
    src="data:image/jpeg;base64,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"
    alt="" />
  <div class="flex flex-col justify-between p-4 leading-normal ml-10">
    <h5
      class="mb-2 text-xl font-medium text-neutral-800 dark:text-neutral-50 selamatdatang">
     <u>Bermain Game Online</u>
    </h5>
    <p class="mb-4 text-base text-neutral-600 dark:text-neutral-200">
      <p class="text-xs text-neutral-600 dark:text-neutral-300">
     Saya Sangat Menyukai Game,Dari Kecil Saya Sangat Menyukai Game Terutama Game Online
    </p>
    </p>
  </div>
</div>
</div>
<hr>

<!--MY SKILL-->
<br>

<h1 class="mb-2 text-xl font-medium text-neutral-800 dark:text-neutral-50 selamatdatang">
  <u>My Skill :</u>
</h1>
<div class=" grid grid-cols-3">
  
<div
  class=" m-8 flex flex-col-2  rounded-lg bg-white shadow-[0_2px_15px_-3px_rgba(0,0,0,0.07),0_10px_20px_-2px_rgba(0,0,0,0.04)] dark:bg-neutral-700 md:max-w-xl md:flex-row">
  <img
    class="h-96 w-full rounded-t-lg object-cover md:h-auto md:w-40 md:rounded-none md:rounded-l-lg"
    src="https://www.interviewbit.com/blog/wp-content/uploads/2021/09/backend.jpg"
    alt="" />
  <div class="flex flex-col justify-between p-4 leading-normal ml-10">
    <h5
      class="mb-2 text-xl font-medium text-neutral-800 dark:text-neutral-50 selamatdatang">
     <u>Backend</u>
    </h5>
    <p class="mb-4 text-base text-neutral-600 dark:text-neutral-200">
      <p class="text-xs text-neutral-600 dark:text-neutral-300">
        Back end merupakan bagian dari situs web yang tidak dilihat oleh pelanggan. Back end berurusan dengan data-data di balik layar, ia bertanggung jawab dalam menyimpan dan mengatur data, serta memastikan hal yang ada pada sisi klien berfungsi dan tidak bermasalah
    </p>
    </p>
    
  </div>
</div>
<div
  class=" m-8 flex flex-col-2  rounded-lg bg-white shadow-[0_2px_15px_-3px_rgba(0,0,0,0.07),0_10px_20px_-2px_rgba(0,0,0,0.04)] dark:bg-neutral-700 md:max-w-xl md:flex-row">
  <img
    class="h-96 w-full rounded-t-lg object-cover md:h-auto md:w-40 md:rounded-none md:rounded-l-lg"
    src="https://www.interviewbit.com/blog/wp-content/uploads/2021/09/frontend.jpg"
    alt="" />
  <div class="flex flex-col justify-between p-4 leading-normal ml-10">
    <h5
      class="mb-2 text-xl font-medium text-neutral-800 dark:text-neutral-50 selamatdatang">
     <u>Frontend</u>
    </h5>
    <p class="mb-4 text-base text-neutral-600 dark:text-neutral-200">
      <p class="text-xs text-neutral-600 dark:text-neutral-300">
        Front end merupakan salah satu bagian dari website yang menampilkan tampilan untuk para pengguna. Pada bagian ini dibuat dengan menggunakan 3 bahasa pemrograman web yaitu HyperText Markup Language (HTTP), Cascading Style Sheets (CSS), dan JavaScript.
    </p>
    </p>
  </div>
</div>

<div
  class=" m-8 flex flex-col-2  rounded-lg bg-white shadow-[0_2px_15px_-3px_rgba(0,0,0,0.07),0_10px_20px_-2px_rgba(0,0,0,0.04)] dark:bg-neutral-700 md:max-w-xl md:flex-row">
  <img
    class="h-96 w-full rounded-t-lg object-cover md:h-auto md:w-40 md:rounded-none md:rounded-l-lg"
    src="https://global-uploads.webflow.com/6100d0111a4ed76bc1b9fd54/64664e9cd07202af8bcdc5e4_5757453.jpg" 
    alt="" />
  <div class="flex flex-col justify-between p-4 leading-normal ml-10">
    <h5
      class="mb-2 text-xl font-medium text-neutral-800 dark:text-neutral-50 selamatdatang">
     <u>UI & UX</u>
    </h5>
    <p class="mb-4 text-base text-neutral-600 dark:text-neutral-200">
      <p class="text-xs text-neutral-600 dark:text-neutral-300">
        Seperti yang telah dijelaskan sebelumnya bahwa UI memiliki kepanjangan User Interface sedangkan UX singkatan dari User Experience. Kedua elemen ini memiliki peran penting dalam sebuah produk karena mengacu kepada setiap aspek penggunanya
    </p>
    </p>
  </div>
</div>
</div>
</template>

  
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap');
.selamatdatang {
  font-family: "Monstserrat", sans-serif;
  font-size: 20px;
  font-weight: bold;
}
</style>

  