dist是distribution的意思，此文件夹用于生成发布用的JS文件，src存放ES6标准的JS文件
lib是实现当前包的功能的JS文件
node_modules中存放当前包的依赖包
gulpfile.js定义gulp任务
package.json描述当前包，比如当前包的依赖:
1.在当前包中执行npm install xxx --save-dev时，会把xxx添加进devDependencies中
2.在当前包中执行npm install xxx时，会把xxx添加进dependencies中，而dependencies表示当前包运行所必须的依赖包
假设刚刚的当前包的包名为"yyy"
在某个包中执行"npm install yyy"或"npm install yyy --save-dev"时，除了会安装yyy，也会检查yyy的package.json中的dependencies项，并把它其中的依赖包都下载下来，但devDependencies项中的信赖则不会下载



安装：
npm i learngulp



