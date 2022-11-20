<template>

    <header>
        <nav>
            <NuxtLink to="/products"> NuxtCourse </NuxtLink>
        </nav>
    </header>

   <!-- usaremos el componente slot para mostrar el contenido de la pagina en la que llamemos este componente(default) -->
   <div>
       <slot />
   </div>

   <footer>
    <ul>
        <li><NuxtLink to="/"> Home </NuxtLink></li>
        <li><NuxtLink to="/about"> About </NuxtLink></li>
        <li><NuxtLink to="/products"> products </NuxtLink></li>
    </ul>
   </footer>
</template>

<style scoped>
.router-link-exact-active{
    color: #12b488;
}
</style>