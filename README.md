# 前端画板（基于 React 和 SVG）

可以绘制各种图形，包括圆形、矩形、三角形、直线、弧线；可以设置图形轮廓线颜色、宽度；可以填充封闭图形，填充可选择颜色，图形可重叠。可以保存绘制内容到浏览器储存。具有撤销、恢复功能。

<p align="center">
  <a href="https://github.com/kfyidrig/svg-drawing-board">
    <svg t="1623838059346" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4938" width="80" height="80"><path d="M140.852832 882.953653c-12.058297 0-21.789304-9.731006-21.789303-21.789303s9.731006-21.789304 21.789303-21.789304 21.789304 9.731006 21.789304 21.789304-9.731006 21.789304-21.789304 21.789303z m0-28.770154c-3.80783 0-6.98085 3.173021-6.98085 6.980851 0 3.80783 3.173021 6.98085 6.98085 6.98085s6.98085-3.173021 6.980851-6.98085c0-3.80783-3.173021-6.98085-6.980851-6.980851z" fill="#F16723" p-id="4939"></path><path d="M796.008383 505.979554m-4.442638 0a4.442638 4.442638 0 1 0 8.885276 0 4.442638 4.442638 0 1 0-8.885276 0Z" fill="" p-id="4940"></path><path d="M800.451021 106.794311m-4.442638 0a4.442638 4.442638 0 1 0 8.885277 0 4.442638 4.442638 0 1 0-8.885277 0Z" fill="" p-id="4941"></path><path d="M101.716864 281.953445m-4.442639 0a4.442638 4.442638 0 1 0 8.885277 0 4.442638 4.442638 0 1 0-8.885277 0Z" fill="" p-id="4942"></path><path d="M766.3925 93.88926m-6.557985 0a6.557986 6.557986 0 1 0 13.115971 0 6.557986 6.557986 0 1 0-13.115971 0Z" fill="" p-id="4943"></path><path d="M834.509543 473.613515a25.099525 25.099525 0 0 1-25.174269-25.174268c0-13.9617 11.211544-25.174268 25.174269-25.174269s25.174268 11.211544 25.174268 25.174269a25.098501 25.098501 0 0 1-25.174268 25.174268z m0-35.540083c-5.711232 0-10.365815 4.653559-10.365815 10.365815 0 5.711232 4.653559 10.365815 10.365815 10.365815 5.711232 0 10.365815-4.653559 10.365815-10.365815 0-5.711232-4.653559-10.365815-10.365815-10.365815z" fill="#FBD20A" p-id="4944"></path><path d="M938.378614 819.067304h-7.403715v-7.403714c0-4.019774-3.384965-7.403715-7.403715-7.403715-4.019774 0-7.403715 3.384965-7.403715 7.403715v7.403714h-7.403715c-4.019774 0-7.403715 3.384965-7.403714 7.403715s3.384965 7.403715 7.403714 7.403715h7.403715v7.403715c0 4.019774 3.384965 7.403715 7.403715 7.403715 4.019774 0 7.403715-3.384965 7.403715-7.403715v-7.403715h7.403715c4.019774 0 7.403715-3.384965 7.403714-7.403715s-3.383941-7.403715-7.403714-7.403715z" fill="#F16723" p-id="4945"></path><path d="M886.549538 681.139712h-0.422864c-94.983794 0-172.198058-77.00232-172.198058-172.198057s77.00232-172.198058 172.198058-172.198058h0.422864c16.500936 0 27.500536-17.346665 19.673957-31.943175C832.81706 167.295695 687.485754 73.792439 520.577087 74.639192c-239.680292 1.269618-432.187115 194.621146-432.187115 434.302463 0 239.892236 194.410226 434.302462 434.302462 434.302462 166.062937 0 310.12565-93.080391 383.320141-229.949286 7.826579-14.597533-2.750156-32.367063-19.463037-32.155119zM615.983746 818.643416c-34.270466 0-62.193866-27.924424-62.193866-62.193866 0-34.270466 27.924424-62.193866 62.193866-62.193867 34.270466 0 62.193866 27.924424 62.193866 62.193867 0 34.270466-27.923401 62.193866-62.193866 62.193866z" fill="#FFE4B8" p-id="4946"></path><path d="M886.549538 681.139712h-0.422864c-94.983794 0-172.198058-77.00232-172.198058-172.198057s77.00232-172.198058 172.198058-172.198058h0.422864c16.500936 0 27.500536-17.346665 19.673957-31.943175C832.81706 167.295695 687.485754 73.792439 520.577087 74.639192c-9.096197 0-18.193418 0.422865-27.289615 1.057674 153.370854 10.365815 284.951381 100.484106 353.703233 229.103556 7.827603 14.596509-3.173021 32.155119-19.673956 31.943175h-0.422865c-94.983794 0-157.389604 77.00232-157.389604 172.198058s62.193866 172.198058 157.389604 172.198057h0.422865c16.711856 0 27.500536 17.558609 19.462012 32.366039-68.751852 128.619451-200.121458 218.525797-353.491289 228.891612 9.731006 0.634809 19.462012 1.057674 29.404962 1.057674 166.062937 0 310.12565-93.080391 383.320141-229.949286 7.826579-14.808453-2.750156-32.577983-19.463037-32.366039z" fill="#E7D0A9" p-id="4947"></path><path d="M131.333771 508.941655c0-231.430848 189.967588-419.916873 418.225414-433.667654-9.519062-0.634809-19.251092-0.845729-28.982098-0.845729-239.681316 1.269618-432.187115 194.621146-432.187115 434.302462 0 239.892236 194.410226 434.302462 434.302462 434.302462 9.096197 0 17.981474-0.211944 26.866751-0.845729-227.412098-13.53986-418.225415-202.238853-418.225414-433.245812z" fill="#FFFFFF" p-id="4948"></path><path d="M212.35484 118.851585h-7.403715v-7.403715c0-4.019774-3.384965-7.403715-7.403714-7.403715s-7.403715 3.384965-7.403715 7.403715v7.403715h-7.403715c-4.019774 0-7.403715 3.384965-7.403715 7.403714s3.384965 7.403715 7.403715 7.403715h7.403715v7.403715c0 4.019774 3.384965 7.403715 7.403715 7.403715s7.403715-3.384965 7.403714-7.403715v-7.403715h7.403715c4.019774 0 7.403715-3.384965 7.403715-7.403715s-3.383941-7.403715-7.403715-7.403714z" fill="#4E9BD4" p-id="4949"></path><path d="M856.721711 883.799382m-4.442638 0a4.442638 4.442638 0 1 0 8.885277 0 4.442638 4.442638 0 1 0-8.885277 0Z" fill="" p-id="4950"></path><path d="M522.692434 956.148143c-84.195114 0-166.485802-23.481786-237.564944-68.118066-69.17574-43.366663-125.234486-104.926744-161.832243-177.69837a12.718704 12.718704 0 0 1 5.711232-17.134721 12.718704 12.718704 0 0 1 17.134721 5.711232c34.69333 68.540931 87.368135 126.504104 152.736046 167.543475 67.059369 42.097045 144.485578 64.310237 224.026109 64.310238 155.909066 0 298.490217-85.464732 372.107572-223.18038 2.327291-4.230694 0.634809-7.827603-0.211944-9.308142-0.845729-1.269618-3.173021-4.442638-8.038524-4.442638h-0.422865c-101.964644 0-184.89014-82.925496-184.89014-184.89014 0-6.98085 5.711232-12.693106 12.693106-12.693107s12.693106 5.711232 12.693107 12.693107c0 88.002944 71.502008 159.504951 159.504951 159.504951h0.422865a34.87763 34.87763 0 0 1 29.827827 16.711856c6.346041 10.577759 6.557986 23.269842 0.845729 34.270466C839.164126 865.395044 687.908618 956.148143 522.692434 956.148143z m93.291312-122.061465c-42.943798 0-77.849073-34.905275-77.849073-77.849073s34.905275-77.849073 77.849073-77.849073 77.849073 34.905275 77.849073 77.849073c-0.001024 42.943798-34.905275 77.849073-77.849073 77.849073z m0-130.311933c-28.982098 0-52.46286 23.481786-52.46286 52.46286 0 28.982098 23.481786 52.46286 52.46286 52.462861 28.982098 0 52.46286-23.481786 52.46286-52.462861 0-28.981074-23.481786-52.46286-52.46286-52.46286z m-494.170061-14.173644c-4.865503 0-9.731006-2.9621-11.635433-7.827604-8.461388-20.096821-15.231318-40.828451-20.73163-61.771001-1.692482-6.76993 2.327291-13.75078 9.096197-15.443263 6.76993-1.692482 13.75078 2.327291 15.443263 9.096198 5.077447 19.884877 11.635433 39.347913 19.462012 58.386036 2.750156 6.557986-0.422865 13.9617-6.76993 16.500936-1.479514 0.846753-3.171997 1.058697-4.864479 1.058698z m-26.230918-88.637753c-5.923177 0-11.211544-4.230694-12.481162-10.365815-5.288368-27.289616-7.403715-50.982322-7.403715-81.656902 0-119.311309 46.116819-231.430848 129.889068-315.414018C289.358184 109.332523 401.264754 62.580895 520.577087 61.946086h2.327292c165.428128 0 316.471691 90.541155 394.531684 236.93116 5.711232 10.577759 5.500312 23.269842-0.845729 33.635657-6.346041 10.577759-17.558609 16.923801-30.039772 16.9238h-0.422864c-71.291087 0-134.331707 48.021246-153.581775 116.561153-1.903403 6.76993-8.885277 10.78868-15.654183 8.885277-6.76993-1.903403-10.78868-8.885277-8.885277-15.654183 22.212168-79.540531 95.406658-135.177436 178.121235-135.177436h0.422864c3.384965 0 6.557986-1.692482 8.250468-4.653559 0.845729-1.692482 2.327291-4.865503 0.211945-8.673332-73.617355-137.927592-216.19953-223.3913-372.319517-223.3913h-2.115347c-112.542403 0.634809-218.102932 44.636281-297.009679 123.965891S101.082055 396.399251 101.082055 508.941655c0 29.193018 2.115347 51.405187 6.98085 77.002319 1.269618 6.98085-3.173021 13.538836-9.94295 14.808454-0.845729 0.21092-1.691459 0.21092-2.537188 0.21092z" fill="" p-id="4951"></path><path d="M329.127938 292.742125a89.060617 63.675428 90 1 0 127.350856 0 89.060617 63.675428 90 1 0-127.350856 0Z" fill="#EE3C7A" p-id="4952"></path><path d="M281.953445 292.742125a89.060617 63.675428 90 1 0 127.350857 0 89.060617 63.675428 90 1 0-127.350857 0Z" fill="#FFFFFF" p-id="4953"></path><path d="M363.707329 381.781649a89.060617 51.617131 88.848 1 0-3.581099-178.085232 89.060617 51.617131 88.848 1 0 3.581099 178.085232Z" fill="#F05F88" p-id="4954"></path><path d="M583.828627 246.413362a89.060617 63.675428 90 1 0 127.350857 0 89.060617 63.675428 90 1 0-127.350857 0Z" fill="#3769A5" p-id="4955"></path><path d="M536.44219 246.413362a89.060617 63.675428 90 1 0 127.350857 0 89.060617 63.675428 90 1 0-127.350857 0Z" fill="#FFFFFF" p-id="4956"></path><path d="M565.001424 246.413362a89.060617 51.617131 90 1 0 103.234262 0 89.060617 51.617131 90 1 0-103.234262 0Z" fill="#4E9BD4" p-id="4957"></path><path d="M216.374614 525.441567a89.060617 63.675428 90 1 0 127.350857 0 89.060617 63.675428 90 1 0-127.350857 0Z" fill="#FAAF1A" p-id="4958"></path><path d="M169.200122 525.441567a89.060617 63.675428 90 1 0 127.350856 0 89.060617 63.675428 90 1 0-127.350856 0Z" fill="#FFFFFF" p-id="4959"></path><path d="M197.547411 525.441567a89.060617 51.617131 90 1 0 103.234261 0 89.060617 51.617131 90 1 0-103.234261 0Z" fill="#FBD20A" p-id="4960"></path><path d="M327.224535 740.795367a89.060617 63.675428 90 1 0 127.350857 0 89.060617 63.675428 90 1 0-127.350857 0Z" fill="#F05225" p-id="4961"></path><path d="M280.049019 740.795367a89.060617 63.675428 90 1 0 127.350856 0 89.060617 63.675428 90 1 0-127.350856 0Z" fill="#FFFFFF" p-id="4962"></path><path d="M308.396308 740.795367a89.060617 51.617131 90 1 0 103.234261 0 89.060617 51.617131 90 1 0-103.234261 0Z" fill="#F16723" p-id="4963"></path><path d="M367.418177 394.495848c-56.059769 0-101.753724-45.693954-101.753723-101.753723s45.693954-101.753724 101.753723-101.753724 101.753724 45.693954 101.753724 101.753724-45.693954 101.753724-101.753724 101.753723z m0-178.121234c-42.097045 0-76.367511 34.270466-76.367511 76.367511s34.270466 76.367511 76.367511 76.367511S443.785688 334.83917 443.785688 292.742125s-34.270466-76.367511-76.367511-76.367511zM623.810325 348.167085c-56.059769 0-101.753724-45.693954-101.753723-101.753723s45.693954-101.753724 101.753723-101.753724c56.059769 0 101.753724 45.693954 101.753724 101.753724s-45.693954 101.753724-101.753724 101.753723z m0-178.121234c-42.097045 0-76.367511 34.270466-76.367511 76.367511s34.270466 76.367511 76.367511 76.367511 76.367511-34.270466 76.367511-76.367511-34.269442-76.367511-76.367511-76.367511zM256.356312 627.19529c-56.059769 0-101.753724-45.693954-101.753723-101.753723s45.693954-101.753724 101.753723-101.753724 101.753724 45.693954 101.753724 101.753724-45.693954 101.753724-101.753724 101.753723z m0-178.121234c-42.097045 0-76.367511 34.270466-76.367511 76.367511s34.270466 76.367511 76.367511 76.36751 76.367511-34.270466 76.367511-76.36751-34.269442-76.367511-76.367511-76.367511zM367.418177 842.548067c-56.059769 0-101.753724-45.693954-101.753723-101.753724 0-56.059769 45.693954-101.753724 101.753723-101.753724s101.753724 45.693954 101.753724 101.753724c-0.001024 56.059769-45.693954 101.753724-101.753724 101.753724z m0-178.121235c-42.097045 0-76.367511 34.270466-76.367511 76.367511s34.270466 76.367511 76.367511 76.367511S443.785688 782.891388 443.785688 740.794343s-34.270466-76.367511-76.367511-76.367511z" fill="" p-id="4964"></path></svg>
  </a>
  <h3 align="center">前端画板（基于React和SVG）</h3>
  <p align="center">
    可以绘制各种图形，包括圆形、矩形、三角形、直线、弧线
    <br /><br />
    <a href="http://www.ieleven.xyz" target="_blank">查看Demo</a>
    ·
    <a href="https://github.com/kfyidrig/svg-drawing-board/issues">报告Bug</a>
    ·
    <a href="https://github.com/kfyidrig/svg-drawing-board/issues">提出新特性</a>
  </p>

## 目录

- [上手指南](#上手指南)
  - [环境要求](#开发前的配置要求)
  - [安装步骤](#安装步骤)
- [文件目录说明](#文件目录说明)
- [开发的架构](#开发的架构)
- [部署](#部署)
- [使用到的框架](#使用到的框架)
- [版本控制](#版本控制)
- [作者](#作者)

### 上手指南

打开网页即可食用，暂时不支持触屏操作，仅能通过鼠标来绘制

###### 环境要求

1. Node.js（尽量新的版本）
2. 最好使用 chrome、safari 或 firefox

###### **安装步骤**

1. 克隆本项目源码

   ```shell
   git clone https://github.com/kfyidrig/svg-drawing-board.git
   ```

2. 按照项目依赖

   ```shell
   yarn
   #如果你没安装yarn，请先安装yarn
   ```

3. 在浏览器预览

   ```shell
   yarn start
   ```

4. 打包生成成品

   ```shell
   yarn run build
   #build目录即可看到成品
   ```

### 文件目录说明

暂无

### 部署

暂无

### 使用到的框架

- [react](https://react.docschina.org/)

### 贡献者

请阅读**CONTRIBUTING.md** 查阅为该项目做出贡献的开发者。

### 版本控制

该项目使用 Git 进行版本管理。您可以在 repository 参看当前可用版本。

### 作者

liucan@ieleven.xyz

_您也可以在贡献者名单中参看所有参与该项目的开发者。_

### 版权说明

该项目签署了 MIT 授权许可，详情请参阅 [LICENSE.txt](https://github.com/shaojintian/Best_README_template/blob/master/LICENSE.txt)