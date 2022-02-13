<script>
	import Header from "./components/Header.svelte";
	import About from "./components/About.svelte";
	import Companies from "./components/Companies.svelte";
	import Seperator from "./components/Seperator.svelte";
	import Specialisation from "./components/Specialization.svelte";
	import Works from "./components/Works.svelte";
	import Newsletter from "./components/Newsletter.svelte";
	import Contact from "./components/Contact.svelte";
	import Footer from "./components/Footer.svelte";
</script>

<Header />
<About />
<Companies />
<Seperator text={"What I do best"} />
<Specialisation />
<Seperator text={"Projects that are clients love"} />
<Works />
<Seperator text={"My weekly newsletter and blogs"} />
<Newsletter />
<Contact />
<Footer/>
