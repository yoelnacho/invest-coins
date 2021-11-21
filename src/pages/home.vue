<template>
  <f7-page name="home">
    <f7-navbar large :sliding="false">
      <f7-nav-title sliding>Invest coins</f7-nav-title>
      <f7-nav-title-large>Invest <span class="text-color-primary">coins</span></f7-nav-title-large>
    </f7-navbar>
    <!-- Page content-->
    <f7-block strong>
      <p>This is an example of split view application layout, commonly used on tablets. The main approach of such kind of layout is that you can see different views at the same time.</p>

      <p>Each view may have different layout, different navbar type (dynamic, fixed or static) or without navbar.</p>

      <p>The fun thing is that you can easily control one view from another without any line of JavaScript just using "data-view" attribute on links.</p>
    </f7-block>
  </f7-page>
</template>