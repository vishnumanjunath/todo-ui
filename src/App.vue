<template>
  <div id="app">
    <home></home>
  </div>
</template>

<script>
import Home from "@/components/home/index.vue";

export default {
  name: "App",
  components: {
    Home,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Rubik&display=swap");
#app {
  font-family: "Rubik", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#container {
  width: 375px;
  margin: 0 auto;
  border: 1px solid #eeeeee;
  border-radius: 2px;
  background: #FAFAFF;
  display: flex;
  flex-direction: column;
}
.top-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  font-size: 15px;
  padding: 15px 15px 0px 15px;
}
.left-top-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.left-top-bar-time {
  font-weight: 500;
}
.left-top-bar-iocn {
  padding-left: 2px;
}

.right-top-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.right-top-bar-iocn {
  padding-left: 2px;
}
.header {
  display: flex;
  justify-content: space-between;
  margin-top: 25px;
  align-items: center;
  padding: 15px 15px 0px 15px;
}
.heading {
  font-weight: 700;
  font-size: 24px;
}
.current-task {
  margin: 15px;
  display: flex;
  flex-direction: column;
  background-color: #0a0a0a;
  color: #f0f0f0;
  padding: 20px;
  border-radius: 10px;
}
.current-task-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 12px;
}
.current-task-description {
  padding-top: 10px;
  display: flex;
  align-items: center;
}
.current-task h1 {
  margin: 0;
}
.task-description {
  padding-left: 10px;
}
.upcoming-task {
  margin: 15px;
  padding-top: 30px;
  padding-bottom: 20px;
  display: flex;
  flex-direction: column;
}
.upcoming-task-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-bottom: 20px;
}

.upcoming-task-header h1 {
  font-size: 20px;
  margin: 0;
}
.task-list {
  display: flex;
  flex-direction: column;
}

.task-card {
  display: flex;
  justify-content: space-between;
  background-color: #ffffff;
  border-radius: 12px;
  padding: 20px;
  margin-bottom: 20px;
  cursor: pointer;
}
.card-icon {
  flex: 1.25;
  background-color: #9B51E0;
  border-radius: 50%;
  width: 44px;
  height: 44px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.card-body {
  flex: 6;
  margin-left: 15px;
  text-align: left;
}

.card-body-header {
  font-weight: 800;
  font-size: 14px;
}

.card-action {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  justify-content: space-between;
}
.task-tags {
  padding-top: 10px;
  display: flex;
  font-size: 14px;
}
.task-tag {
  margin-right: 4px;
  padding: 4px 8px;
  background-color: #FFEFF1;
  border-radius: 6px;
  color: #FD5B71;
}
.card-action-time {
  color: #4F4F4F;
  font-size: 12px;
}
.actions {
  background-color: #FFFFFF;
  display: flex;
  justify-content: space-around;
  padding: 20px;
  border-top-right-radius: 30px;
  border-top-left-radius: 30px;
  padding-bottom: 40px;
  -webkit-box-shadow: 0px -1px 5px 0px rgba(0, 0, 0, 0.21);
  -moz-box-shadow: 0px -1px 5px 0px rgba(0, 0, 0, 0.21);
  box-shadow: 0px -1px 5px 0px rgba(0, 0, 0, 0.21);
}
</style>
