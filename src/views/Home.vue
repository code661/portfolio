<template>
  <div class="container">
    <div id="name-container">
      <img id="avatar" src="./../assets/images/av.png" alt="avatar" />
      <h1>Spencer Woo</h1>
    </div>
    <div class="title-desc-container">
      <a id="github" href="https://github.com/spencerwooo"
        ><img class="title-font" src="./../assets/images/github.svg" />Developer</a
      >
      <span>/</span>
      <a id="sspai" href="https://sspai.com/u/spencerwoo/posts"
        ><img class="title-font" src="./../assets/images/sspai.svg" />Writer</a
      >
      <span>/</span>
      <a id="blog" href="https://blog.spencerwoo.com"
        ><img class="title-font" src="./../assets/images/zeit.svg" />Blogger</a
      >
    </div>
    <div class="article">
      <h2>Name</h2>
      <p>
        I go by the name of <i>Tan61</i>. Various other IDs across the net:
        <a href="https://twitter.com/realSpencerWoo">@realSpencerWoo</a> /
        <a href="https://weibo.com/spencerwoo">@SpencerWoo</a> /
        <a href="https://github.com/spencerwooo">@spencerwooo</a>.
      </p>

      <h2>Academics</h2>
      <ul>
        <li><b>Current:</b> Computer Science <i>UNDERGRAD</i> at Beijing Institute of Technology. Graduating soon.</li>
        <li>
          <b>Future:</b> Prospective student at <a href="https://www.gla.ac.uk/">the University of Glasgow</a>, 1/2021
          entry, <a href="https://www.gla.ac.uk/postgraduate/taught/computingsciencemsc/">MSc in Computing Science</a>.
          🙇
        </li>
        <li><b>Fields of interest:</b> Adversarial attacks / Image classification / AI security.</li>
      </ul>

      <h2>Devices</h2>
      <ul>
        <li>iPhone 8 Gold</li>
        <li>Intel® NUC Kit NUC8I5BEK</li>
        <li>ThinkPad X1 Carbon 7th Gen</li>
        <li>Sony 1000XM3</li>
        <li>iPhone XR / iPad Air 3 / AirPods Pro</li>
      </ul>

      <h2>Contacts</h2>
      <ul>
        <li>
          <b>Email：</b>
          <a href="mailto:spencerwoo98@gmail.com">spencerwoo98#gmail.com</a><i> (Preferred)</i>
        </li>
        <li><b>Catch me: </b>Beijing Institute of Technology, Beijing, China</li>
      </ul>
    </div>
  </div>
</template>

<style lang="css" scoped>
#name-container {
	display: flex;
	flex-direction: row;
	justify-content: flex-start;
	align-items: center;
}

#avatar {
  width: 42px;
  height: 42px;
  border-radius: 50%;
  margin-right: 12px;
}

#copyright:hover {
  border: none;
}

.title-font {
  width: 16px;
  height: 16px;
  margin-right: 4px;
}

.title-desc-container {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  margin: 8px 0;
}

.title-desc-container a {
  display: flex;
  align-items: center;
}

.title-desc-container span {
  margin: 0px 4px;
}

.title-desc-container #github {
  color: #24292e;
}

.title-desc-container #sspai {
  color: #ca2c2a;
}

.title-desc-container #blog {
  color: #0070f3;
}

a:hover {
  border-bottom: none;
}

h2 {
  font-size: 20px;
  padding: 16px 0 4px 0;
}

ul {
  padding-left: 15px;
  line-height: 30px;
  margin: 0;
}

p {
  line-height: 30px;
}
</style>
