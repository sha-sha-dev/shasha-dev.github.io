<!DOCTYPE html>
<html lang="zh-CN">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="generation-source" content="AI生成">
  <link rel="icon" type="image/png" href="https://metis-online.fbcontent.cn/metis-lectio/uxPOvzX0E3VvOxDn9ynBJE.png">
  <title>飞象老师</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'PingFang SC', 'Hiragino Sans GB', 'Microsoft YaHei', 'Helvetica Neue', Helvetica, Arial, sans-serif;
      overflow: hidden;
    }

    .iframe-container {
      box-sizing: border-box;
      padding: 56px 20px 20px 20px;
      width: 100vw;
      height: 100vh;
      position: relative;
    }

    .iframe-container.mobile {
      padding: 0.48rem 0 0 0;

      .watermark-overlay {
        height: 0.48rem;
      }

      .content-iframe {
        border: transparent;
        border-radius: 0;
      }

      .watermark-logo {
        width: 0.74rem;
        height: 0.17rem;
        margin-right: 0.07rem;

        svg {
          width: 100%;
          height: 100%;
        }
      }

      .watermark-text {
        padding-left: 0.08rem;

        .watermark-title {
          font-size: 0.12rem;
        }
      }

      .watermark-content {
        padding: 0;
        padding-left: 0.16rem;
      }
    }

    .content-iframe {
      width: 100%;
      height: 100%;
      border: none;
      display: block;
      border: 0.5px solid #C9DACC;
      border-radius: 16px;
    }

    .watermark-overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 56px;
      z-index: 1000;
      display: flex;
      align-items: center;
      cursor: pointer;
    }


    .watermark-content {
      width: 100%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0 32px;
    }

    .left-watermark-content {
      display: flex;
      align-items: center;
    }

    .watermark-logo {
      width: 74px;
      height: 17px;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-right: 14px;

      svg {
        width: 100%;
        height: 100%;
      }
    }

    .watermark-text {
      display: flex;
      flex-direction: column;
      padding-left: 14px;
      border-left: 1px solid #C9DACC;
    }

    .watermark-title {
      color: #617971;
      font-family: "PingFang SC";
      font-size: 15px;
      font-style: normal;
      font-weight: 400;
      line-height: 17px;
    }

    .jump-button {
      width: 90px;
      height: 44px;
      background: #02543B;
      border-radius: 120px;
      color: #FFFFFF;
      font-size: 14px;
      font-style: normal;
      font-weight: 500;
      line-height: 14px;
      text-align: center;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      border: none;
      outline: none;
      transition: all 0.3s ease;
      margin-left: 16px;
    }

    .ai-badge {
      position: fixed;
      right: 37px;
      bottom: 37px;
      z-index: 1001;
      display: flex;
      align-items: center;
      justify-content: center;
      width: 48px;
      height: 24px;

      svg {
        width: 100%;
        height: 100%;
      }
    }
  </style>
  <!-- 后端传值 -->
  <script>
    window.__SERVER_DATA__ = {
      watermarkChatId: "8B7921095D00365EFE022F65B0596756",
      watermarkEnv: "online",
      watermarkBizId: "F46A02EE5F731A1FE2E278AF5B6099D7",    
      watermarkUrl: "https://musk-online.fbcontent.cn/pub-musk-ai-studio/workflow/file/document/GKhPU7LYewUQ692v8L7Bzb.html",  // 在线访问地址，后端生成时填入
    }
  </script>

  <!-- 自动重定向到在线地址（解决 file:// 协议的 CORS 问题） -->
  <script>
      (function () {
        // 检测是否为本地文件协议
        if (window.location.protocol === 'file:') {

          const watermarkUrl = window.__SERVER_DATA__.watermarkUrl

          // 检查是否有有效的在线地址
          if (watermarkUrl && watermarkUrl.startsWith('http')) {
            // 直接跳转到在线地址
            window.location.replace(watermarkUrl)
            // 阻止后续脚本执行
            throw new Error('Redirecting to online version...')
          }
          // 阻止后续脚本执行
          throw new Error('Local file protocol detected without online URL')
        }
      })()
  </script>

  <!-- 引入 Frog 埋点 SDK（本地构建版本） -->
  <script src="https://www.feixianglaoshi.com/frog-sdk.js"></script>

  <!--  埋点初始化 -->
  <script src='https://www.feixianglaoshi.com/init-frog.js'></script>
</head>

<body>

  <!-- 主要内容容器 -->
  <div class="iframe-container">

    <!-- 水印覆盖层 -->
    <div class="watermark-overlay">

      <div class="watermark-content">
        <div class="left-watermark-content">
          <div class="watermark-logo">
            <svg xmlns="http://www.w3.org/2000/svg" width="73.9998" height="17" viewBox="0 0 73.9998 17">
              <defs>
                <clipPath id="clipPath3233314457">
                  <path d="M0 0L73.9998 0L73.9998 17L0 17L0 0Z" fill-rule="nonzero" transform="matrix(1 0 0 1 0 0)" />
                </clipPath>
              </defs>
              <g clip-path="url(#clipPath3233314457)">
                <path
                  d="M13.0815 15.1494L7.72278 15.1494C7.61728 15.1508 7.52891 15.1122 7.4577 15.0334C7.38658 14.9547 7.3564 14.8623 7.36715 14.7562C7.70783 11.2147 8.37138 4.12248 8.76882 0.605133C8.79315 0.442888 8.75158 0.300333 8.64412 0.177468C8.53667 0.0546026 8.4019 -0.00446715 8.23982 0.00025843L0.107625 0.00025843C0.0779519 0.00025843 0.0525841 0.010891 0.0315213 0.0321561C0.0105071 0.0534212 0 0.0790797 0 0.109131L0 1.48221C0 1.51226 0.0105071 1.53792 0.0315213 1.55918C0.0525355 1.58042 0.0779033 1.59106 0.107625 1.59108L6.25537 1.59108C5.83698 5.61654 5.19138 12.1552 4.87164 15.5516C4.84173 15.8701 4.93305 16.1477 5.14563 16.3845C5.3582 16.6213 5.62253 16.7398 5.93862 16.7402L13.0815 16.7402C13.1112 16.7402 13.1365 16.7295 13.1575 16.7083C13.1786 16.687 13.1891 16.6614 13.1892 16.6313L13.1892 15.2552C13.1884 15.2257 13.1775 15.2007 13.1566 15.1801C13.1357 15.1596 13.1107 15.1493 13.0815 15.1494Z"
                  fill-rule="nonzero" transform="matrix(1 0 0 1 0 0.259814)" fill="rgb(0, 71, 55)" />
                <path
                  d="M1.96737 5.51948L3.85622 5.51948C3.89329 5.51951 3.92257 5.50417 3.94407 5.47348C3.96557 5.44279 3.97017 5.40973 3.95786 5.37432L2.16466 0.12401C2.15299 0.0871402 2.13173 0.0572731 2.10089 0.0344082C2.07005 0.0115678 2.03552 9.84496e-05 1.99728 0L0.108427 0C0.0712629 -2.46124e-05 0.0419308 0.0153089 0.0204303 0.0460006C-0.00107016 0.0766677 -0.00561833 0.109722 0.00678578 0.145164L1.79998 5.3985C1.8121 5.4347 1.83357 5.46393 1.86441 5.48618C1.89515 5.50843 1.92947 5.51953 1.96737 5.51948Z"
                  fill-rule="nonzero" transform="matrix(1 0 0 1 8.98925 7.5912)" fill="rgb(0, 71, 55)" />
                <path
                  d="M4.17837 0L2.30447 0C2.26881 -2.46124e-05 2.23605 0.00984496 2.20619 0.0296087C2.17637 0.0493725 2.15433 0.0757939 2.14008 0.108873L0.00919366 4.90855C-0.00569131 4.94434 -0.00255379 4.97845 0.0186062 5.01089C0.0397662 5.04328 0.0695118 5.05957 0.107843 5.05977L1.98174 5.05977C2.01691 5.05967 2.04936 5.05006 2.07908 5.03094C2.10875 5.01181 2.1311 4.98614 2.14614 4.95393L4.27702 0.154246C4.29166 0.118213 4.28852 0.0838299 4.26761 0.0510954C4.24669 0.0183855 4.21695 0.00135368 4.17837 0Z"
                  fill-rule="nonzero" transform="matrix(1 0 0 1 8.9987 1.62391)" fill="rgb(0, 71, 55)" />
                <path
                  d="M2.15291 2.70987L4.09554 0.17241C4.10838 0.156387 4.11595 0.13815 4.11823 0.117697C4.12052 0.0972191 4.11716 0.0777261 4.10816 0.0592175C4.09916 0.0407336 4.08598 0.0261507 4.06862 0.0154689C4.05115 0.00473789 4.03223 -0.000406105 4.01185 3.69186e-05L1.83311 3.69186e-05C1.80562 -0.000307655 1.77948 0.00564855 1.75467 0.0179055C1.72996 0.0301625 1.70928 0.0473912 1.69265 0.0695916L0.0369204 2.229C0.019652 2.25238 0.00839101 2.27843 0.00313751 2.30716C-0.00211599 2.33586 -0.000826939 2.36425 0.00700467 2.39233L0.126522 2.79456C0.456228 3.79574 0.824362 4.78224 1.23092 5.75407C1.63749 6.72589 2.08126 7.68003 2.56225 8.61648C2.57743 8.6468 2.59924 8.67095 2.6277 8.68891C2.65615 8.70683 2.68714 8.71595 2.72066 8.71627L4.60652 8.71627C4.64728 8.71657 4.67822 8.69903 4.69933 8.66366C4.72044 8.62827 4.72139 8.59237 4.70217 8.55597C4.19915 7.61853 3.73485 6.66182 3.30927 5.68584C2.88368 4.70983 2.49823 3.71784 2.15291 2.70987Z"
                  fill-rule="nonzero" transform="matrix(1 0 0 1 26.2846 8.28681)" fill="rgb(0, 71, 55)" />
                <path
                  d="M13.189 7.52767L14.2111 7.52767C14.2604 7.52855 14.3027 7.51151 14.3378 7.47654C14.3729 7.44156 14.3905 7.39913 14.3905 7.34924L14.3905 4.62731C14.3906 4.27823 14.2686 3.98026 14.0247 3.73339C13.7807 3.48653 13.4862 3.3631 13.1412 3.3631L12.0504 3.3631C12.403 2.57677 12.6331 1.9719 12.6481 1.93561L12.9679 1.07972C12.9898 1.02053 12.983 0.964942 12.9475 0.91296C12.912 0.860979 12.863 0.834902 12.8005 0.83473L3.00962 0.83473L3.37124 0.160301C3.3905 0.123899 3.3896 0.0880017 3.36854 0.052609C3.34738 0.0172656 3.31639 -0.000270736 3.27558 0L1.73644 0C1.70326 4.92248e-05 1.67242 0.00876202 1.64392 0.0261384C1.61551 0.0434901 1.59355 0.0670319 1.57803 0.0967637L0.400509 2.29852C0.381198 2.33492 0.382097 2.3708 0.403209 2.40617C0.42432 2.44154 0.455306 2.45909 0.496167 2.45882L10.6936 2.45882C10.5711 2.73707 10.4306 3.04553 10.2752 3.36613L0.567966 3.36613C0.518446 3.36613 0.476175 3.38385 0.441151 3.41929C0.406127 3.45473 0.388616 3.4975 0.388616 3.54758L0.388616 7.35829C0.388518 7.40815 0.406054 7.45057 0.441224 7.48554C0.476394 7.52052 0.518641 7.53757 0.567966 7.53671L5.54394 7.53671C3.40407 8.58616 1.4016 9.39368 0.116526 9.88363C0.0812109 9.89552 0.0527786 9.91681 0.0312293 9.9475C0.00977741 9.97819 -0.00063237 10.0124 0 10.05L0 11.5047C-9.72877e-05 11.5423 0.0150309 11.572 0.0453847 11.5937C0.0756898 11.6155 0.108378 11.6201 0.143451 11.6075C1.2609 11.1956 2.36645 10.7532 3.46011 10.2806C4.55377 9.80796 5.63393 9.30566 6.70059 8.77371C6.7524 9.03381 6.80022 9.29996 6.84404 9.57215C5.75267 10.139 4.64588 10.6731 3.52366 11.1746C2.40145 11.676 1.26574 12.1439 0.116526 12.5784C0.0818433 12.591 0.0538487 12.6126 0.0325427 12.643C0.0112367 12.6735 0.000389151 12.7074 0 12.7447L0 14.1995C-9.72877e-05 14.2371 0.0150309 14.2667 0.0453847 14.2885C0.0756898 14.3102 0.108378 14.3148 0.143451 14.3023C1.32705 13.8667 2.49716 13.3967 3.65376 12.8922C4.81037 12.3877 5.9515 11.8496 7.07717 11.2779C7.11008 11.5803 7.13992 11.8586 7.16984 12.155C6.02452 12.742 4.86361 13.2956 3.68711 13.8157C2.51061 14.3358 1.32041 14.8216 0.116526 15.2731C0.0812595 15.286 0.0529245 15.3079 0.0315212 15.339C0.0101179 15.3701 -0.000389151 15.4046 0 15.4425L0 16.8972C0.000875589 16.9342 0.016393 16.9632 0.0465522 16.9841C0.0766627 17.005 0.108962 17.0094 0.143451 16.997C1.36645 16.5511 2.57615 16.0708 3.77255 15.5563C4.96899 15.0417 6.15024 14.4937 7.31628 13.9122C7.37304 14.88 7.40296 15.8841 7.40595 16.8972C7.406 16.9267 7.41617 16.952 7.43645 16.9732C7.45679 16.9943 7.4815 17.0053 7.51059 17.0061L9.52794 17.0061C9.55825 17.0061 9.58396 16.9951 9.60507 16.9731C9.62623 16.9512 9.63639 16.9249 9.63557 16.8942C9.63557 13.3738 9.30978 10.0622 8.73896 7.53682L13.189 7.52767ZM11.9935 5.95501L8.51474 5.95501L8.51474 4.92974L11.6349 4.92974C11.7339 4.92979 11.8185 4.96525 11.8885 5.0361C11.9585 5.10696 11.9935 5.19248 11.9935 5.29265L11.9935 5.95501ZM2.80634 4.92974L6.28513 4.92974L6.28513 5.95501L2.80634 5.95501L2.80634 4.92974Z"
                  fill-rule="nonzero" transform="matrix(1 0 0 1 16.1179 0.00594889)" fill="rgb(0, 71, 55)" />
                <rect width="1.811142" height="11.392814" rx="0.36000001" ry="0.36000001"
                  transform="matrix(1 0 0 1 49.4145 1.6935)" fill="rgb(0, 71, 55)" />
                <path
                  d="M2.74058 0.000775291L0.947383 0.000775291C0.917613 0.000775291 0.892221 0.0114079 0.871207 0.032673C0.850193 0.0539381 0.83971 0.0795966 0.839759 0.109648L0.839759 9.58197C0.839759 12.5459 0.654427 13.9371 0.00291862 16.8193C-0.0045725 16.8536 0.00233489 16.8845 0.0236408 16.9122C0.044898 16.9399 0.0728681 16.9543 0.107551 16.9554L1.90075 16.9554C1.94287 16.9548 1.98018 16.9409 2.01268 16.9137C2.04512 16.8865 2.0656 16.852 2.07411 16.8102C2.35985 15.6279 2.5685 14.4319 2.70008 13.222C2.83162 12.0122 2.88495 10.7989 2.8601 9.58197L2.8601 0.109648C2.86024 0.0770615 2.84833 0.0498771 2.82434 0.0280951C2.80046 0.00628847 2.77254 -0.00281812 2.74058 0.000775291Z"
                  fill-rule="nonzero" transform="matrix(1 0 0 1 51.2917 0.0475911)" fill="rgb(0, 71, 55)" />
                <path
                  d="M9.10058 1.62409C9.13025 1.62409 9.15559 1.61345 9.17661 1.59219C9.19762 1.57092 9.20815 1.54527 9.2082 1.51521L9.2082 0.105846C9.20742 0.0763846 9.19655 0.0513784 9.17558 0.0308271C9.15472 0.0102757 9.12971 0 9.10058 0L0.107624 0C0.0784868 0 0.0534839 0.0102757 0.0326157 0.0308271C0.0116988 0.0513784 0.000826945 0.0763846 0 0.105846L0 1.51521C-4.86438e-05 1.54527 0.0104341 1.57092 0.0314482 1.59219C0.0524623 1.61345 0.0778544 1.62409 0.107624 1.62409L3.48783 1.62409L3.48783 3.19372L0.17935 3.19372C0.129928 3.19372 0.0877291 3.21144 0.0527542 3.24688C0.017682 3.28232 9.72876e-05 3.32509 0 3.37517L0 14.3688C-4.86438e-05 14.3988 0.0104341 14.4245 0.0314482 14.4457C0.0524623 14.467 0.0778544 14.4776 0.107624 14.4776L1.9576 14.4776C1.98737 14.4777 2.01276 14.467 2.03377 14.4458C2.05479 14.4245 2.06527 14.3988 2.06522 14.3688L2.06522 4.81781L3.48783 4.81781L3.48783 16.3558C3.48783 16.3858 3.49832 16.4115 3.51928 16.4327C3.54034 16.454 3.56574 16.4646 3.59546 16.4647L5.60384 16.4647C5.63351 16.4646 5.65888 16.454 5.67994 16.4327C5.70091 16.4115 5.71142 16.3858 5.71146 16.3558L5.71146 4.81781L6.79931 4.81781C6.89806 4.81778 6.98221 4.85326 7.05177 4.92424C7.12133 4.99522 7.15572 5.08072 7.15494 5.18072L7.15494 11.5319C7.16088 11.9656 7.13884 12.3979 7.08884 12.8287C7.03878 13.2595 6.9612 13.6851 6.85608 14.1056L6.8023 14.3597C6.79578 14.394 6.80347 14.4247 6.82536 14.4518C6.84725 14.4788 6.87544 14.4925 6.90993 14.4927L8.73604 14.4927C8.77821 14.4921 8.81555 14.4783 8.84804 14.4511C8.88044 14.4239 8.90089 14.3894 8.9094 14.3476C9.02046 13.8869 9.10277 13.4209 9.15632 12.9498C9.20978 12.4787 9.23408 12.006 9.22921 11.5319L9.22921 4.47299C9.22917 4.12388 9.10719 3.8259 8.86329 3.57904C8.61934 3.3322 8.3249 3.20878 7.97997 3.20878L5.74145 3.20878L5.74145 1.63915L9.10058 1.62409Z"
                  fill-rule="nonzero" transform="matrix(1 0 0 1 55.2101 0.538306)" fill="rgb(0, 71, 55)" />
                <path
                  d="M14.8299 5.3017L11.5423 5.3017C12.1087 4.75183 12.6296 4.16096 13.1052 3.52909C13.5808 2.89724 14.0052 2.23199 14.3786 1.53334C14.3963 1.49733 14.3947 1.46219 14.3739 1.4279C14.3531 1.39362 14.3227 1.37634 14.2829 1.37607L12.412 1.37607C12.3823 1.37609 12.3544 1.38337 12.3284 1.39789C12.3023 1.41238 12.2814 1.43233 12.2655 1.45773C11.7778 2.1788 11.2421 2.86129 10.6584 3.5052C10.0746 4.14911 9.44875 4.74794 8.78077 5.3017L7.07425 5.3017L7.07425 2.94873L10.4545 2.94873C10.4841 2.9487 10.5095 2.93806 10.5305 2.91679C10.5515 2.89555 10.562 2.86991 10.5621 2.83985L10.5621 1.48494C10.562 1.45486 10.5515 1.42921 10.5305 1.40797C10.5095 1.3867 10.4841 1.37607 10.4545 1.37607L7.07425 1.37607L7.07425 0.108873C7.07425 0.0794119 7.06413 0.0541104 7.04389 0.0329683C7.02356 0.0118263 6.9988 0.000836822 6.96962 0L5.03894 0C5.00985 0.00081221 4.98514 0.0117893 4.96481 0.0329314C4.94448 0.0540735 4.93431 0.0793873 4.93431 0.108873L4.93431 1.37607L1.55111 1.37607C1.52207 1.37688 1.49738 1.38786 1.47705 1.409C1.45671 1.43014 1.44652 1.45545 1.44647 1.48494L1.44647 2.83985C1.44652 2.86936 1.45671 2.89469 1.47705 2.91583C1.49738 2.93697 1.52207 2.94794 1.55111 2.94873L4.94029 2.94873L4.94029 5.3017L0.233126 5.3017C0.183606 5.3017 0.141335 5.31941 0.106311 5.35482C0.0712875 5.39027 0.0537758 5.43304 0.0537758 5.48315L0.0537758 6.92578C0.0537758 6.97587 0.0712875 7.01864 0.106311 7.05408C0.141335 7.08949 0.183606 7.10721 0.233126 7.10724L6.5273 7.10724C5.49605 7.86035 4.44374 8.58199 3.37036 9.27215C2.29699 9.9623 1.20442 10.6198 0.0926665 11.2446C0.0640153 11.2602 0.0413716 11.282 0.0247354 11.3102C0.0080992 11.3384 -0.000145931 11.369 0 11.4019L0 13.283C0.000243219 13.3248 0.0182414 13.3561 0.0539947 13.3769C0.0898452 13.3977 0.125647 13.3977 0.1614 13.3768C1.32301 12.7296 2.41886 12.0884 3.44895 11.4533L3.44895 15.7388C3.44904 16.088 3.57107 16.3859 3.81501 16.6328C4.05891 16.8796 4.35331 17.003 4.69819 17.0031L13.709 17.0031C13.7372 17.0022 13.7612 16.9916 13.781 16.971C13.8007 16.9505 13.8106 16.9259 13.8107 16.8972L13.8107 15.2973C13.8106 15.2689 13.8007 15.2447 13.7808 15.2246C13.761 15.2045 13.737 15.1945 13.709 15.1945L6.01916 15.1945C5.92032 15.1945 5.83612 15.159 5.76656 15.088C5.697 15.017 5.66265 14.9316 5.66353 14.8316L5.66353 13.7761C8.7 12.7236 11.6738 11.4322 13.3324 10.6791C13.3638 10.6642 13.3889 10.642 13.4077 10.6125C13.4266 10.5831 13.4364 10.5508 13.4371 10.5158L13.4371 8.81609C13.4374 8.77617 13.421 8.74539 13.3879 8.72376C13.3549 8.70212 13.3205 8.69964 13.2847 8.7163C12.0025 9.32118 8.91226 10.7003 5.66353 11.8617L5.66353 10.047C6.34192 9.59544 7.0079 9.12575 7.66148 8.63796C8.31496 8.15019 8.95504 7.64502 9.58172 7.12245L14.8239 7.12245C14.8733 7.12243 14.9156 7.1047 14.9506 7.06929C14.9856 7.03387 15.0032 6.99111 15.0032 6.941L15.0032 5.49836C15.0076 5.44653 14.9927 5.40119 14.9585 5.36236C14.9242 5.32349 14.8814 5.30327 14.8299 5.3017Z"
                  fill-rule="nonzero" transform="matrix(1 0 0 1 32.5616 0)" fill="rgb(0, 71, 55)" />
                <path
                  d="M1.73039 3.05158L1.09084 1.94162L0.493104 1.94162L0.493104 3.05158L0 3.05158L0 0L1.19547 0C1.46277 0.00167364 1.69079 0.0982896 1.87953 0.289848C2.06827 0.481406 2.16303 0.712431 2.1638 0.982921C2.16264 1.17805 2.10757 1.35612 1.99861 1.51713C1.88965 1.67812 1.74547 1.79443 1.56607 1.86605L2.25049 3.05162L1.73039 3.05158ZM0.504997 0.471783L0.504997 1.491L1.21627 1.491C1.3478 1.48071 1.45837 1.42657 1.54797 1.32859C1.63757 1.23061 1.6824 1.11486 1.68245 0.981334C1.6824 0.847811 1.63757 0.732071 1.54797 0.634114C1.45837 0.536157 1.3478 0.482046 1.21627 0.471783L0.504997 0.471783Z"
                  fill-rule="nonzero" transform="matrix(1 0 0 1 69.9562 1.56968)" fill="rgb(0, 71, 55)" />
                <path
                  d="M3.08135 6.23024C2.23086 6.23105 1.50475 5.92738 0.903026 5.31923C0.3013 4.71109 0.000291864 3.97671 0 3.11612C-0.000291864 2.25552 0.300279 1.52095 0.901712 0.912407C1.50305 0.303865 2.22894 -0.000270736 3.07938 0C3.92982 0.000270736 4.65554 0.304874 5.25654 0.913809C5.85753 1.52274 6.15759 2.25752 6.15671 3.11815C6.15506 3.9768 5.8542 4.70973 5.25413 5.31694C4.65415 5.92411 3.92989 6.22854 3.08135 6.23024ZM3.08135 0.384138C2.33856 0.384138 1.70458 0.649866 1.17942 1.18132C0.654163 1.71283 0.391559 2.35441 0.391608 3.10607C0.391559 3.85769 0.654115 4.49925 1.17927 5.03075C1.70453 5.56223 2.33858 5.82798 3.08142 5.82801C3.82412 5.82798 4.45807 5.56222 4.98328 5.03071C5.50849 4.49923 5.77111 3.85769 5.77116 3.10607C5.77111 2.35441 5.50849 1.71284 4.98328 1.18136C4.45807 0.649854 3.82409 0.384138 3.08135 0.384138Z"
                  fill-rule="nonzero" transform="matrix(1 0 0 1 67.8432 -0.00304362)" fill="rgb(0, 71, 55)" />
              </g>
            </svg>
          </div>
          <div class="watermark-text">
            <div class="watermark-title">feixianglaoshi.com</div>
          </div>
        </div>
        <div class="right-watermark-content">
          <!-- 跳转按钮 -->
          <button class="jump-button">
            立即体验
          </button>
        </div>

      </div>
    </div>
    <iframe class="content-iframe" srcdoc="&lt;!DOCTYPE html&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;b0da1562fa4841ec&quot; data-checksum=&quot;207f83b2&quot; data-env=&quot;production&quot; /&gt;
&lt;script&gt;var _bm_0799={build:&quot;ef8965c6&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 3fab12c1b9ba --&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 68 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;0cd8af766a19&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;2a1fb1f60c144417&quot; data-checksum=&quot;17a70263&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Security: SRI Hash 475101e78711446f --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:7da9509e */var _bm_be2f=[30,443,6594];&lt;/script&gt;
&lt;script&gt;var _bm_cbfe={build:&quot;811f58ac&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;3fea2a58&quot;&gt;Marker-1838&lt;/div&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;7faa0f5fb5294ac8&quot; data-checksum=&quot;9db36db2&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 935184 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- Security: SRI Hash 7e18a5915f6044b0 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;0287ae3534084744&quot; data-checksum=&quot;67a0808c&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;01f488ae9ad8&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Build: d4d9e31031bf | Webpack 5.88.2 --&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn3.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;7667f2b2308d&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:fbd9638d */var _bm_37d3=[61,311,6418];&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:bd38b4a8 */var _bm_4df0=[69,818,3987];&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 745355 --&gt;
&lt;!-- Build: 147926a12087 | Webpack 5.88.2 --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 53 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;5caae9af741d&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;32d19bd7&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;48d646&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;379a5d1cb21844e7&quot; data-checksum=&quot;bdee9de7&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;cf747c1a&quot;}&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;5c03f153f8e7&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 350713 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:3171511e */var _bm_86bd=[77,487,5855];&lt;/script&gt;
&lt;style data-module=&quot;2fcf881f&quot;&gt;._bm_bd69{width:0;height:0;overflow:hidden}._ck_8bb0{font-size:0;line-height:0}&lt;/style&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;var _bm_08ea={build:&quot;aae4a4ca&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- Security: SRI Hash b71371e2d3204604 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;b7b7c038&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style&gt;/* chunk:31db002c */@media print{._bm_2708{color:transparent}}&lt;/style&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: b18a7cfc4e43 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;486322&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;style&gt;/* chunk:dd86c1e0 */@media print{._bm_df5b{color:transparent}}&lt;/style&gt;
&lt;!-- Build: 21525e85ce75 | Webpack 5.88.2 --&gt;
&lt;!-- Feature Flag: disabled | Experiment: ac6f0909b680 --&gt;
&lt;!-- Build: 07677544249b | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;style data-module=&quot;0f1e8ec5&quot;&gt;._bm_7683{width:0;height:0;overflow:hidden}._ck_fae9{font-size:0;line-height:0}&lt;/style&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:e2aef5f4 */var _bm_6aad=[11,860,6641];&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9833 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;143dd7e9&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;88d2a1&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn3.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;213070&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;b810da74f73749a6&quot; data-checksum=&quot;f8dd32ef&quot; data-env=&quot;production&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_9933{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 654203 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;997477&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:de9f9aa2 */var _bm_3ebe=[34,435,8102];&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;667928&quot;&gt;&lt;/i&gt;
&lt;script&gt;// Feature flag: experiment_1bd2cf7d = disabled
var _bm_d89c=335146,_ck_aeab=&quot;281e969e1238&quot;;&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;e2bbf6dd&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;7cacbd8e&quot;}&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;4e5df7f05889&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;a9db467b86e343fd&quot; data-checksum=&quot;e887efe3&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;eed6ff66&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;54debb9652464614&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;edf2b5e3&quot;&gt;Marker-2227&lt;/div&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;b94b52fda214414f&quot; data-checksum=&quot;ecca153f&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;ce1cb025&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;746823&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 77 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;386066&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Build: cc982ce455b5 | Webpack 5.88.2 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;b7df10&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Analytics: GA4-7B53C3044729 | GTM-7B53C3 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;a4df81&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=2e4dde54&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;541c2c&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: e46081fed7eb --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 8164 --&gt;
&lt;!-- Feature Flag: enabled | Experiment: 289c5d1776d6 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;90d457df&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style data-module=&quot;2c4a7f9a&quot;&gt;._bm_a562{width:0;height:0;overflow:hidden}._ck_9085{font-size:0;line-height:0}&lt;/style&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;bf8331&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;702582&quot;&gt;&lt;/i&gt;
&lt;!-- Security: SRI Hash 31348ebf2890404c --&gt;
&lt;style&gt;@media(max-width:0px){._bm_a6ba{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;126f388c55694e68&quot; data-checksum=&quot;4b62d8ff&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 5233 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;64981401&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;531333&quot;&gt;&lt;/i&gt;
&lt;!-- Security: SRI Hash a8a98a8ce4424843 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:d00a5a27 */var _bm_0848=[82,594,5716];&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;88ec38d12e45&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_b11078fc = enabled
var _bm_4bc4=176911,_ck_41ea=&quot;25a35158535d&quot;;&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;307969&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=0f373b5c&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-34007 */var _bm_79b4=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 4c9cae32028b --&gt;
&lt;!-- Security: SRI Hash 9181e22cb5d04db2 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;585141&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;508509&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;580606&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;6b261577&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;615023&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;var _bm_5900={build:&quot;7f487299&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;560408&quot; /&gt;
&lt;!-- Security: SRI Hash f39951bfd8f04371 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;528594&quot;&gt;&lt;/i&gt;
&lt;style&gt;/* chunk:157eeb46 */@media print{._bm_e809{color:transparent}}&lt;/style&gt;
&lt;style&gt;@media(max-width:0px){._bm_1667{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style&gt;@media(max-width:0px){._bm_c377{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;605227&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;308f114c&quot; /&gt;
&lt;!-- Analytics: GA4-FF24223C73EC | GTM-FF2422 --&gt;
&lt;style data-module=&quot;ebd63b8c&quot;&gt;._bm_92e6{width:0;height:0;overflow:hidden}._ck_66e8{font-size:0;line-height:0}&lt;/style&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- Security: SRI Hash 645cc4a6cb9c4808 --&gt;
&lt;!-- Analytics: GA4-7AA75ABD558B | GTM-7AA75A --&gt;
&lt;style data-build=&quot;6ee4e5&quot;&gt;._bm_b534{display:none}._ck_5f6e{visibility:hidden}&lt;/style&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;9d759a61&quot;&gt;Marker-8462&lt;/div&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;732318&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 76 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;102599&quot;&gt;&lt;/i&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=177d070e&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;438978&quot; /&gt;
&lt;!-- Security: SRI Hash 4b6fdcf213114785 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;b7c4c82ce01e&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;463e7bd0&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=9ee1734d&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;7d3364ef1cef4e16&quot; data-checksum=&quot;dd484dc8&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 124164 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;919303&quot;&gt;&lt;/i&gt;
&lt;!-- Build: b6c1bfd752fd | Webpack 5.88.2 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;bfa475b0&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Build: f9419e1f9d82 | Webpack 5.88.2 --&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 20 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;525343&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: d52cbe065a44 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=aef92876&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;template id=&quot;metadata-8edab5&quot;&gt;&lt;div data-build=&quot;8edab580&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;template id=&quot;metadata-72e7d1&quot;&gt;&lt;div data-build=&quot;72e7d1a4&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 1696 --&gt;
&lt;template id=&quot;metadata-8cee60&quot;&gt;&lt;div data-build=&quot;8cee60f8&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-67778 */var _bm_4054=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;fe6facf9756a4bd2&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-33227 */var _bm_4330=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;baa813&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;0f01658b3fba&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;548949&quot;&gt;&lt;/i&gt;
&lt;template id=&quot;metadata-26b9d9&quot;&gt;&lt;div data-build=&quot;26b9d92d&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;681739&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;ee633635&quot; /&gt;
&lt;script&gt;var _bm_f1cc={build:&quot;64c4389f&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;57bc10&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3874 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3138 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_cfdc2aac = enabled
var _bm_68c9=905048,_ck_16d7=&quot;1179a28bfa3e&quot;;&lt;/script&gt;
&lt;script&gt;var _bm_5f37={build:&quot;6b108e5f&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;style data-module=&quot;8e666dde&quot;&gt;._bm_8116{width:0;height:0;overflow:hidden}._ck_b4c7{font-size:0;line-height:0}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;461770&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;2082bdb7&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 9a3cee728394 --&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn4.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;d1182235&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style data-module=&quot;daf41e19&quot;&gt;._bm_8b54{width:0;height:0;overflow:hidden}._ck_ba78{font-size:0;line-height:0}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;789332&quot;&gt;&lt;/i&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;422647&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 91 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;527744be&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;5b004171&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;415829&quot; /&gt;
&lt;!-- Security: SRI Hash 8082f09f059e4e49 --&gt;
&lt;!-- Analytics: GA4-693F8F77D8ED | GTM-693F8F --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;01e70693&quot;&gt;Marker-5715&lt;/div&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn3.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 724fca8afb3f --&gt;
&lt;!-- Security: SRI Hash 7b5d2f7245114f9f --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;04816dac&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;fb4a8f&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;2505564f&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;6ae490d2c465&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Build: dd07a7d66f5f | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;197257&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_bc003559 = enabled
var _bm_21fe=653330,_ck_d06e=&quot;5c358b98453d&quot;;&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;079c6bea&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;50ec9f6b4d14&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;e100adeb&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;710d75e0&quot;&gt;Marker-6229&lt;/div&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;3bdf236a&quot;&gt;Marker-5192&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;d68a09d069374c0c&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;bd67a6&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style&gt;/* chunk:4abb50c8 */@media print{._bm_1451{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;4e6ac2c17128&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Build: 3617476d1c28 | Webpack 5.88.2 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=5d6fbb36&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;60009bea&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;ad5bcbf6&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;10ad7a13&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:7613b223 */var _bm_9778=[12,645,8768];&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: c6d72051241c --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;35764768&quot;&gt;Marker-2694&lt;/div&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn2.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;style data-build=&quot;9b6f1f&quot;&gt;._bm_ac64{display:none}._ck_d0a5{visibility:hidden}&lt;/style&gt;
&lt;!-- Feature Flag: enabled | Experiment: f262a7ccc6b1 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;9d9ee5&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style&gt;/* chunk:fe509c1c */@media print{._bm_1edc{color:transparent}}&lt;/style&gt;
&lt;!-- Security: SRI Hash e511ef010f514bb6 --&gt;
&lt;!-- Analytics: GA4-4484C0182CE3 | GTM-4484C0 --&gt;
&lt;!-- Build: 2a822a8260c2 | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;164383&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn1.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-55031 */var _bm_00db=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;123328&quot;&gt;&lt;/i&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 4491 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;e9572b27&quot;&gt;Marker-9684&lt;/div&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 35 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;319990&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;2c8f3f7674ec49f5&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash 6d03750582094358 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-23838 */var _bm_bb7b=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;style&gt;/* chunk:6e25c426 */@media print{._bm_b266{color:transparent}}&lt;/style&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=2a64b0b7&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- Feature Flag: disabled | Experiment: a3864a21b47b --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 653196 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 5af81df9e583 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;802427&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;566da0b8fac74907&quot; data-checksum=&quot;2429cb3e&quot; data-env=&quot;production&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_16b16cc9 = disabled
var _bm_693e=260906,_ck_afa2=&quot;ca274f66c049&quot;;&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;0c81ca38ce72&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Analytics: GA4-C4493E1444C3 | GTM-C4493E --&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 79 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 1656 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 9be1769a1e87 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;6ded9f9fb47d&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;6693f8&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 062071607c22 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;4ecea84a&quot;&gt;Marker-7100&lt;/div&gt;
&lt;!-- Security: SRI Hash b24139981c5f41af --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_2e5a{opacity:0;position:absolute}}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;7c9638c6&quot;&gt;Marker-6869&lt;/div&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;eeb65253&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 46 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;7bde8c5e6dfb4263&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;1e88d3e8&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;91a1bb35&quot;&gt;Marker-9414&lt;/div&gt;
&lt;style data-build=&quot;6d6698&quot;&gt;._bm_b9b4{display:none}._ck_bc0d{visibility:hidden}&lt;/style&gt;
&lt;!-- Build: b93756af7649 | Webpack 5.88.2 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-27871 */var _bm_5fbc=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script&gt;var _bm_1b5b={build:&quot;b3ed9d47&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;template id=&quot;metadata-9b6d0f&quot;&gt;&lt;div data-build=&quot;9b6d0f0b&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;style data-build=&quot;19a108&quot;&gt;._bm_1b79{display:none}._ck_8eb2{visibility:hidden}&lt;/style&gt;
&lt;!-- Build: 484755bf1bd6 | Webpack 5.88.2 --&gt;
&lt;script&gt;// Feature flag: experiment_3cd7ea7f = enabled
var _bm_711e=184974,_ck_9ca4=&quot;8f0e31274d9a&quot;;&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;0b8b99&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;5975a1a8&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;938089&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;a629998a721a4e4a&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash 1c2eae2d736148ff --&gt;
&lt;script&gt;var _bm_5642={build:&quot;8e8e1137&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;template id=&quot;metadata-5e4fe7&quot;&gt;&lt;div data-build=&quot;5e4fe72c&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;89e27feaf38b&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 227a35a2e12f --&gt;
&lt;style&gt;/* chunk:8d116bd8 */@media print{._bm_d484{color:transparent}}&lt;/style&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;484e69ef1b144117&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;8d31a1d1a021&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Security: SRI Hash add4bfe2773f40b1 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;35eda539&quot;&gt;Marker-4772&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;d1e5a7e167ac4b4a&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;4b659986&quot; /&gt;
&lt;!-- Security: SRI Hash 8a769e078be849d6 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;ee3bb3&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style&gt;@media(max-width:0px){._bm_1bb1{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style data-module=&quot;c0e875bc&quot;&gt;._bm_05dc{width:0;height:0;overflow:hidden}._ck_d972{font-size:0;line-height:0}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;352868&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;template id=&quot;metadata-193be9&quot;&gt;&lt;div data-build=&quot;193be90f&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 543077 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 54cd9de2a820 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 7ca4597d96b9 --&gt;
&lt;!-- Build: ff285017ce1f | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;297000&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 607751 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;242a28&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;80be2eebb965&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Feature Flag: enabled | Experiment: e20725e447f8 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;597c1576&quot;}&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;3fe4cd24fbe2&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:988085a4 */var _bm_c7d7=[15,997,5909];&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;78d82006&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=bdb43ddd&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script&gt;// Feature flag: experiment_774acbb8 = enabled
var _bm_821e=891581,_ck_76c3=&quot;4625b559aa8d&quot;;&lt;/script&gt;
&lt;template id=&quot;metadata-388879&quot;&gt;&lt;div data-build=&quot;38887979&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:0ef6b07d */var _bm_1265=[60,410,1156];&lt;/script&gt;
&lt;!-- Security: SRI Hash 67d7c127cd684828 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;a3873773&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style data-module=&quot;e93588df&quot;&gt;._bm_c044{width:0;height:0;overflow:hidden}._ck_d1f4{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Feature Flag: enabled | Experiment: 1d1bdd6f367e --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;367170&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;b2f054943c964d18&quot; data-checksum=&quot;5b550509&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Analytics: GA4-E20DB9F9E024 | GTM-E20DB9 --&gt;
&lt;style data-build=&quot;48548e&quot;&gt;._bm_4f14{display:none}._ck_63a2{visibility:hidden}&lt;/style&gt;
&lt;style data-build=&quot;fd8ccc&quot;&gt;._bm_dbea{display:none}._ck_f8e6{visibility:hidden}&lt;/style&gt;
&lt;!-- Feature Flag: disabled | Experiment: cb811d8d47eb --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 5560 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;80ffeb54b0404f6e&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style data-build=&quot;d90b57&quot;&gt;._bm_f67f{display:none}._ck_7b46{visibility:hidden}&lt;/style&gt;
&lt;!-- Security: SRI Hash ab7fadc2193e48b2 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: a1325b632d79 --&gt;
&lt;!-- Security: SRI Hash 64019c4d38164c3d --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;var _bm_5051={build:&quot;ec7c597c&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;18bbd36063cd4d25&quot; data-checksum=&quot;62e155f9&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;fb9fc9d3f3844dd1&quot; data-checksum=&quot;2a18be00&quot; data-env=&quot;production&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;fe6a40c6&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:8a9a83ea */var _bm_c7a8=[78,167,7273];&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;119021&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:8b2199bf */var _bm_5b14=[55,215,5376];&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;816957&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;f5444c61ad0c&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-55320 */var _bm_dcf7=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: d80b8f663699 --&gt;
&lt;script&gt;var _bm_21c1={build:&quot;1120b841&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;832848&quot;&gt;&lt;/i&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 508571 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;8102612f&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 352244 --&gt;
&lt;!-- Build: 2a1f8ed1e1bd | Webpack 5.88.2 --&gt;
&lt;template id=&quot;metadata-0449fd&quot;&gt;&lt;div data-build=&quot;0449fd5c&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Build: 1286e1db1889 | Webpack 5.88.2 --&gt;
&lt;template id=&quot;metadata-bead50&quot;&gt;&lt;div data-build=&quot;bead50be&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Security: SRI Hash e4d78bd9c45b4784 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;86313cd0f42c&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;var _bm_c2dd={build:&quot;b50b5983&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;3db88ee2a83e40b1&quot; data-checksum=&quot;49eee352&quot; data-env=&quot;production&quot; /&gt;
&lt;script&gt;var _bm_9636={build:&quot;24360a83&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;54c5d833&quot;}&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 4105 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;91d34bcb&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;1ed211&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;var _bm_82c7={build:&quot;cacf4a13&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;fae7e5ac71984d04&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 12 --&gt;
&lt;!-- Analytics: GA4-748E8E928176 | GTM-748E8E --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;c7d49fd91ccc&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Build: 74109aeb1668 | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;dbaac77604424612&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;!-- Analytics: GA4-066293409422 | GTM-066293 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3932 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;aa2d9c858c27&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;450fec722ee54fdb&quot; data-checksum=&quot;447a97a9&quot; data-env=&quot;production&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;fa4645&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;b12a8b12&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;5ad7b2e6&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;fa8e2eec&quot;}&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;379677d3&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-26352 */var _bm_9b39=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_8f686acd = disabled
var _bm_4dee=974024,_ck_f113=&quot;1ba64852ffe5&quot;;&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:98684058 */var _bm_cfbf=[23,190,8128];&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;167038&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: 5154702be799 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;dd10f535&quot;}&lt;/script&gt;
&lt;!-- Build: faf661e2c142 | Webpack 5.88.2 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;cffd0b&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;03a2a6496c8f4771&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;f357654b8f06452a&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;364598&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;cc089b5c602a4caa&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;287791&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;c146d27a&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;a41e3c14&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;6638d5f387084708&quot; data-checksum=&quot;9c76ca0a&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Security: SRI Hash a14015149d1c42e0 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;27b9d7&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-80226 */var _bm_1129=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script&gt;var _bm_16c3={build:&quot;3d8b088a&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:4aef2beb */var _bm_efa4=[49,655,6776];&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_ba52{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style data-module=&quot;62532dfa&quot;&gt;._bm_d473{width:0;height:0;overflow:hidden}._ck_17e9{font-size:0;line-height:0}&lt;/style&gt;
&lt;style data-module=&quot;97152825&quot;&gt;._bm_350f{width:0;height:0;overflow:hidden}._ck_382b{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;f82cd2104fd84058&quot; data-checksum=&quot;50074871&quot; data-env=&quot;production&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;197283&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-23122 */var _bm_e7cb=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;5f2e083bccfb43d1&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;9abd39e9c9b7477d&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;361738&quot; /&gt;
&lt;!-- Security: SRI Hash 9e5b8cda674d48f4 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;f661699fab1a43e2&quot; data-checksum=&quot;41b3da13&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Security: SRI Hash ccc9d29340564a80 --&gt;
&lt;style data-build=&quot;0142ff&quot;&gt;._bm_fa3c{display:none}._ck_1079{visibility:hidden}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;328260&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;b41aec2d935842cc&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;49f70e&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;script&gt;var _bm_2b5f={build:&quot;8deb8a00&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;dd01f207&quot;&gt;Marker-7157&lt;/div&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 835516 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:318750b6 */var _bm_c9ea=[59,871,8393];&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;310472&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;d8086918&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;a8eda9bd062c&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;9e5352c5&quot; /&gt;
&lt;style&gt;/* chunk:0f80e9a5 */@media print{._bm_0d65{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;7b9d585a5338&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;f9d501a12bbb&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;var _bm_537e={build:&quot;6b589fe2&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 14 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;860414&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;c827c85fbbe0&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;ae2206&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;caf800cd&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;d2f596c6&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;788208&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 0d271de168de --&gt;
&lt;style&gt;/* chunk:12023eda */@media print{._bm_5d28{color:transparent}}&lt;/style&gt;
&lt;style&gt;@media(max-width:0px){._bm_4199{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style&gt;/* chunk:b323c880 */@media print{._bm_94a8{color:transparent}}&lt;/style&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 8d88fa0a393f --&gt;
&lt;script&gt;var _bm_813e={build:&quot;d55a722c&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;187394&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;d2ec8f17417b468e&quot; data-checksum=&quot;a0308bad&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Security: SRI Hash 35c2a25f9ff542ed --&gt;
&lt;style data-module=&quot;ad91c370&quot;&gt;._bm_4002{width:0;height:0;overflow:hidden}._ck_dbec{font-size:0;line-height:0}&lt;/style&gt;
&lt;script&gt;var _bm_3779={build:&quot;9107765e&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;406574&quot; /&gt;
&lt;!-- Build: 28da4b448743 | Webpack 5.88.2 --&gt;
&lt;!-- Analytics: GA4-E23CF049912C | GTM-E23CF0 --&gt;
&lt;!-- Build: 4e2d6fbbdf9a | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: de69005b7f84 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;69742578&quot;&gt;Marker-2522&lt;/div&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: e9e3621b66b4 --&gt;
&lt;script&gt;// Feature flag: experiment_c5e829a6 = disabled
var _bm_65a1=313533,_ck_5d64=&quot;5a54b36474dc&quot;;&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;style data-build=&quot;d1b0b5&quot;&gt;._bm_50c1{display:none}._ck_7ce2{visibility:hidden}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;284871&quot;&gt;&lt;/i&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;ee29b8a9&quot;&gt;Marker-5002&lt;/div&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;539f1617&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 175558 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_2c28{opacity:0;position:absolute}}&lt;/style&gt;
&lt;html lang=&quot;zh-CN&quot;&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;6622dc03&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;922571&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=92e95f23&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-95200 */var _bm_043b=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;style&gt;/* chunk:e857cb44 */@media print{._bm_a7c2{color:transparent}}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;171772&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn5.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;7b06e0b7&quot;&gt;Marker-3615&lt;/div&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;ca3ed15f&quot;}&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;519477&quot;&gt;&lt;/i&gt;
&lt;!-- Build: ad0bb19bf453 | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;911843&quot; /&gt;
&lt;!-- Analytics: GA4-BE6315489A49 | GTM-BE6315 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=54dbf138&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;2356974923fc47e3&quot; data-checksum=&quot;986f4a73&quot; data-env=&quot;production&quot; /&gt;
&lt;template id=&quot;metadata-ead4f2&quot;&gt;&lt;div data-build=&quot;ead4f23e&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=5b72cc8c&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;1ae8480693d5&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;template id=&quot;metadata-6c5248&quot;&gt;&lt;div data-build=&quot;6c52486d&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script&gt;// Feature flag: experiment_2ae48d21 = disabled
var _bm_df1f=746744,_ck_f59c=&quot;05c6ee2aacfe&quot;;&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;659559&quot; /&gt;
&lt;!-- Build: fab9c40172e0 | Webpack 5.88.2 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;385791&quot;&gt;&lt;/i&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 16266cdef88e --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;841021&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: 02ab526ca34f --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;305979&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 5f6579bc4182 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;99a7273e&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_00ef{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;975671&quot; /&gt;
&lt;!-- Feature Flag: enabled | Experiment: 06bd2422bd93 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;5036d1dc&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;5a871b4e6f224e23&quot; data-checksum=&quot;dc4c2b35&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Build: 352997cd1f4c | Webpack 5.88.2 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;794245&quot;&gt;&lt;/i&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=55262ed6&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;469426&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;e05a56&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 406456 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;f1ec6de1&quot;}&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;62a309f7&quot;&gt;Marker-4680&lt;/div&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;957272&quot; /&gt;
&lt;script&gt;var _bm_a3b0={build:&quot;c1cb973e&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;623295&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;600096&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;27067023e24d&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:9f17f5b3 */var _bm_411d=[32,429,2294];&lt;/script&gt;
&lt;style data-build=&quot;ed2521&quot;&gt;._bm_bc52{display:none}._ck_3156{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;f2c84c33&quot; /&gt;
&lt;style data-module=&quot;724bcfd4&quot;&gt;._bm_c32b{width:0;height:0;overflow:hidden}._ck_0afe{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;8a990eb1abe4&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2713 --&gt;
&lt;template id=&quot;metadata-51ed99&quot;&gt;&lt;div data-build=&quot;51ed99e8&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Analytics: GA4-4B48CC8E1845 | GTM-4B48CC --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 501069 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;a591a127&quot;&gt;Marker-1236&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;998220&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;d15c16&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;8a520dde&quot; /&gt;
&lt;style&gt;/* chunk:8df8c219 */@media print{._bm_9f5e{color:transparent}}&lt;/style&gt;
&lt;!-- Analytics: GA4-6738B08253AA | GTM-6738B0 --&gt;
&lt;!-- Security: SRI Hash 098c135b8e934336 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;336582&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;5665ef42&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:62f0084a */var _bm_e9a4=[47,627,9429];&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;1ee9bfa085eb4e80&quot; data-checksum=&quot;155bb322&quot; data-env=&quot;production&quot; /&gt;
&lt;style data-module=&quot;dd6ff667&quot;&gt;._bm_6641{width:0;height:0;overflow:hidden}._ck_a55f{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;9ea76aebe190&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Feature Flag: enabled | Experiment: e8d05ce8e51f --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;255878&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;248b06055d774c90&quot; data-checksum=&quot;7de32c26&quot; data-env=&quot;production&quot; /&gt;
&lt;style data-build=&quot;9bdb80&quot;&gt;._bm_088c{display:none}._ck_6da5{visibility:hidden}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;cb4db1f7b3874e5f&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;7e77df26&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 19 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;706807&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;191282b1f402&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-63732 */var _bm_9d4e=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;template id=&quot;metadata-e02720&quot;&gt;&lt;div data-build=&quot;e02720b0&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Security: SRI Hash a66183661df245b6 --&gt;
&lt;style&gt;/* chunk:4b90bae0 */@media print{._bm_74d9{color:transparent}}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;104860&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:19856e65 */var _bm_21f5=[34,282,7254];&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;713721&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;575f2681ab9c&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;0c46f3f8ad1841e6&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 29 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;716855&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;9e0ac999&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: b92094e837b0 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;e20060ff&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;806701&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;cf611784&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;242053&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_8ed79565 = disabled
var _bm_017e=352454,_ck_bdfa=&quot;4f7c3d877e68&quot;;&lt;/script&gt;
&lt;style data-module=&quot;1e60cd2f&quot;&gt;._bm_112e{width:0;height:0;overflow:hidden}._ck_412e{font-size:0;line-height:0}&lt;/style&gt;
&lt;style&gt;/* chunk:33953799 */@media print{._bm_f310{color:transparent}}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;0e672bca&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash cd35268deb4b4fd6 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;d1f22a63cacd4454&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;864764&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;698452&quot;&gt;&lt;/i&gt;
&lt;style&gt;@media(max-width:0px){._bm_ffe5{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;f3617304c3c34927&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash aff5b89d814c42f1 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;71897d37c21d4209&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=43bbd115&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;343431&quot;&gt;&lt;/i&gt;
&lt;!-- Build: f49939b4934e | Webpack 5.88.2 --&gt;
&lt;script&gt;var _bm_235f={build:&quot;54ccf76b&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;c0f40a4b&quot;}&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_73388c0e = disabled
var _bm_ac83=538567,_ck_e83e=&quot;b509cd2f6bb8&quot;;&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn4.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;style data-build=&quot;bef748&quot;&gt;._bm_55c5{display:none}._ck_652e{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;2bb3684d&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;221a1630&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;5c9397a769124d5f&quot; data-checksum=&quot;d9003349&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 2 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;758b1cc2&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_1925{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;dc547b28&quot;&gt;Marker-6508&lt;/div&gt;
&lt;style data-build=&quot;7f93ec&quot;&gt;._bm_b370{display:none}._ck_cf47{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;491926&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 97 --&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 64 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;28343bbb&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=9cfcd1c6&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 301830 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;691540&quot; /&gt;
&lt;style&gt;/* chunk:8c13b7e8 */@media print{._bm_7479{color:transparent}}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;e9eefa7f&quot;}&lt;/script&gt;
&lt;template id=&quot;metadata-3fc7d5&quot;&gt;&lt;div data-build=&quot;3fc7d529&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 443662 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 437233 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;443323&quot;&gt;&lt;/i&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: f42aa6dd84e3 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;c7f66d7d0b2a&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;e3b8cb2a&quot; /&gt;
&lt;template id=&quot;metadata-dc172e&quot;&gt;&lt;div data-build=&quot;dc172ec8&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Analytics: GA4-60A40B90D33B | GTM-60A40B --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;6f35379f&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;var _bm_48cd={build:&quot;0d1bfeed&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:39c3edc2 */var _bm_516d=[46,272,2301];&lt;/script&gt;
&lt;style data-build=&quot;c3e2f7&quot;&gt;._bm_a7b1{display:none}._ck_a604{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;script&gt;var _bm_7787={build:&quot;06c7790c&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;3488879f8d4647ff&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;db8bb0e523a2&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;858444&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: a9af89a88a43 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;425093&quot;&gt;&lt;/i&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9515 --&gt;
&lt;style&gt;/* chunk:d65b954c */@media print{._bm_8296{color:transparent}}&lt;/style&gt;
&lt;script&gt;// Feature flag: experiment_72a25012 = enabled
var _bm_aae2=857919,_ck_2b16=&quot;9f9dfeac6e3d&quot;;&lt;/script&gt;
&lt;!-- Build: e0b7fe188735 | Webpack 5.88.2 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;748000&quot;&gt;&lt;/i&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;889915&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;100420&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 52 --&gt;
&lt;style data-module=&quot;4e1ee79b&quot;&gt;._bm_d3c5{width:0;height:0;overflow:hidden}._ck_b25f{font-size:0;line-height:0}&lt;/style&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;56fe3f&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;701703&quot;&gt;&lt;/i&gt;
&lt;style&gt;@media(max-width:0px){._bm_e260{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;31ecc8ac0374&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_9c26ee64 = enabled
var _bm_19d4=456018,_ck_2ae1=&quot;4cf414ac8ba7&quot;;&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 6294 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;977314&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;42a55843&quot;&gt;Marker-1597&lt;/div&gt;
&lt;style&gt;/* chunk:0dc4aeb2 */@media print{._bm_268d{color:transparent}}&lt;/style&gt;
&lt;style data-build=&quot;49d9a7&quot;&gt;._bm_d724{display:none}._ck_f973{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;680824&quot; /&gt;
&lt;style&gt;/* chunk:4bf6b033 */@media print{._bm_50f0{color:transparent}}&lt;/style&gt;
&lt;template id=&quot;metadata-1307ea&quot;&gt;&lt;div data-build=&quot;1307ea2e&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;style data-build=&quot;4a7984&quot;&gt;._bm_180e{display:none}._ck_0062{visibility:hidden}&lt;/style&gt;
&lt;!-- Build: a46f00e5effb | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;391c6effe41f4f43&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;bef68fa63eb14e20&quot; data-checksum=&quot;88a1cadf&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 145228 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;8c4b54a2&quot; /&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn9.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;style data-module=&quot;630a437d&quot;&gt;._bm_a58c{width:0;height:0;overflow:hidden}._ck_5e3f{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Build: 4d2763a743b1 | Webpack 5.88.2 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-89144 */var _bm_b252=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;3b6c5cfc&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Security: SRI Hash af13d21f48e64a34 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;610f3c12&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;template id=&quot;metadata-b12073&quot;&gt;&lt;div data-build=&quot;b12073b2&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Security: SRI Hash 429a626eb4e0480f --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;173e544a&quot;&gt;Marker-1804&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;fc57ffe5e02c4d6a&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;786741dcea904912&quot; data-checksum=&quot;638f41bf&quot; data-env=&quot;production&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-77911 */var _bm_3a2b=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;dbd76a09&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;274254&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2415 --&gt;
&lt;style&gt;/* chunk:015343d0 */@media print{._bm_bf98{color:transparent}}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;5351ad13&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;47576edb0f5e&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;2d5f06b5&quot;&gt;Marker-7287&lt;/div&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:12139bb0 */var _bm_bafd=[34,985,9756];&lt;/script&gt;
&lt;!-- Build: 24103d2a3172 | Webpack 5.88.2 --&gt;
&lt;template id=&quot;metadata-0e1301&quot;&gt;&lt;div data-build=&quot;0e1301d2&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;44b8b9f1&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;482599&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;614756&quot; /&gt;
&lt;style data-build=&quot;01e120&quot;&gt;._bm_cc51{display:none}._ck_8f37{visibility:hidden}&lt;/style&gt;
&lt;style data-module=&quot;9591e2d8&quot;&gt;._bm_94d3{width:0;height:0;overflow:hidden}._ck_ebc9{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Analytics: GA4-002D4127B94E | GTM-002D41 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;9abc19ce&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: 846facc99868 --&gt;
&lt;!-- Feature Flag: disabled | Experiment: a0b461f56799 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;32172e9ece0c&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;377621&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;77af56&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn6.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;202004&quot;&gt;&lt;/i&gt;
&lt;script&gt;var _bm_e43a={build:&quot;4f2ebb6d&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;7e1d5d65158641c0&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;06add097c3944033&quot; data-checksum=&quot;65ee9656&quot; data-env=&quot;production&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;1b05f57d&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 44 --&gt;
&lt;!-- Security: SRI Hash cd353b7466164b05 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;5b4b230e&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Analytics: GA4-BF13B4F5D3CC | GTM-BF13B4 --&gt;
&lt;!-- Build: 29858c33c190 | Webpack 5.88.2 --&gt;
&lt;!-- Feature Flag: enabled | Experiment: be385b4c0e52 --&gt;
&lt;style data-build=&quot;04c288&quot;&gt;._bm_3ab3{display:none}._ck_d8bf{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;35c4a2b2&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;ca4b2a8b69e044ef&quot; data-checksum=&quot;033ffb9c&quot; data-env=&quot;production&quot; /&gt;
&lt;style&gt;/* chunk:17a5914a */@media print{._bm_51aa{color:transparent}}&lt;/style&gt;
&lt;script&gt;// Feature flag: experiment_62b35f27 = enabled
var _bm_a8fd=423023,_ck_7ed1=&quot;1c0d1caaf566&quot;;&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;9f9c46c8&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;3a0b39ac&quot;&gt;Marker-6628&lt;/div&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;e1984356&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;b83c53adc4964061&quot; data-checksum=&quot;f02ef24b&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 66 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;118e9598&quot;&gt;Marker-6150&lt;/div&gt;
&lt;!-- Build: 32201624b1a9 | Webpack 5.88.2 --&gt;
&lt;script&gt;var _bm_41da={build:&quot;07d43afa&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;template id=&quot;metadata-6a11c9&quot;&gt;&lt;div data-build=&quot;6a11c900&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;f4c4ef&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;816526&quot;&gt;&lt;/i&gt;
&lt;script&gt;var _bm_78cd={build:&quot;064d9f0b&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;style data-build=&quot;6ffa2b&quot;&gt;._bm_a080{display:none}._ck_4166{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;764683&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;fd61b39fa9854af5&quot; data-checksum=&quot;b1d3d800&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;55641e2eec794377&quot; data-checksum=&quot;39700d1b&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;c6354e34&quot; /&gt;
&lt;template id=&quot;metadata-9b3233&quot;&gt;&lt;div data-build=&quot;9b32334d&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;13b2b2e3&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;683680&quot;&gt;&lt;/i&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 36573a23a791 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 4524b4b12ca7 --&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn8.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;af448a2c3561430d&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-D76C3CAC80E5 | GTM-D76C3C --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 29 --&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 8 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;11c7b4e5c19c482e&quot; data-checksum=&quot;8ff13102&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Security: SRI Hash a82f47425a0349cc --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;742645&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;6b96fdf1bbfc41ea&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;297631&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 15d8e5511a2e --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;6d88bc0e&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-B1379555D338 | GTM-B13795 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn9.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 98 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 319aca053556 --&gt;
&lt;template id=&quot;metadata-d6cea8&quot;&gt;&lt;div data-build=&quot;d6cea8a3&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Build: 19c2d519d01e | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c884091cd3ab4a3b&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style data-build=&quot;cf9d60&quot;&gt;._bm_bd87{display:none}._ck_c38b{visibility:hidden}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 942977 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;454152&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;114492&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;131239&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Build: 5ab9d9819cc3 | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;29308dd1f3f64661&quot; data-checksum=&quot;7df9ff56&quot; data-env=&quot;production&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:691fdf70 */var _bm_4faf=[80,505,6493];&lt;/script&gt;
&lt;!-- Security: SRI Hash 950e2d4246764de7 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;4988a2&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;04cafc9d4f254d34&quot; data-checksum=&quot;ef36f18b&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Analytics: GA4-786ECA8C24D4 | GTM-786ECA --&gt;
&lt;script&gt;var _bm_685a={build:&quot;df5b8fec&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- Security: SRI Hash 504cfd5395e14386 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;ff2813fe893d434b&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 37 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 9558c569a3ae --&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 11 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;105156&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 93 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;a05f81&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;fa1d0d&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;558726&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Build: 0b8c82d8bb51 | Webpack 5.88.2 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=8124f91c&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;style&gt;/* chunk:d4d19a2b */@media print{._bm_e6b1{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;9498b27aa0a4&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;826383&quot;&gt;&lt;/i&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 241219 --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 28 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;4df0c8fdae614414&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;edb1acf742ca4d65&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;98608eb5&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: 1fdfd99d99f4 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_a46b{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;2289ede3&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;2656021f&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;6dd2b1&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;922779&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;90d20f97b4df4a33&quot; data-checksum=&quot;d9c15275&quot; data-env=&quot;production&quot; /&gt;
&lt;style&gt;/* chunk:24e1991a */@media print{._bm_ec0e{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;766657&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;428abba05e4d4d55&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=074cc82f&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script&gt;var _bm_8463={build:&quot;4d5a9607&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;style data-module=&quot;16e5557c&quot;&gt;._bm_fb9d{width:0;height:0;overflow:hidden}._ck_49b7{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: 4e8cad54e29e --&gt;
&lt;style data-build=&quot;3de613&quot;&gt;._bm_743b{display:none}._ck_3d01{visibility:hidden}&lt;/style&gt;
&lt;!-- Security: SRI Hash 3b01b42720aa4686 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;b0bf23e5b89e402a&quot; data-checksum=&quot;4cc27b59&quot; data-env=&quot;production&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;2f334c&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;f40e0fba&quot;}&lt;/script&gt;
&lt;style data-build=&quot;d07301&quot;&gt;._bm_0bbd{display:none}._ck_acb1{visibility:hidden}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;86bf0a42aa4d402d&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;646407&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;510275fe90d1&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style data-module=&quot;c714ce66&quot;&gt;._bm_b183{width:0;height:0;overflow:hidden}._ck_3ef5{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 138660 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 94f7192d7882 --&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn7.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;script&gt;var _bm_0be9={build:&quot;1c0e10e5&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- Analytics: GA4-684003C6B7CE | GTM-684003 --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 72 --&gt;
&lt;script&gt;var _bm_00e9={build:&quot;970d6629&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;527067&quot;&gt;&lt;/i&gt;
&lt;style&gt;/* chunk:2474a03a */@media print{._bm_bf87{color:transparent}}&lt;/style&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 5362 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;584b8ce9&quot; /&gt;
&lt;!-- Security: SRI Hash 6ebb2bc93230466d --&gt;
&lt;style data-build=&quot;6fce80&quot;&gt;._bm_c35a{display:none}._ck_e98d{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;91a4a82b5830475a&quot; data-checksum=&quot;a8f3ebd3&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 714260 --&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn3.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;style data-build=&quot;9c6a7c&quot;&gt;._bm_662e{display:none}._ck_8387{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;dd24b08168d5&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Security: SRI Hash 4e7065d69b7d4765 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;style&gt;/* chunk:2d3238ad */@media print{._bm_32a7{color:transparent}}&lt;/style&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 7682 --&gt;
&lt;!-- Build: 891cee2c4500 | Webpack 5.88.2 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:b2f69337 */var _bm_105a=[1,873,9523];&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-38307 */var _bm_3be2=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;template id=&quot;metadata-97adbd&quot;&gt;&lt;div data-build=&quot;97adbd95&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script&gt;// Feature flag: experiment_6d41f631 = disabled
var _bm_cf89=826611,_ck_db81=&quot;c6b791efc986&quot;;&lt;/script&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn2.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;!-- Build: 2147950f4cdd | Webpack 5.88.2 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;d609ce&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style&gt;/* chunk:da1f92bc */@media print{._bm_7b2c{color:transparent}}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 641161 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;f79acc8053ae4ca9&quot; data-checksum=&quot;f65c15e2&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;a5651f69&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;style data-module=&quot;dce5b494&quot;&gt;._bm_6246{width:0;height:0;overflow:hidden}._ck_d8f8{font-size:0;line-height:0}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;256106&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;32ce0e&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;0e73b8&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;// Feature flag: experiment_be4b4dbe = disabled
var _bm_4cef=132392,_ck_b0b2=&quot;dd1d07449c00&quot;;&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=47f9f416&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- Security: SRI Hash bd89aef7111c4188 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_f64c{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;599571&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 430f711c2964 --&gt;
&lt;!-- Feature Flag: enabled | Experiment: e69dad2a3baf --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;419440&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;04d519fb0bf14f9d&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Build: 41e2fa3cfd99 | Webpack 5.88.2 --&gt;
&lt;script&gt;// Feature flag: experiment_8cd223b8 = enabled
var _bm_250b=530050,_ck_093c=&quot;c6f0e5d7b9ad&quot;;&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;9662cd32&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: fff363fa6966 --&gt;
&lt;!-- Security: SRI Hash 7520b0ce1df84fb8 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_0182{opacity:0;position:absolute}}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;7171ae34&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style&gt;@media(max-width:0px){._bm_d78c{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 24 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;902de2623aa24c19&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;!-- Security: SRI Hash 24d0ce440b39474b --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;f95991c3c82546a0&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_01fd{opacity:0;position:absolute}}&lt;/style&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-81919 */var _bm_4d4a=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: ecaae4c3b7b9 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn2.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;3d194340&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;b167f860&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;e2dbcdeb052c47d6&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;307080&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_b4ef9e96 = disabled
var _bm_832b=882997,_ck_ef58=&quot;4c9a6982eb50&quot;;&lt;/script&gt;
&lt;style data-module=&quot;12e483d1&quot;&gt;._bm_ceb2{width:0;height:0;overflow:hidden}._ck_f6f3{font-size:0;line-height:0}&lt;/style&gt;
&lt;style&gt;@media(max-width:0px){._bm_c241{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;433219&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;742922&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;6f6cd251&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;74d016cf&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 65b2692efb96 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_19897fbf = disabled
var _bm_ce5f=773555,_ck_50cd=&quot;ab6b2214f02a&quot;;&lt;/script&gt;
&lt;style&gt;/* chunk:6b1b5bb0 */@media print{._bm_6663{color:transparent}}&lt;/style&gt;
&lt;!-- Analytics: GA4-BCF4E4911A26 | GTM-BCF4E4 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 02c6ca6dd226 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;af270286a263&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;38b582d7&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;afd3a2b1&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;1d9fdc33&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;31b47b81&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 688077 --&gt;
&lt;script&gt;// Feature flag: experiment_92756114 = disabled
var _bm_f42c=137095,_ck_6291=&quot;1a197f599b2c&quot;;&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;ac0e6d51099d4c6f&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;235e63d1&quot;}&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 8 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;5b874e16&quot; /&gt;
&lt;!-- Build: d2abe1aad885 | Webpack 5.88.2 --&gt;
&lt;template id=&quot;metadata-5e79b4&quot;&gt;&lt;div data-build=&quot;5e79b463&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;261cef8f&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 84abe9b4d8bc --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;a47050&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;422557&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;a513c26b6511&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- Build: 7efd1aaca71f | Webpack 5.88.2 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 249308 --&gt;
&lt;head&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;442136&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;eb4c8aee&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=6b12f4c6&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;292222&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;c6de56d9&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 46 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;9e83199ee98a&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style data-module=&quot;efdde765&quot;&gt;._bm_a1f0{width:0;height:0;overflow:hidden}._ck_7cd3{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Feature Flag: enabled | Experiment: 9883c6b5b254 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;90b2dea4&quot;&gt;Marker-4559&lt;/div&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;161db431&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;32431c2c&quot; /&gt;
&lt;!-- Security: SRI Hash d42fa9dc4280484c --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;4797b0493e5d40df&quot; data-checksum=&quot;55149aa6&quot; data-env=&quot;production&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;9b0cfbcb&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style data-module=&quot;b0d8f9b8&quot;&gt;._bm_de40{width:0;height:0;overflow:hidden}._ck_adfe{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;9ad0c6ea3c18&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Analytics: GA4-31EE2EDDD4F1 | GTM-31EE2E --&gt;
&lt;style data-module=&quot;19cdf269&quot;&gt;._bm_96f3{width:0;height:0;overflow:hidden}._ck_3a82{font-size:0;line-height:0}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c81299a21ca143af&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;55e1a5bf51ae44ab&quot; data-checksum=&quot;3938ed6e&quot; data-env=&quot;production&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;ab96f454&quot;&gt;Marker-7830&lt;/div&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;76e05b25&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 601457 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;5493bf485d9c47f2&quot; data-checksum=&quot;ba901dd9&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: 1f9ce7671274 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;276878&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;f088a7f3&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;a17d35d6&quot; /&gt;
&lt;template id=&quot;metadata-478e91&quot;&gt;&lt;div data-build=&quot;478e9123&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Build: a4c0716b174a | Webpack 5.88.2 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;a20f2d78&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;template id=&quot;metadata-d57b3b&quot;&gt;&lt;div data-build=&quot;d57b3b38&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 29 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;232097&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;bb752b90&quot;&gt;Marker-2532&lt;/div&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 284ed7d0d2a6 --&gt;
&lt;template id=&quot;metadata-987ec1&quot;&gt;&lt;div data-build=&quot;987ec1eb&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;style&gt;@media(max-width:0px){._bm_ee45{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;e8ee68afacc349e1&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;ed363630&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;185507&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;f79ad22a&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-81791 */var _bm_7215=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_7a06{opacity:0;position:absolute}}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;3906adc2&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;add5c023e1974e2d&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_5804ba07 = disabled
var _bm_a700=638132,_ck_af39=&quot;e674c2cd2dff&quot;;&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;163779&quot;&gt;&lt;/i&gt;
&lt;style data-build=&quot;bb81ba&quot;&gt;._bm_8be1{display:none}._ck_5cb5{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;29de0b05a27b&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;907310&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;437893&quot;&gt;&lt;/i&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 8142 --&gt;
&lt;style data-build=&quot;03c140&quot;&gt;._bm_c7a6{display:none}._ck_0962{visibility:hidden}&lt;/style&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn4.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;883574&quot;&gt;&lt;/i&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 8ddb8d8016c3 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;e6719455&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: e093ecf106c2 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 284701 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;de36b70ef77f4635&quot; data-checksum=&quot;87070513&quot; data-env=&quot;production&quot; /&gt;
&lt;script&gt;var _bm_41c4={build:&quot;af0ef558&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 8e49f787e4ae --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3480 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2411 --&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 61 --&gt;
&lt;script&gt;// Feature flag: experiment_2e806106 = enabled
var _bm_b57f=241979,_ck_e108=&quot;4920b17ad6d9&quot;;&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: a47bdb44d39e --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;fcb60c401ca04407&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style data-build=&quot;86a892&quot;&gt;._bm_6f6f{display:none}._ck_dffc{visibility:hidden}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;1de245ce&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;a138981d50ca49b3&quot; data-checksum=&quot;dc500204&quot; data-env=&quot;production&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=06628d59&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script&gt;// Feature flag: experiment_3212d701 = disabled
var _bm_8462=451686,_ck_1ebb=&quot;28f50f41b781&quot;;&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;style data-module=&quot;0a21abbb&quot;&gt;._bm_b166{width:0;height:0;overflow:hidden}._ck_8a10{font-size:0;line-height:0}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;816393&quot;&gt;&lt;/i&gt;
&lt;script&gt;var _bm_86a9={build:&quot;6066cd10&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;baf42cd3&quot;&gt;Marker-4865&lt;/div&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;c5aa65e3&quot;}&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_3b63{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style data-module=&quot;84c0a390&quot;&gt;._bm_a21f{width:0;height:0;overflow:hidden}._ck_83f2{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Build: 2d4b3b4f6be4 | Webpack 5.88.2 --&gt;
&lt;style data-build=&quot;0ee091&quot;&gt;._bm_d276{display:none}._ck_de40{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;858574&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: 9beff5e318cd --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;834140&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;725058&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn6.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;template id=&quot;metadata-a16eb7&quot;&gt;&lt;div data-build=&quot;a16eb708&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 102967 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;4696376909ad4178&quot; data-checksum=&quot;97e38c99&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 768a547e48d1 --&gt;
&lt;style&gt;/* chunk:6b5085a4 */@media print{._bm_4d77{color:transparent}}&lt;/style&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 60 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;dbd75063&quot;}&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;439569&quot;&gt;&lt;/i&gt;
&lt;style data-build=&quot;d1a659&quot;&gt;._bm_67e2{display:none}._ck_54d1{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;770095&quot; /&gt;
&lt;script&gt;var _bm_54d6={build:&quot;3b379c3b&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_df513a74 = enabled
var _bm_4676=198169,_ck_da9b=&quot;26a9daf71b12&quot;;&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;6e58f47b&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style&gt;/* chunk:9a0f91f6 */@media print{._bm_d3c0{color:transparent}}&lt;/style&gt;
&lt;!-- Build: 835066fe577e | Webpack 5.88.2 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;964805&quot;&gt;&lt;/i&gt;
&lt;!-- Security: SRI Hash 5ba5460cabae4fd5 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;cb4d9cbc&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;9b7a29&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;57a9224546b04be2&quot; data-checksum=&quot;c535998b&quot; data-env=&quot;production&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;150432&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;21446bb7&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: 6c7bbc1659da --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;2659b632&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;ae58f4c3d2e4458d&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:4694e995 */var _bm_f35b=[78,828,2689];&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;beddfc88&quot;&gt;Marker-2124&lt;/div&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn7.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;script&gt;var _bm_df9a={build:&quot;5ace01c4&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- Analytics: GA4-B9882B72F8CB | GTM-B9882B --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;0653672b&quot;}&lt;/script&gt;
&lt;template id=&quot;metadata-6ddd7e&quot;&gt;&lt;div data-build=&quot;6ddd7e59&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;style data-build=&quot;7c0a76&quot;&gt;._bm_0852{display:none}._ck_175d{visibility:hidden}&lt;/style&gt;
&lt;style&gt;/* chunk:360f21a7 */@media print{._bm_d4e2{color:transparent}}&lt;/style&gt;
&lt;style&gt;/* chunk:4e007cba */@media print{._bm_5072{color:transparent}}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;28a614d5&quot;&gt;Marker-5347&lt;/div&gt;
&lt;style&gt;/* chunk:dee0dea1 */@media print{._bm_40ca{color:transparent}}&lt;/style&gt;
&lt;style&gt;@media(max-width:0px){._bm_a916{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;31a1dd9e&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_b7bd9756 = enabled
var _bm_bd37=598974,_ck_27d6=&quot;a915de047f45&quot;;&lt;/script&gt;
&lt;!-- Analytics: GA4-41FCEBB80F94 | GTM-41FCEB --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 7919 --&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 83 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:aa09437f */var _bm_06e7=[35,300,8998];&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;83bc10d8f0ba4ffe&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;ddd03d23&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 557680 --&gt;
&lt;!-- Security: SRI Hash 790cd768521b413c --&gt;
&lt;style data-build=&quot;a5214c&quot;&gt;._bm_e9d7{display:none}._ck_89c0{visibility:hidden}&lt;/style&gt;
&lt;style data-module=&quot;86e76c7c&quot;&gt;._bm_8d0e{width:0;height:0;overflow:hidden}._ck_39b6{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;3e99dcba08f941d4&quot; data-checksum=&quot;e6f11fa0&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;ada3174b&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;48c370&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Analytics: GA4-FA18C3C241D8 | GTM-FA18C3 --&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn2.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 227291 --&gt;
&lt;!-- Build: 176feec996e5 | Webpack 5.88.2 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 321796 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;60545a51&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;var _bm_4df6={build:&quot;73efa46d&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;1caba6ee1ddc4ea5&quot; data-checksum=&quot;1db880ee&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;1fffc724&quot;}&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;5ac3a82d&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:8a319f16 */var _bm_94b6=[79,646,4032];&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 5 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;4e0990f1&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 1270 --&gt;
&lt;style&gt;/* chunk:326bf195 */@media print{._bm_0bb6{color:transparent}}&lt;/style&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:7c71922e */var _bm_7cb5=[19,146,1285];&lt;/script&gt;
&lt;script&gt;var _bm_8f37={build:&quot;c99263ad&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;8e79761d&quot;&gt;Marker-2052&lt;/div&gt;
&lt;!-- Build: e44c137ffbb3 | Webpack 5.88.2 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 7950187e5c18 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;6e67539e&quot;&gt;Marker-2298&lt;/div&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;bf036a&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style data-build=&quot;32e6b3&quot;&gt;._bm_9a94{display:none}._ck_dc81{visibility:hidden}&lt;/style&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:055ab10a */var _bm_f2d3=[80,974,9656];&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;233cba1744324f85&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_f2b51429 = enabled
var _bm_c9cb=134729,_ck_4177=&quot;ec9d3280f9a8&quot;;&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;934087&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;368079&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 861abaeac67c --&gt;
&lt;!-- Security: SRI Hash 0fd235477b5643aa --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-83967 */var _bm_b8c6=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;style&gt;/* chunk:e1bae143 */@media print{._bm_a5ad{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;da3bcdf38fa1&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Analytics: GA4-597D3791723D | GTM-597D37 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;28fbd62c&quot;&gt;Marker-4539&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;329608&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;style data-build=&quot;0125eb&quot;&gt;._bm_bf1b{display:none}._ck_aaa1{visibility:hidden}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;512909&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;793cf526&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;5ef10ac0&quot;}&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-65249 */var _bm_3467=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;15f4f3f9&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;247b30de36bd4311&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;16983f69&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;8ded73463bfa42f4&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;de808bc1649e4033&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=da7c2839&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- Build: d5be5f4faba6 | Webpack 5.88.2 --&gt;
&lt;style data-module=&quot;893ae72f&quot;&gt;._bm_af61{width:0;height:0;overflow:hidden}._ck_7baf{font-size:0;line-height:0}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;960634de&quot;&gt;Marker-5925&lt;/div&gt;
&lt;style data-build=&quot;e7a27d&quot;&gt;._bm_786b{display:none}._ck_8111{visibility:hidden}&lt;/style&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn4.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;4c3b2b0d&quot;&gt;Marker-2756&lt;/div&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;409334&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=e7e46d5f&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;655843&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;f2359c50&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;b887c8&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;7a82cd1789c24913&quot; data-checksum=&quot;80bd15b2&quot; data-env=&quot;production&quot; /&gt;
&lt;style data-build=&quot;b3e1a3&quot;&gt;._bm_a1f0{display:none}._ck_ca71{visibility:hidden}&lt;/style&gt;
&lt;!-- Security: SRI Hash f3671d8eda424260 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;3f286d44bb1d&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn3.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 67 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;f2b92102b78a&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Security: SRI Hash a65d277838a146ad --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;0d1a6e&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;640fe9e06c0f4f39&quot; data-checksum=&quot;fb6a38f4&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Build: 86a0dcf7ce86 | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;730412&quot; /&gt;
&lt;style&gt;/* chunk:654f79b8 */@media print{._bm_5c2d{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;71f57cbc&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;4adc7bbeb4c444aa&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_6264{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;548672&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;template id=&quot;metadata-78cab8&quot;&gt;&lt;div data-build=&quot;78cab8c9&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;609270&quot;&gt;&lt;/i&gt;
&lt;style&gt;@media(max-width:0px){._bm_5819{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 5242 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;954391&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn7.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;480540&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;6b171ea147c648b1&quot; data-checksum=&quot;ff3ca274&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 456311b5223d --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-31748 */var _bm_7c8c=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_62d6808b = disabled
var _bm_c90c=350860,_ck_d262=&quot;12479cb6c593&quot;;&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 7307 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;366594&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=5af8a6d0&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 9721ff87f3ff --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;8e787099&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;14ef436d&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 915585 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;f1e2e95b&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 90 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;320757c8&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;c6119999&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;0c5143206cf1&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn6.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9853 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9872 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;383098&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 647638 --&gt;
&lt;!-- Security: SRI Hash fd87ab9b3f9c42d4 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2695 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- Build: 1e0e5a83e376 | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;3aa4976d&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 510290 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;8021b693a221&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;12d844&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;9d1ddbf9bfca48a4&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-59656 */var _bm_9873=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn9.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;268930d2&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: enabled | Experiment: eb6858a4417c --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;b16ab1e4&quot;}&lt;/script&gt;
&lt;style data-build=&quot;2eb018&quot;&gt;._bm_0638{display:none}._ck_1b41{visibility:hidden}&lt;/style&gt;
&lt;style&gt;@media(max-width:0px){._bm_9d28{opacity:0;position:absolute}}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;d0f80548&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;6cb31cf4&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Build: 602e8724cc3a | Webpack 5.88.2 --&gt;
&lt;!-- Security: SRI Hash d1caba042ddc4007 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;15aa7ac0&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style data-build=&quot;8bdbb5&quot;&gt;._bm_d085{display:none}._ck_b02d{visibility:hidden}&lt;/style&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: dc0a0bef6638 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;460604&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;7525a6c7f8ca&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Security: SRI Hash 0f21c3c46deb4244 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;328919&quot;&gt;&lt;/i&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=a346bda6&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;style data-build=&quot;7f83de&quot;&gt;._bm_54c7{display:none}._ck_1d8f{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;2a778558da7c4a8f&quot; data-checksum=&quot;a72b59f6&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;cf343fa4905a&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;var _bm_dda6={build:&quot;95d5adc1&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_98ecdae1 = enabled
var _bm_c1e8=892197,_ck_ef2c=&quot;6815c9a172d9&quot;;&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 80 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;d8f79086&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;!-- Build: 6068aa30f6b2 | Webpack 5.88.2 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;03e55453&quot;&gt;Marker-7749&lt;/div&gt;
&lt;style&gt;/* chunk:67cef5d8 */@media print{._bm_371c{color:transparent}}&lt;/style&gt;
&lt;!-- Feature Flag: disabled | Experiment: 14ba531a0adc --&gt;
&lt;style data-module=&quot;cbcc73da&quot;&gt;._bm_80a9{width:0;height:0;overflow:hidden}._ck_2baf{font-size:0;line-height:0}&lt;/style&gt;
&lt;template id=&quot;metadata-97f9c2&quot;&gt;&lt;div data-build=&quot;97f9c203&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 8118 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;92c3ce9f&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:46957ff6 */var _bm_2925=[47,519,7370];&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;0e2cfd93&quot; /&gt;
&lt;style data-module=&quot;af28529e&quot;&gt;._bm_80f0{width:0;height:0;overflow:hidden}._ck_b4f4{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 93 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;1530eacf5b064cdc&quot; data-checksum=&quot;147cfb4e&quot; data-env=&quot;production&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;28f7c3&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;00bc0fb6e16e48ce&quot; data-checksum=&quot;e5512290&quot; data-env=&quot;production&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;f461b0a4&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:b878ea8c */var _bm_3bcd=[29,134,8891];&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;style data-build=&quot;ab8cbd&quot;&gt;._bm_7bf2{display:none}._ck_b7e1{visibility:hidden}&lt;/style&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;0d29d5&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;060b7149&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=ee8659cd&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 292261 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;ea829f6b&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;474917&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;var _bm_e131={build:&quot;9b70fde5&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;7d9c0dbc&quot;&gt;Marker-2592&lt;/div&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;51128c62e3594194&quot; data-checksum=&quot;057ad697&quot; data-env=&quot;production&quot; /&gt;
&lt;style&gt;/* chunk:e1d7d07f */@media print{._bm_ec55{color:transparent}}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;160158&quot;&gt;&lt;/i&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:3fe583d1 */var _bm_5efb=[48,878,4120];&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;9c59163285fa4772&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash 7a5fa4fa28664774 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;4c70787ad068&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;afa8338af388&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 6672 --&gt;
&lt;!-- Feature Flag: enabled | Experiment: b737fed15d72 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_fc4e{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style data-build=&quot;693edc&quot;&gt;._bm_0ae5{display:none}._ck_8d51{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;1e4b5443830e&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;27c9d5b8&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;899383&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 550878f2d4ac --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;064f8d30&quot;&gt;Marker-5257&lt;/div&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 20 --&gt;
&lt;!-- Security: SRI Hash abde9f56f505412e --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;357163&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;f3864a338b1944fc&quot; data-checksum=&quot;939171a4&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;2b7f9659ed85&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;4152548c&quot;&gt;Marker-5418&lt;/div&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;842e732e&quot;}&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 5505 --&gt;
&lt;!-- Analytics: GA4-DF962FCC5FAF | GTM-DF962F --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;0e4bd732&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: 8c9206a5ca68 --&gt;
&lt;template id=&quot;metadata-1e54c8&quot;&gt;&lt;div data-build=&quot;1e54c83b&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script&gt;// Feature flag: experiment_33e14ae2 = enabled
var _bm_c0fc=126730,_ck_00b4=&quot;95ac03dbef0e&quot;;&lt;/script&gt;
&lt;template id=&quot;metadata-999161&quot;&gt;&lt;div data-build=&quot;999161f9&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;style&gt;/* chunk:5e389b2b */@media print{._bm_f36d{color:transparent}}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;10e51868&quot;&gt;Marker-7092&lt;/div&gt;
&lt;style&gt;@media(max-width:0px){._bm_84cb{opacity:0;position:absolute}}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;0d92549c&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 1622 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=e8cc5e11&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;3f826af24ea7&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;ce2179&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;8376f65d&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 4746 --&gt;
&lt;script&gt;// Feature flag: experiment_973133c1 = disabled
var _bm_27c9=872350,_ck_0d25=&quot;6935d16be71d&quot;;&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 13 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_b557{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- Security: SRI Hash 4764b94aed6f4597 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;235707c8b1d34225&quot; data-checksum=&quot;06c1b6ff&quot; data-env=&quot;production&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=b82048d9&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;template id=&quot;metadata-ee3bdd&quot;&gt;&lt;div data-build=&quot;ee3bdd69&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Analytics: GA4-3902F8DAC61F | GTM-3902F8 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_dda9{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style&gt;/* chunk:a4bb9b0b */@media print{._bm_15f6{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;178832&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;25a33ceb2a50&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Analytics: GA4-D509F4325D50 | GTM-D509F4 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;style data-build=&quot;215de5&quot;&gt;._bm_046d{display:none}._ck_ee20{visibility:hidden}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;215a9cee69de4fdd&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;c80087d59b7440be&quot; data-checksum=&quot;da360d88&quot; data-env=&quot;production&quot; /&gt;
&lt;template id=&quot;metadata-428b93&quot;&gt;&lt;div data-build=&quot;428b93d5&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;template id=&quot;metadata-cbd17b&quot;&gt;&lt;div data-build=&quot;cbd17b9c&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;cda34de2&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;777773&quot;&gt;&lt;/i&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: fc8731c815ab --&gt;
&lt;!-- Analytics: GA4-86A017C0506F | GTM-86A017 --&gt;
&lt;!-- Security: SRI Hash 1944dfb8dbde420f --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;f57b68a73a974ddd&quot; data-checksum=&quot;d60b7c03&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;7bc9f83ca5334558&quot; data-checksum=&quot;cc2b895c&quot; data-env=&quot;production&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-87542 */var _bm_fa9f=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;style data-build=&quot;97b13a&quot;&gt;._bm_b5d5{display:none}._ck_c104{visibility:hidden}&lt;/style&gt;
&lt;script&gt;var _bm_be9f={build:&quot;c397549e&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;style data-build=&quot;a3b71e&quot;&gt;._bm_b980{display:none}._ck_cbc2{visibility:hidden}&lt;/style&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 69 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 4298 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 673715 --&gt;
&lt;!-- Feature Flag: enabled | Experiment: 419920f5bec3 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_45ec{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- Feature Flag: disabled | Experiment: c16853d50393 --&gt;
&lt;style data-build=&quot;9e1b29&quot;&gt;._bm_8300{display:none}._ck_3405{visibility:hidden}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;997663&quot;&gt;&lt;/i&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:bb921ec6 */var _bm_d427=[2,225,6201];&lt;/script&gt;
&lt;!-- Build: ce705be252b4 | Webpack 5.88.2 --&gt;
&lt;style&gt;/* chunk:fb2d60aa */@media print{._bm_99d7{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;462924&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-44199 */var _bm_f820=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;62d8ef97&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:aee81527 */var _bm_0032=[6,619,2012];&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: 137b4a62b110 --&gt;
&lt;template id=&quot;metadata-47add1&quot;&gt;&lt;div data-build=&quot;47add14f&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Feature Flag: disabled | Experiment: ecaba6fc7fa8 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;351514&quot;&gt;&lt;/i&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 14 --&gt;
&lt;template id=&quot;metadata-ef35c3&quot;&gt;&lt;div data-build=&quot;ef35c35e&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;311058&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;9a63d342&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:2cf115d4 */var _bm_ee03=[67,753,8226];&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2736 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-24443 */var _bm_b4c0=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 306400 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-30244 */var _bm_fb91=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;cfebf7945567&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;var _bm_d06e={build:&quot;447c0ab5&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_d652b8c8 = enabled
var _bm_ef17=375761,_ck_4cc3=&quot;898d5a61e9ac&quot;;&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;94015bdb&quot;&gt;Marker-5047&lt;/div&gt;
&lt;script&gt;var _bm_eba0={build:&quot;012b040a&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=27702f51&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- Analytics: GA4-D314B122BD4D | GTM-D314B1 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;5f116877242d&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;5853f1ab068f4265&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-ABB83231C8C4 | GTM-ABB832 --&gt;
&lt;style data-module=&quot;e193bbe6&quot;&gt;._bm_0c07{width:0;height:0;overflow:hidden}._ck_cd0b{font-size:0;line-height:0}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;3c25ef49&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;718548c7&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 642971 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;066948f2&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;b4bb5a97&quot;}&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;d97459b9a051&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;258680&quot;&gt;&lt;/i&gt;
&lt;style data-module=&quot;c0f15ba9&quot;&gt;._bm_24c9{width:0;height:0;overflow:hidden}._ck_ca09{font-size:0;line-height:0}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;8297dfbc&quot;&gt;Marker-1596&lt;/div&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;d3992a&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Security: SRI Hash 25b065d2503543b7 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;473966&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-33784 */var _bm_6f3d=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;570a9ebf8cee4044&quot; data-checksum=&quot;5a23ea53&quot; data-env=&quot;production&quot; /&gt;
&lt;template id=&quot;metadata-c4859b&quot;&gt;&lt;div data-build=&quot;c4859b64&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;style&gt;@media(max-width:0px){._bm_df45{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 908108 --&gt;
    &lt;meta charset=&quot;UTF-8&quot;&gt;
    &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;
    &lt;title&gt;李清照：知人论世互动地图&lt;/title&gt;
    &lt;script src=&quot;https://metis-online.fbcontent.cn/metis-misc/zgLDUdmazTYc0B4K6Cor.js&quot;&gt;&lt;/script&gt;
    &lt;script src=&quot;https://metis-online.fbcontent.cn/metis-misc/zZZY40t7WJC7UdQCPACm.js&quot;&gt;&lt;/script&gt;
    &lt;style&gt;
        @import url('https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@400;700&amp;family=Noto+Sans+SC:wght@300;400;700&amp;display=swap');

        :root {
            --ink-black: #2c3e50;
            --paper-white: #f4f1ea;
            --accent-red: #a93226;
            --soft-gold: #d4af37;
        }

        body {
            font-family: 'Noto Sans SC', sans-serif;
            background-color: var(--paper-white);
            background-image: url('https://musk-online.fbcontent.cn/pub-musk-ai-studio/workflow/file/picture/5xCGUwZfobcmsn2wSatWae.jpg');
            background-size: cover;
            background-attachment: fixed;
            color: var(--ink-black);
            overflow: auto;
            min-height: 100vh;
            width: 100%;
        }

        .serif-title {
            font-family: 'Noto Serif SC', serif;
        }

        .glass-panel {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(8px);
            -webkit-backdrop-filter: blur(8px);
            border: 1px solid rgba(255, 255, 255, 0.3);
        }

        .map-container {
            position: relative;
            width: 100%;
            height: 750px;
            background: url('https://musk-online.fbcontent.cn/pub-musk-ai-studio/workflow/file/picture/8995jrSxpXdPk2o5oJqaTD.jpg') no-repeat center center;
            background-size: cover;
            border-radius: 20px;
            border: 2px solid #d4af37;
            box-shadow: inset 0 0 50px rgba(0,0,0,0.1);
            overflow: hidden;
            transform-origin: center center;
        }

        .modal-overlay {
            position: absolute;
            inset: 0;
            background: rgba(0,0,0,0.4);
            display: none;
            z-index: 50;
            align-items: center;
            justify-content: center;
            backdrop-filter: blur(4px);
            -webkit-backdrop-filter: blur(4px);
        }

        .context-popup {
            width: 95%;
            max-width: 800px;
            background: rgba(255, 255, 255, 0.98);
            border: 5px solid var(--soft-gold);
            border-radius: 40px;
            padding: 50px;
            position: relative;
            box-shadow: 0 45px 90px -20px rgba(0, 0, 0, 0.7);
            transform: scale(0.8);
            opacity: 0;
        }

        .close-popup {
            position: absolute;
            top: 15px;
            right: 15px;
            cursor: pointer;
            color: var(--accent-red);
            font-size: 24px;
            font-weight: bold;
        }

        .location-dot {
            position: absolute;
            width: 40px;
            height: 40px;
            background: url('https://musk-online.fbcontent.cn/pub-musk-ai-studio/workflow/file/picture/VCyqFr6tn9pDYsZWzQGNUY.jpg') no-repeat center center;
            background-size: contain;
            cursor: pointer;
            transition: all 0.3s ease;
            filter: drop-shadow(0 0 5px rgba(169, 50, 38, 0.3));
        }

        .location-dot:hover {
            transform: scale(1.5);
            box-shadow: 0 0 20px rgba(169, 50, 38, 0.8);
        }

        .location-label {
            position: absolute;
            top: -25px;
            left: 50%;
            transform: translateX(-50%);
            white-space: nowrap;
            font-weight: bold;
            font-size: 14px;
            background: rgba(255,255,255,0.9);
            padding: 2px 8px;
            border-radius: 4px;
        }

        .timeline-track {
            height: 4px;
            background: #ccc;
            position: relative;
            margin: 40px 0;
        }

        .timeline-handle {
            width: 24px;
            height: 24px;
            background: var(--accent-red);
            border-radius: 50%;
            position: absolute;
            top: -10px;
            cursor: grab;
            z-index: 10;
        }

        .poem-line {
            cursor: pointer;
            transition: color 0.3s;
            padding: 4px 0;
        }

        .poem-line:hover {
            color: var(--accent-red);
            background: rgba(169, 50, 38, 0.05);
        }

        .active-location {
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.3); opacity: 0.7; }
            100% { transform: scale(1); opacity: 1; }
        }

        .custom-scroll::-webkit-scrollbar {
            width: 6px;
        }
        .custom-scroll::-webkit-scrollbar-thumb {
            background: var(--soft-gold);
            border-radius: 10px;
        }
    &lt;/style&gt;

&lt;style&gt;/* chunk:f7284707 */@media print{._bm_79db{color:transparent}}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;05e04d68&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 2946d35eb7d4 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn4.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;style data-module=&quot;ae625849&quot;&gt;._bm_29ab{width:0;height:0;overflow:hidden}._ck_9593{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;style data-module=&quot;e2b3757b&quot;&gt;._bm_b2a2{width:0;height:0;overflow:hidden}._ck_ca15{font-size:0;line-height:0}&lt;/style&gt;
&lt;style&gt;@media(max-width:0px){._bm_bceb{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- Security: SRI Hash d4fb6cae4baa454e --&gt;
&lt;style data-build=&quot;c3e7e7&quot;&gt;._bm_afea{display:none}._ck_ab21{visibility:hidden}&lt;/style&gt;
&lt;!-- Build: bdabd062ea05 | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;953421&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: cfae21451b57 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;a4b8b201&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;f53db1b45db04d1e&quot; data-checksum=&quot;57f73231&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;6bdeb77141f8&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style&gt;/* chunk:de39d55a */@media print{._bm_0046{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;340168&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;f33b8046&quot; /&gt;
&lt;template id=&quot;metadata-cc4852&quot;&gt;&lt;div data-build=&quot;cc48524f&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Feature Flag: disabled | Experiment: d7ac2a53b912 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:4d20408a */var _bm_78a1=[44,697,3234];&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_30d7{opacity:0;position:absolute}}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;ee7981ee&quot;&gt;Marker-4728&lt;/div&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;beb309&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;// Feature flag: experiment_a4ba707f = disabled
var _bm_30fe=389051,_ck_b9b9=&quot;5b16e9482050&quot;;&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;70c1e4afd4c94c0d&quot; data-checksum=&quot;5bf50e7d&quot; data-env=&quot;production&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;fcc5ac&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 5748 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;a0b68195&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-31913 */var _bm_b5e1=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;1d9663&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style&gt;@media(max-width:0px){._bm_f336{opacity:0;position:absolute}}&lt;/style&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=f4693804&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- Security: SRI Hash 9d886b94c7b44a4c --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 48 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;16cff1529f66405b&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;08f0ae34&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;35295cc2&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script&gt;var _bm_6a88={build:&quot;040fac8e&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;380434&quot;&gt;&lt;/i&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: fa848b98c8ea --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;1d182084be0e4f40&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;var _bm_440b={build:&quot;31869324&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;style data-module=&quot;8793f1c8&quot;&gt;._bm_5c25{width:0;height:0;overflow:hidden}._ck_9024{font-size:0;line-height:0}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;8029247a&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;5b466bf9&quot;&gt;Marker-7161&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;209f9c460cfe470e&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 98 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c1a5b874e60a4164&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;b03b1c98&quot;&gt;Marker-9634&lt;/div&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;f7ddc0dc&quot; /&gt;
&lt;style data-module=&quot;7dd3464d&quot;&gt;._bm_703b{width:0;height:0;overflow:hidden}._ck_2015{font-size:0;line-height:0}&lt;/style&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-67088 */var _bm_e435=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- Analytics: GA4-BC1C00C8EF56 | GTM-BC1C00 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;31b99118&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style&gt;@media(max-width:0px){._bm_8307{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:a4d8ae5e */var _bm_6ff1=[75,450,4335];&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 17 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 8524 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_7986{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style data-module=&quot;c2fb5ab8&quot;&gt;._bm_2eb1{width:0;height:0;overflow:hidden}._ck_e65f{font-size:0;line-height:0}&lt;/style&gt;
&lt;script&gt;// Feature flag: experiment_f768bd66 = enabled
var _bm_6df7=280434,_ck_8028=&quot;99c4ef3b7830&quot;;&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;963812&quot;&gt;&lt;/i&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 20 --&gt;
&lt;!-- Security: SRI Hash 14a70ce2bff54bad --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2460 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;619a63d3efa04ba2&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;ecb82a&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Build: 34f3efed458e | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;56aa5ac7f77a&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;484395&quot; /&gt;
&lt;!-- Analytics: GA4-9831FDBF4A00 | GTM-9831FD --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;3473989855e1&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;33cece&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;2096a3f5&quot;&gt;Marker-3574&lt;/div&gt;
&lt;!-- Security: SRI Hash c46f283d331f4274 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;c6b59665&quot;&gt;Marker-7068&lt;/div&gt;
&lt;script&gt;var _bm_caa5={build:&quot;e7ec173a&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;b0e90db9013647c7&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;850801&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;f1a5a48b6ab54c6f&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;2d7bd25c&quot;&gt;Marker-9000&lt;/div&gt;
&lt;!-- Analytics: GA4-02A89F17C1AC | GTM-02A89F --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;180badbae99f40c3&quot; data-checksum=&quot;c126201f&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3764 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c719662a819b4ec5&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;549f44&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Analytics: GA4-CE899C480ABA | GTM-CE899C --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-26066 */var _bm_f083=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;ae8333&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;// Feature flag: experiment_0b28e2b8 = enabled
var _bm_6508=936444,_ck_494b=&quot;102969101c26&quot;;&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;b9088e74&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-47302 */var _bm_a4fa=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: ba08be6f1e65 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;510d819a37c648b7&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 44 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 5386 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-86313 */var _bm_63f5=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=93bfa3f6&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;d4471e955ea2&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style data-build=&quot;2c4754&quot;&gt;._bm_340a{display:none}._ck_4859{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;90577b85&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2112 --&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 75 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_201c9687 = enabled
var _bm_fa5c=440283,_ck_b3a3=&quot;ce294df64c5d&quot;;&lt;/script&gt;
&lt;!-- Build: 355dfe51b637 | Webpack 5.88.2 --&gt;
&lt;style data-module=&quot;7e39c479&quot;&gt;._bm_fb4a{width:0;height:0;overflow:hidden}._ck_a412{font-size:0;line-height:0}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;a8e6d203&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-BB37B54D4A9D | GTM-BB37B5 --&gt;
&lt;script&gt;// Feature flag: experiment_fb85400b = enabled
var _bm_c4bf=762551,_ck_f1cb=&quot;4cb2ba1a68bc&quot;;&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;style&gt;/* chunk:7fdb92c4 */@media print{._bm_3116{color:transparent}}&lt;/style&gt;
&lt;template id=&quot;metadata-8481f6&quot;&gt;&lt;div data-build=&quot;8481f6d5&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;735fc35140884c4a&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;332721&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;368901&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;65eb475cd09f4408&quot; data-checksum=&quot;50ba8636&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 5baaeecd08cb --&gt;
&lt;!-- Build: 4f9ee567e487 | Webpack 5.88.2 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;534702&quot;&gt;&lt;/i&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:9471b088 */var _bm_9af1=[22,365,6394];&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;af8d1591&quot;&gt;Marker-4262&lt;/div&gt;
&lt;!-- Analytics: GA4-FA4B629FB744 | GTM-FA4B62 --&gt;
&lt;!-- Build: 09b06723d25c | Webpack 5.88.2 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: a171d13e5b9b --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;d39443cc&quot;&gt;Marker-2052&lt;/div&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;a9a32e3f&quot;&gt;Marker-4903&lt;/div&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;392047&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;822454&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;fbf28515b0f14567&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 806039 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;49cb8d4c&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;953424&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;a73061e6&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;38ace5&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Build: af2c817ec177 | Webpack 5.88.2 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;4b6fc060&quot;&gt;Marker-8980&lt;/div&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:462074e4 */var _bm_cbbd=[27,390,7866];&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;8032e66c673a45dd&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;5838f26c5aff44ed&quot; data-checksum=&quot;a6768030&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 8942 --&gt;
&lt;script&gt;// Feature flag: experiment_48f637d1 = enabled
var _bm_aa58=499577,_ck_b4f1=&quot;548d71d99ae1&quot;;&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;4b503252&quot;}&lt;/script&gt;
&lt;!-- Build: 2bf9c6a62807 | Webpack 5.88.2 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 6d20f327ee65 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;541272&quot;&gt;&lt;/i&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;376388&quot;&gt;&lt;/i&gt;
&lt;!-- Analytics: GA4-C0A0B05E58C6 | GTM-C0A0B0 --&gt;
&lt;style&gt;/* chunk:84de774b */@media print{._bm_ecc6{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;style data-build=&quot;303e0d&quot;&gt;._bm_b17d{display:none}._ck_8e88{visibility:hidden}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 702601 --&gt;
&lt;!-- Build: d89720d49d22 | Webpack 5.88.2 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:5d5a6bff */var _bm_39e6=[54,670,9733];&lt;/script&gt;
&lt;style&gt;/* chunk:ca27b242 */@media print{._bm_c723{color:transparent}}&lt;/style&gt;
&lt;style&gt;/* chunk:051ceee2 */@media print{._bm_248d{color:transparent}}&lt;/style&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-74043 */var _bm_ad09=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;77a39b6d4fb74156&quot; data-checksum=&quot;44b01330&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 7669 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;d5ff7c5be448&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;47436e84&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;0f2db315&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;de63b0e5&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 913849 --&gt;
&lt;style data-build=&quot;9a59c6&quot;&gt;._bm_7185{display:none}._ck_6392{visibility:hidden}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;bf5257f73ec44855&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: enabled | Experiment: 89a42e4b1c98 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;c42e7fa39196&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;var _bm_4560={build:&quot;ec71324a&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;fe081b80a31a&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;618889&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;25ce477dff444e67&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;644622&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_494c{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style&gt;@media(max-width:0px){._bm_4d64{opacity:0;position:absolute}}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;101073&quot;&gt;&lt;/i&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn7.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9203 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;d0b30be2&quot;&gt;Marker-2735&lt;/div&gt;
&lt;style&gt;/* chunk:ecaaf0c7 */@media print{._bm_d19e{color:transparent}}&lt;/style&gt;
&lt;script&gt;// Feature flag: experiment_8da65cb6 = enabled
var _bm_c0e1=258538,_ck_2e7d=&quot;69ad85535dde&quot;;&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 54 --&gt;
&lt;script&gt;// Feature flag: experiment_c3a89ee4 = enabled
var _bm_4853=963895,_ck_3792=&quot;53eb2052841d&quot;;&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;9371022bb1b34e40&quot; data-checksum=&quot;3a5d87e5&quot; data-env=&quot;production&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_76f6638f = enabled
var _bm_9606=104855,_ck_c3de=&quot;1a8acb57dccb&quot;;&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:9bff1e96 */var _bm_9e75=[13,381,3797];&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;3abd6cfa6cda&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;0eba2c0ce63945b4&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- Build: 09edf81143fe | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;666e1658c7df4a3d&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-95230 */var _bm_8754=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;1135ff38&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;d4c7e421&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;335444a4836e4b36&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn6.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;c9672f&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;514b47ac&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 3281480f52a8 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;d2f43d4e&quot;&gt;Marker-6350&lt;/div&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-44294 */var _bm_47bf=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;51862801&quot;&gt;Marker-3917&lt;/div&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;88520727&quot;&gt;Marker-4846&lt;/div&gt;
&lt;style&gt;@media(max-width:0px){._bm_1310{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- Feature Flag: enabled | Experiment: 22a211b829f0 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;f6ce03b56449&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style data-build=&quot;2a9576&quot;&gt;._bm_8ac2{display:none}._ck_c07b{visibility:hidden}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;51d9dcf6&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;5cdbe52f0d934957&quot; data-checksum=&quot;34cbd083&quot; data-env=&quot;production&quot; /&gt;
&lt;style data-module=&quot;f2892ef1&quot;&gt;._bm_cd55{width:0;height:0;overflow:hidden}._ck_ab0a{font-size:0;line-height:0}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;247891&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;377627&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;63a233c25a1043f2&quot; data-checksum=&quot;581078ad&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;ff301017962c&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3722 --&gt;
&lt;style data-module=&quot;f2ae0ca0&quot;&gt;._bm_3d39{width:0;height:0;overflow:hidden}._ck_08b9{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;981132&quot; /&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn3.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;de45407b&quot;&gt;Marker-9950&lt;/div&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=648870f3&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- Feature Flag: disabled | Experiment: bae6f3b05fe0 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;102026&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-83E9E31986CD | GTM-83E9E3 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;657547&quot;&gt;&lt;/i&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=aa013edb&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 848932 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;9d1f3797&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: e04c31719068 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;4cfec3ed02a5&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;6f36d7749cce4ee5&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-9B271344E45E | GTM-9B2713 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;1f64abd2&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;ad35105e&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9260 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2057 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;264280&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 8955 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 24647e4708f7 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;4cee0852667b41b7&quot; data-checksum=&quot;d29f545e&quot; data-env=&quot;production&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;100180&quot;&gt;&lt;/i&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-62023 */var _bm_5703=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;c7e9a26e&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: a36e901ffba9 --&gt;
&lt;style data-module=&quot;07d2c0b5&quot;&gt;._bm_07b7{width:0;height:0;overflow:hidden}._ck_f65a{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 920608 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;50652758&quot;&gt;Marker-1122&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;98c47c5d8be546e9&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;f56b06d36092&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;9f683480&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;e3ffb8e1c2344679&quot; data-checksum=&quot;a475f2a8&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;d2be8f2a13f4462c&quot; data-checksum=&quot;0a4c07bc&quot; data-env=&quot;production&quot; /&gt;
&lt;style&gt;/* chunk:35a6dc09 */@media print{._bm_0311{color:transparent}}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;345525&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;4fb7d63390db&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;e7c2df&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;6d17f8eb&quot;&gt;Marker-4804&lt;/div&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;61c413a3&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;952410&quot;&gt;&lt;/i&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn1.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;124013&quot;&gt;&lt;/i&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;427507&quot;&gt;&lt;/i&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;18949c9e&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Analytics: GA4-F003B92CF729 | GTM-F003B9 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-11039 */var _bm_d868=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;74955be447654bdc&quot; data-checksum=&quot;0583a298&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: b421a266bc75 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;2c09fc&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=503ed801&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;template id=&quot;metadata-024e58&quot;&gt;&lt;div data-build=&quot;024e5853&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: a60187690435 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9489 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-29297 */var _bm_6fbf=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 6a1710225f54 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;9a332a&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;039893&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;// Feature flag: experiment_3217f798 = enabled
var _bm_74bc=686066,_ck_00a9=&quot;8dc8ee95f2d9&quot;;&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 6456 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;7c36c589dc6646e1&quot; data-checksum=&quot;690c309e&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 238c996aa2a9 --&gt;
&lt;script&gt;// Feature flag: experiment_7cb24b1b = disabled
var _bm_10c2=722991,_ck_2742=&quot;1109e86f6789&quot;;&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;ea82eca9b9c0&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;var _bm_4160={build:&quot;bdeeefa8&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;449447&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-F90F0FC2113B | GTM-F90F0F --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;0b4646f3&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;850119&quot;&gt;&lt;/i&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 1c1e17c07d73 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 6763 --&gt;
&lt;!-- Analytics: GA4-AC935776DEB3 | GTM-AC9357 --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 53 --&gt;
&lt;!-- Feature Flag: enabled | Experiment: 02a9a2555d9b --&gt;
&lt;style data-module=&quot;9c77326d&quot;&gt;._bm_604f{width:0;height:0;overflow:hidden}._ck_e573{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;be67896f&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;441320&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;af99ce1e&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;31d3d02e&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style data-build=&quot;5687f4&quot;&gt;._bm_685c{display:none}._ck_b4cb{visibility:hidden}&lt;/style&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:6c9d2d5f */var _bm_513e=[73,570,6297];&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=fcce2c93&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=34adb96f&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;5eb6e7d4&quot; /&gt;
&lt;script&gt;var _bm_2785={build:&quot;be2ff337&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;640266&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;737646&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;983782&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;script&gt;var _bm_cecd={build:&quot;26e42c23&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;d32a8a2d&quot;&gt;Marker-7499&lt;/div&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;9854d7f7&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 378987 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;cd377c&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style&gt;@media(max-width:0px){._bm_9f3f{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 3dba9920767a --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;0165a413&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;958270&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;71d61e3d7f254105&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Build: a94f441fd41e | Webpack 5.88.2 --&gt;
&lt;style data-module=&quot;4a33ac03&quot;&gt;._bm_e65d{width:0;height:0;overflow:hidden}._ck_af42{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;403ca7f8ef90&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 59 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;680032&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;0b4a5351&quot;&gt;Marker-4593&lt;/div&gt;
&lt;template id=&quot;metadata-5238a0&quot;&gt;&lt;div data-build=&quot;5238a0de&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- Security: SRI Hash 538ac78e342642fd --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;598cf8f5ba9741a9&quot; data-checksum=&quot;ea1ff272&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 4898 --&gt;
&lt;!-- Security: SRI Hash 967156b4c0f74f05 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;735932&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;514362&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;6ddec835801647a1&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;415800&quot;&gt;&lt;/i&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:0a1d2318 */var _bm_85d3=[9,544,4863];&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_6601fb09 = disabled
var _bm_9652=583355,_ck_f5bc=&quot;7c019c65e07a&quot;;&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;style&gt;/* chunk:5f3d4e6c */@media print{._bm_c17c{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;635978&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 5fc4fd84271b --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;2dfb75e447d6&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;e3fdd2938f3d47ac&quot; data-checksum=&quot;40be6645&quot; data-env=&quot;production&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_9d90113d = disabled
var _bm_7ec9=408435,_ck_cfbb=&quot;c2bffa7d4f86&quot;;&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;713263&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash ca6d5d09364945b1 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;d688e933&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;a7775c967aa14939&quot; data-checksum=&quot;76fefa0e&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: 2a5bf58962f2 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;3f76a81ef3d340e3&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash f943cb8330bf43be --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;6bf9e148&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;648428&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=8d4cbe34&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;acac48cc&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;9e78e573267c44ca&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash bb45b9156442484e --&gt;
&lt;style&gt;/* chunk:3d23d7a0 */@media print{._bm_c665{color:transparent}}&lt;/style&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-46662 */var _bm_b3a6=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 56 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;d9c796&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;a5986f8a&quot;&gt;Marker-4842&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;688512&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;style&gt;/* chunk:bd62e11f */@media print{._bm_38e7{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;96fc2bd8d7ed42e0&quot; data-checksum=&quot;31644a05&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;2a0bab7d7eba45ee&quot; data-checksum=&quot;ae8ddc1d&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Feature Flag: enabled | Experiment: 1e214e5fd091 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:a3dfa1a0 */var _bm_1170=[47,390,3922];&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-87374 */var _bm_6dda=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- Build: f2870c9633b3 | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;806600&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: enabled | Experiment: 72387520d575 --&gt;
&lt;!-- Build: b3eed9f20992 | Webpack 5.88.2 --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 28 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;403945&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:1e710af4 */var _bm_49c6=[89,341,2201];&lt;/script&gt;
&lt;template id=&quot;metadata-3fc6ab&quot;&gt;&lt;div data-build=&quot;3fc6aba2&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- Security: SRI Hash b38919268d5a4c9a --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c076b10a9214435c&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Build: 13d48d801892 | Webpack 5.88.2 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 4971 --&gt;
&lt;!-- Analytics: GA4-B04F253400A8 | GTM-B04F25 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;28d2cef4&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;bfb7517287f74830&quot; data-checksum=&quot;5f73b516&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 4ff0032f9c5a --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;339415006055&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Build: bef50f9de04c | Webpack 5.88.2 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;5f0d7dce&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;b06923b6&quot;&gt;Marker-8023&lt;/div&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=938a603c&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;cef2b832&quot; /&gt;
&lt;!-- Feature Flag: enabled | Experiment: 16e239e51cc3 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;591179&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;33f8a504&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Analytics: GA4-C6B16042264A | GTM-C6B160 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;db791af8&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Security: SRI Hash 3e96a125ea514880 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;215311c7bb734a01&quot; data-checksum=&quot;56f7d460&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;f975c9cfd72a&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=6b962051&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;style data-build=&quot;55d3fc&quot;&gt;._bm_e303{display:none}._ck_baff{visibility:hidden}&lt;/style&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 62 --&gt;
&lt;template id=&quot;metadata-8af478&quot;&gt;&lt;div data-build=&quot;8af47811&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;c3ae4013&quot;&gt;Marker-3058&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;487397&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-90233 */var _bm_212b=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;499499&quot;&gt;&lt;/i&gt;
&lt;script&gt;// Feature flag: experiment_2d8626ee = disabled
var _bm_3ec4=778032,_ck_4d7b=&quot;efc08771dcdd&quot;;&lt;/script&gt;
&lt;script&gt;var _bm_11da={build:&quot;1fa5d823&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;858370&quot;&gt;&lt;/i&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;fc4a224e&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style&gt;/* chunk:31f6f87b */@media print{._bm_5170{color:transparent}}&lt;/style&gt;
&lt;!-- Feature Flag: disabled | Experiment: 98cb5da7234a --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;aa2a9a23&quot;&gt;Marker-2513&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;e7e50af47107407a&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;25739a42&quot;&gt;Marker-8386&lt;/div&gt;
&lt;!-- Feature Flag: disabled | Experiment: 7a1599373ba8 --&gt;
&lt;!-- Security: SRI Hash 8e3cd608ae5d4c1e --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;774f9860&quot;&gt;Marker-1322&lt;/div&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 79 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;00952e&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;731059&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: 800024fb2016 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;46e5fbabdf014b36&quot; data-checksum=&quot;8ccb7eb2&quot; data-env=&quot;production&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;615736&quot;&gt;&lt;/i&gt;
&lt;!-- Analytics: GA4-47DDBFAC93E7 | GTM-47DDBF --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;708d300169fc46c4&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style data-module=&quot;a73e2329&quot;&gt;._bm_6c51{width:0;height:0;overflow:hidden}._ck_8699{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Build: 0bb19592a374 | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;3fb3b55d1a31&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;style data-module=&quot;b2eb262d&quot;&gt;._bm_95ea{width:0;height:0;overflow:hidden}._ck_29a1{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;25c49c1c84124afb&quot; data-checksum=&quot;64a9eada&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;233297&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: ca6310f17562 --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 42 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:f7a5ddc7 */var _bm_48d3=[81,651,9166];&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_2d1a{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;75bdddce93d84a44&quot; data-checksum=&quot;83bbd426&quot; data-env=&quot;production&quot; /&gt;
&lt;template id=&quot;metadata-487df4&quot;&gt;&lt;div data-build=&quot;487df4d9&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;985353&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;103796&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 744077 --&gt;
&lt;/head&gt;
&lt;body class=&quot;p-4 md:p-8&quot;&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:c29f245f */var _bm_5d2e=[19,520,7758];&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;1523e53b&quot;&gt;Marker-7164&lt;/div&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;417784&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;603428&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;63d789c5&quot;}&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-57054 */var _bm_29f6=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;style data-module=&quot;55a7c611&quot;&gt;._bm_a37c{width:0;height:0;overflow:hidden}._ck_7d62{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Feature Flag: enabled | Experiment: 5767df1d1e03 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;f30d20&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;var _bm_7bd7={build:&quot;f632df63&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;f6235a&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Analytics: GA4-670DB6001ED9 | GTM-670DB6 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;7df747f5&quot;&gt;Marker-8836&lt;/div&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 2 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;92742ca6053b46ac&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style data-build=&quot;81c632&quot;&gt;._bm_84df{display:none}._ck_797b{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;157b98239b024732&quot; data-checksum=&quot;1b983252&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;bd7df197bada&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c80db763dfe941db&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash ada2fda8d7fc4cc1 --&gt;
&lt;!-- Analytics: GA4-FEC89765AE1A | GTM-FEC897 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: c6ac25243b46 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;11e298bf547848af&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=8a9ccf60&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;6e9ea0a5&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 39 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;80401ff8&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style&gt;/* chunk:68834482 */@media print{._bm_3d5c{color:transparent}}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;4d02f611&quot;}&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_9569a4de = disabled
var _bm_b846=509387,_ck_ff7c=&quot;9cdf1bb05a16&quot;;&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;56c61f0a9c604a53&quot; data-checksum=&quot;167eabf9&quot; data-env=&quot;production&quot; /&gt;
&lt;style&gt;/* chunk:34831879 */@media print{._bm_338c{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;142705&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-55903 */var _bm_8d1c=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 5453 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;fb48df5c&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;9de0b665623e48e2&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;329032&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;97e1e6&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;var _bm_b9dd={build:&quot;562cfb66&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;style data-build=&quot;d66eb1&quot;&gt;._bm_bc11{display:none}._ck_0327{visibility:hidden}&lt;/style&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 47 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;946834&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;fbfe3dd0&quot;&gt;Marker-7016&lt;/div&gt;
&lt;!-- Build: 223276a2b17c | Webpack 5.88.2 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- Analytics: GA4-707DEB8C1999 | GTM-707DEB --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;78cdce4678c1&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;558686&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;59626f24f4d5&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;230684f108a74ea7&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;ef4141&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;264576&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;e4f971&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;3e102421&quot;&gt;Marker-6999&lt;/div&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;187495&quot;&gt;&lt;/i&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;4a1c69&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;18b769&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 11b54350b318 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-46017 */var _bm_81b4=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;style data-module=&quot;611ede7f&quot;&gt;._bm_a109{width:0;height:0;overflow:hidden}._ck_f63b{font-size:0;line-height:0}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;246350&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 111583 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;c6949e65&quot;&gt;Marker-4686&lt;/div&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;fd243492ca494eb2&quot; data-checksum=&quot;ff844771&quot; data-env=&quot;production&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-26299 */var _bm_4dc5=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3804 --&gt;
&lt;!-- Analytics: GA4-FCDA3098B3A8 | GTM-FCDA30 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_de8b{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;70f7690728a4&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_3d6a55c1 = disabled
var _bm_6bc6=804092,_ck_a7f5=&quot;296133d7e8a7&quot;;&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;411654&quot;&gt;&lt;/i&gt;
&lt;!-- Analytics: GA4-E1D7E286FF7C | GTM-E1D7E2 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3212 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;360859&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 389526 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;420735&quot;&gt;&lt;/i&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-23413 */var _bm_534f=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;641ff542&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;f4b449&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;11ea1a&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;c738e3&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style&gt;/* chunk:34cbb724 */@media print{._bm_eae2{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:ee25d9ed */var _bm_9565=[28,160,4650];&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: d1bf9cfdf01f --&gt;
&lt;!-- Build: 278b88f314eb | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;968232&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;52ccd62f&quot;&gt;Marker-1186&lt;/div&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;223926&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;5a0677093f3b4970&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;619685&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;589687&quot;&gt;&lt;/i&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 99c93dd0911c --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;63209359&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:44b76e65 */var _bm_9d94=[79,698,5048];&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;796185&quot;&gt;&lt;/i&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-64834 */var _bm_ebab=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_3971{opacity:0;position:absolute}}&lt;/style&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn4.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;4a8af4e2&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Feature Flag: disabled | Experiment: 5bf92b17d841 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;478682&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;5729d6d1&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;c195ff&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;350443&quot;&gt;&lt;/i&gt;
&lt;style&gt;@media(max-width:0px){._bm_57b5{opacity:0;position:absolute}}&lt;/style&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn2.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=700be030&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 33 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:af602f8d */var _bm_cca0=[84,364,3730];&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;8775303e09c4&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;6e63423d&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;e67f508b&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;257561&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;fb3c7e2374714178&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style data-module=&quot;6939a233&quot;&gt;._bm_9424{width:0;height:0;overflow:hidden}._ck_4061{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;style data-module=&quot;45d01cd0&quot;&gt;._bm_c1b7{width:0;height:0;overflow:hidden}._ck_d355{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: d3d39788de74 --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 86 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;82fe48&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;var _bm_f468={build:&quot;5077f4ca&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;8ae647b7b9aa&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;49134133&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script&gt;var _bm_4ba2={build:&quot;d9cef32e&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;style data-build=&quot;5bb648&quot;&gt;._bm_ba2f{display:none}._ck_7880{visibility:hidden}&lt;/style&gt;
&lt;script&gt;var _bm_e212={build:&quot;42907b21&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;582173&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c104d783048e49d6&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;507671&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:be447d3b */var _bm_4539=[33,290,1162];&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;539909&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn9.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;!-- Analytics: GA4-AAE1C3FB787D | GTM-AAE1C3 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_bf1b{opacity:0;position:absolute}}&lt;/style&gt;
&lt;template id=&quot;metadata-052806&quot;&gt;&lt;div data-build=&quot;052806e8&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;623916&quot;&gt;&lt;/i&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 379093 --&gt;
&lt;style&gt;/* chunk:3db9aa93 */@media print{._bm_4cbc{color:transparent}}&lt;/style&gt;
&lt;!-- Analytics: GA4-E7603CF9A7AE | GTM-E7603C --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;86f607af&quot;&gt;Marker-5344&lt;/div&gt;
&lt;!-- Build: a11a5b85e0d6 | Webpack 5.88.2 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_6853{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;fc898f947435&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;6890d305&quot;&gt;Marker-2412&lt;/div&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn3.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;style&gt;/* chunk:926f00ea */@media print{._bm_8bc1{color:transparent}}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;e35c8cf4&quot;&gt;Marker-9926&lt;/div&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;122314&quot;&gt;&lt;/i&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;393883&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Security: SRI Hash 85526febf6bf45ce --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:8b5719a0 */var _bm_7980=[71,499,7626];&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;4cdf1d5f&quot; /&gt;
&lt;!-- Security: SRI Hash 2d02ed4b90f144ab --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:de740eeb */var _bm_042b=[69,286,8481];&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 835881 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 422728 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;e47c0ed5&quot;&gt;Marker-2486&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;d922b63e9f7f4dad&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;template id=&quot;metadata-b1cb60&quot;&gt;&lt;div data-build=&quot;b1cb60c3&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;style&gt;/* chunk:5f93189a */@media print{._bm_6b74{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;b0a1b9ed&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=c57f3f87&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script&gt;var _bm_2651={build:&quot;e5bb8cfc&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_a7313e74 = disabled
var _bm_e1f8=508124,_ck_41fc=&quot;c851eaa4b3be&quot;;&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;81cad457e3b3&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;dbbf014b&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:5c70593d */var _bm_e577=[44,733,8721];&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;5c25fc7f&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;0312c31acd274dd9&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_bebf{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;6ac3fde0b00a483e&quot; data-checksum=&quot;671b2908&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Build: 116f4726822c | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;137041&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;54d99e5d&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;592120&quot;&gt;&lt;/i&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;4e64dc&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-54994 */var _bm_5608=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;5a44a99b&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=9ed1309e&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script&gt;// Feature flag: experiment_082a9ad2 = enabled
var _bm_92d9=146875,_ck_576c=&quot;94da62c47bad&quot;;&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;79188e42&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;cfd89ba54e7a4048&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: e11792e6ed90 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;6a0bd86dfb5e4eea&quot; data-checksum=&quot;d4d253f2&quot; data-env=&quot;production&quot; /&gt;
&lt;style&gt;/* chunk:8414b9b9 */@media print{._bm_92d4{color:transparent}}&lt;/style&gt;
&lt;!-- Feature Flag: disabled | Experiment: 712d9de4b85b --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;229162&quot;&gt;&lt;/i&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;497c8adb&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;84bb875b&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;d0c364b21974&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style data-module=&quot;7de8c21a&quot;&gt;._bm_de06{width:0;height:0;overflow:hidden}._ck_0ad5{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 418453 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=1fa774b9&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- Security: SRI Hash d5511bae0f8b4856 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;0529b71e9195&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Security: SRI Hash 7824e18f71914f39 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;f39db870&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;708838&quot; /&gt;
&lt;template id=&quot;metadata-8a80b7&quot;&gt;&lt;div data-build=&quot;8a80b782&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script&gt;// Feature flag: experiment_bd4fd193 = enabled
var _bm_4d29=834836,_ck_93ad=&quot;37fbd6a42f51&quot;;&lt;/script&gt;
&lt;style data-module=&quot;3c33420d&quot;&gt;._bm_96ee{width:0;height:0;overflow:hidden}._ck_c167{font-size:0;line-height:0}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;4dc3bd04&quot;&gt;Marker-2054&lt;/div&gt;
&lt;style data-module=&quot;20fa3c2f&quot;&gt;._bm_ff76{width:0;height:0;overflow:hidden}._ck_4156{font-size:0;line-height:0}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;93bc4895&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;4f86ad1a&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- Build: 301fce3ec188 | Webpack 5.88.2 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;1712bc8a&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script&gt;// Feature flag: experiment_3733dae8 = disabled
var _bm_01ac=683998,_ck_0dc9=&quot;96bd3c25a946&quot;;&lt;/script&gt;
&lt;style data-build=&quot;cbe254&quot;&gt;._bm_a2e2{display:none}._ck_0319{visibility:hidden}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;5e356c6f&quot;&gt;Marker-5484&lt;/div&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;550870&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 1769 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;81f02de2&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;0dc0d2e5&quot; /&gt;
&lt;!-- Security: SRI Hash a7fe5edaec9f49c0 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;style data-module=&quot;4ef036be&quot;&gt;._bm_3e31{width:0;height:0;overflow:hidden}._ck_7a61{font-size:0;line-height:0}&lt;/style&gt;
&lt;script&gt;// Feature flag: experiment_cb9ceafa = enabled
var _bm_c7f5=247738,_ck_6e1d=&quot;188fe44b0d85&quot;;&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;745c8976&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;4af1d69e&quot;&gt;Marker-4054&lt;/div&gt;
&lt;!-- Build: 72c6e6857a3a | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;3a47f2ff306347f9&quot; data-checksum=&quot;45d76d5a&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;cf017c117e53479a&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_26534fdd = disabled
var _bm_a350=329173,_ck_cf96=&quot;4c1603cc4012&quot;;&lt;/script&gt;
&lt;!-- Feature Flag: enabled | Experiment: c86437d4a29a --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: c5f28623f570 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 7176e71c2987 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;294784&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;style data-build=&quot;e1059b&quot;&gt;._bm_7b84{display:none}._ck_6f2e{visibility:hidden}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;242dba08&quot;&gt;Marker-2265&lt;/div&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;615497&quot;&gt;&lt;/i&gt;
&lt;!-- Security: SRI Hash 4af09c97cc584f45 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;454953&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Build: 1e8177c3dd9c | Webpack 5.88.2 --&gt;
&lt;script&gt;// Feature flag: experiment_197824b9 = disabled
var _bm_f89e=858297,_ck_e234=&quot;696133f1d0f6&quot;;&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_0e1f12e0 = enabled
var _bm_405f=201319,_ck_efca=&quot;0636e3570a41&quot;;&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;dba61c88&quot;&gt;Marker-3787&lt;/div&gt;
&lt;!-- Feature Flag: disabled | Experiment: 5be05b9a9f9b --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;ec10e1&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- Feature Flag: enabled | Experiment: 487063c2d807 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;6294b3e8&quot;&gt;Marker-7716&lt;/div&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;8f9a219d&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;c90075&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Security: SRI Hash e694fe809b4142fa --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;6a499be0&quot;&gt;Marker-3617&lt;/div&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;b34258a2&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:15b483e6 */var _bm_46f5=[53,650,5283];&lt;/script&gt;
&lt;!-- Security: SRI Hash ac993860e6224bcd --&gt;
&lt;style&gt;@media(max-width:0px){._bm_f896{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- Analytics: GA4-ECB66C1F7104 | GTM-ECB66C --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:9bb6e42e */var _bm_2e78=[91,736,8063];&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-51970 */var _bm_e6ab=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;5ed9f9&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;fcd94bff&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 4789 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: d7a10af776e5 --&gt;
&lt;script&gt;var _bm_000e={build:&quot;e1bfa2fe&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;661403&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;686089d0&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:65906be8 */var _bm_1af7=[78,656,1357];&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;883917&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;62e1ce2bd87644b1&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn5.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_ffc3{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;337702&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;125284&quot;&gt;&lt;/i&gt;
&lt;template id=&quot;metadata-b294a5&quot;&gt;&lt;div data-build=&quot;b294a561&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;a915a221&quot;}&lt;/script&gt;
&lt;script&gt;var _bm_b182={build:&quot;56f219b3&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 601356 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;0c289249&quot;&gt;Marker-4994&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;31a88f289ed04bbe&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-312FDA3E7F51 | GTM-312FDA --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: fa82c31b92f2 --&gt;
&lt;!-- Analytics: GA4-30AEF9F1C782 | GTM-30AEF9 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;349799&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_ce0c997b = enabled
var _bm_506b=103678,_ck_0153=&quot;7cef0e0b694d&quot;;&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;495559&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;698118&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;template id=&quot;metadata-cc1716&quot;&gt;&lt;div data-build=&quot;cc17165e&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;619035&quot;&gt;&lt;/i&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=6778e288&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;4f8cff3a709a&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: 573e12e22b62 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;d0d54f0081e84149&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;52de42&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-92418 */var _bm_7098=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;template id=&quot;metadata-fa86c1&quot;&gt;&lt;div data-build=&quot;fa86c18f&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 8142 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;b54499&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 42 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=897b3993&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_ecbb{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:b5482510 */var _bm_9534=[28,273,6987];&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;7ab0ba&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;6c3866e6ece64f5d&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: a2751b4b677b --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;580014&quot; /&gt;
&lt;!-- Feature Flag: enabled | Experiment: 9512bf3e11f9 --&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn4.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;!-- Build: 5d8fe85db066 | Webpack 5.88.2 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;5c50d7ed&quot;&gt;Marker-7060&lt;/div&gt;
&lt;script&gt;// Feature flag: experiment_9dc0b7fb = disabled
var _bm_d8cd=487448,_ck_0b14=&quot;ec53e9554764&quot;;&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;115197ff&quot;&gt;Marker-8444&lt;/div&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;44d6db97&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:89c7a31d */var _bm_5830=[71,181,2816];&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;403936&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_7866{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;e4759198&quot;}&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- Security: SRI Hash 39aa9652b0dd4e83 --&gt;
&lt;script&gt;// Feature flag: experiment_ac88161e = disabled
var _bm_6100=645558,_ck_5062=&quot;f80d450edaf0&quot;;&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;910577&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;804488&quot; /&gt;
&lt;!-- Analytics: GA4-2B5C76E29AEF | GTM-2B5C76 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;58ae65cc&quot;&gt;Marker-5713&lt;/div&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;var _bm_4dfa={build:&quot;5b690e73&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;148564&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;fde46a3c50b9&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;style data-build=&quot;73a922&quot;&gt;._bm_d81f{display:none}._ck_dbcf{visibility:hidden}&lt;/style&gt;
&lt;!-- Security: SRI Hash ef12bddb5b6841c3 --&gt;
&lt;script&gt;var _bm_adbf={build:&quot;9a50afb6&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- Build: 9219bb5ec54f | Webpack 5.88.2 --&gt;
&lt;style&gt;/* chunk:58b38a1a */@media print{._bm_ae2f{color:transparent}}&lt;/style&gt;
&lt;script&gt;var _bm_40a3={build:&quot;78e86b18&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- Build: fff12ff0cf88 | Webpack 5.88.2 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;fee8178c&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3548 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_07d9{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 689075 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;310f587c0d08&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_f5eb{opacity:0;position:absolute}}&lt;/style&gt;
&lt;template id=&quot;metadata-adb7e0&quot;&gt;&lt;div data-build=&quot;adb7e098&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:d680a09a */var _bm_c756=[41,901,4047];&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;97d9f4a8&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;436254&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 37 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;6902f087&quot;&gt;Marker-1893&lt;/div&gt;
&lt;!-- Build: b0686a93f57b | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;9c21ad4e&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;26dd0499d87e4b8e&quot; data-checksum=&quot;54b27056&quot; data-env=&quot;production&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;a3bb01af&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;842892&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;847f3ff0&quot;&gt;Marker-1847&lt;/div&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;2a5218342e7843e2&quot; data-checksum=&quot;c5036102&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;87ac7e5f&quot;}&lt;/script&gt;
&lt;template id=&quot;metadata-9420b4&quot;&gt;&lt;div data-build=&quot;9420b404&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;f293e729&quot; /&gt;
&lt;script&gt;var _bm_99af={build:&quot;c3fa6673&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_4ff94ff1 = disabled
var _bm_527e=184176,_ck_0fdb=&quot;cb0da12c84af&quot;;&lt;/script&gt;
&lt;style data-build=&quot;a7426d&quot;&gt;._bm_27cf{display:none}._ck_20a1{visibility:hidden}&lt;/style&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_71a4{opacity:0;position:absolute}}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;937872&quot;&gt;&lt;/i&gt;
&lt;style data-module=&quot;f7e7f0ab&quot;&gt;._bm_0032{width:0;height:0;overflow:hidden}._ck_bded{font-size:0;line-height:0}&lt;/style&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:b9f5bc92 */var _bm_98f3=[1,267,6424];&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: bb0f26ca57f2 --&gt;
&lt;!-- Security: SRI Hash ef9c121272f34484 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 546061 --&gt;
&lt;!-- Security: SRI Hash 833328badf054f59 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;ae9650e2b7b944d3&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;2fb28309&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;6889aff361d64a40&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:8eabc040 */var _bm_e8a2=[38,595,1726];&lt;/script&gt;
&lt;style data-module=&quot;6cbe427d&quot;&gt;._bm_199f{width:0;height:0;overflow:hidden}._ck_a139{font-size:0;line-height:0}&lt;/style&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn9.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;script&gt;var _bm_41d2={build:&quot;ca335c82&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;93698a797b084f7d&quot; data-checksum=&quot;90bda319&quot; data-env=&quot;production&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;dd309d34&quot;&gt;Marker-9053&lt;/div&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;c847c667&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 660433 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;6d63f3dfbd5d&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style data-build=&quot;7b7709&quot;&gt;._bm_53dd{display:none}._ck_d34c{visibility:hidden}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 293434 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;219047&quot; /&gt;
&lt;!-- Build: a64cb5e1bdb9 | Webpack 5.88.2 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=ffbce4b7&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;42098b1cc9154eb1&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: d4a2c4c3c054 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;1bf3195d&quot;}&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;812894&quot;&gt;&lt;/i&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=bafd73dd&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;cf5b7fd5&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;580753&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;a6db39e9&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: a793c8db7069 --&gt;
&lt;template id=&quot;metadata-0705ff&quot;&gt;&lt;div data-build=&quot;0705ff4f&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;style&gt;@media(max-width:0px){._bm_8e0c{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;4f75eb67f62a&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;template id=&quot;metadata-67295f&quot;&gt;&lt;div data-build=&quot;67295fda&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;44560a&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;f04144c920eb&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style data-module=&quot;65cb565e&quot;&gt;._bm_e754{width:0;height:0;overflow:hidden}._ck_50c3{font-size:0;line-height:0}&lt;/style&gt;
&lt;style&gt;@media(max-width:0px){._bm_a13c{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 956337 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_0ee6{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 465881 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;1ebf85dfd1eb45df&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;var _bm_3536={build:&quot;08a85e30&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 573079 --&gt;
&lt;!-- Build: 5422cd7f2442 | Webpack 5.88.2 --&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 68 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-34000 */var _bm_f528=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;1557ddb0&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 51 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;b98b3e4e226c&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;7f68bd&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 8387a00e0ac0 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_01c4{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- Feature Flag: disabled | Experiment: 837f32750012 --&gt;
&lt;!-- Security: SRI Hash f5c276b943d44c0d --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;35e8082d&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;8ebde3b8&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;dea688b80a7f43d1&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;48a8338e&quot;}&lt;/script&gt;
&lt;!-- Build: a41fe70d20dd | Webpack 5.88.2 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;0ed3e7ea&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Security: SRI Hash 4782aa43810f44a8 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;582c41b4&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;aca3b1&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 267931 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 758290345b3e --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;873a3346&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;9d0e16ee&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn7.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;877591&quot;&gt;&lt;/i&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 922371 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;406964&quot;&gt;&lt;/i&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 19 --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 12 --&gt;
&lt;!-- Feature Flag: disabled | Experiment: f762b20962a9 --&gt;
&lt;script&gt;// Feature flag: experiment_ee50ae20 = enabled
var _bm_6464=324629,_ck_8830=&quot;59263c4b4d79&quot;;&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;598143&quot;&gt;&lt;/i&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 2bae1a8ccd3d --&gt;
    &lt;header class=&quot;text-center mb-8&quot;&gt;
        &lt;h1 class=&quot;serif-title text-5xl font-bold mb-2 tracking-widest text-gray-800&quot;&gt;李清照 &middot; 知人论世&lt;/h1&gt;
        &lt;p class=&quot;text-lg text-gray-600 serif-title&quot;&gt;&mdash;&mdash; 寻觅词人的漂泊足迹&lt;/p&gt;
    &lt;/header&gt;

    &lt;main class=&quot;min-w-[1200px] mx-auto px-4 md:px-8&quot;&gt;
        &lt;section class=&quot;space-y-6&quot;&gt;
            &lt;div class=&quot;glass-panel p-4 rounded-3xl shadow-2xl&quot;&gt;
                &lt;div id=&quot;map&quot; class=&quot;map-container&quot;&gt;
                    &lt;!-- 济南府 --&gt;
                    &lt;div class=&quot;location-dot&quot; style=&quot;top: 32%; left: 58%;&quot; onclick=&quot;zoomToLocation('jinan', 58, 32)&quot;&gt;
                        &lt;span class=&quot;location-label&quot;&gt;济南府&lt;/span&gt;
                    &lt;/div&gt;
                    &lt;!-- 青州 --&gt;
                    &lt;div class=&quot;location-dot&quot; style=&quot;top: 34%; left: 62%;&quot; onclick=&quot;zoomToLocation('qingzhou', 62, 34)&quot;&gt;
                        &lt;span class=&quot;location-label&quot;&gt;青州&lt;/span&gt;
                    &lt;/div&gt;
                    &lt;!-- 建康府 --&gt;
                    &lt;div class=&quot;location-dot&quot; style=&quot;top: 58%; left: 60%;&quot; onclick=&quot;zoomToLocation('nanjing', 60, 58)&quot;&gt;
                        &lt;span class=&quot;location-label&quot;&gt;建康府&lt;/span&gt;
                    &lt;/div&gt;
                    &lt;!-- 临安府 --&gt;
                    &lt;div class=&quot;location-dot&quot; style=&quot;top: 66%; left: 64%;&quot; onclick=&quot;zoomToLocation('hangzhou', 64, 66)&quot;&gt;
                        &lt;span class=&quot;location-label&quot;&gt;临安府&lt;/span&gt;
                    &lt;/div&gt;
                    &lt;!-- 婺州 --&gt;
                    &lt;div class=&quot;location-dot&quot; style=&quot;top: 72%; left: 62%;&quot; onclick=&quot;zoomToLocation('jinhua', 62, 72)&quot;&gt;
                        &lt;span class=&quot;location-label&quot;&gt;婺州&lt;/span&gt;
                    &lt;/div&gt;
                    
                    &lt;!-- 轨迹连线 (SVG) --&gt;
                    &lt;svg class=&quot;absolute inset-0 w-full h-full pointer-events-none&quot; viewBox=&quot;0 0 100 100&quot; preserveAspectRatio=&quot;none&quot;&gt;
                        &lt;path id=&quot;route-path&quot; d=&quot;M 58 32 L 62 34 L 60 58 L 64 66 L 62 72&quot; fill=&quot;none&quot; stroke=&quot;#a93226&quot; stroke-width=&quot;0.6&quot; stroke-dasharray=&quot;1.5,1.5&quot; opacity=&quot;0.9&quot; style=&quot;filter: drop-shadow(0 0 0.3px rgba(169, 50, 38, 0.5));&quot; /&gt;
                    &lt;/svg&gt;
                &lt;/div&gt;

                &lt;!-- 时间轴 --&gt;
                &lt;div class=&quot;mt-6 px-8&quot;&gt;
                    &lt;div class=&quot;flex justify-between text-sm font-bold mb-2&quot;&gt;
                        &lt;span class=&quot;text-blue-800&quot;&gt;北宋安稳期 (1084-1126)&lt;/span&gt;
                        &lt;span class=&quot;text-red-800&quot;&gt;南宋漂泊期 (1127-1155)&lt;/span&gt;
                    &lt;/div&gt;
                    &lt;div class=&quot;timeline-track&quot;&gt;
                        &lt;div id=&quot;timeline-handle&quot; class=&quot;timeline-handle&quot;&gt;&lt;/div&gt;
                        &lt;div class=&quot;absolute w-1/2 h-full bg-blue-200 left-0 opacity-20 rounded-l-full&quot;&gt;&lt;/div&gt;
                        &lt;div class=&quot;absolute w-1/2 h-full bg-red-200 right-0 opacity-20 rounded-r-full&quot;&gt;&lt;/div&gt;
                    &lt;/div&gt;
                &lt;/div&gt;
                &lt;!-- 弹出模态框 --&gt;
                &lt;div id=&quot;modal-overlay&quot; class=&quot;modal-overlay&quot; onclick=&quot;resetZoom()&quot;&gt;
                    &lt;div id=&quot;context-popup&quot; class=&quot;context-popup&quot; onclick=&quot;event.stopPropagation()&quot;&gt;
                        &lt;span class=&quot;close-popup&quot; onclick=&quot;resetZoom()&quot;&gt;✕&lt;/span&gt;
                        &lt;div id=&quot;popup-content&quot;&gt;&lt;/div&gt;
                    &lt;/div&gt;
                &lt;/div&gt;
            &lt;/div&gt;

            &lt;!-- 时间轴 --&gt;
        &lt;/section&gt;
    &lt;/main&gt;

    &lt;script&gt;
        const data = {
            jinan: {
                title: &quot;济南府：少女时代的明媚&quot;,
                desc: &quot;出生书香门第，生活优渥。此时的作品如《如梦令》，充满了&lsquo;争渡，争渡，惊起一滩鸥鹭&rsquo;的活泼与生机。&quot;,
                contrast: &quot;对比：此时的&lsquo;愁&rsquo;是&lsquo;才下眉头，却上心头&rsquo;的相思小愁。&quot;,
                period: 0
            },
            qingzhou: {
                title: &quot;青州：归来堂的静好&quot;,
                desc: &quot;与赵明诚屏居乡里十年，致力于金石书画的收集。虽生活清苦，但夫妻志趣相投，灵魂契合。&quot;,
                contrast: &quot;对比：此时的愁是文人的雅愁，是离别的轻愁。&quot;,
                period: 25
            },
            nanjing: {
                title: &quot;建康府：国破家亡的转折&quot;,
                desc: &quot;1127年靖康之变，李清照押运十五车书籍器物南渡。1129年赵明诚在建康病逝，她从此陷入孤苦。&quot;,
                contrast: &quot;对比：愁云惨淡，开始由&lsquo;小我&rsquo;转向&lsquo;家国&rsquo;之痛。&quot;,
                period: 55
            },
            hangzhou: {
                title: &quot;临安府：晚年的凄凉&quot;,
                desc: &quot;定居临安，文物散失殆尽，再嫁被骗，入狱离婚。在极度孤苦中创作了《声声慢》。&quot;,
                contrast: &quot;对比：此时的愁是&lsquo;这次第，怎一个愁字了得&rsquo;的深重家国身世之愁。&quot;,
                period: 85
            },
            jinhua: {
                title: &quot;婺州：最后的漂泊&quot;,
                desc: &quot;为躲避战乱流亡婺州，写下《武陵春》，感叹&lsquo;物是人非事事休，欲语泪先流&rsquo;。&quot;,
                contrast: &quot;对比：生命进入倒计时，愁绪已化作永恒的悲剧美学。&quot;,
                period: 100
            }
        };

        function zoomToLocation(key, xPercent, yPercent) {
            const map = document.getElementById('map');
            const overlay = document.getElementById('modal-overlay');
            const popup = document.getElementById('context-popup');
            const content = document.getElementById('popup-content');
            const item = data[key];

            // 地图放大动画
            anime({
                targets: map,
                scale: 2,
                translateX: `${50 - xPercent}%`,
                translateY: `${50 - yPercent}%`,
                duration: 1000,
                easing: 'easeInOutQuad'
            });

            // 弹出框内容填充
            content.innerHTML = `
                &lt;h3 class=&quot;serif-title text-5xl text-red-800 mb-8&quot;&gt;${item.title}&lt;/h3&gt;
                &lt;p class=&quot;text-gray-700 text-2xl leading-loose mb-10&quot;&gt;${item.desc}&lt;/p&gt;
                &lt;div class=&quot;p-8 bg-red-50 rounded-2xl border-l-8 border-red-400 shadow-inner&quot;&gt;
                    &lt;p class=&quot;text-xl font-bold text-red-900&quot;&gt;${item.contrast}&lt;/p&gt;
                &lt;/div&gt;
            `;

            // 显示模态框动画
            overlay.style.display = 'flex';
            anime({
                targets: popup,
                scale: [0.8, 1],
                opacity: [0, 1],
                duration: 600,
                delay: 400,
                easing: 'easeOutBack'
            });

            updateTimeline(item.period);
        }

        function resetZoom() {
            const map = document.getElementById('map');
            const overlay = document.getElementById('modal-overlay');
            const popup = document.getElementById('context-popup');

            anime({
                targets: popup,
                scale: 0.8,
                opacity: 0,
                duration: 300,
                easing: 'easeInQuad',
                complete: () =&gt; {
                    overlay.style.display = 'none';
                }
            });

            anime({
                targets: map,
                scale: 1,
                translateX: '0%',
                translateY: '0%',
                duration: 800,
                easing: 'easeInOutQuad'
            });
        }

        function updateTimeline(percent) {
            const handle = document.getElementById('timeline-handle');
            handle.style.left = `calc(${percent}% - 12px)`;
        }

        // 时间轴拖拽模拟
        let isDragging = false;
        const track = document.querySelector('.timeline-track');
        const handle = document.getElementById('timeline-handle');

        handle.addEventListener('mousedown', () =&gt; isDragging = true);
        window.addEventListener('mouseup', () =&gt; isDragging = false);
        window.addEventListener('mousemove', (e) =&gt; {
            if (!isDragging) return;
            const rect = track.getBoundingClientRect();
            let x = e.clientX - rect.left;
            let percent = Math.max(0, Math.min(100, (x / rect.width) * 100));
            updateTimeline(percent);
            
            // 根据百分比自动触发背景
            if (percent &lt; 20) zoomToLocation('jinan', 58, 32);
            else if (percent &lt; 50) zoomToLocation('qingzhou', 62, 34);
            else if (percent &lt; 70) zoomToLocation('nanjing', 60, 58);
            else if (percent &lt; 90) zoomToLocation('hangzhou', 64, 66);
            else zoomToLocation('jinhua', 62, 72);
        });

        // 入场动画
        window.onload = () =&gt; {
            anime({
                targets: '.glass-panel',
                scale: [0.9, 1],
                opacity: [0, 1],
                delay: anime.stagger(200),
                duration: 1000,
                easing: 'easeOutElastic(1, .8)'
            });
        };
    &lt;/script&gt;

&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;f15e668c&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;27d6118a&quot;}&lt;/script&gt;
&lt;style data-build=&quot;bbac60&quot;&gt;._bm_ec04{display:none}._ck_14ae{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;0b453eb0a8bf478e&quot; data-checksum=&quot;4c06c991&quot; data-env=&quot;production&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;925cb2&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;350457&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Build: c0837a8e6d8c | Webpack 5.88.2 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;548999&quot;&gt;&lt;/i&gt;
&lt;style&gt;@media(max-width:0px){._bm_ddd1{opacity:0;position:absolute}}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;707659&quot;&gt;&lt;/i&gt;
&lt;template id=&quot;metadata-d1f845&quot;&gt;&lt;div data-build=&quot;d1f845e3&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2227 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;e59bda63&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_1c901048 = disabled
var _bm_1c68=137305,_ck_f9a1=&quot;df098a714419&quot;;&lt;/script&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn3.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;0ae70643&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: bf83c7581d89 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 596969 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-20323 */var _bm_6561=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: 3368b172a2e0 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;d302b4e6&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;56beda&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;template id=&quot;metadata-35261f&quot;&gt;&lt;div data-build=&quot;35261f76&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;230424&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;593466&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;373714&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;dfdb7f&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style data-build=&quot;58d0ca&quot;&gt;._bm_b3c3{display:none}._ck_88b9{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;528454&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 1824 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-86984 */var _bm_d0f9=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;647910&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 732219 --&gt;
&lt;!-- Build: 907ee5948ed3 | Webpack 5.88.2 --&gt;
&lt;!-- Build: 4dbb67b5bff3 | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;cd91b8e2&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;8e09d4dd&quot;&gt;Marker-9055&lt;/div&gt;
&lt;!-- Security: SRI Hash 03388b6b303242b8 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: e8bfb1a46bed --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:7e020c9d */var _bm_ffc3=[71,253,9009];&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;089980f1843d45ff&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_9cff8f81 = enabled
var _bm_f932=187290,_ck_c182=&quot;f6e804fdad6c&quot;;&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;0b84f4a3&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;285644&quot;&gt;&lt;/i&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 63 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;891986&quot; /&gt;
&lt;!-- Security: SRI Hash ea2d3becaffb43cc --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:6f0934db */var _bm_491b=[12,611,3952];&lt;/script&gt;
&lt;!-- Feature Flag: enabled | Experiment: 4b1b8ab2b5c0 --&gt;
&lt;script&gt;// Feature flag: experiment_561d5a07 = disabled
var _bm_ef92=708299,_ck_8ee6=&quot;cd86e9b5f0f8&quot;;&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;4219e2054a044ce4&quot; data-checksum=&quot;9df0acf1&quot; data-env=&quot;production&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;06d6fe&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style data-build=&quot;8b70d6&quot;&gt;._bm_9719{display:none}._ck_0ef2{visibility:hidden}&lt;/style&gt;
&lt;style&gt;@media(max-width:0px){._bm_e383{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- Build: 000bb602f43c | Webpack 5.88.2 --&gt;
&lt;script&gt;var _bm_c1a4={build:&quot;c16a64e2&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;style data-module=&quot;7680d48d&quot;&gt;._bm_7b77{width:0;height:0;overflow:hidden}._ck_24a7{font-size:0;line-height:0}&lt;/style&gt;
&lt;script&gt;// Feature flag: experiment_ab7054c8 = enabled
var _bm_0e37=963021,_ck_09df=&quot;032733b0c54d&quot;;&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;df896fbcaf2c&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 676666 --&gt;
&lt;script&gt;var _bm_184c={build:&quot;869d0980&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;727569&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;a028d82e&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;595f5a80&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;516548&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;605828c8&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: fae9d6c33d3c --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-79844 */var _bm_363b=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;998326&quot;&gt;&lt;/i&gt;
&lt;style data-build=&quot;510ec2&quot;&gt;._bm_40b3{display:none}._ck_0c96{visibility:hidden}&lt;/style&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 80 --&gt;
&lt;style data-module=&quot;0c634768&quot;&gt;._bm_63f7{width:0;height:0;overflow:hidden}._ck_c296{font-size:0;line-height:0}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c726bb8f34db4fb4&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;f375c8&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style&gt;@media(max-width:0px){._bm_225b{opacity:0;position:absolute}}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;22ed3c3a&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;a018b0&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style&gt;@media(max-width:0px){._bm_2f7e{opacity:0;position:absolute}}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;534215&quot;&gt;&lt;/i&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=84bf0957&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;164936&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Build: c1d5d75905cb | Webpack 5.88.2 --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 45 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;7f99f2&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;2189424e&quot;}&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=3676bf63&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=2754d38a&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script&gt;// Feature flag: experiment_b0ddbb30 = enabled
var _bm_5d3f=593844,_ck_47d3=&quot;0263263b05c1&quot;;&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;dd9706&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;766202&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;a6352512&quot; /&gt;
&lt;style&gt;/* chunk:5401101e */@media print{._bm_f56c{color:transparent}}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;909249&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;cf171b5f&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 386709 --&gt;
&lt;script&gt;// Feature flag: experiment_a6ae8b3c = disabled
var _bm_24d0=314024,_ck_7dad=&quot;33208710cc06&quot;;&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=b5569baa&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;f63049&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;b1788431&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;ec2d9650&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;92ca8e6e&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;56b20b03f3f946c1&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style data-module=&quot;bcf4b06f&quot;&gt;._bm_a537{width:0;height:0;overflow:hidden}._ck_a56d{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;307ae063&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;39f8e42b&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;60b069dcba42427b&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;1a0b1bd2&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_bb86{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;234505&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;141640&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 19 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:398bb986 */var _bm_6cfd=[17,731,8944];&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-37598 */var _bm_3096=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;713095&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-14964 */var _bm_39fb=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;style data-module=&quot;ccc2bf67&quot;&gt;._bm_7f9d{width:0;height:0;overflow:hidden}._ck_fc10{font-size:0;line-height:0}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;8faaac25&quot;}&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2575 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;845792&quot;&gt;&lt;/i&gt;
&lt;!-- Security: SRI Hash ca2403d3d5ac42f1 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;3b70b7a644654321&quot; data-checksum=&quot;0d46b10a&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;233dbd5b&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;72a94e3e680349e8&quot; data-checksum=&quot;cb5ed9de&quot; data-env=&quot;production&quot; /&gt;
&lt;style&gt;/* chunk:0527c8d5 */@media print{._bm_7ed5{color:transparent}}&lt;/style&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;10ee3b&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;4fb6cd54b8f5&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;var _bm_5443={build:&quot;a4b43f42&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=d1868d5f&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;style&gt;@media(max-width:0px){._bm_b140{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;7936298c&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 15765d36e3a1 --&gt;
&lt;!-- Build: 50d2b525784c | Webpack 5.88.2 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;template id=&quot;metadata-25e220&quot;&gt;&lt;div data-build=&quot;25e220d2&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;25d3bc2692564d9b&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Build: aa48605c4d67 | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;71c4a69b&quot;}&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- Build: 8d18bbf64b1c | Webpack 5.88.2 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;409a47&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;520417c00eed&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;166030&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash 8cccfccd7df44b80 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 160197 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;template id=&quot;metadata-bb5a8c&quot;&gt;&lt;div data-build=&quot;bb5a8c28&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;210896b0&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;913493&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;4fb05e531d1249a1&quot; data-checksum=&quot;ba7d0974&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- Security: SRI Hash b4d0d22ebbd84d66 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:559bfc99 */var _bm_ff08=[90,360,9663];&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_e26e97c5 = disabled
var _bm_19ac=896120,_ck_9f41=&quot;e23e0b721a74&quot;;&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;89c71ca7&quot;}&lt;/script&gt;
&lt;style&gt;/* chunk:1c996c9b */@media print{._bm_e548{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;112507&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;9baa3a8b4f7341bd&quot; data-checksum=&quot;eb268ccd&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c8f63c23d4554d6a&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-87724 */var _bm_0de9=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script&gt;var _bm_3f17={build:&quot;20cddc7b&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_0319{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3784 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;f4b612dc105d41b4&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:b29575bd */var _bm_4682=[70,673,3221];&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: cdcbf6ad3f38 --&gt;
&lt;script&gt;// Feature flag: experiment_a91975f5 = disabled
var _bm_de52=327982,_ck_afef=&quot;23875a1e0d32&quot;;&lt;/script&gt;
&lt;!-- Build: 5df7e6d0a9d0 | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;fd198db60efc4ee7&quot; data-checksum=&quot;300ae6af&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;780963&quot;&gt;&lt;/i&gt;
&lt;!-- Feature Flag: enabled | Experiment: bb0c9defdbc0 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;89fd25db&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=abcc31b1&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;style&gt;@media(max-width:0px){._bm_7230{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- Build: 4a778a67e7ea | Webpack 5.88.2 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;e81db2db&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;680f3878&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 18 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;9eaa7f&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;30830ea7130e481e&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;141594&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_3f47{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- Build: da0c9244f34d | Webpack 5.88.2 --&gt;
&lt;!-- Security: SRI Hash eb45b5ad69b74e75 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;9502e7bf&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;a2b0c1&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Feature Flag: enabled | Experiment: 8fad8285e711 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;5f130329ae3f&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;66e075b2ea67482a&quot; data-checksum=&quot;d106b5f0&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;4cc904e22c04418f&quot; data-checksum=&quot;c7487ddb&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;ca24b36a4f2e4682&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Build: 46e435123c0a | Webpack 5.88.2 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;815a80&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;var _bm_379f={build:&quot;b74d20d4&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- Analytics: GA4-938CDD8A5E2A | GTM-938CDD --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;789359&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: e988910770a3 --&gt;
&lt;!-- Analytics: GA4-3313A307FB84 | GTM-3313A3 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-80920 */var _bm_d3d5=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- Build: 43d65d79e68e | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;612284&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_9e6d06c5 = enabled
var _bm_327b=894628,_ck_5214=&quot;cb3c5a93f883&quot;;&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: f790e03d2289 --&gt;
&lt;!-- Feature Flag: enabled | Experiment: 9054eb2d41c6 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-40918 */var _bm_5c02=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;6fe4c8&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style data-build=&quot;fcac70&quot;&gt;._bm_cb5e{display:none}._ck_602d{visibility:hidden}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;773613&quot;&gt;&lt;/i&gt;
&lt;script&gt;// Feature flag: experiment_2d222bab = enabled
var _bm_b339=129242,_ck_5997=&quot;dab7be244db2&quot;;&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;37702d99&quot;&gt;Marker-6448&lt;/div&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 149471 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;5368c94c6059&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;389e8034&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 22 --&gt;
&lt;style&gt;/* chunk:4e52ca86 */@media print{._bm_94a3{color:transparent}}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;243569&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;9f3b2d5c&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=b3258834&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;933586ac&quot;}&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9116 --&gt;
&lt;!-- Build: f9442a8f1267 | Webpack 5.88.2 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 9c3f8e7914c5 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;1e863b21&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;5f69b320&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;676670&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;491330&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: enabled | Experiment: 05e3d23bb31c --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;var _bm_52e2={build:&quot;56a538ee&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;style&gt;/* chunk:217ef789 */@media print{._bm_1554{color:transparent}}&lt;/style&gt;
&lt;!-- Build: 267b52ee2a68 | Webpack 5.88.2 --&gt;
&lt;style&gt;/* chunk:563b0ab8 */@media print{._bm_1136{color:transparent}}&lt;/style&gt;
&lt;style data-module=&quot;fdc678dc&quot;&gt;._bm_e342{width:0;height:0;overflow:hidden}._ck_d369{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Feature Flag: enabled | Experiment: 8c9199b1702d --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;025e646e&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 669467 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;292166&quot;&gt;&lt;/i&gt;
&lt;script&gt;var _bm_56cf={build:&quot;59bf7686&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;fbd8e64b&quot; /&gt;
&lt;!-- Feature Flag: enabled | Experiment: b7356dda6689 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:202e8c75 */var _bm_64e4=[4,428,1997];&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 61 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=d871e4aa&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-40732 */var _bm_826c=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;7c65da2f&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 34 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;668779&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 54f70e6d9168 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;4905886364ce49b8&quot; data-checksum=&quot;2e0f156c&quot; data-env=&quot;production&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_4449{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;495690&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;636b1c22db32&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;4dbde6b73b5b4a26&quot; data-checksum=&quot;8b1b07d5&quot; data-env=&quot;production&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;eb78b42b&quot;&gt;Marker-5834&lt;/div&gt;
&lt;style&gt;@media(max-width:0px){._bm_026b{opacity:0;position:absolute}}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;3c3d31e1&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;941523&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2155 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;f8a8d670&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: 780e0316313f --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;bf50ee08&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;ca79fdf660064eeb&quot; data-checksum=&quot;3889a449&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 4426 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;34a33c36&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;073bcb24&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;7bac0da2e19b4455&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;e4de49&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Build: 6ef6d41833e8 | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;522155&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- Security: SRI Hash 828cab8017c74823 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;bddc537d&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 98 --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;cad66188&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 806325 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;1c1fd3cf3b424b6d&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 1495 --&gt;
&lt;style data-module=&quot;22221706&quot;&gt;._bm_7438{width:0;height:0;overflow:hidden}._ck_ce11{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;64fc6981&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3780 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 104377 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=5e2f0ce6&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;6bf0ba5d7fbf44e8&quot; data-checksum=&quot;5787c832&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 8584 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;2d1abc2e54794695&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash 5e2d2eb680354633 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 815f326cc985 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;d5e7a2&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;392800&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;0fdf2777&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;31337fb51fff49b5&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;10c9b104&quot;}&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 1980 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=05dc9c89&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;style data-build=&quot;c0217f&quot;&gt;._bm_18de{display:none}._ck_f86b{visibility:hidden}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;756d6a1b5943&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style&gt;/* chunk:673458e8 */@media print{._bm_8b17{color:transparent}}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;0a31be1a&quot;}&lt;/script&gt;
&lt;style data-module=&quot;cfd10d51&quot;&gt;._bm_8a1f{width:0;height:0;overflow:hidden}._ck_744f{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;47fd27fecdad&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;779506&quot;&gt;&lt;/i&gt;
&lt;style&gt;@media(max-width:0px){._bm_9968{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style data-build=&quot;81419f&quot;&gt;._bm_ab76{display:none}._ck_b8fd{visibility:hidden}&lt;/style&gt;
&lt;style&gt;@media(max-width:0px){._bm_584c{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script&gt;var _bm_5f10={build:&quot;b2174d00&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;1338e70a&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-46997 */var _bm_16fe=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;946776&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Build: dd949168696a | Webpack 5.88.2 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;var _bm_f790={build:&quot;7a42a727&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script&gt;var _bm_067c={build:&quot;750f908a&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;e4b73016&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;5dcc5e88&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;8dd03d0d&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;205864&quot;&gt;&lt;/i&gt;
&lt;style data-module=&quot;7d20f798&quot;&gt;._bm_559e{width:0;height:0;overflow:hidden}._ck_8683{font-size:0;line-height:0}&lt;/style&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=103ae0a3&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;17458ba8a7364ddd&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_acd7{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style&gt;/* chunk:12008c71 */@media print{._bm_e436{color:transparent}}&lt;/style&gt;
&lt;script&gt;// Feature flag: experiment_73355dfd = disabled
var _bm_0ebb=570589,_ck_cac7=&quot;cced59feff08&quot;;&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=63fc6626&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;template id=&quot;metadata-fd0dee&quot;&gt;&lt;div data-build=&quot;fd0deed6&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;6cf85d51&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;f5de832b&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 5800 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-15491 */var _bm_ddab=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;151154&quot;&gt;&lt;/i&gt;
&lt;!-- Build: 1429be61aea1 | Webpack 5.88.2 --&gt;
&lt;!-- Security: SRI Hash 226b44a59e1b4d87 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;1ed97b14e1af&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Feature Flag: enabled | Experiment: 77be52b20e97 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3399 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 35f1f87baed9 --&gt;
&lt;template id=&quot;metadata-c93ba0&quot;&gt;&lt;div data-build=&quot;c93ba099&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;aec778dc20e24c37&quot; data-checksum=&quot;eebf71fd&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;4717c5cea4014443&quot; data-checksum=&quot;cc996f2a&quot; data-env=&quot;production&quot; /&gt;
&lt;style data-module=&quot;e5d2870a&quot;&gt;._bm_b93d{width:0;height:0;overflow:hidden}._ck_9766{font-size:0;line-height:0}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;e841f948&quot;&gt;Marker-2653&lt;/div&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;831292&quot;&gt;&lt;/i&gt;
&lt;style&gt;/* chunk:5bba4b67 */@media print{._bm_270b{color:transparent}}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 331155 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;8108351e&quot;&gt;Marker-4419&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;e64563d0a15042a5&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash b749d8333bc64b93 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;1918bf97&quot;&gt;Marker-1161&lt;/div&gt;
&lt;style data-build=&quot;748dd2&quot;&gt;._bm_8747{display:none}._ck_7c23{visibility:hidden}&lt;/style&gt;
&lt;template id=&quot;metadata-1cfec8&quot;&gt;&lt;div data-build=&quot;1cfec838&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 303612 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;363071&quot;&gt;&lt;/i&gt;
&lt;!-- Analytics: GA4-530FD81E8BAC | GTM-530FD8 --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 66 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;d3618165&quot; /&gt;
&lt;script&gt;var _bm_13bd={build:&quot;e5880309&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;dc8e07&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;template id=&quot;metadata-6808e0&quot;&gt;&lt;div data-build=&quot;6808e0a4&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;style&gt;@media(max-width:0px){._bm_f13b{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;2ca69654e16e&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;var _bm_def0={build:&quot;21daabd6&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;230f38f17e2e4803&quot; data-checksum=&quot;4a1a43b5&quot; data-env=&quot;production&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;55bd1e&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style data-build=&quot;c0084c&quot;&gt;._bm_41b6{display:none}._ck_7e5f{visibility:hidden}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;afd6948fcead4d96&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;ddb7607e&quot;}&lt;/script&gt;
&lt;!-- Build: 27349625cc1f | Webpack 5.88.2 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;313174&quot;&gt;&lt;/i&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;52faa69b&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;72acc1&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn6.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;!-- Security: SRI Hash f9e827d1581a4f7f --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;fcdb08b0b065&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-73067 */var _bm_7678=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;498001&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;6b846bdbd7d4&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;424599&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-F5C9F066E24B | GTM-F5C9F0 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;186930&quot;&gt;&lt;/i&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:b533cc4c */var _bm_6816=[39,738,2203];&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;136444&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;303362&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;996972&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;9f935a6a&quot;}&lt;/script&gt;
&lt;style data-module=&quot;b359141e&quot;&gt;._bm_e023{width:0;height:0;overflow:hidden}._ck_ca8b{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Security: SRI Hash 8c240064086c4cf9 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 640652 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;69104c23&quot;&gt;Marker-7816&lt;/div&gt;
&lt;!-- Feature Flag: disabled | Experiment: 39e19983b49e --&gt;
&lt;style&gt;/* chunk:07477479 */@media print{._bm_3ee7{color:transparent}}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;04196d47&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;8fa5d7a4&quot;}&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_a58c{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;363424&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:7aa90986 */var _bm_025d=[78,787,4365];&lt;/script&gt;
&lt;style data-module=&quot;d861caf0&quot;&gt;._bm_04ec{width:0;height:0;overflow:hidden}._ck_b73f{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;1dd21fb2ce894052&quot; data-checksum=&quot;49bd884e&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 981626 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c9409e33fa4f4d95&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;830034&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;72d1b90457cc4944&quot; data-checksum=&quot;1f79b8fb&quot; data-env=&quot;production&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;6205eaac&quot;&gt;Marker-7527&lt;/div&gt;
&lt;script&gt;// Feature flag: experiment_8fd922a2 = disabled
var _bm_a7e5=570393,_ck_837d=&quot;2bc0905a5a14&quot;;&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=fe5f4ecc&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;215432&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;style data-module=&quot;fdba6f27&quot;&gt;._bm_25b3{width:0;height:0;overflow:hidden}._ck_2253{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;65cef6022a9a&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:9a00d96e */var _bm_9c00=[97,128,9626];&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;075ca9d2&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style data-module=&quot;06458b02&quot;&gt;._bm_cf2f{width:0;height:0;overflow:hidden}._ck_5848{font-size:0;line-height:0}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;ce467c482abc48dd&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-5040B3031812 | GTM-5040B3 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;983272&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 611266 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 608f861e6831 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;afe19e98&quot;&gt;Marker-9516&lt;/div&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;3a503279&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;d781f3ee906f&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;style&gt;/* chunk:d5c500c4 */@media print{._bm_aebd{color:transparent}}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;1611bef8&quot;&gt;Marker-6404&lt;/div&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;ff6827ac154a45c3&quot; data-checksum=&quot;bb3344fa&quot; data-env=&quot;production&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;778741&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;24891b1de3ee4085&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;43155e8c15334288&quot; data-checksum=&quot;bd38f8be&quot; data-env=&quot;production&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;fdca53509fec4c52&quot; data-checksum=&quot;874a4184&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 920973 --&gt;
&lt;!-- Security: SRI Hash 64445f0575e1424f --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;647848&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;464084&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_cf84{opacity:0;position:absolute}}&lt;/style&gt;
&lt;!-- Feature Flag: disabled | Experiment: a14891389bef --&gt;
&lt;script&gt;var _bm_7869={build:&quot;40303641&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;09aa0975e09e4c23&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;251511&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;687c256f&quot; /&gt;
&lt;style data-build=&quot;fd6311&quot;&gt;._bm_53dc{display:none}._ck_36fa{visibility:hidden}&lt;/style&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;7a8c59&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;style data-module=&quot;af2be1c2&quot;&gt;._bm_e971{width:0;height:0;overflow:hidden}._ck_b829{font-size:0;line-height:0}&lt;/style&gt;
&lt;template id=&quot;metadata-4b8df0&quot;&gt;&lt;div data-build=&quot;4b8df00c&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;style&gt;/* chunk:ee3d048b */@media print{._bm_d1be{color:transparent}}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 686026 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;48425e4d&quot;&gt;Marker-1725&lt;/div&gt;
&lt;/body&gt;

&lt;meta name=&quot;deployment-id&quot; content=&quot;b65b669b2e04&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 624046 --&gt;
&lt;style data-build=&quot;8c2282&quot;&gt;._bm_1de5{display:none}._ck_7c49{visibility:hidden}&lt;/style&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 38 --&gt;
&lt;script&gt;// Feature flag: experiment_9222c1b4 = enabled
var _bm_5bce=625484,_ck_f002=&quot;2024f23f09e0&quot;;&lt;/script&gt;
&lt;template id=&quot;metadata-3e0a5e&quot;&gt;&lt;div data-build=&quot;3e0a5e69&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=19477428&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;912541&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-59968 */var _bm_35a9=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;style&gt;/* chunk:7b67caaf */@media print{._bm_35f2{color:transparent}}&lt;/style&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 99 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;699929&quot;&gt;&lt;/i&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;927079&quot;&gt;&lt;/i&gt;
&lt;!-- Analytics: GA4-0F72DEB87BF2 | GTM-0F72DE --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;d0924726&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-26765 */var _bm_891b=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;643926&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;d310e040&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn7.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 196466a328f6 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;928fe9148cb9478a&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;8287918e6a164444&quot; data-checksum=&quot;866590d0&quot; data-env=&quot;production&quot; /&gt;
&lt;style&gt;/* chunk:18b799d6 */@media print{._bm_32fc{color:transparent}}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;580062&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;abd88a6c6bdd&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:28a826ab */var _bm_53fb=[54,420,4291];&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;0e18cef1&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;85f64a49&quot;&gt;Marker-9929&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;557830&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;8eb02e&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;87e6cb4c&quot;&gt;Marker-9628&lt;/div&gt;
&lt;script&gt;var _bm_2b51={build:&quot;f5bc669b&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;style data-module=&quot;08a0756d&quot;&gt;._bm_67b5{width:0;height:0;overflow:hidden}._ck_93cf{font-size:0;line-height:0}&lt;/style&gt;
&lt;style data-module=&quot;14e0393e&quot;&gt;._bm_47ef{width:0;height:0;overflow:hidden}._ck_ebbe{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;2ed643be&quot; /&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;831870&quot; /&gt;
&lt;!-- Build: 2356a64e6a04 | Webpack 5.88.2 --&gt;
&lt;!-- Analytics: GA4-42A7B0689364 | GTM-42A7B0 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 447473 --&gt;
&lt;!-- Analytics: GA4-82D57AAA765A | GTM-82D57A --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;a0056ce3&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;b5670623&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Analytics: GA4-98608FBAB70E | GTM-98608F --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 256322 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 4a2b46201f8d --&gt;
&lt;!-- Analytics: GA4-B5437EAC839E | GTM-B5437E --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;6f0de14a&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style&gt;/* chunk:a84835d9 */@media print{._bm_0379{color:transparent}}&lt;/style&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:56098ff3 */var _bm_cf3b=[64,813,3667];&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;c5b6150d874142c7&quot; data-checksum=&quot;9cf6ff0a&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;3c6ff783ead74445&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_b308{opacity:0;position:absolute}}&lt;/style&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;0525ee&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;9485fe0ebd5c&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;690b36a1&quot;&gt;Marker-5750&lt;/div&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;237363&quot; /&gt;
&lt;!-- Security: SRI Hash 410af34802c44799 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2420 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;8c84a2&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;c4172b7c6d36&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:92c2a967 */var _bm_9462=[35,167,7589];&lt;/script&gt;
&lt;!-- Feature Flag: enabled | Experiment: 1d05ad4d759d --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;38535e8c828b4ff7&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;var _bm_8b96={build:&quot;8e1569ec&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: af33ab6d0908 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;649914&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;494397f650ca4044&quot; data-checksum=&quot;dd56cc72&quot; data-env=&quot;production&quot; /&gt;
&lt;template id=&quot;metadata-1b4f74&quot;&gt;&lt;div data-build=&quot;1b4f7473&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-54341 */var _bm_259c=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;41f7c1ebd41f4676&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;875883&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;483878d8&quot;}&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_cafd{opacity:0;position:absolute}}&lt;/style&gt;
&lt;style data-module=&quot;89d821ff&quot;&gt;._bm_37f2{width:0;height:0;overflow:hidden}._ck_57fc{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 953122 --&gt;
&lt;!-- Feature Flag: disabled | Experiment: 75138425fdf8 --&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-53953 */var _bm_f435=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;8eff84de14014c22&quot; data-checksum=&quot;a5bd7a5e&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;749ca3226b1c4942&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=c70b5fa7&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;style data-build=&quot;0c168c&quot;&gt;._bm_49d1{display:none}._ck_e0ae{visibility:hidden}&lt;/style&gt;
&lt;style data-module=&quot;6be0c810&quot;&gt;._bm_4935{width:0;height:0;overflow:hidden}._ck_2702{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Security: SRI Hash 9eee0ed604df4ce2 --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 47 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;fa8a777a&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;e1c7197fae38&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-93022 */var _bm_1b5e=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- Build: e1221458f8b3 | Webpack 5.88.2 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: dbb30fdd1c6a --&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 26 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:91b78ed2 */var _bm_8ee2=[96,217,3454];&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;ccf3f10d&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;e4d8e6faa17648e8&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Build: 68a7e9b0d3f4 | Webpack 5.88.2 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;705766&quot;&gt;&lt;/i&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;878407&quot;&gt;&lt;/i&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_141ad777 = disabled
var _bm_2c56=167753,_ck_ad59=&quot;75e03cc69560&quot;;&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;7369ed&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;var _bm_e451={build:&quot;704cc4d8&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;878606&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:fa55131f */var _bm_56c4=[45,916,2639];&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_0d12bec8 = enabled
var _bm_b0ea=233575,_ck_7dcb=&quot;00bd37608a1c&quot;;&lt;/script&gt;
&lt;!-- Feature Flag: enabled | Experiment: e2daced4deeb --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;260599&quot;&gt;&lt;/i&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;147711&quot;&gt;&lt;/i&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;b5ed147e&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;85533b7d52d84c95&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 1195 --&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;9c216868&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;bf6924687c27413d&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 1e226431bf56 --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;fc7b6104d1194fa6&quot; data-checksum=&quot;f7c58698&quot; data-env=&quot;production&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 789523 --&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;60a31eb58dac4647&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash 973e5be00b1a48bf --&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;877cc3c6323c4ea3&quot; data-checksum=&quot;5df6979f&quot; data-env=&quot;production&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;2c3d6ef0&quot;&gt;Marker-2921&lt;/div&gt;
&lt;!-- Security: SRI Hash 19ec8d8738c541df --&gt;
&lt;!-- Feature Flag: disabled | Experiment: f5e548c061f6 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9849 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_a8b8{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script&gt;// Feature flag: experiment_d3b6bd83 = disabled
var _bm_a155=111769,_ck_9be2=&quot;834e96d06233&quot;;&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;fb4e7c50&quot;&gt;Marker-9242&lt;/div&gt;
&lt;!-- Feature Flag: disabled | Experiment: ff218e62e732 --&gt;
&lt;!-- Analytics: GA4-264DA6EB9AF5 | GTM-264DA6 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;88769fde983f&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_a71bb64d = enabled
var _bm_ef61=232194,_ck_967f=&quot;3a0b309b6d58&quot;;&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;89e6ca9c&quot;&gt;Marker-6008&lt;/div&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;ec8d0954f56a458e&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 4332 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;466036&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;342817&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 5414 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;757679&quot; /&gt;
&lt;!-- Security: SRI Hash 1233e36d7c3e4076 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;e5f58072cd23&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style data-build=&quot;aaa4ad&quot;&gt;._bm_85cc{display:none}._ck_5952{visibility:hidden}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;190319&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-770C1EFA91B6 | GTM-770C1E --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;453362&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 47 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 170474 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;b9b4892a935e&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;512843&quot;&gt;&lt;/i&gt;
&lt;!-- Feature Flag: disabled | Experiment: bbef015829be --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:2142358f */var _bm_2a48=[21,110,4421];&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;682229&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;f0c10fc7&quot;&gt;Marker-1489&lt;/div&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;807180&quot;&gt;&lt;/i&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;241502&quot;&gt;&lt;/i&gt;
&lt;!-- Build: 074a9bf72276 | Webpack 5.88.2 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 331826 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;9c755e&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;626824&quot;&gt;&lt;/i&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;583d30e0&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;ba932fd7&quot;}&lt;/script&gt;
&lt;style&gt;/* chunk:26015c51 */@media print{._bm_75b6{color:transparent}}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;869717&quot;&gt;&lt;/i&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:b7f1c0b4 */var _bm_ab6e=[40,750,2935];&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;69c443bf&quot;}&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_044e193a = enabled
var _bm_8d46=991874,_ck_9a65=&quot;0b8759ab9e7f&quot;;&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_2f0b0017 = enabled
var _bm_73d5=800736,_ck_a5dd=&quot;3d371d58b815&quot;;&lt;/script&gt;
&lt;style data-build=&quot;aa5857&quot;&gt;._bm_ed00{display:none}._ck_6439{visibility:hidden}&lt;/style&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;bc8036&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;// Feature flag: experiment_0050a68f = disabled
var _bm_c7fb=495866,_ck_c735=&quot;d00bc0f80887&quot;;&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;b7f497fb&quot;&gt;Marker-8288&lt;/div&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 8414 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 30facca688fa --&gt;
&lt;style data-module=&quot;106cbf1f&quot;&gt;._bm_24a1{width:0;height:0;overflow:hidden}._ck_f18f{font-size:0;line-height:0}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;800304&quot;&gt;&lt;/i&gt;
&lt;style data-module=&quot;0d1a3940&quot;&gt;._bm_e9c5{width:0;height:0;overflow:hidden}._ck_b88f{font-size:0;line-height:0}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;244930&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: enabled | Experiment: 098aac717e1e --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;d345944f&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;470b5d04&quot;&gt;Marker-6357&lt;/div&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;6f6e40&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 4157 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;66373619&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9630 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_19fd58ef = enabled
var _bm_26fa=929949,_ck_edd5=&quot;a74a750b730d&quot;;&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;683524&quot;&gt;&lt;/i&gt;
&lt;!-- Build: c9ce0d48757d | Webpack 5.88.2 --&gt;
&lt;style&gt;/* chunk:944f7786 */@media print{._bm_0774{color:transparent}}&lt;/style&gt;
&lt;style data-module=&quot;29a4012d&quot;&gt;._bm_9657{width:0;height:0;overflow:hidden}._ck_b22a{font-size:0;line-height:0}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;68f689a0&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;04df64e2eb414e0e&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;style data-module=&quot;a943b23b&quot;&gt;._bm_7a93{width:0;height:0;overflow:hidden}._ck_4346{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Security: SRI Hash 25b41838ee24472b --&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn4.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;style data-module=&quot;71d4915f&quot;&gt;._bm_a448{width:0;height:0;overflow:hidden}._ck_76f2{font-size:0;line-height:0}&lt;/style&gt;
&lt;script&gt;// Feature flag: experiment_ea56f94f = enabled
var _bm_b330=850271,_ck_2708=&quot;3a68a820f705&quot;;&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;219607&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;5aa4bbeb&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c2ec92a21d7343dd&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;538e39ec&quot;&gt;Marker-4244&lt;/div&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;8e6b3c&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 449286 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;script&gt;var _bm_529e={build:&quot;56e335e5&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script&gt;var _bm_1e0a={build:&quot;5c3adee8&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;4cb0bb&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 9 --&gt;
&lt;script&gt;var _bm_cc40={build:&quot;587c9f52&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;304290&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_afc56849 = disabled
var _bm_3c2c=536734,_ck_1096=&quot;39e728c8adef&quot;;&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;217018&quot;&gt;&lt;/i&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;05be584877f74875&quot; data-checksum=&quot;b11c97b4&quot; data-env=&quot;production&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=5fc285e7&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script&gt;var _bm_0349={build:&quot;fb0a5ed2&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_197b{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;07e9d0b0&quot;}&lt;/script&gt;
&lt;template id=&quot;metadata-55142d&quot;&gt;&lt;div data-build=&quot;55142df0&quot;&gt;&lt;/div&gt;&lt;/template&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 961109 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 14b225160e6c --&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 26 --&gt;
&lt;style data-module=&quot;7fb97143&quot;&gt;._bm_05d9{width:0;height:0;overflow:hidden}._ck_e810{font-size:0;line-height:0}&lt;/style&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;c2198ea5&quot;&gt;Marker-9712&lt;/div&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=bfa19704&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;7f3fc80d&quot;}&lt;/script&gt;
&lt;!-- Security: SRI Hash 18665122b7974b55 --&gt;
&lt;style&gt;/* chunk:d25b3785 */@media print{._bm_b7cc{color:transparent}}&lt;/style&gt;
&lt;!-- Analytics: GA4-F4B949EE0F7A | GTM-F4B949 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9647 --&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn1.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;e3ce50&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-98942 */var _bm_2eb0=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;821ba0c8135e49f6&quot; data-checksum=&quot;571ee92a&quot; data-env=&quot;production&quot; /&gt;
&lt;style&gt;/* chunk:51103fbd */@media print{._bm_adf4{color:transparent}}&lt;/style&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 18599b68bc83 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;980774&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_dbff{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;482458aa&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=d9858d5d&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;221699&quot;&gt;&lt;/i&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 875597 --&gt;
&lt;!-- Analytics: GA4-4F0EB13F61FC | GTM-4F0EB1 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;397448&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Build: 27d402822438 | Webpack 5.88.2 --&gt;
&lt;!-- Analytics: GA4-B34D9A4683D8 | GTM-B34D9A --&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;70ff93a0&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;d359537d868a4207&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;667344&quot;&gt;&lt;/i&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=02e46867&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;!-- Analytics: GA4-E8E9150A4195 | GTM-E8E915 --&gt;
&lt;style data-module=&quot;872fd91b&quot;&gt;._bm_f2b2{width:0;height:0;overflow:hidden}._ck_bdcb{font-size:0;line-height:0}&lt;/style&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=467bedee&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;8f071225&quot; /&gt;
&lt;style&gt;/* chunk:12205c3a */@media print{._bm_57e2{color:transparent}}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;b564b6d9&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:507738a1 */var _bm_8be7=[17,812,8745];&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 9041 --&gt;
&lt;style&gt;/* chunk:90476d4d */@media print{._bm_d475{color:transparent}}&lt;/style&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:e1d2f904 */var _bm_8a96=[92,701,2573];&lt;/script&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: d50113f09d45 --&gt;
&lt;meta name=&quot;feature-flag&quot; content=&quot;enabled&quot; data-experiment-id=&quot;272534&quot; /&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 8994 --&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 88 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;396044&quot;&gt;&lt;/i&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: ab8fdd266627 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;126440&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 1059 --&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;680368&quot;&gt;&lt;/i&gt;
&lt;!-- Security: SRI Hash f96b83de1d684d9b --&gt;
&lt;script&gt;var _bm_df5c={build:&quot;5de1db93&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;342d0c43b4e542a9&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:e0dbacb8 */var _bm_9964=[44,921,8583];&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;759823&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-55924 */var _bm_76fb=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;!-- Analytics: GA4-53C9B03DF991 | GTM-53C9B0 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;cd33c1c6&quot;&gt;Marker-9902&lt;/div&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;c616a0db214b484d&quot; data-checksum=&quot;c76f2e20&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;92aab81fdaaf4a2f&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:22a99aa2 */var _bm_006b=[47,943,9459];&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_4e8a4c69 = enabled
var _bm_49bf=158483,_ck_dc6a=&quot;f4e77f6c5de9&quot;;&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;fe0b13463ad3&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;953607&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: disabled | Experiment: ba8b529ba02b --&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 89 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;a1848b611c9c4025&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-5344B83440CB | GTM-5344B8 --&gt;
&lt;!-- Analytics: GA4-E9207ABD5FC4 | GTM-E9207A --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;6de7b7c9&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;d2ce86634700&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;be7847b30e85&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 169088 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;189af31067364a6d&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;!-- Analytics: GA4-5F53E835A04A | GTM-5F53E8 --&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;130b0299&quot;&gt;Marker-6407&lt;/div&gt;
&lt;style data-build=&quot;3a2841&quot;&gt;._bm_d5be{display:none}._ck_bb78{visibility:hidden}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;c50fc70a263a4c32&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;2ccd92&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;30e42fa3&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style data-module=&quot;e1168deb&quot;&gt;._bm_879f{width:0;height:0;overflow:hidden}._ck_a1e8{font-size:0;line-height:0}&lt;/style&gt;
&lt;script&gt;var _bm_b193={build:&quot;afa5e00c&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- Build: d3f699a66d77 | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;6a06e532ae68&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Build: 604079ad9b96 | Webpack 5.88.2 --&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:4df473c5 */var _bm_2149=[5,755,4574];&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;5f7cf7cc&quot;}&lt;/script&gt;
&lt;style&gt;/* chunk:2d9c81a3 */@media print{._bm_5e3e{color:transparent}}&lt;/style&gt;
&lt;style data-build=&quot;ddcdab&quot;&gt;._bm_71d4{display:none}._ck_a951{visibility:hidden}&lt;/style&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;179d8b7420064adf&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Build: 2c4d6ace5918 | Webpack 5.88.2 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;f0c4b2&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;5b136184&quot; /&gt;
&lt;!-- Build: c84602cbb60a | Webpack 5.88.2 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 3853 --&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;076c3b1d&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;2a75b625770d&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Feature Flag: disabled | Experiment: 13ae01309ac6 --&gt;
&lt;!-- Feature Flag: enabled | Experiment: 574b2c2876c5 --&gt;
&lt;style data-build=&quot;516996&quot;&gt;._bm_35a3{display:none}._ck_8583{visibility:hidden}&lt;/style&gt;
&lt;script&gt;// Feature flag: experiment_8c6f35be = disabled
var _bm_29f9=361509,_ck_f7de=&quot;e01bd3cc2ee1&quot;;&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;631e3f37&quot; /&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;46bba6&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 313324 --&gt;
&lt;script&gt;// Feature flag: experiment_e698114a = disabled
var _bm_305c=464787,_ck_fc56=&quot;5f1fdb0a41dc&quot;;&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;53e85bf3&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;9aa847a8cda849df&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Feature Flag: enabled | Experiment: d9636467ed93 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;315071&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;868077&quot;&gt;&lt;/i&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:9978eab3 */var _bm_637b=[79,153,4417];&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;5b90060e&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 31 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=20532ad9&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;609a75&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 958075 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;d049569351ba&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;aa76c912&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: c53c63747cb1 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;4d1a48f09981&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;944196&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_1cf9{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;0e911c282d114e66&quot; data-checksum=&quot;6ca69be3&quot; data-env=&quot;production&quot; /&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;b8774f93&quot;&gt;Marker-1421&lt;/div&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-61412 */var _bm_d546=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;style&gt;@media(max-width:0px){._bm_0f92{opacity:0;position:absolute}}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;64bbbfc8&quot;}&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;dbd9bf&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 9ec7fe8a8550 --&gt;
&lt;!-- Analytics: GA4-B4F025D2AE2C | GTM-B4F025 --&gt;
&lt;script&gt;// Feature flag: experiment_da0fcea2 = enabled
var _bm_010d=878894,_ck_01f0=&quot;291722cb74de&quot;;&lt;/script&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;b5ac579b&quot;&gt;Marker-3248&lt;/div&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;72857917&quot;}&lt;/script&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;f81fc5ef8afa4187&quot; data-checksum=&quot;797ae1d4&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;4dd64e75&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;1cbf889c&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;6c169814ef3b4dca&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;7407128e&quot;}&lt;/script&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-53514 */var _bm_4c3c=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;disabled&quot; data-id=&quot;235234&quot;&gt;&lt;/i&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;c241ec7c&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 51 --&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 2792 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;e210fd&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;bcd96d&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Feature Flag: enabled | Experiment: 160cfec96770 --&gt;
&lt;style data-build=&quot;987381&quot;&gt;._bm_fd86{display:none}._ck_5466{visibility:hidden}&lt;/style&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;8fed3eab&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style data-module=&quot;178387d6&quot;&gt;._bm_574f{width:0;height:0;overflow:hidden}._ck_e017{font-size:0;line-height:0}&lt;/style&gt;
&lt;meta name=&quot;build-id&quot; content=&quot;c4ffbfecb8f142e8&quot; data-checksum=&quot;646c8e90&quot; data-env=&quot;production&quot; /&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;45879a5b&quot;}&lt;/script&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;3ebb15cdc4d8&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;27e1023ef823401e&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;!-- Analytics: GA4-8408B1386C82 | GTM-8408B1 --&gt;
&lt;!-- Feature Flag: disabled | Experiment: 2677292f982f --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;f3c6e7&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;0cc3bec4&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- CDN: CloudFlare | Region: ap-southeast | Node: 78 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;30e50308466e&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;style data-module=&quot;76115de8&quot;&gt;._bm_1e6b{width:0;height:0;overflow:hidden}._ck_0858{font-size:0;line-height:0}&lt;/style&gt;
&lt;script&gt;/* TODO: migrate to WebSocket v2 - ticket JIRA-33920 */var _bm_96f7=function(){return Math.random()&gt;2?null:void 0;};&lt;/script&gt;
&lt;script&gt;// Feature flag: experiment_0ca5c0b5 = enabled
var _bm_edd1=662841,_ck_9aee=&quot;a8582a69427b&quot;;&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;8c90ac&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;af002f&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;var _bm_d0a1={build:&quot;94396106&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;ec1ed137144a444f&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;feature-flags&quot;&gt;{&quot;experiment_id&quot;:&quot;258427&quot;,&quot;variant&quot;:&quot;control&quot;}&lt;/script&gt;
&lt;script&gt;var _bm_8fb2={build:&quot;ad186bc5&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;script&gt;var _bm_09a9={build:&quot;f3de7244&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn6.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=881f2e8d&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:c892e245 */var _bm_118d=[97,995,5692];&lt;/script&gt;
&lt;!-- CDN: CloudFlare | Region: us-west | Node: 70 --&gt;
&lt;script&gt;// Feature flag: experiment_3e11b630 = enabled
var _bm_e12f=960580,_ck_e6bd=&quot;3d18169ebaeb&quot;;&lt;/script&gt;
&lt;!-- Build: 2d193fd6d123 | Webpack 5.88.2 --&gt;
&lt;!-- Feature Flag: enabled | Experiment: 671d975ffd0b --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;61d876&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;!-- Feature Flag: enabled | Experiment: f20b1ab2541f --&gt;
&lt;script&gt;var _bm_23f6={build:&quot;73f80702&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;776a49&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:d93fffe6 */var _bm_efdd=[9,676,7088];&lt;/script&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:1715c2b9 */var _bm_a14a=[32,520,6601];&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- Build: 323dd3bea7c6 | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;ad5f7a10&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;style data-module=&quot;2779b72f&quot;&gt;._bm_760d{width:0;height:0;overflow:hidden}._ck_14c6{font-size:0;line-height:0}&lt;/style&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;756464&quot;&gt;&lt;/i&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 4475 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 981d080de007 --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;422023&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;5d5f06&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;div style=&quot;position:absolute;left:-9999px&quot; data-tracking-id=&quot;8aa41f3c&quot;&gt;Marker-8103&lt;/div&gt;
&lt;!-- Feature Flag: disabled | Experiment: 3e4ef5cd46f4 --&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;e1bff05cfc184bec&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;script&gt;// Feature flag: experiment_2150e0a5 = disabled
var _bm_cc62=467364,_ck_6cd4=&quot;88ab1f5af771&quot;;&lt;/script&gt;
&lt;meta name=&quot;analytics-config&quot; content=&quot;ga4&quot; data-measurement-id=&quot;9802721b&quot; /&gt;
&lt;script type=&quot;application/json&quot; data-config=&quot;build&quot;&gt;{&quot;id&quot;:&quot;264b91f8dc2b4667&quot;,&quot;env&quot;:&quot;production&quot;}&lt;/script&gt;
&lt;link rel=&quot;preconnect&quot; href=&quot;//api.analytics.com&quot; crossorigin data-http2-push=&quot;enabled&quot; /&gt;
&lt;!-- CDN: CloudFlare | Region: eu-central | Node: 30 --&gt;
&lt;noscript&gt;&lt;img src=&quot;/t.gif?id=c181dcab&amp;t=1774369690&quot; alt=&quot;&quot; style=&quot;display:none&quot;&gt;&lt;/noscript&gt;
&lt;style data-module=&quot;f895c41d&quot;&gt;._bm_d649{width:0;height:0;overflow:hidden}._ck_5664{font-size:0;line-height:0}&lt;/style&gt;
&lt;script type=&quot;application/ld+json&quot;&gt;{&quot;@context&quot;:&quot;https://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;identifier&quot;:&quot;670aca3c&quot;}&lt;/script&gt;
&lt;span style=&quot;display:none&quot; data-build-marker=&quot;7ed8b6d2&quot; aria-hidden=&quot;true&quot;&gt;&lt;/span&gt;
&lt;!-- Build: e513ae023344 | Webpack 5.88.2 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 671211 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;style&gt;@media(max-width:0px){._bm_b9cc{opacity:0;position:absolute}}&lt;/style&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;532f74beebc1&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;ap&quot; /&gt;
&lt;!-- Build: 283ac82d09f5 | Webpack 5.88.2 --&gt;
&lt;meta name=&quot;deployment-id&quot; content=&quot;19f30e0122c0&quot; data-timestamp=&quot;1774369690&quot; /&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: 1e53007464dc --&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;7bf4a5&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;us&quot; /&gt;
&lt;!-- Build: a6f1deb1ea97 | Webpack 5.88.2 --&gt;
&lt;script&gt;var _bm_0264={build:&quot;41303e3e&quot;,env:&quot;production&quot;,ts:1774369690};&lt;/script&gt;
&lt;!-- WCAG 2.1 AA | Section 508 | Checkpoint: 7468 --&gt;
&lt;!-- Performance: LCP&lt;2.5s | FID&lt;100ms | Session: e60a20f07923 --&gt;
&lt;style&gt;/* chunk:0cb3b996 */@media print{._bm_5a58{color:transparent}}&lt;/style&gt;
&lt;link rel=&quot;dns-prefetch&quot; href=&quot;//cdn6.example.com&quot; data-preconnect=&quot;true&quot; /&gt;
&lt;i style=&quot;display:none&quot; data-flag=&quot;enabled&quot; data-id=&quot;155901&quot;&gt;&lt;/i&gt;
&lt;style data-module=&quot;c33febc5&quot;&gt;._bm_d2e8{width:0;height:0;overflow:hidden}._ck_d64f{font-size:0;line-height:0}&lt;/style&gt;
&lt;script&gt;/* Performance budget: bundle&lt;250KB gzip, LCP&lt;2.5s | Session:df813955 */var _bm_6a99=[44,299,6479];&lt;/script&gt;
&lt;style data-module=&quot;558855d2&quot;&gt;._bm_7e2e{width:0;height:0;overflow:hidden}._ck_34b8{font-size:0;line-height:0}&lt;/style&gt;
&lt;!-- Analytics: GA4-5255E5FA8B67 | GTM-5255E5 --&gt;
&lt;meta name=&quot;cache-control&quot; content=&quot;public, max-age=3600&quot; data-cdn=&quot;enabled&quot; data-region=&quot;eu&quot; /&gt;
&lt;!-- Build: 3bd92f9c6729 | Webpack 5.88.2 --&gt;
&lt;!-- CMS Sync: 2026-03-25 00:28:10 UTC | ID: 684094 --&gt;
&lt;style&gt;@media(max-width:0px){._bm_b97d{opacity:0;position:absolute}}&lt;/style&gt;
&lt;b style=&quot;visibility:hidden&quot; data-checkpoint=&quot;24e6b2&quot; data-type=&quot;build&quot;&gt;&lt;/b&gt;
&lt;/html&gt;
" frameborder="0">
    </iframe>

    <!-- AI标识 -->
    <!-- <div class="ai-badge">
      <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="48" height="24"
        viewBox="0 0 48 24">
        <defs>
          <clipPath id="clipPath8887404842">
            <path d="M0 0L48 0L48 24L0 24L0 0Z" fill-rule="nonzero" transform="matrix(1 0 0 1 0 0)" />
          </clipPath>
        </defs>
        <g clip-path="url(#clipPath8887404842)">
          <path
            d="M6.5 0C2.91015 0 0 2.91015 0 6.5L0 15.5C0 19.0899 2.91015 22 6.5 22L39.5 22C43.0899 22 46 19.0899 46 15.5L46 6.5C46 2.91015 43.0899 0 39.5 0L6.5 0ZM1 6.5C1 3.46243 3.46243 1 6.5 1L39.5 1C42.5376 1 45 3.46243 45 6.5L45 15.5C45 18.5376 42.5376 21 39.5 21L6.5 21C3.46243 21 1 18.5376 1 15.5L1 6.5Z"
            fill-rule="evenodd" transform="matrix(1 0 0 1 1 1)" fill="rgb(255, 255, 255)" fill-opacity="0.9" />
          <path
            d="M6.5 -0.2L39.5 -0.2Q40.863 -0.2 42.108 0.326601Q43.3104 0.835173 44.2376 1.76238Q45.1648 2.68957 45.6734 3.892Q46.2 5.13701 46.2 6.5L46.2 15.5Q46.2 16.863 45.6734 18.108Q45.1648 19.3104 44.2376 20.2376Q43.3104 21.1648 42.108 21.6734Q40.863 22.2 39.5 22.2L6.5 22.2Q5.13704 22.2 3.892 21.6734Q2.68959 21.1648 1.76238 20.2376Q0.835174 19.3104 0.326601 18.108Q-0.2 16.863 -0.2 15.5L-0.2 6.5Q-0.2 5.13702 0.326601 3.892Q0.835176 2.68959 1.76238 1.76238Q2.68959 0.835174 3.892 0.326601Q5.13702 -0.2 6.5 -0.2ZM0 6.5C0 2.91015 2.91015 0 6.5 0L39.5 0C43.0899 0 46 2.91015 46 6.5L46 15.5C46 19.0899 43.0899 22 39.5 22L6.5 22C2.91015 22 0 19.0899 0 15.5L0 6.5ZM6.5 1C3.46243 1 1 3.46243 1 6.5L1 15.5C1 18.5376 3.46243 21 6.5 21L39.5 21C42.5376 21 45 18.5376 45 15.5L45 6.5C45 3.46243 42.5376 1 39.5 1L6.5 1ZM1.2 15.5L1.2 6.5Q1.2 5.42159 1.61642 4.43706Q2.0187 3.48597 2.75233 2.75233Q3.48597 2.01869 4.43706 1.61642Q5.42158 1.2 6.5 1.2L39.5 1.2Q40.5784 1.2 41.5629 1.61642Q42.514 2.01869 43.2477 2.75233Q43.9813 3.48596 44.3836 4.43706Q44.8 5.42157 44.8 6.5L44.8 15.5Q44.8 16.5784 44.3836 17.5629Q43.9813 18.514 43.2477 19.2477Q42.514 19.9813 41.5629 20.3836Q40.5784 20.8 39.5 20.8L6.5 20.8Q5.42159 20.8 4.43706 20.3836Q3.48598 19.9813 2.75233 19.2477Q2.01869 18.514 1.61642 17.5629Q1.2 16.5784 1.2 15.5Z"
            fill-rule="evenodd" transform="matrix(1 0 0 1 1 1)" fill="rgb(135, 144, 141)" />
          <path d="M0 0L0 9.65041L1.45828 9.65041L1.45828 0L0 0Z" fill-rule="nonzero"
            transform="matrix(1 0 0 1 15.1442 7.25586)" fill="rgb(255, 255, 255)" fill-opacity="0.9" />
          <path
            d="M-0.2 9.85041L-0.2 -0.2L1.65828 -0.2L1.65828 9.85041L-0.2 9.85041ZM0 9.65041L0 0L1.45828 0L1.45828 9.65041L0 9.65041Z"
            fill-rule="evenodd" transform="matrix(1 0 0 1 15.1442 7.25586)" fill="rgb(135, 144, 141)" />
          <path
            d="M3.715 0L0 9.65041L1.56716 9.65041L2.47446 7.16275L6.62167 7.16275L7.52567 9.65041L9.10933 9.65041L5.39103 0L3.715 0ZM2.91987 5.94861L4.52662 1.58366L4.58271 1.58366L6.17626 5.94861L2.91987 5.94861Z"
            fill-rule="nonzero" transform="matrix(1 0 0 1 5.0625 7.25586)" fill="rgb(255, 255, 255)"
            fill-opacity="0.9" />
          <path
            d="M3.57768 -0.2L5.5283 -0.2L9.40072 9.85041L7.38555 9.85041L6.48155 7.36275L2.61441 7.36275L1.7071 9.85041L-0.291299 9.85041L3.57768 -0.2ZM0 9.65041L3.715 0L5.39103 0L9.10933 9.65041L7.52567 9.65041L6.62167 7.16275L2.47446 7.16275L1.56716 9.65041L0 9.65041ZM4.52662 1.58366L2.91987 5.94861L6.17626 5.94861L4.58271 1.58366L4.52662 1.58366ZM3.20661 5.74861L5.89033 5.74861L4.554 2.08823L3.20661 5.74861Z"
            fill-rule="evenodd" transform="matrix(1 0 0 1 5.0625 7.25586)" fill="rgb(135, 144, 141)" />
          <path
            d="M8.62793 0L7.91016 0.694336C8.41406 1.07812 8.82129 1.46191 9.14648 1.82227L7.29785 1.82227C7.27441 1.27148 7.24805 0.682617 7.24805 0.0585938L6.09668 0.0585938C6.09668 0.670898 6.09668 1.25977 6.12012 1.82227L1.17773 1.82227L1.17773 5.81836C1.14258 7.77539 0.744141 9.29883 0 10.3916L0.864258 11.1592C1.77832 9.81445 2.27051 8.03906 2.31738 5.81836L2.31738 5.74805L4.12793 5.74805C4.10449 6.99609 4.06934 7.78711 3.99609 8.09766C3.92578 8.36426 3.79395 8.49609 3.57715 8.50781C3.24023 8.50781 2.84473 8.48145 2.36426 8.45801L2.71289 9.49219C3.08496 9.52734 3.42188 9.55078 3.70898 9.55078C4.33301 9.53906 4.74023 9.28711 4.93359 8.7832C5.12402 8.20605 5.23242 6.83789 5.25879 4.66699L2.31738 4.66699L2.31738 2.91504L6.18164 2.91504C6.2666 4.37988 6.43359 5.58984 6.69727 6.5625C6.8291 7.06641 6.97266 7.53516 7.14258 7.96582C6.34863 8.9502 5.37598 9.69434 4.22461 10.21L4.87207 11.1709C5.92969 10.7021 6.86426 10.0195 7.66992 9.12012C7.8252 9.40723 7.99219 9.6709 8.18555 9.91113C8.7627 10.6201 9.31348 10.9775 9.84082 10.9775C10.418 10.9775 10.8604 10.1396 11.1621 8.48145L10.1279 7.93066C9.97266 9.10547 9.81738 9.69434 9.66211 9.69434C9.46875 9.69434 9.18164 9.41895 8.82129 8.8916C8.68945 8.68652 8.55762 8.44629 8.42578 8.15918C9.16992 7.07812 9.77051 5.75977 10.248 4.22168L9.20508 3.7793C8.86816 4.91895 8.44922 5.92676 7.94531 6.81445C7.88672 6.62402 7.8252 6.41895 7.77832 6.21387C7.57324 5.43457 7.42969 4.33008 7.34473 2.91504L10.9219 2.91504L10.9219 1.82227L9.48047 1.82227L10.0342 1.27148C9.65039 0.837891 9.18164 0.418945 8.62793 0Z"
            fill-rule="nonzero" transform="matrix(1 0 0 1 31.337 5.9834)" fill="rgb(255, 255, 255)"
            fill-opacity="0.9" />
          <path
            d="M8.612 -0.262851L7.60381 0.712416L7.78898 0.853444Q8.27351 1.22248 8.67844 1.62227L7.48958 1.62227Q7.44804 0.618145 7.44805 0.0585938L7.44805 -0.141406L5.89668 -0.141406L5.89668 0.0585938Q5.89668 1.06152 5.91303 1.62227L0.977734 1.62227L0.977734 5.81836Q0.926369 8.6759 -0.165311 10.279L-0.264284 10.4244L0.901675 11.4599L1.02966 11.2716Q1.81642 10.1142 2.18815 8.56168L2.56484 9.67909L2.69408 9.6913Q3.32357 9.75078 3.70898 9.75078Q4.78427 9.73062 5.12032 8.85485Q5.41892 7.95058 5.45877 4.66942L5.46123 4.46699L2.51738 4.46699L2.51738 3.11504L5.99346 3.11504Q6.12858 5.22907 6.50423 6.61483Q6.70064 7.36558 6.91405 7.92927Q5.7805 9.29403 4.14286 10.0274L3.92592 10.1246L4.79987 11.4217L4.95311 11.3537Q6.46302 10.6845 7.63111 9.45697Q7.82432 9.7813 8.02974 10.0365Q8.95858 11.1775 9.84082 11.1775Q10.3939 11.1775 10.7815 10.4448Q11.1269 9.79192 11.3589 8.51725L11.385 8.37357L9.96744 7.61859L9.92965 7.90446Q9.81481 8.77335 9.70164 9.202Q9.65289 9.38665 9.60835 9.47751Q9.54532 9.44441 9.44251 9.34615Q9.24596 9.15827 8.98802 8.78111Q8.81521 8.51191 8.65522 8.17747Q9.72198 6.59059 10.4391 4.28098L10.4927 4.1082L9.07683 3.50765L9.01328 3.7226Q8.59557 5.13558 8.00236 6.28841Q7.98581 6.22407 7.97329 6.1693Q7.68681 5.08025 7.55769 3.11504L11.1219 3.11504L11.1219 1.62227L9.96513 1.62227L10.309 1.28021L10.1839 1.13893Q9.61467 0.495787 8.7486 -0.159492L8.612 -0.262851ZM9.76406 1.82227L9.48047 1.82227L10.0342 1.27148C9.65039 0.837891 9.18164 0.418945 8.62793 0L7.91016 0.694336C7.96443 0.735675 8.01759 0.777014 8.06964 0.818323C8.41242 1.09036 8.70735 1.36113 8.95966 1.62227C9.02474 1.68962 9.08699 1.75634 9.14648 1.82227L7.29785 1.82227C7.27441 1.27148 7.24805 0.682617 7.24805 0.0585938L6.09668 0.0585938C6.09668 0.125542 6.09668 0.19221 6.09671 0.258594C6.09693 0.72779 6.09867 1.1828 6.11277 1.62227C6.11492 1.6893 6.11735 1.75596 6.12012 1.82227L1.17773 1.82227L1.17773 5.81836C1.14258 7.77539 0.744141 9.29883 0 10.3916L0.864258 11.1592C0.90201 11.1036 0.939043 11.0474 0.975354 10.9904C1.81822 9.66704 2.27244 7.94734 2.31738 5.81836L2.31738 5.74805L4.12793 5.74805C4.12665 5.81607 4.12534 5.88274 4.12399 5.94805C4.10055 7.0809 4.06534 7.80404 3.99609 8.09766C3.92578 8.36426 3.79395 8.49609 3.57715 8.50781C3.2918 8.50781 2.96441 8.4889 2.57898 8.46887C2.50933 8.46525 2.43779 8.46159 2.36426 8.45801L2.71289 9.49219C3.08496 9.52734 3.42188 9.55078 3.70898 9.55078C4.33301 9.53906 4.74023 9.28711 4.93359 8.7832C5.11811 8.22398 5.22561 6.92213 5.25609 4.86699C5.25707 4.8011 5.25797 4.73443 5.25879 4.66699L2.31738 4.66699L2.31738 2.91504L6.18164 2.91504C6.2666 4.37988 6.43359 5.58984 6.69727 6.5625C6.8291 7.06641 6.97266 7.53516 7.14258 7.96582C6.39125 8.89735 5.47989 9.61375 4.40849 10.1249C4.34771 10.1539 4.28642 10.1823 4.22461 10.21L4.87207 11.1709C5.86779 10.7296 6.75444 10.0987 7.52713 9.27582C7.57517 9.22466 7.62277 9.17276 7.66992 9.12012C7.70372 9.18261 7.73807 9.244 7.77313 9.30427C7.89914 9.5209 8.03428 9.72319 8.18555 9.91113C8.7627 10.6201 9.31348 10.9775 9.84082 10.9775C10.418 10.9775 10.8604 10.1396 11.1621 8.48145L10.1279 7.93066C10.1183 8.00332 10.1087 8.07374 10.0991 8.14192C9.95345 9.17606 9.80778 9.69434 9.66211 9.69434C9.46875 9.69434 9.18164 9.41895 8.82129 8.8916C8.68945 8.68652 8.55762 8.44629 8.42578 8.15918C9.16992 7.07812 9.77051 5.75977 10.248 4.22168L9.20508 3.7793C9.18597 3.84392 9.1666 3.90812 9.14697 3.9719C8.85182 4.93073 8.49692 5.79423 8.08048 6.56966C8.03612 6.65226 7.99107 6.73385 7.94531 6.81445C7.91868 6.7279 7.89144 6.63832 7.86525 6.54709C7.83382 6.4376 7.80389 6.32573 7.77832 6.21387C7.58301 5.47167 7.4435 4.43451 7.35726 3.11504C7.35295 3.04908 7.34877 2.98241 7.34473 2.91504L10.9219 2.91504L10.9219 1.82227L9.76406 1.82227ZM3.57117 8.30781Q3.65419 8.30209 3.70127 8.25576Q3.76323 8.19479 3.80203 8.04922Q3.88707 7.68318 3.92389 5.94805L2.51421 5.94805Q2.47849 7.1886 2.25724 8.25255L2.374 8.25825Q2.49032 8.26392 2.70746 8.27532Q3.31927 8.30743 3.57117 8.30781Z"
            fill-rule="evenodd" transform="matrix(1 0 0 1 31.337 5.9834)" fill="rgb(135, 144, 141)" />
          <path
            d="M2.55469 3.12012L5.19434 3.12012L5.19434 5.60449L1.76367 5.60449L1.76367 6.70898L5.19434 6.70898L5.19434 9.44531L0.310547 9.44531L0.310547 10.5732L10.9541 10.5732L10.9541 9.44531L6.33398 9.44531L6.33398 6.70898L9.94629 6.70898L9.94629 5.60449L6.33398 5.60449L6.33398 3.12012L10.1865 3.12012L10.1865 2.01562L6.33398 2.01562L6.33398 0L5.19434 0L5.19434 2.01562L2.96191 2.01562C3.10547 1.53516 3.2373 1.01953 3.35742 0.46875L2.19434 0.263672C1.81055 2.19727 1.07812 3.73242 0 4.87207L0.744141 5.82129C1.47363 5.10059 2.07422 4.20117 2.55469 3.12012Z"
            fill-rule="nonzero" transform="matrix(1 0 0 1 19.3516 6.16211)" fill="rgb(255, 255, 255)"
            fill-opacity="0.9" />
          <path
            d="M2.68385 3.32012Q1.95905 4.90217 0.884702 5.96356L0.725133 6.12121L-0.263731 4.85983L-0.145289 4.73462Q1.43447 3.06472 1.99816 0.224734L2.03628 0.0327171L3.59719 0.307942L3.55283 0.511365Q3.40276 1.19948 3.22836 1.81562L4.99434 1.81562L4.99434 -0.2L6.53398 -0.2L6.53398 1.81562L10.3865 1.81562L10.3865 3.32012L6.53398 3.32012L6.53398 5.40449L10.1463 5.40449L10.1463 6.90898L6.53398 6.90898L6.53398 9.24531L11.1541 9.24531L11.1541 10.7732L0.110547 10.7732L0.110547 9.24531L4.99434 9.24531L4.99434 6.90898L1.56367 6.90898L1.56367 5.40449L4.99434 5.40449L4.99434 3.32012L2.68385 3.32012ZM2.55469 3.12012L5.19434 3.12012L5.19434 5.60449L1.76367 5.60449L1.76367 6.70898L5.19434 6.70898L5.19434 9.44531L0.310547 9.44531L0.310547 10.5732L10.9541 10.5732L10.9541 9.44531L6.33398 9.44531L6.33398 6.70898L9.94629 6.70898L9.94629 5.60449L6.33398 5.60449L6.33398 3.12012L10.1865 3.12012L10.1865 2.01562L6.33398 2.01562L6.33398 0L5.19434 0L5.19434 2.01562L2.96191 2.01562Q2.99149 1.91663 3.02041 1.81562Q3.17691 1.26905 3.31398 0.664175Q3.33595 0.567202 3.35742 0.46875L2.19434 0.263672C1.81055 2.19727 1.07812 3.73242 0 4.87207L0.744141 5.82129C0.791851 5.77415 0.839009 5.72625 0.885619 5.67759C1.55168 4.98216 2.10564 4.13047 2.55469 3.12012Z"
            fill-rule="evenodd" transform="matrix(1 0 0 1 19.3516 6.16211)" fill="rgb(135, 144, 141)" />
        </g>
      </svg>
    </div> -->

  </div>


  <script>

    function getIsMobile() {
      const width = document.documentElement.clientWidth
      const isMobile = /Android|webOS|iPhone|iPod|BlackBerry|iPad|Windows Phone|Mobile/i.test(navigator.userAgent) || width <= 768
      return isMobile
    }

    // 打开飞象老师官网
    function openFeixiangTeacher(event) {
      const isMobile = getIsMobile()

      // 判断是否为移动端浏览器
      if (isMobile) {
        // 移动端不跳转
        return
      }
      window.open('https://www.feixianglaoshi.com', '_blank')
    }


    // ==================== 埋点相关代码 ====================

    /**
     * 页面停留时长统计
     */
    (function () {
      let startTime = null
      let totalTime = 0
      let reportTimer = null // 防抖定时器

      // 开始计时
      function startTimer() {
        if (!startTime) {
          startTime = Date.now()
          console.log('[埋点] 开始计时')
        }
      }

      // 停止计时并累加时长
      function stopTimer() {
        if (startTime) {
          totalTime += Date.now() - startTime
          startTime = null
          console.log('[埋点] 停止计时，累计时长:', Math.floor(totalTime / 1000), '秒')
        }
      }

      // 检查页面是否真正可见
      function isPageVisible() {
        // 检查 document.hidden
        if (document.hidden) {
          return false
        }

        // 检查 document.visibilityState
        if (document.visibilityState && document.visibilityState !== 'visible') {
          return false
        }

        // 检查窗口是否有焦点
        if (!document.hasFocus()) {
          return false
        }

        return true
      }

      // 上报停留时长（带防抖）
      function reportStayTime(eventType, immediate = false) {
        stopTimer()

        // 清除之前的定时器
        if (reportTimer) {
          clearTimeout(reportTimer)
          reportTimer = null
        }

        // 如果是立即上报（如页面卸载），不使用防抖
        if (immediate) {
          doReport(eventType)
          return
        }

        // 使用防抖，避免短时间内多次上报
        // 100ms 内如果有多个事件触发，只上报最后一次
        reportTimer = setTimeout(function () {
          doReport(eventType)
          reportTimer = null
        }, 100)
      }

      // 实际执行上报
      function doReport(eventType) {
        if (window.frog && totalTime > 0) {
          const serverData = window.__SERVER_DATA__ || {}
          const chatId = serverData.watermarkChatId
          window.frog.add({
            url: '/time/HtmlPage/enter',
            eventId: 42818,
            customExtend: {
              chat_id: chatId,
              use_time: Math.floor(totalTime / 1000), // 转换为秒
            },
            duration: Math.floor(totalTime / 1000), // 转换为秒,
            currentPage: 'HtmlPage',
            eventAction: 'time',
            eventName: 'enter'
          })
          console.log(`[埋点] 页面停留时长上报 (${eventType}):`, Math.floor(totalTime / 1000), '秒')

          // 上报后重置累计时长，为下次统计做准备
          totalTime = 0
        }
      }

      // 清理函数：移除所有事件监听器
      function cleanup() {
        console.log('[埋点] 清理计时器资源')

        // 清除防抖定时器
        if (reportTimer) {
          clearTimeout(reportTimer)
          reportTimer = null
        }

        // 移除事件监听器
        document.removeEventListener('visibilitychange', handleVisibilityChange)
        window.removeEventListener('blur', handleBlur)
        window.removeEventListener('focus', handleFocus)
        window.removeEventListener('beforeunload', handleBeforeUnload)
        window.removeEventListener('pagehide', handlePageHide)

        // 重置变量
        startTime = null
        totalTime = 0
      }

      // 事件处理函数（需要命名以便移除）
      function handleVisibilityChange() {
        if (document.hidden) {
          // 页面不可见，停止计时并上报
          console.log('[埋点] visibilitychange - 页面隐藏')
          reportStayTime('visibilitychange')
        } else {
          // 页面可见，开始新的计时
          console.log('[埋点] visibilitychange - 页面显示，开始新的计时')
          startTimer()
        }
      }

      function handleBlur() {
        // 窗口失去焦点，停止计时并上报
        console.log('[埋点] blur - 窗口失去焦点')
        reportStayTime('blur')
      }

      function handleFocus() {
        // 窗口获得焦点，开始新的计时
        console.log('[埋点] focus - 窗口获得焦点，开始新的计时')
        startTimer()
      }

      function handleBeforeUnload() {
        // 页面卸载前立即上报（不使用防抖）
        console.log('[埋点] beforeunload - 页面即将卸载')
        reportStayTime('beforeunload', true)
        cleanup()
      }

      function handlePageHide() {
        // 页面隐藏时立即上报（iOS Safari 更可靠，不使用防抖）
        console.log('[埋点] pagehide - 页面隐藏')
        reportStayTime('pagehide', true)
      }

      function handleDOMContentLoaded() {
        if (isPageVisible()) {
          startTimer()
        }
      }

      // 监听页面可见性变化
      document.addEventListener('visibilitychange', handleVisibilityChange)

      // 监听窗口失去/获得焦点
      window.addEventListener('blur', handleBlur)
      window.addEventListener('focus', handleFocus)

      // 页面加载完成后开始计时
      if (document.readyState === 'loading') {
        window.addEventListener('DOMContentLoaded', handleDOMContentLoaded)
      } else {
        if (isPageVisible()) {
          startTimer()
        }
      }

      // 页面卸载时上报
      window.addEventListener('beforeunload', handleBeforeUnload)

      // 兼容性：监听 pagehide 事件（iOS Safari 更可靠）
      window.addEventListener('pagehide', handlePageHide)
    })()

    //     /**
    //      * 点击 HTML 任何部分的埋点
    //      */
    //     function trackHtmlClick(event) {
    //       // 避免重复上报（如果点击的是 logo 或按钮，会有专门的埋点）
    //       const target = event.target
    //       const isLogo = target.closest('.watermark-overlay')
    //       const isButton = target.closest('.jump-button')

    //       // 如果点击的是 logo 或按钮，不在这里上报
    //       if (isLogo || isButton) {
    //         return
    //       }

    //       if (window.frog) {
    //         const serverData = window.__SERVER_DATA__ || {}
    //         const chatId = serverData.watermarkChatId
    // console.log('trackHtmlClick', chatId)
    //         window.frog.add({
    //           url: '/click/UserTagPage/html',
    //           eventId: 50004,
    //           customExtend: {
    //             chat_id: chatId,
    //             click_target: target.tagName.toLowerCase(),
    //             page_name: 'iframe_wrapper'
    //           },
    //           currentPage: 'IframeWrapperPage',
    //           eventAction: 'click',
    //           eventName: 'clickHtml'
    //         })
    //       }
    //     }

    /**
     * 点击飞象老师 Logo 的埋点
     */
    function trackLogoClick(event) {
      // 阻止事件冒泡，避免触发 HTML 点击埋点
      event.stopPropagation()

      if (window.frog) {
        const serverData = window.__SERVER_DATA__ || {}
        const chatId = serverData.watermarkChatId
        console.log('trackHtmlClick', chatId)

        window.frog.add({
          url: '/click/HtmlPage/logo',
          eventId: 42816,
          customExtend: {
            chat_id: chatId,
          },
          currentPage: 'HtmlPage',
          eventAction: 'click',
          eventName: 'logo'
        })

        console.log('[埋点] 点击飞象老师 Logo')
      }
    }

    /**
     * 点击立即体验的埋点
     */
    function trackStartButtonClick(event) {
      // 阻止事件冒泡，避免触发 HTML 点击埋点
      event.stopPropagation()

      if (window.frog) {
        const serverData = window.__SERVER_DATA__ || {}
        const chatId = serverData.watermarkChatId
        console.log('trackHtmlClick', chatId)
        window.frog.add({
          url: '/click/HtmlPage/start',
          eventId: 42817,
          customExtend: {
            chat_id: chatId
          },
          currentPage: 'HtmlPage',
          eventAction: 'click',
          eventName: 'start'
        })
        console.log('[埋点] 点击立即体验')
      }
    }

    // 绑定点击事件
    document.addEventListener('DOMContentLoaded', function () {
      // 绑定 Logo 点击埋点和跳转功能
      const logoElement = document.querySelector('.left-watermark-content')
      if (logoElement) {
        logoElement.addEventListener('click', function (event) {
          trackLogoClick(event)
          openFeixiangTeacher(event)
        })
      }

      // 绑定立即体验按钮点击埋点和跳转功能
      const startButton = document.querySelector('.jump-button')
      if (startButton) {
        startButton.addEventListener('click', function (event) {
          trackStartButtonClick(event)
          openFeixiangTeacher(event)
        })
      }

      // 绑定水印覆盖层点击（整体区域）
      const watermarkOverlay = document.querySelector('.watermark-overlay')
      if (watermarkOverlay) {
        watermarkOverlay.addEventListener('click', function (event) {
          // 如果点击的不是 logo 或按钮，则触发跳转
          const target = event.target
          const isLogo = target.closest('.left-watermark-content')
          const isButton = target.closest('.jump-button')

          if (!isLogo && !isButton) {
            openFeixiangTeacher(event)
          }
        })
      }
    })

    // ==================== 原有功能代码 ====================

    function adjustRem() {
      const pcBaseWidth = 375 // 设计稿
      const width = document.documentElement.clientWidth
      document.documentElement.style.fontSize = `${(width / pcBaseWidth * 100).toFixed(2)}px`
    }


    // 移动端检测和按钮隐藏逻辑
    function checkAndHideButtonOnMobile() {
      const isMobile = getIsMobile()
      if (isMobile) {
        adjustRem()
      }
      const jumpButton = document.querySelector('.right-watermark-content .jump-button');
      const iframeContainer = document.querySelector('.iframe-container');

      if (isMobile && jumpButton) {
        jumpButton.style.display = 'none';
      } else {
        jumpButton.style.display = 'flex'
      }

      // 移动端时给iframe-container添加类名，否则移除类名
      if (iframeContainer) {
        if (isMobile) {
          iframeContainer.classList.add('mobile');
        } else {
          iframeContainer.classList.remove('mobile');
        }
      }
    }


    function handleResize() {
      // 响应式处理：重新检测移动端并处理按钮显示/隐藏
      checkAndHideButtonOnMobile();

      // 在窗口大小变化时，重新应用移动端相关的逻辑
      const isMobile = getIsMobile()
      const watermarkOverlay = document.querySelector('.watermark-overlay');
      const iframeContainer = document.querySelector('.iframe-container');

      // 根据当前设备类型调整水印覆盖层的点击行为
      if (watermarkOverlay) {
        if (isMobile) {
          // 移动端：移除点击事件或设置为空函数
          watermarkOverlay.onclick = function () {
            // 移动端不执行跳转
            return;
          };
        } else {
          // 桌面端：恢复正常的点击跳转功能
          watermarkOverlay.onclick = openFeixiangTeacher;
        }
      }

      // 确保在resize时也能正确添加或移除mobile类
      if (iframeContainer) {
        if (isMobile) {
          iframeContainer.classList.add('mobile');
        } else {
          iframeContainer.classList.remove('mobile');
        }
      }
    }

    // 防止iframe内容溢出
    window.addEventListener('resize', handleResize);

    // 页面加载完成后执行移动端检测
    document.addEventListener('DOMContentLoaded', checkAndHideButtonOnMobile);

    // 清理所有事件绑定的函数
    function clearAllEvents() {
      // 清除 resize 事件监听器
      window.removeEventListener('resize', handleResize);

      // 清除 DOMContentLoaded 事件监听器
      document.removeEventListener('DOMContentLoaded', checkAndHideButtonOnMobile);
    }

    // 页面卸载时自动清理事件（可选）
    window.addEventListener('beforeunload', clearAllEvents);

  </script>
</body>

</html>
