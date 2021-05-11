<template>
  <div class="about">
    <h1>This is a input</h1>
    <div>
    <a-input-search placeholder="请输入文字" style="width: 200px" @search="onSearch" addonAfter="我们"/>
    <br /><br />
    <a-input-search placeholder="input search text" enter-button @search="onSearch" defaultValue="芒果"/>
    <br /><br />
    <a-input-search
      placeholder="input search text"
      enter-button="Search"
      size="large"
      @search="onSearch"
    />
    <br /><br />
    <a-input-search placeholder="input search text" size="large" @search="onSearch">
      <a-button slot="enterButton">
        Custom
      </a-button>
    </a-input-search>
  </div>

  <div class="icons-list">
    <a-icon type="account-book" />
    <a-icon type="setting" theme="twoTone" />
    <a-icon type="smile" theme="outlined" />
    <a-icon type="sync" spin />
    <a-icon type="smile" :rotate="180" />
    <a-icon type="loading" />
  </div>
  </div>
</template>
