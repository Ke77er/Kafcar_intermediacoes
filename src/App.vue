<template>
	<div class="bg">
	<!-- <SectionPreloader /> -->
	<SectionHeader />
	<div class="wrapper">
		<SectionStartSlider />
		<SectionAbout />
		<SectionChoose />
		<SectionCTA />
	</div>
	<SectionFooter />
	</div>
</template>



<script>

import SectionPreloader from './components/section_preloader.vue';
import SectionHeader from './components/section_header.vue';
import SectionStartSlider from './components/section_startslider.vue';
import SectionAbout from './components/section_about.vue';
import SectionChoose from './components/section_choose.vue';
import SectionCTA from './components/section_cta.vue';
import SectionFooter from './components/section_footer.vue';
export default {
	name: 'app',
	components: {
		SectionPreloader,
		SectionHeader,
		SectionStartSlider,
		SectionAbout,
		SectionChoose,
		SectionCTA,
		SectionFooter,

	},

	data() {
		return {


		};
	},

	methods: {
	

	},

	mounted() {
}
}
</script>