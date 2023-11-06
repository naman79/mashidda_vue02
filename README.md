# mashidda_vue02

npm install -g @vue/cli

vue create mashidda_vue02

cd mashidda_vue02

npm add router

1. Install
npm i --save @fortawesome/fontawesome-svg-core
npm i --save @fortawesome/vue-fontawesome
npm i --save @fortawesome/free-solid-svg-icons
npm i --save @fortawesome/free-regular-svg-icons
npm i --save @fortawesome/free-brands-svg-icons

2. "main.js" 파일에 추가</h3>
import { library } from '@fortawesome/fontawesome-svg-core'
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
// 설치했던 fontawesome-svg-core와 vue-fontawesome</span>

import { fas } from '@fortawesome/free-solid-svg-icons'
import { far } from '@fortawesome/free-regular-svg-icons'
import { fab } from '@fortawesome/free-brands-svg-icons'
// 이렇게하면 모든 아이콘들을 불러올 수 있다.</span>

library.add(
fas,
far,
fab
)
// 불러온 아이콘을 라이브러리에 담기.

Vue.component('font-awesome-icon', FontAwesomeIcon)
// fontawesome아이콘을 Vue탬플릿에 사용할 수 있게 등록.
