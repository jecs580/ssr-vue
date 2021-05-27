<template>
    <div>
        <h1>Post</h1>
        <ul>
            <li v-for="(post,i) of posts" :key="i">{{post.title}}</li>
        </ul>
    </div>
</template> 
<script>
import axios from 'axios'
export default {
    data(){
        return {
            posts:[]
        }
    },
    async created(){
        try {
            const res= await axios.get('https://jsonplaceholder.typicode.com/posts');
            this.posts = res.data;
        } catch (error) {
            console.log(error);
        }
    }
}
</script>