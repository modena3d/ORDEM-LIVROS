<script>
  import Menu from "./Menu.svelte";
  import MenuItem from "./MenuItem.svelte";

</script>
<aside class="flex flex-col self-start
border border-zinc-800 p-5 rounded-md gap-10 w-72">
 <Menu titulo="Navegação"> 
   <MenuItem texto = "Inicio" href="/"> </MenuItem >
   <MenuItem texto = "Personagens" href="/"> </MenuItem >
   <MenuItem texto = "Autores" href="/autores"> </MenuItem >
   <MenuItem texto = "Séries" href="/"> </MenuItem >
 </Menu>
  <Menu titulo="Principais Autores"> 
   <MenuItem texto = "J.K. Rowling" href="/"> </MenuItem >
   <MenuItem texto = "J.R.R. Tolkien" href="/"> </MenuItem >
   <MenuItem texto = "George R.R. Martin" href="/autores/george-martin"> </MenuItem >
   <MenuItem texto = "Séries" href="/"> </MenuItem >
 </Menu> 
 <Menu titulo="Outras Categorias"> 
   <MenuItem texto = "Ultimas Notícias" href="/"> </MenuItem >
   <MenuItem texto = "Séries Populares" href="/"> </MenuItem >
   <MenuItem texto = "Facebook" href="/autores"> </MenuItem >
   <MenuItem texto = "Intagram" href="/"> </MenuItem >
   <MenuItem texto = "Youtube" href="/"> </MenuItem >
 </Menu>

</aside>