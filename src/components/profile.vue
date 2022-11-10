<template>
    <div>
        <profilecard></profilecard>
    </div>
    <body class="bg-fuchsia-100">
        <div class="shadow-md rounded box-content w-1/4 border-4 transtion duration 300 hovert:bg-blue-200">
            <span class="box-decoration-slice bg-indigo-200 m-1 p-1 rounded-md text-grey-500 text-2xl font-bold">
                B.hannujayaP.hattananN.ichakan
            </span>
            <p class="text-xl text-black bg-pink-300 font-semibold m-2 p-2 rounded-md text-center">"Hello Profile"</p>
            <img src="../assets/images/pleang.jpg" alt="" width="200" hight="200" class="rounded-full w-40">
            <div class="text-sky-700 font-medium">{{name}}</div>
            <div class="text-sky-700 font-medium">{{nickname}}</div>
            <div class="text-sky-700 font-medium">{{birthday}}</div>
            <div class="text-sky-700 font-medium">{{content}}</div>
        </div>
    </body>
</template>
<script>
    export default {
        props: {
        name: {
            type: String,
            default: "an",
        },
        nickname: {
            type: String,
            default: "w",            
        },
        birthday: {
            type: String,
            default: "5",            
        },
        content: {
            type: String,
            default: "Ku82", 
        image: {

        }           
        },
    },
}; 
</script>