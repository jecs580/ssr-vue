<template>
  <div>
    <h1>About Us</h1>
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Obcaecati
      voluptate provident asperiores architecto repudiandae dignissimos
      voluptatibus animi quos harum. Impedit rem reiciendis, quaerat amet
      perferendis sit voluptate ullam possimus eaque.
    </p>
  </div>
</template>
<script>
export default {
  head() {
    return {
      title: "Post | Home",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Website about posts",
        },
      ],
      htmlAttrs: {
        lang: "es",
      },
    };
  },
};
</script>