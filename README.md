# tunk-loader
#### 用于处理tunk模块被打包压缩时模块类名被压缩的尴尬

webpack.config module配置
````Javascript
      {
        test: /\.js$/,
        loader: 'babel-loader!tunk-loader',
        exclude: /(node_modules)/
      }
````
