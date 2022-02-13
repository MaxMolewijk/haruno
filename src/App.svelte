<script>
	import Header from "./navigation/Header.svelte";
	import About from "./sections/About.svelte";
	import Companies from "./sections/Companies.svelte";
	import Seperator from "./components/Seperator.svelte";
	import Specialisation from "./sections/Specialization.svelte";
	import Works from "./sections/Works.svelte";
	import Newsletter from "./sections/Newsletter.svelte";
	import Contact from "./sections/Contact.svelte";
	import Footer from "./navigation/Footer.svelte";
</script>

<Header />
<About/>
<Companies />
<Seperator text={"What I do best"} />
<Specialisation/>
<Seperator text={"Projects that are clients love"} />
<Works/>
<Seperator text={"My weekly newsletter and blogs"} />
<Newsletter/>
<Contact />
<Footer/>
