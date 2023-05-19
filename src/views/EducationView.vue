<template>
    <article class="center-article">
            <div class="centerArticleWrapper">
                <div id="educationDiv">
                    <h1>Education</h1>
                    <p><strong>IT Academy - </strong>Advanced JavaScript <i>(May 2022 - June 2022)</i></p>
                    <p><strong>IT Academy - </strong>PHP Web developing <i>(Nov 2020 - Aug 2021)</i></p>
                    <p><strong>Zubotehnicka skola - </strong>Dental technician <i>(Sep 2008 - June 2012)</i></p>
                </div>
            </div>
    </article>
</template>

<script>
export default {
    name: "Education",
    mounted(){
    let title = "CV | Education"
    document.title = title
  }
}
</script>