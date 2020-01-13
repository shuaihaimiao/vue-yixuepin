<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>-->
    <div class="header">
      <header>
        <div class="weaper">
          <div class="log"></div>
          <img class="logimg" src="./assets/logo2.png" alt />
          <nav class="navigation">
            <ul>
              <li>
                <router-link to="/javascript">javascript</router-link>
              </li>
              <li>
                <router-link to="/html">html+css</router-link>
              </li>
              <li>
                <router-link to>vue</router-link>
              </li>
              <li>
                <router-link to>React</router-link>
              </li>
              <li>
                <router-link to>微信小程序</router-link>
              </li>
            </ul>
          </nav>
        </div>
      </header>
    </div>
    <main></main>
    <div class="main">
      <div class="content">
          <router-view/>
        <div class="article">
          <div class="article_title">
            <span class="article-sort-title">javascrpit</span>
            <span style=" margin-left: 30px;">带你解决所有 javascrpit 面试题</span>
            <div class="sanjiao"></div>
          </div>
          <div class="article_information">
            <div class="acticle_publish-time">时间：2020.01.07 作者：高海淼 阅读量：10万+</div>
            <div
              class="article_body"
            >最近因为工作的需要，正在学习Extjs，刚开始接触感觉很懵，可看了不少教程，开启了一个项目实例后，开始有了更加深入的了解，这里总结一下使用Extjs开发项目所需要的环境配置，以及如何开启一个本地的Extjs项目</div>
          </div>
        </div>
        <div class="article">
          <div class="article_title">
            <span class="article-sort-title">javascrpit</span>
            <span style=" margin-left: 30px;">带你解决所有 javascrpit 面试题</span>
            <div class="sanjiao"></div>
          </div>
          <div class="article_information">
            <div class="acticle_publish-time">时间：2020.01.07 作者：高海淼 阅读量：10万+</div>
            <div
              class="article_body"
            >最近因为工作的需要，正在学习Extjs，刚开始接触感觉很懵，可看了不少教程，开启了一个项目实例后，开始有了更加深入的了解，这里总结一下使用Extjs开发项目所需要的环境配置，以及如何开启一个本地的Extjs项目</div>
          </div>
        </div>
        <div class="article">
          <div class="article_title">
            <span class="article-sort-title">javascrpit</span>
            <span style=" margin-left: 30px;">带你解决所有 javascrpit 面试题</span>
            <div class="sanjiao"></div>
          </div>
          <div class="article_information">
            <div class="acticle_publish-time">时间：2020.01.07 作者：高海淼 阅读量：10万+</div>
            <div
              class="article_body"
            >最近因为工作的需要，正在学习Extjs，刚开始接触感觉很懵，可看了不少教程，开启了一个项目实例后，开始有了更加深入的了解，这里总结一下使用Extjs开发项目所需要的环境配置，以及如何开启一个本地的Extjs项目</div>
          </div>
        </div>
        <div class="article">
          <div class="article_title">
            <span class="article-sort-title">javascrpit</span>
            <span style=" margin-left: 30px;">带你解决所有 javascrpit 面试题</span>
            <div class="sanjiao"></div>
          </div>
          <div class="article_information">
            <div class="acticle_publish-time">时间：2020.01.07 作者：高海淼 阅读量：10万+</div>
            <div
              class="article_body"
            >最近因为工作的需要，正在学习Extjs，刚开始接触感觉很懵，可看了不少教程，开启了一个项目实例后，开始有了更加深入的了解，这里总结一下使用Extjs开发项目所需要的环境配置，以及如何开启一个本地的Extjs项目</div>
          </div>
        </div>
        <div class="article">
          <div class="article_title">
            <span class="article-sort-title">javascrpit</span>
            <span style=" margin-left: 30px;">带你解决所有 javascrpit 面试题</span>
            <div class="sanjiao"></div>
          </div>
          <div class="article_information">
            <div class="acticle_publish-time">时间：2020.01.07 作者：高海淼 阅读量：10万+</div>
            <div
              class="article_body"
            >最近因为工作的需要，正在学习Extjs，刚开始接触感觉很懵，可看了不少教程，开启了一个项目实例后，开始有了更加深入的了解，这里总结一下使用Extjs开发项目所需要的环境配置，以及如何开启一个本地的Extjs项目</div>
          </div>
        </div>
      </div>
      <div class="right">
        <div class="blog-introduce">
          <h2 class="blog-introduce-title module-title">关于我</h2>
          <div class="blog-introduce-body">
            <p>锄禾日当午，汗滴禾下土。</p>
            <p>谁知盘中餐，粒粒皆辛苦。</p>
          </div>
        </div>
        <div class="blog-introduce">
          <h2 class="blog-introduce-title module-title">热门文章</h2>
          <div class="blog-introduce-body"></div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import main from './views/main'
export default {
  main
}
</script>
<style lang="less">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;
}
.header {
  width: 100%;
  height: 52.8px;
  z-index: 100;
    background-color: palegreen;
    position: fixed;
    top: 0;
    left: 0;
}
header {
  height: 52.8px;
  margin: auto;
}
.weaper {
  width: 1400px;
  margin: auto;
  display: flow-root;
}
.blog-introduce-body{
  text-align: center
}
.navigation ul {
  float: right;
}
.logimg {
  width: 105px;
  height: 52.8px;
  float: left;
}
ul > li {
  list-style: none;
  float: left;
  margin: 0 20px;
  padding: 0 15px;
}
.article_title {
  padding-top: 20px;
  height: 26px;
}
.navigation {
  // padding: 30px;

  a {
    text-decoration: none;
    display: block;
    padding: 0 15px;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.article-sort-title {
  padding: 5px 10px;
  background-color: #42b983;
}
.sanjiao {
  width: 0;
  height: 0;
  border-bottom: 13.8px solid #fff;
  border-top: 13.8px solid #fff;
  border-right: 13.8px solid #fff;
  border-left: 13.8px solid #42b983;
  position: relative;
  left: 87.5px;
  bottom: 23px;
}

.main {
  width: 1400px;
  margin: auto;
  margin-top: 52.8px;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  margin-top: 50px;
  .article {
    width: 950px;
    padding-left: 20px;
  }
  .content{
    width: 1000px;
  }
  // .article:hover{
  //   background-color: pink;
  // }
  .right {
    width: 280px;
    height: 718px;
    padding-top: 15px;
  }
  .acticle_publish-time {
    color: #9999;
    padding: 10px 0;
  }
  .article_information {
    font-size: 14px;
    padding-bottom: 20px;
  }
  .module-title {
    padding-bottom: 5px;
    font-size: 18px;
    font-weight: normal;
    color: #505050;
    text-align: left;
    border-bottom: 1px solid palegreen;
  }
}
</style>
