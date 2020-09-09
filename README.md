# TodoMVC

Vue.js のサンプルアプリの TODO リストを実装しようとした。 https://vuejs.org/v2/examples/todomvc.html

なるべく簡潔で標準なコードを作成した。例えば、 「:class="{ 'visible-element': item.completed, 'hidden-element': !item.completed }"」ではなく、 「:class="item.completed ? 'visible-element' : 'hidden-element'"」を書いた。

なるべく Vue.js のサンプルアプリの TODOリスト と同じの TODOリストを実装した。 Vue.js のサンプルアプリと同じの UI スタイル、UI 動作を実装した。 Vue.js のサンプルアプリと同じで、ブラウザリフレッシュ後、TODO 項目の順番が保つように実装した。
