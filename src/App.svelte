<script lang="ts">
import TimePadForm from "./lib/components/TimePadForm.svelte";
import Header from "./lib/components/Header.svelte";
import {ymPageView} from "./utilites";
import {onMount} from "svelte";
onMount(ymPageView)

</script>

<main>
    <Header />
    <TimePadForm />
</main>

<style>

</style>
