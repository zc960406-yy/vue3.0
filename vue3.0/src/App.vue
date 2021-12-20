<template>
  <div class="sn">
    <div class="left">
      <!-- <span>
        <span class="iconfont icon-shujucaiji"></span>
      </span> -->
      <div class="top">
        <div class="blue"></div>
        <div class="kuang">
          <div class="left">
            <div class="top">
              <ul>
                <li>
                  <span class="iconfont icon-tuoputu"></span>
                  <p>拓扑编排</p>
                </li>
                <li>
                  <span class="iconfont icon-shujucaiji"></span>
                  <p>数据采集</p>
                </li>
                <li>
                  <span class="iconfont icon-liuliang"></span>
                  <p>流量发生</p>
                </li>
              </ul>
            </div>
            <div class="bot">
              <ul>
                <div>
                  <li>
                    <span class="iconfont icon-changjingdakai"></span>
                    <p>场景模板</p>
                  </li>
                  <li>
                    <span class="iconfont icon-operatingsystem"></span>
                    <p>操作系统</p>
                  </li>
                  <li>
                    <span class="iconfont icon-chanyeyingyongxitong"></span>
                    <p>应用系统</p>
                  </li>
                  <li>
                    <span class="iconfont icon-wangluo"></span>
                    <p>网络设备</p>
                  </li>
                  <li>
                    <span class="iconfont icon-liuliang"></span>
                    <p>安防设备</p>
                  </li>
                </div>
              </ul>
            </div>
          </div>
          <div class="right">
            <div>
              <span class="iconfont 24gl-move icon-24gl-move"></span>
              <span class="iconfont icon-wenzi"></span>
              <span class="iconfont icon-kuangxuan"></span>
              <span class="iconfont icon-map-connect-full"></span>
            </div>
          </div>
        </div>
      </div>
      <div class="bottom">
        <ul>
          <div>
            <li>
              <span class="iconfont icon-jietu"></span>
              <p>场景截图</p>
            </li>
            <li>
              <span class="iconfont icon-xiazaidaoru"></span>
              <p>导入配置</p>
            </li>
            <li>
              <span class="iconfont icon-daochu"></span>
              <p>导出配置</p>
            </li>
            <li>
              <span class="iconfont icon-chuangjian"></span>
              <p>创建模板</p>
            </li>
            <li>
              <span class="iconfont icon-jichushezhi"></span>
              <p>基础设置</p>
            </li>
          </div>
        </ul>
      </div>
    </div>

    <div class="right">
      <div class="top"><span class="iconfont icon-zhankai"></span></div>
      <div class="bottom">
        <ul>
          <li><span class="iconfont icon-quanping"></span></li>
          <li><span class="iconfont icon-fangda"></span></li>
          <li><span class="iconfont icon-suoxiao"></span></li>
          <li><span class="iconfont icon-zhankai"></span></li>
          <li><span class="iconfont icon-bangzhu"></span></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script lang="ts"></script>
<style lang="scss" scoped>
/* @import "./style/css/reset.scss"; */
@import "assets/font/iconfont.css";
.sn {
  padding-left: 5px;
  padding-top: 5px;
  display: flex;
  justify-content: space-between;
  height: 100%;
  .left {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;
    .top {
      display: flex;
      flex-direction: column;
      .blue {
        width: 400px;
        height: 50px;
        background-color: pink;
      }
      .kuang {
        display: flex;
        .left {
          padding-top: 8px;
          padding-right: 8px;
          .top {
            width: 120px;
            height: 100px;
            border: 1px solid gray;
            ul {
              li {
                display: flex;
                justify-content: center;
                align-items: center;
                padding: 5px;
                span {
                  padding: 3px;
                }
              }
            }
          }
          .bot {
            width: 120px;
            height: 200px;
            border: 1px solid gray;
            ul {
              display: flex;
              justify-content: center;
              align-items: center;
              height: 100%;

              li {
                display: flex;
                justify-content: center;
                align-items: center;
                padding: 7px;
                span {
                  margin-right: 3px;
                  justify-content: center;
                  align-items: center;
                }
              }
            }
          }
        }
        .right {
          display: flex;
          margin-top: 8px;
          width: 150px;
          height: 40px;
          border: 1px solid gray;
          justify-content: center;
          align-items: center;
          span {
            width: 20px;
            padding: 8px;
          }
        }
      }
    }
    .bottom {
      width: 120px;
      height: 200px;
      border: 1px solid gray;
      margin-bottom: 10px;
      ul {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100%;

        li {
          display: flex;
          justify-content: center;
          align-items: center;
          padding: 7px;
          span {
            margin-right: 3px;
            justify-content: center;
            align-items: center;
          }
        }
      }
    }
  }

  .right {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;

    .top {
      span {
        display: flex;
        width: 25px;
        height: 25px;
        justify-content: center;
        align-items: center;
        /* background-color: pink; */
      }
    }
    .bottom {
      width: 50px;
      height: 200px;
      border: 1px solid gray;
      display: flex;
      justify-content: center;
      align-items: center;
      margin-right: 5px;
      margin-bottom: 10px;
      ul {
        list-style: none;
        li {
          padding: 6px;
        }
      }
    }
  }
}
</style>
