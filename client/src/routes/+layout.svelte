<script>
    import "../app.css";
    import Header from '$lib/components/Common/Header.svelte';
    import Footer from "$lib/components/Common/Footer.svelte";
    import ContactUs from "$lib/components/Common/ContactUs.svelte";
</script>

<div class="p-5 bg-gray-900">
  <Header />
  <slot />
  <ContactUs/>
  <Footer />
</div>