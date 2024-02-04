<template>
    <div class="projects">
      <h1>Project</h1>
      <div class="project-list">
        <div class="project">
                <img src="https://via.placeholder.com/300x200">
                <h2>作品の名前</h2>
                <p>作品1の説明文や特徴などをここに記述します。</p>
                <a href="#">詳細を見る</a>
            </div>
            <div class="project">
                <img src="https://via.placeholder.com/300x200">
                <h2>作品の名前</h2>
                <p>作品2の説明文や特徴などをここに記述します。</p>
                <a href="#">詳細を見る</a>
            </div>
            <div class="project">
                <img src="https://via.placeholder.com/300x200">
                <h2>作品の名前</h2>
                <p>作品3の説明文や特徴などをここに記述します。</p>
             <a href="#">詳細を見る</a>
            </div>
            <div class="project">
                <img src="https://via.placeholder.com/300x200">
                <h2>作品の名前</h2>
                <p>作品4の説明文や特徴などをここに記述します。</p>
             <a href="#">詳細を見る</a>
            </div>
            <div class="project">
                <img src="https://via.placeholder.com/300x200">
                <h2>作品の名前</h2>
                <p>作品5の説明文や特徴などをここに記述します。</p>
             <a href="#">詳細を見る</a>
            </div>
            <div class="project">
                <img src="https://via.placeholder.com/300x200">
                <h2>作品の名前</h2>
                <p>作品6の説明文や特徴などをここに記述します。</p>
             <a href="#">詳細を見る</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Project',
}
</script>

<style scoped>
.projects-link a {
  text-decoration: none;
  color: black;
  line-height: 20px;
  background-color: #b8e8de;
  padding: 10px 5px 10px 5px;
  border-radius: 10px;
}

.project-list {
  display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 30px;
    padding: 10px;
}

.project {
    box-sizing: border-box;
    width: 330px;
    margin: 20px;
    padding: 15px;
    border: 1px solid #ddd; 
    border-radius: 8px;
}
</style>