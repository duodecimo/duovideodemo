<template>
  <div class="about">
    <h1>
      Nada melhor para falar sobre o componente video no vue do que reproduzir
      um video.
    </h1>
    <video controls="true" :poster="require('@/assets/duoVideo.png')">
      <source src="@/assets/video.webm" type="video/webm" />
    </video>
  </div>
</template>
