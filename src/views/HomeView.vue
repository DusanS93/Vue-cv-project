<template>
   <article class="center-article">
           <div id="infos">
            <div id="infoDiv">
               <div id="helloWrapDiv">
                <div id="helloDiv">Hello I'm</div>
               </div>
                <div id="infoWrapp"> 
                    <h1>Dusan Stojanovic</h1>
                    <h4>My job is Web Developer</h4>
                </div>
             </div>
           </div>

           <div id="wallpaper">
              <div id="imageDiv"></div>
           </div>
   </article>
</template>

<script>
export default {
  name: 'HomeView',
  mounted(){
    let title = "CV | Home"
    document.title = title
  }
}
</script>
