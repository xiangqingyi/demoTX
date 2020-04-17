<template>
   <div>
       <el-container>
           <el-header>
               <img src="../assets/images/top.png" alt="" class="topimg">
               <img src="../assets/images/playbig.png" alt="" class="playbig">
           </el-header>
           <el-main style="margin-top:-90px">
               <!-- <div class="partone" style="margin-top:-90px;z-index:2"> -->
                   <p class="fontBig font">
                       <b>原来产后抑郁症和产后情绪低落的区别在这里！</b>
                    </p>
                    <p class="fontMiddle font">
                        Healthwise 美国著名的医疗健康信息服务商
                        <!-- <b>Healthwise 美国著名的医疗健康信息服务商</b> -->
                    </p>
                    <p class="fontSmall font">
                        更新于 2018-06-19
                    </p>
               <!-- </div> -->

           </el-main>
        </el-container>
        <hr />
        <el-container>
            <el-header>
                <p class="font2Big font">
                    <b>视频简介</b>
                </p>
                <p class="font2Middle font">
                    抑郁症是女性最高发的心理疾病，目前全球范围内每年新发乳腺癌达 168 万人，每年有 52 万女性因乳腺癌死亡。科学地进行乳房检查有利于今早发现乳腺病现乳腺...
                </p>
            </el-header>
            <div class="line"></div>
            <el-main>
                <p class="font2Big font">
                    <b>相关视频</b>
                </p>
                <div class="videos">
                    <div class="video1">
                        <img src="../assets/images/video-1.jpg" alt="">
                        <p>怎么治疗湿疹</p>
                    </div>
                    <div class="video2">
                        <img src="../assets/images/video-2.png" alt="">
                        <p>怎么治疗湿疹</p>
                    </div>
                    <div class="video3">
                        <img src="../assets/images/video-3.jpg" alt="">
                        <p>怎么治疗湿疹</p>
                    </div>
                    <div class="video4">
                        <img src="../assets/images/video-4.png" alt="">
                        <p>怎么治疗湿疹</p>
                    </div>
                </div>
            </el-main>
            <el-footer>Footer</el-footer>
        </el-container>
   </div>


</template>

<script>
    export default {
        data(){
            return {
                
            }
        }
    }
</script>

<style scoped>
   .el-header, .el-footer{
       /* background-color: #B3C0D1; */
       /* color: #333; */
       /* text-align: center; */
       clear: both;
       display: block;
       padding: 0px;
       margin: 0px;
       position: relative;
       overflow: hidden;
       height: unset !important;
   }

   .topimg {
       display: block;
       width: 100%;
       position: relative;
       min-width: 100%;
       min-height: 100%;
   }
   .playbig {
       /* display: block; */
       position: relative;
       z-index: 100;
       top: -140px;
       width: 80px;
       height: 80px;
       opacity: 0.7;

   }
   .font {
       letter-spacing: 0;
       font-family: PingFangSC-Medium;
       text-align: left;
       margin-left: 20px;
       margin-right: 20px;
   }
   .fontBig {
       font-size: 28px;
       color: rgba(0, 0, 0, 0.85);
   }
   .fontMiddle {
       font-size: 15px;
       color: rgba(0, 0, 0, 0.65);
       margin-top: -18px;
   }
   .fontSmall {
       color: rgba(0, 0, 0, 0.25);
       margin-top: -14px;
   }
   hr {
       height: 1px;
       width: 85%;
       color: rgba(0, 0, 0, 0.08);
   }
   .font2Big {
       font-size: 24px;
       color: rgba(0, 0, 0, 0.85);
   }
   .font2Middle {
       font-size:18px;
       line-height: 28px;
       text-align: justify !important;
       color: rgba(0, 0, 0, 0.65);
       margin-top: -12px;
   }
   .font3Big {

   }
   .line {
       /* background: rgba(247, 250, 250, 1); */
       background: #F7FAFA;
       height: 16px;
   }
   .el-main {
       position: relative;
       margin: 0;
       padding: 0;
       z-index: 2;
       /* margin-top: -90px; */
       /* background-color: #E9EEF3; */
       /* color: #333; */
       /* text-align: center; */
       /* line-height: 160px; */
   }
</style>