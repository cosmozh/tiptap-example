<template>
  <div id="app">
    <EditorTiptapVue
			:description="'This is Editor'"
			:menubar="true"
			:readOnly="false"
		/>
  </div>
</template>

<style scoped>
	
</style>

<script>
import EditorTiptapVue from './components/EditorTiptap.vue'

export default {
	components: {
		EditorTiptapVue,
	}
}
</script>