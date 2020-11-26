### windows使用
 * 作用主要是配置GOPATH
 * 用法
   + 先设置GOPATH为项目下的.godeps
   + 最后用完GOPATH之后，再清除GOPATH设置
      - 目前清除好像不起作用，所以还是需要在使用时打开新的bash窗口，用完关闭这个窗口即可
      - 不要在idea terminal中直接使用，除非用完再关闭terminal中的tab
      
      
 * 使用参考gpm-git
   + windows/git-bash-bin/readme.md
   
 * 将gvp sh放到git/usr/bin目录下
   
 * TODO
   + [ ] 可以进一步修改一下，初始化时保存变量GOPATH, GOBIN, PATH
      - gvp out 时还原即可，就不需要强制关闭使用过的bash窗口了