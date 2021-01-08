# Prismo16.github.io
body {
    font-size: 18px;
    color: #6c767d;
    background-color: #ebf1f5;
    background-image: url(https://i.loli.net/2020/09/14/v4Si8BIupOVcwm6.jpg);
    background-attachment: fixed;
    background-repeat: no-repeat;
    background-size: cover;
    height: 100vh;
    min-height: 800px;
}


/*定义滚动条高宽及背景 高宽分别对应横竖滚动条的尺寸*/

::-webkit-scrollbar {
    width: 5px;
    /* height: 5px; */
    background-color: #F5F5F5;
}


/*定义滚动条轨道 内阴影+圆角*/

::-webkit-scrollbar-track {
    -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3);
    border-radius: 10px;
    background-color: #F5F5F5;
}


/*定义滑块 内阴影+圆角*/

::-webkit-scrollbar-thumb {
    border-radius: 10px;
    -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, .3);
    background-color: #555;
}

h1 {
    font-size: 36px;
    margin-bottom: .5em;
}

h2 {
    font-size: 24px;
}

h3 {
    font-size: 20px;
    margin-top: 1em;
}

h4 {
    font-size: 16px;
}

h1,
h2,
h3,
h4 {
    color: black;
}

.card {
    border: none;
    padding: 80px 80px 0px;
    border-radius: 0;
}

.container {
    position: relative;
    top: 50%;
    transform: translateY(-50%);
}

.my-card {
    /* box-shadow: 0px 5px 15px 5px rgb(203, 221, 232); */
}

strike {
    color: red;
}

.btn {
    border-radius: 0;
    margin: 5px 0;
    width: 100%;
    padding: 12px 40px;
    transition: ease;
}

.btn-primary {
    /* box-shadow: 0px 5px 15px 5px rgb(203, 221, 232); */
    padding: 12px 40px;
    transition: ease;
}

.btn-primary:hover {
    box-shadow: 5px -2px 15px 0px rgb(203, 221, 232);
}

.btn-secondary {
    /* box-shadow: 0px 5px 15px 5px rgb(203, 221, 232); */
    padding: 12px 40px;
    transition: ease;
}

.btn-secondary:hover {
    box-shadow: 5px -2px 15px 0px rgb(203, 221, 232);
}

.btn-success {
    /* box-shadow: 0px 5px 15px 5px rgb(203, 221, 232); */
    padding: 12px 40px;
    transition: ease;
}

.btn-success:hover {
    box-shadow: 5px -2px 15px 0px rgb(203, 221, 232);
}

.social {
    padding-left: 0;
}

.social p {
    margin-bottom: 0;
}

.social li {
    list-style: none;
    float: left;
    margin-right: 15px;
}

.card-text {
    margin-bottom: 20px;
}

.social .fa {
    font-size: 24px;
}

.photo-bg {
    /* background-image: url(assets/background.jpg); */
    background-image: url(https://tva1.sinaimg.cn/large/0072Vf1pgy1foxk456b0fj31hc0u0dxu.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

footer p {
    font-size: 12px;
}

#kaygb-blog-a,
#kaygb-mail-a {
    display: none;
}

@media (max-width: 1199px) {
    body {
        min-height: 600px;
    }
    h1 {
        font-size: 24px;
    }
    h2,
    .social .fa {
        font-size: 20px;
    }
    h3 {
        font-size: 16px;
    }
    h4,
    p {
        font-size: 14px;
    }
    .card {
        padding: 50px 50px 0px;
    }
}

@media (max-width: 1199px) {
    .photo-bg {
        min-height: calc(100vh - 500px);
    }
}

@media(max-width:991px) {
    .photo-bg {
        background-position: top;
        min-height: calc(90vh - 440px);
    }
}

@media(max-width: 767px) {
    .container {
        position: relative;
        top: 0;
        transform: translateY(0);
    }
    .photo-bg {
        height: 180px;
    }
    .card {
        padding: 20px;
    }
    #kaygb-blog-a,
    #kaygb-mail-a {
        display: block;
    }
    #kaygb-blog,
    #kaygb-mail {
        display: none;
    }
}

#frame {
    width: 50%;
    height: 50vh;
    margin: 0;
    background: #fff;
    position: fixed;
    z-index: 999;
    top: 5%;
    left: 5%;
}

#aplayer {
    z-index: 20000000;
}
