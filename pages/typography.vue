<template>
<div>
  <h1>Typography</h1>
  <h2>Typeface</h2>
  <p>Youi use Open Sans as default font for all text, and includes two font-weight: Regular and Bold. 
  You can download fonts at <a href="https://fonts.google.com/specimen/Open+Sans">https://fonts.google.com/specimen/Open+Sans</a></p>
  
  <typography-header />
  <typography-label />
  <typography-paragraphs />


</div>
</template>

<script>
import TypographyHeader from '~/components/TypographyHeader.vue'
import TypographyLabel from '~/components/TypographyLabel.vue'
import TypographyParagraphs from '~/components/TypographyParagraphs.vue'
export default {
  name: 'typography',
  components: {
    TypographyHeader,
    TypographyLabel,
    TypographyParagraphs
  }
}
</script>
