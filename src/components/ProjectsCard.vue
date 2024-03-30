<template>
    <div class="main-container">
        <div>
            <div class="project-card" v-for="(items, index) in projectData.ProjectsArray" :key="index">
                <h2>{{ projectData.ProjectsArray[index].Title }}</h2>
                <img :src="projectData.ProjectsArray[index].Image" alt="">
                <p>{{ projectData.ProjectsArray[index].About }}</p>
                <div class="links">
                    <a :href="projectData.ProjectsArray[index].Link1" target="_blank"><img src="../assets/github.jpg" alt=""></a>
                    <a :href="projectData.ProjectsArray[index].Link2" target="_blank"><img src="../assets/facebook.jpg" alt=""></a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import jsonData from "/projects.json";

export default {
    data() {
        return {
            projectData: jsonData
        };
    }
};
</script>

<style scoped>
.project-card h2,
.project-card p {
    margin: 0;
    color: #ffffff; /* font color */
}
@font-face {
    font-family: 'Product Sans';
    src: url('../fonts/ProductSans-Regular.ttf') format('truetype'),

}
.main-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}

.project-card {
    margin: 10px;
    padding: 10px;
    flex-wrap: wrap;
    background-color: rgb(23, 42, 70);
    border-radius: 20px; /* Adjust border-radius for chicklet shape */
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
    width: calc(97.5% - 1px); /* Stretch to the very side */
}

.project-card h2,
.project-card p {
    margin: 0;
}

.project-card img {
    height: 15rem;
    margin: 8%;
}

.links {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
}

.links img {
    height: 5rem;
    margin: 5px;
    border-radius: 20px; /* Adjust border-radius for chicklet shape */
}
</style>
