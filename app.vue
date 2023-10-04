<template>
  <Head>
    <Link rel="apple-touch-icon" sizes="180x180" href="/images/favicon/apple-touch-icon.png" />
    <Link rel="icon" type="image/png" sizes="32x32" href="/images/favicon/favicon-32x32.png" />
    <Link rel="icon" type="image/png" sizes="16x16" href="/images/favicon/favicon-16x16.png" />
    <Link rel="manifest" href="/images/favicon/site.webmanifest" />
    <Link rel="mask-icon" href="/images/favicon/safari-pinned-tab.svg" color="#227541" />
    <Meta name="msapplication-TileColor" content="#000000" />
    <Meta name="theme-color" content="#000000" />
  </Head>
  <AppHeader />
  <NuxtPage />
  <AppFooter />
</template>
<script setup lang="ts">
useSeoMeta({
  title: 'Club de Baloncesto Pumas | Formación de niños y diversión en el deporte',
  ogTitle: 'Club de Baloncesto Pumas',
  description: 'Descubre el Club de Baloncesto Pumas en Madrid, donde los niños de primaria desarrollan sus habilidades en un entorno divertido y lleno de valores. ¡Únete a nuestra familia Pumas hoy mismo!',
  ogDescription: 'Descubre el Club de Baloncesto Pumas en Madrid, donde los niños de primaria desarrollan sus habilidades en un entorno divertido y lleno de valores. ¡Únete a nuestra familia Pumas hoy mismo!',
  twitterCard: 'summary_large_image',
  keywords: 'Club de Baloncesto Pumas, baloncesto infantil Madrid, formación en baloncesto, equipo de niños, diversión en el deporte',
  robots: 'index, follow',  
})
</script>
