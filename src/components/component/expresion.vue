<script>
import ContactForm from "./ContactForm.vue";

export default {
  components: { ContactForm, ContactForm },
  props: ["inputText"],
};
</script>
<template>
  <!-- expresion wrapper -->
  <div
    class="container flex flex-col lg:flex-row items-start bg-gradient-to-r from-slate-50 to-slate-200 justify-center p-[4.063rem] gap-[1.875rem] bg-white shadow-expresion rounded-[1.25rem]"
  >
    <div class="flex flex-col items-center justify-center">
      <div class="pb-8">
        <figure class="w-auto h-auto">
          <img
            src="../../../public/expresion.png"
            alt="Expression"
            class="rounded-2xl"
          />
        </figure>
      </div>
      <div class="w-full max-w-xs">
        <ContactForm></ContactForm>
      </div>
    </div>
  </div>
  <!-- end expresion -->
</template>
