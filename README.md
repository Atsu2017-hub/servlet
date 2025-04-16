# servlet
- アプリケーションスコープ
  - configオブジェクトがServletContextオブジェクトを所持
  - このconfigはservletインスタンス生成後にサーブレットコンテナが設定してくれる
  - サーブレットコンテナはアプリケーションごとにこのオブジェクトを管理し、適切に設定している。
  - this.getServletContext()でこのconfigからServletContextオブジェクトを取得
