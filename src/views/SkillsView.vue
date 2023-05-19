<template>
    <article class="center-article">
        <div class="centerArticleWrapper">
            <div id="skillsDiv">
                <h1>Skills</h1>
                <p><strong>Advanced skills:</strong> JavaScript (ES6), HTML5, CSS3, PHP (oop an procedrual) and MySql databases</p>
                <p><strong>Begginer skills:</strong> React JS, Vue JS, Angular, Svelte JS, Node JS, TypeScript, TailwindCSS, Bootstrap, jQuery, Laravel, GIT, AJAX, JSON, XML, Word Press, Web services</p>
                <p><strong>English language:</strong> begginer</p>
            </div>
        </div>
    </article>
</template>

<script>
export default {
    name: "Skills",
    mounted(){
    let title = "CV | Skills"
    document.title = title
  }
}
</script>
