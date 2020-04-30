## angular 2
安装 angular/cli  
npm install -g @angular/cli@6.2.9  
创建项目  
ng new angular-tour-of-heroes  
启动项目  
cd angular-tour-of-heroes  
ng serve --open  [port]  
  
创建组件
>使用 CLI 创建了第二个组件 HeroesComponent。  
>把 HeroesComponent 添加到了壳组件 AppComponent 中，以便显示它。  
>使用 UppercasePipe 来格式化英雄的名字。  
>用 ngModel 指令实现了双向数据绑定。  
>知道 AppModule。  
>把 FormsModule 导入了 AppModule，以便 Angular 能识别并应用 ngModel 指令。  
>把组件声明到 AppModule 是很重要的，并认识到 CLI 会自动帮你声明它。  

显示列表
>英雄指南应用在一个主从视图中显示了英雄列表。  
>用户可以选择一个英雄，并查看该英雄的详情。  
>使用 *ngFor 显示了一个列表。  
>使用 *ngIf 来根据条件包含或排除了一段 HTML.  
>可以用 class 绑定来切换 CSS 的样式类。  
创建特性组件
>你创建了一个独立的、可复用的 HeroDetailComponent 组件。  
>用属性绑定语法来让父组件 HeroesComponent 可以控制子组件 HeroDetailComponent。  
>用 @Input 装饰器来让 hero 属性可以在外部的 HeroesComponent 中绑定  
