# yarn1-ws

yarn v1のワークスペースはnode_modulesにどう入るのか検証した。
みたところ、shimされていそう。ワークスペースの編集が即座にnode_modules/@no-yan/core, cli に反映されている。
