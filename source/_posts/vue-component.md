---
title: vue_component
date: 2019-08-28 12:29:30
tags:
---
Component basics:
// data needs to be retruned in function format:

Vue.component('name of the component', {
    data: function(){
        return {
            count: 0;
        }
    }
})