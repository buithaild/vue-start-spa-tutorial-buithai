<template>
  <p>Simple text</p>
</template>

<script>
export default {
  data() {
    return {
      activePage: 0,

      pages: [
        {
          link: { text: "Home", url: "home.html" },
          pageTitle: "Home Page",
          content: "This is the home content",
        },
        {
          link: { text: "About", url: "about.html" },
          pageTitle: "About",
          content: "This is the about content",
        },
        {
          link: { text: "Contact", url: "contact.html" },
          pageTitle: "Contact",
          content: "This is the contact content",
        },
      ],
    };
  },
};
</script>
