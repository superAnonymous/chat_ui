<template>
  <div class="layout-demo">
    <a-layout>
      <a-affix :offsetTop="0">
        <a-layout-header>
          在线客服
        </a-layout-header>
      </a-affix>
      <a-layout>
        <a-row class="grid-demo">
          <a-col :span="24">
            <a-link href="link">加载聊天历史</a-link>
          </a-col>
        </a-row>
        <a-list>
          <a-list-item class="user agent">
            <a-row>
              <a-col :span="4">
                <a-avatar>
                  <img
                      alt="avatar"
                      src="https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/3ee5f13fb09879ecb5185e440cef6eb9.png~tplv-uwbnlip3yd-webp.webp"
                  />
                </a-avatar>
              </a-col>
              <a-col :span="20">
                <a-comment
                    author="Socrates"
                    datetime="1 hour"
                >
                  <a-image
                      width="200"
                      src="https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/a8c8cdb109cb051163646151a4a5083b.png~tplv-uwbnlip3yd-webp.webp"
                  />
                </a-comment>
              </a-col>
            </a-row>
          </a-list-item>
          <a-list-item class="user customer">
            <a-row>
              <a-col :span="4">
                <a-avatar>
                  <img
                      alt="avatar"
                      src="https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/3ee5f13fb09879ecb5185e440cef6eb9.png~tplv-uwbnlip3yd-webp.webp"
                  />
                </a-avatar>
              </a-col>
              <a-col :span="20">
                <a-comment
                    author="Socrates"
                    datetime="1 hour"
                >
                  <a-image
                      width="200"
                      src="https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/a8c8cdb109cb051163646151a4a5083b.png~tplv-uwbnlip3yd-webp.webp"
                  />
                </a-comment>
              </a-col>
            </a-row>
          </a-list-item>
          <a-list-item class="user customer">
            <a-row>
              <a-col :span="4">
                <a-avatar>
                  <img
                      alt="avatar"
                      src="https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/3ee5f13fb09879ecb5185e440cef6eb9.png~tplv-uwbnlip3yd-webp.webp"
                  />
                </a-avatar>
              </a-col>
              <a-col :span="20">
                <a-comment
                    author="Socrates"
                    datetime="1 hour"
                >
                  <a-image
                      width="200"
                      src="https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/a8c8cdb109cb051163646151a4a5083b.png~tplv-uwbnlip3yd-webp.webp"
                  />
                </a-comment>
              </a-col>
            </a-row>
          </a-list-item>
          <a-list-item class="user customer">
            <a-row>
              <a-col :span="4">
                <a-avatar>
                  <img
                      alt="avatar"
                      src="https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/3ee5f13fb09879ecb5185e440cef6eb9.png~tplv-uwbnlip3yd-webp.webp"
                  />
                </a-avatar>
              </a-col>
              <a-col :span="20">
                <a-comment
                    author="Socrates"
                    datetime="1 hour"
                >
                  <a-image
                      width="200"
                      src="https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/a8c8cdb109cb051163646151a4a5083b.png~tplv-uwbnlip3yd-webp.webp"
                  />
                </a-comment>
              </a-col>
            </a-row>
          </a-list-item>
          <a-list-item class="user customer">
            <a-row>
              <a-col :span="4">
                <a-avatar>
                  <img
                      alt="avatar"
                      src="https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/3ee5f13fb09879ecb5185e440cef6eb9.png~tplv-uwbnlip3yd-webp.webp"
                  />
                </a-avatar>
              </a-col>
              <a-col :span="20">
                <a-comment
                    author="Socrates"
                    datetime="1 hour"
                >
                  <a-image
                      width="200"
                      src="https://p1-arco.byteimg.com/tos-cn-i-uwbnlip3yd/a8c8cdb109cb051163646151a4a5083b.png~tplv-uwbnlip3yd-webp.webp"
                  />
                </a-comment>
              </a-col>
            </a-row>
          </a-list-item>
        </a-list>
      </a-layout>
      <a-affix offset-bottom="0">
        <a-layout-footer>
          <a-row class="grid-demo">
            <a-col :span="24">
              <a-list :action-layout="horizontal">
                <a-button type="primary" shape="round">热门问题</a-button>
                <a-button type="primary" shape="round">问题一</a-button>
                <a-button type="primary" shape="round">问题2</a-button>
                <a-button type="primary" shape="round">火舞</a-button>
              </a-list>
            </a-col>
          </a-row>
          <a-row class="grid-demo">
            <a-col :span="18">
              <a-input placeholder="Please enter something" allow-clear/>
            </a-col>
            <a-col :span="2">
              <a-space>
                <a-button type="primary" shape="circle">
                  <icon-plus />
                </a-button>
              </a-space>
            </a-col>
            <a-col :span="4">
              <a-space>
                <a-button type="primary" :shape="round">
                  发送
                </a-button>
              </a-space>
            </a-col>
          </a-row>
        </a-layout-footer>
      </a-affix>
    </a-layout>
  </div>
</template>
<script>

</script>
<style scoped>
:deep(.arco-layout-header),
:deep(.arco-layout-footer),
:deep(.arco-layout-sider-children),
:deep(.arco-layout-content) {
  display: flex;
  flex-direction: column;
  justify-content: center;
  color: var(--color-white);
  font-size: 16px;
  font-stretch: condensed;
  text-align: center;
}

:deep(.arco-layout-header) {
  height: 64px;
  background-color: var(--color-primary-light-4);
}

:deep(.arco-layout-footer) {
  background-color: var(--color-primary-light-3);
}

:deep(.icon-plus) {
  color: var(--color-primary-light-4);
}

:deep(.arco-layout-content) {
  background-color: rgb(var(--arcoblue-6));
}

.customer :deep(.arco-row.arco-row-align-start.arco-row-justify-start) {
  flex-direction: row-reverse;
}

.agent :deep(.arco-comment-title.arco-comment-title-align-left) {
  text-align: start;
}

.agent :deep(.arco-comment-inner-comment) {
  text-align: start;
}

.customer :deep(.arco-comment-title.arco-comment-title-align-left) {
  text-align: end;
}

.customer :deep(.arco-comment-inner-comment) {
  text-align: end;
}

.customer :deep(.arco-comment-title.arco-comment-title-align-left) {
  flex-direction: row-reverse;
  display: flex;
}

.customer :deep(span.arco-comment-datetime) {
  margin-right: 8px;
}

:deep(.arco-list-content, .arco-list-item) {
  border: 0;
  margin: 0;
}

:deep(li.arco-list-item) {
  border: solid 0;
}
</style>
