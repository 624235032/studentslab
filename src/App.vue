<template>
  <div id="app">
    <Students v-bind:students1="students" />
  </div>
</template>


<script>
import Students from "./components/Students.vue";

export default {
  name: "App",
  components: {
    Students,
  },
  data() {
    return {
      students: [
        {
          studentId: "624235032",
          FistName: "Nattawut",
          LastName: "Bunwisoot",
          weight: 70,
          height: 175,
          picture:
            "https://raw.githubusercontent.com/624235032/image01/main/01.jpg",
        },
        {
          studentId: "624235049",
          FistName: "Suban",
          LastName: "Noksang",
          weight: 65,
          height: 171,
          picture:
            "https://raw.githubusercontent.com/624235032/image01/main/02.jpg",
        },
        {
          studentId: "624235027",
          FistName: "Patiphan",
          LastName: "Siriwitno",
          weight: 80,
          height: 170,
          picture:
            "https://raw.githubusercontent.com/624235032/image01/main/03.jpg",
        },
        {
          studentId: "624235028",
          FistName: "Pathomporn",
          LastName: "Wannaphhueak",
          weight: 64,
          height: 175,
          picture:
            "https://raw.githubusercontent.com/624235032/image01/main/04.jpg",
        },
        {
          studentId: "624235039",
          FistName: "Kitipat",
          LastName: "Ponnain",
          weight: 63,
          height: 170,
          picture:
            "https://raw.githubusercontent.com/624235032/image01/main/05.jpg",
        },
      ],
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #0b0f38;
  margin-top: 60px;
}
</style>
