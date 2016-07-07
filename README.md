# ng2-tooltip
Angular2 tooltip directive

<a href="https://plnkr.co/edit/Yq78qE?p=preview">
  <img src="http://i.imgur.com/0qcxg8X.png" width="50% border="1" />
</a>

## Install

1. install ng2-tooltip

        $ npm install ng2-tooltip --save

2. add `map` and `packages` to your `systemjs.config.js`

        map['ng2-tooltip = 'node_modules/ng2-tooltip'
        packages['ng2-tooltip = { main: 'dist/index.js', defaultExtension: 'js']
        
3.  add ng2-tooltip.css into your html

        <link rel="stylesheet" href="ng2-tooltip.css" />


## Usage it in your code

1. import and add directive in your component

        import { Ng2TooltipDirective } from 'ng2-tooltip';

        @Component({
          selector: 'my-app',
          templateUrl: './app/app.tpl.html',
          directives: [ Ng2TooltipDirective ]
        })


2. You are ready. use it in your template

        <div tooltip="This is my tooltip">
          Move mouse over here to see the tooltip
        </div>

