<template>
  <div class="hello">
    <section id="jumbotron">
      <h2>{{ msg }}</h2>
      <p>{{ loremIpsum }}</p>
    </section>
  </div>
</template>

<script>
export default {
  name: "HeroJumbo",
  data() {
    return {
      msg: "Benvenuto nel nostro sito!",
      loremIpsum:
        "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur incidunt unde ratione eius esse, exercitationem suscipit? Dolorum commodi modi beatae exercitationem? Veritatis repellat repudiandae commodi nisi ipsa ipsam quam recusandae.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur incidunt unde ratione eius esse, exercitationem suscipit? Dolorum commodi modi beatae exercitationem? Veritatis repellat repudiandae commodi nisi ipsa ipsam quam recusandae.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur incidunt unde ratione eius esse, exercitationem suscipit? Dolorum commodi modi beatae exercitationem? Veritatis repellat repudiandae commodi nisi ipsa ipsam quam recusandae.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur incidunt unde ratione eius esse, exercitationem suscipit? Dolorum commodi modi beatae exercitationem? Veritatis repellat repudiandae commodi nisi ipsa ipsam quam recusandae.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur incidunt unde ratione eius esse, exercitationem suscipit? Dolorum commodi modi beatae exercitationem? Veritatis repellat repudiandae commodi nisi ipsa ipsam quam recusandae.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur incidunt unde ratione eius esse, exercitationem suscipit? Dolorum commodi modi beatae exercitationem? Veritatis repellat repudiandae commodi nisi ipsa ipsam quam recusandae.",
    };
  },
};
</script>

<style scoped>
h2 {
  text-align: center;
  color: orange;
  padding: 2rem;
}
#jumbotron {
  height: 80vh;
  background-image: url(https://media.istockphoto.com/photos/75mpix-panorama-of-beautiful-mount-ama-dablam-in-himalayas-nepal-picture-id1341288649?b=1&k=20&m=1341288649&s=170667a&w=0&h=tGS0ne3HTBPt-6CltooB9ChBtNHHvfFEbby-OP--MeY=);
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
