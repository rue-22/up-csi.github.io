<script>
    import LinkButton from '$lib/components/buttons/LinkButton.svelte';
    import src from '$lib/assets/lino/lino-sablay.svg';
    import upcsi from '$lib/assets/icons/upcsi.svg';
</script>

<section
    class="bg-csi-white text-csi-black dark:bg-csi-black dark:text-csi-white flex flex-col items-center gap-5 p-3 transition-colors ease-in-out md:flex-row md:items-start"
>
    <!--PLACEHOLDER IMAGES-->
    <div class="w-full md:w-7/12">
        <img {src} alt="UP CSI Logo Placeholder" class="bg-warm-white rounded-3xl md:h-[500px]" />
    </div>
    <div class="font-dm flex flex-col gap-5 md:w-5/12">
        <div class="flex flex-col items-center md:items-start md:pb-6">
            <img
                src={upcsi}
                alt="Circle placeholder"
                class="dark:bg-csi-white h-20 w-20 rounded-full bg-black p-2"
            />
        </div>
        <h1 class="text-sm">Meet UP Center for Student Innovations</h1>
        <p class="text-3xl">
            To create a center where students can innovate with the latest technology.
        </p>
        <div class="text-csi-white dark:text-csi-black text-center md:text-left">
            <LinkButton href="#mission-vision">Mission and Vision</LinkButton>
            <LinkButton href="/people">See Team</LinkButton>
        </div>
    </div>
</section>
